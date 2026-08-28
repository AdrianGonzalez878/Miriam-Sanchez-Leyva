# Perfil digital — Miriam Sánchez Leyva · Leyva Bakery

Ficha de presentación estilo BNI para **Miriam Sánchez Leyva**, chef repostera de Leyva Bakery.

## Stack

- [Astro](https://astro.build) (estático)
- Tailwind CSS v4
- Contenido en `src/data/profile.ts`

## Desarrollo

Requiere Node.js 22+.

```bash
nvm use 22
npm install
npm run dev
```

Abre [http://127.0.0.1:4321](http://127.0.0.1:4321).

## Producción

```bash
npm run build
npm run preview
```

La salida queda en `dist/` (ideal para Vercel o Cloudflare Pages).

## Editar contenido

Todo el texto, enlaces, clientes, HORLI y galería vive en:

`src/data/profile.ts`

Fotos en `public/images/`. Para un retrato más nítido, sustituye `miriam-portrait.png`.
