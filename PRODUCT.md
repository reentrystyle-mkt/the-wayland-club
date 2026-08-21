# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

static HTML/CSS (single-file: `index.html`, no framework, no build step)

## Users

Personas en Argentina que buscan acceder a cannabis medicinal de forma legal.
Se dividen en dos situaciones reales: quienes ya tienen REPROCANN vigente y
quieren asociarse para acceder al catálogo, y quienes todavía no lo tienen y
necesitan que el Club los derive con su equipo médico para gestionarlo.

## Product Purpose

Sitio informativo (no transaccional) para The Wayland Club, una ONG habilitada
por el Ministerio de Salud de Argentina que opera dentro del marco legal
REPROCANN. El sitio explica qué es el Club, cómo funciona el proceso de
asociación, qué es REPROCANN, y deriva todo el contacto real a WhatsApp e
Instagram. No hay checkout ni catálogo transaccional todavía.

## Positioning

No es una tienda: es una ONG que acompaña a la persona en todo el proceso,
desde la primera consulta hasta la dispensa. La membresía existe pero es sin
costo — solo se presenta la documentación que pide REPROCANN. El diferencial
frente a otros dispensarios/gestores es ese acompañamiento real dentro del
marco legal, respaldado por REPROCANN/Ministerio de Salud, INASE y Orgánicos
de Argentina S.A.

## Operating Context

Sin local físico — 100% online. El flujo real: WhatsApp (wa.link/3i3nep) e
Instagram (@the.waylandclub) son los únicos canales de contacto. El catálogo
completo (variedades, formatos) todavía no está activo; por ahora se comparte
manualmente por WhatsApp a quien lo pide.

## Capabilities and Constraints

- Nunca escribir "cannabis" sin estilizar en el contenido **visible** de la
  página — siempre "C4NN4BIS" (identidad de marca). La configuración SEO
  (`<title>`, meta description) sí usa "Cannabis" normal para ser encontrable
  en buscadores.
- Sin precios en el sitio.
- Sin imágenes de personas fumando o usando el producto.
- Sin datos de catálogo inventados — la grilla de variedades/formatos se sacó
  del sitio hasta tener contenido real; mientras tanto es un teaser que deriva
  a WhatsApp.
- Lenguaje siempre de "acceder", "asociarse", "dispensar" — nunca lenguaje de
  compra/venta ni de uso recreativo.
- La foto de "Quiénes somos" es un placeholder marcado en el código
  (`CARGAR: foto real`) hasta que el cliente entregue una imagen real.

## Brand Commitments

Nombre: The Wayland Club. Paleta dorado/ámbar (`--color-accent`) sobre verde
muy oscuro casi negro en el hero, y secciones más claras (blanco/off-white)
en el resto del sitio. Tipografía: Space Grotesk (display) + DM Sans (texto)
+ DM Mono (labels/datos). Logo con isotipo "W" (bicolor magenta/verde azulado)
provisto por el cliente — usado también como favicon.

## Evidence on Hand

- Logo del Club: `assets/wayland-logo.png` (con fondo removido).
- Favicon recortado del isologo: `assets/favicon-32.png`,
  `assets/favicon-512.png`, `assets/apple-touch-icon.png`.
- Logos de respaldo institucional provistos por el cliente:
  `assets/badge-reprocann.png` (REPROCANN + Ministerio de Salud),
  `assets/badge-organicos.png` (Orgánicos de Argentina S.A.),
  `assets/badge-inase.jpg` (INASE).
- Contacto real: WhatsApp `https://wa.link/3i3nep`, Instagram
  `@the.waylandclub`.
- No hay fotografía propia del equipo/espacio todavía (placeholder activo).
- No hay catálogo de variedades/formatos confirmado todavía (teaser activo).

## Product Principles

1. Acompañamiento real por sobre venta — el tono nunca es de tienda.
2. Todo dentro del marco legal, y eso se demuestra con evidencia (REPROCANN,
   Ministerio de Salud, INASE, Orgánicos de Argentina S.A.), no solo se dice.
3. No inventar contenido que no esté confirmado (catálogo, fotos, precios,
   resultados) — mejor un placeholder honesto que un dato falso.
4. La membresía es una barrera de cero fricción: existe, pero nunca cuesta
   dinero ni tiempo de más — solo la documentación que ya exige REPROCANN.

## Accessibility & Inclusion

`prefers-reduced-motion` respetado (desactiva partículas, parallax y
animaciones de entrada). Sin requisito de accesibilidad adicional confirmado
por el cliente todavía.
