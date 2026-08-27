# Perfil digital — Ma. Azeret Leyva Gómez · Leyva Bakery

Ficha de presentación estilo BNI para **Azeret Leyva**, representante del negocio. Miriam (su hija) aparece como chef creativa detrás de las creaciones.

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

Fotos en `public/images/`:
- Foto de Azeret → ponla en `public/images/` y actualiza `photo` en `profile.ts`
- Retrato de Miriam → `miriam-portrait.png`
