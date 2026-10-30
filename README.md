# CultureOn — Links

Página de links ao estilo "link tree" da CultureOn: um único `index.html`, sem dependências nem build.

## Editar links

Abre `index.html` e edita a lista `LINKS` no `<script>` (no fim do ficheiro):

```js
{ label: "Instagram", sub: "Bastidores, projetos e switches", url: "https://instagram.com/..." },
```

- `url: ""` → o link fica escondido até ter um URL.
- `featured: true` → destaca o botão (fundo invertido).
- Para email usa `mailto:email@dominio.pt`; para WhatsApp usa `https://wa.me/351XXXXXXXXX`.

## Publicar (GitHub Pages)

Settings → Pages → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save.
A página fica em `https://cultureon.github.io/culture-on-links/`.
Para um domínio próprio (ex.: `links.cultureon.pt`), adiciona-o em Settings → Pages → Custom domain e cria um registo CNAME no DNS a apontar para `cultureon.github.io`.

## Marca

- Títulos: Syne · Corpo: Inter
- Cores: preto `#0A0A0A`, branco `#F5F5F2`, acento `#D9FF47`
- Easter egg: o interruptor ON/OFF no topo passa a página para o modo claro e troca os links por um interruptor em cápsula com uma linha de luz a escapar. Ao 1.º e 2.º clique a luz pisca ("Ainda não.", "VAAAI!"); ao 3.º o painel escurece, a cápsula acende ("É AGORA!") e a página volta a ON. A página abre sempre em ON.
