# abrir

Página lanzadora de la planilla de compras: abre las 3 opciones de un renglón en pestañas, en orden de recomendación.

- Uso: `https://juromeroagd.github.io/abrir/#<link1>|<link2>|<link3>` (cada link con `encodeURIComponent`).
- Los links van después del `#`, así que no se envían a ningún servidor.
- Solo abre solas las tiendas de la lista `TIENDAS` de `index.html`; si aparece otro dominio, muestra los links para abrirlos a mano.
- La primera vez Chrome bloquea las ventanas emergentes: hay que permitirlas para `juromeroagd.github.io`.
