# Ultimate DNS Filter

Um filtro unificado para **AdGuard Home**, **AdGuard Desktop**, **DNS-based blockers** e compatíveis.  
Combina múltiplas listas confiáveis — como **OISD**, **Hagezi Pro++**, entre outras listas de anúncios e rastreadores — removendo duplicatas e normalizando todas as entradas em um único arquivo otimizado.

---

## Objetivo

- Reunir várias blocklists em um único filtro eficiente.  
- Remover duplicatas automaticamente.  
- Reduzir carga no AdGuard Home e melhorar performance.  
- Manter a lista limpa, simples e atualizada.

---

O script `main.py`:

1. Lê todas as listas dentro da pasta `filters/`
2. Converte tudo para o formato AdGuard/ABP (`||dominio^`)
3. Remove entradas repetidas
4. Gera um único arquivo: **ultimatednsfilter.txt**

Nada é modificado nas listas originais.

---

## Uso no AdGuard Home

No painel:

**Filters → Custom → Add filter → URL da lista**

Use o link RAW: https://raw.githubusercontent.com/L1nco/UltimateDNSFilter/refs/heads/main/ultimatednsfilter.txt

