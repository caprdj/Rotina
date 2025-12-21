# Casa — Cardápio + Inventário (PWA)

Este repositório reúne **2 apps em 1 único PWA** (instalável no Android/Samsung).

## Estrutura
- `index.html` → tela inicial (menu)
- `cardapio.html` → app Cardápio
- `inventario.html` → app Inventário
- `manifest.json` → manifesto do PWA
- `sw.js` → service worker (offline)
- `icons/` → ícones (substitua pelos seus)

## Como publicar no GitHub Pages
1. Crie um repositório (ex.: `CASA`).
2. Faça upload **de todos os arquivos** desta pasta.
3. No GitHub: **Settings → Pages**
   - Source: `Deploy from a branch`
   - Branch: `main` (root)
4. O link ficará assim:
   - `https://SEUUSUARIO.github.io/CASA/`

## Como instalar no Samsung (Galaxy M53)
- Abra o link no **Google Chrome**.
- Toque em **⋮ Menu → Instalar app** (ou **Adicionar à tela inicial**).
- Depois, abra sempre pelo ícone instalado.

## Ícones
Substitua os arquivos em `icons/` pelos seus ícones mantendo os mesmos nomes:
- `icon-192.png`
- `icon-512.png`
- `icon-192-maskable.png`
- `icon-512-maskable.png`
- `apple-touch-icon.png`
