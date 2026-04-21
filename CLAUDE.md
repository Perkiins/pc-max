# PC MAX — Landing personal

Web de servicios personales: reparación de ordenadores, desarrollo web y programación a medida en Barcelona.

## Stack
- **Framework**: Astro 4 (static output)
- **Estilos**: CSS puro con custom properties (sin dependencias externas)
- **Font**: Inter (Google Fonts)
- **Deploy**: Vercel (gratis, CDN global, carga instantánea)

## Estructura
```
src/pages/index.astro   # página única con todo el contenido y estilos
public/logo.png         # logo principal (fondo blanco, tipografía oscura + chip azul)
```

## Secciones
1. **Nav** — sticky con blur, logo + links + CTA
2. **Hero** — full height, tagline, 2 CTAs
3. **Servicios** — 3 cards (Reparación, Web, Programación)
4. **Proyectos** — 4 cards (JackBeds, Shopify Tracker, HokoSocial, CS Radar)
5. **Contacto** — formulario mailto + email directo
6. **Footer** — minimal

## Colores (dark theme)
- Fondo: `#0d0d0d`
- Superficie: `#141414`
- Acento azul: `#5ba8d4` (del logo original)
- Texto: `#f0f0f0`

## Comandos
```bash
npm install       # setup
npm run dev       # desarrollo local → http://localhost:4321
npm run build     # build producción → dist/
npm run preview   # previsualizar build
```

## Deploy en Vercel
Conectar repo GitHub en vercel.com → deploy automático en cada push a main.

## Contacto configurado
- Email: pcmaxbarcelona@outlook.es
- Formulario: usa mailto (abre cliente de email del visitante)
- Mejora futura: migrar a Formspree (gratis, 50 envíos/mes) para recibir sin depender del cliente de email del visitante
