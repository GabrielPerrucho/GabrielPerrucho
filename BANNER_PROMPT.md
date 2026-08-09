# Prompt para gerar o banner externamente (alternativa ao banner.svg)

O `banner.svg` incluso já é um banner funcional, leve e editável em texto — é a opção recomendada, pois usa fontes reais e nenhum peso extra de imagem. Use este prompt apenas se preferir uma versão ilustrada/gerada por IA de imagem (Midjourney, DALL·E, etc.).

## Especificação técnica

- **Dimensões:** 1280 × 320px (proporção 4:1, padrão para banners de topo de README/GitHub)
- **Formato de saída:** PNG ou WebP, otimizado a menos de 300 KB
- **Estilo:** flat design digital, minimalista, tech/dark, sem texturas fotorrealistas
- **Paleta obrigatória:**
  - Fundo: preto-azulado profundo (#0A0E14 a #10151D)
  - Acento primário: ciano suave (#4FD1C5)
  - Acento secundário: âmbar (#F2B675)
  - Acento pontual: violeta (#8B7CF6)
  - Texto/linhas: cinza-claro (#E6EDF3) sobre o fundo escuro

## Prompt (em inglês, para melhor resultado nos geradores de imagem)

```
A minimal, modern dark-mode banner for a developer's GitHub profile,
1280x320px, flat vector illustration style, no photorealism.

Background: deep near-black navy (#0A0E14) with a very subtle dot-grid
pattern and two soft radial glows — one cyan (#4FD1C5) in the upper-left,
one violet (#8B7CF6) in the lower-right, both low opacity.

Composition: left side has generous negative space reserved for bold
sans-serif headline text (leave this area empty/clean). Right side
features a stylized code editor or terminal window: a rounded rectangle
card with a dark surface (#10151D), a thin border (#202836), three small
traffic-light dots (red, yellow, green) at the top-left of the window,
and a few lines suggesting monospace code using thin rectangles or
faint text in cyan and amber tones — abstract, not readable text.

Add a few small floating geometric accents: a rounded bracket "< >",
a small terminal cursor block, thin connecting lines like a subtle
circuit or network pattern — kept sparse and elegant, not cluttered.

Mood: professional, calm, technical, portfolio-ready — like a premium
developer tool's marketing banner, not a gaming or neon aesthetic.
No text, no logos, no watermarks, no people, no 3D renders.
```

## Depois de gerar

1. Salve a imagem como `banner.png` (ou `.webp`) dentro da pasta do repositório do seu perfil (`[SEU-GITHUB]/[SEU-GITHUB]`).
2. No `README.md` do perfil, troque a referência de `./banner.svg` para `./banner.png` na tag `<img>`.
3. Se for adicionar texto (seu nome, cargo), prefira fazer isso depois em um editor simples (Figma, Canva) por cima da imagem gerada — geradores de IA erram texto com frequência.
