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
- "MADE Waffle Soft" (tipografía primaria del brand book oficial) es gratis
  solo para uso personal — no está licenciada para uso comercial. El sitio
  usa "Montserrat" (Google Fonts, gratis, recta/geométrica — el cliente
  probó primero "Baloo 2" rounded y pidió algo más recto) hasta que el
  cliente compre la licencia comercial de Waffle Soft; si la compran,
  reemplazar `--font-display` y cargar el archivo propio.

## Brand Commitments

Nombre: The Wayland Club. Paleta oficial del brand book del cliente
(2026-08-21): negro `#000000` / blanco `#ffffff` como base, con jerarquía de
acento deliberada (no las 6 en igual peso):
- **Teal `#155574`** — acento estructural/institucional: bordes, íconos,
  eyebrow, indicador de nav, links. Reemplaza el dorado que yo había
  propuesto en la primera iteración.
- **Magenta `#eb269f`** — acento de acción, usado con moderación: fondo de
  botones primarios, CTA del nav, el bloque CTA final. Nunca como fondo de
  sección completa fuera de esos momentos puntuales.
- **Mustard `#bbb54e`** — textura chica: partículas del hero, detalles de
  gradiente. Oliva `#404416` — tinte profundo en gradientes, no protagonista.

Tipografía: "Montserrat" (display/headlines, ver nota de licencia arriba) +
DM Sans (cuerpo general, incluida la bajada del hero y el párrafo de
REPROCANN — Arapey italic se probó ahí y se revirtió por pedido del
cliente) + DM Mono (labels/datos). Logo con
isotipo "W" (bicolor magenta/teal) provisto por el cliente — usado también
como favicon y, recortado, como ícono de marca en el nav junto al wordmark
"The Wayland Club".

## Evidence on Hand

- Logo del Club: `assets/wayland-logo.png` (con fondo removido).
- Favicon recortado del isologo: `assets/favicon-32.png`,
  `assets/favicon-512.png`, `assets/apple-touch-icon.png`.
- Logos de respaldo institucional provistos por el cliente:
  `assets/badge-reprocann.jpg` (REPROCANN), `assets/badge-organicos.jpg`
  (Orgánicos de Argentina S.A.), `assets/badge-ministerio.jpg` (Ministerio de
  Salud, logo propio y separado de REPROCANN), `assets/badge-inase.jpg`
  (INASE). Orden fijo en la sección "Todo dentro del marco legal": REPROCANN,
  Orgánicos, Ministerio, INASE — en mobile rotan solos en un carrusel.
- Imagen de ejemplo de la credencial REPROCANN (`assets/reprocann-card.jpg`,
  datos ficticios "Juan Perez") ilustrando la sección "¿Qué es REPROCANN?".
- Envíos: solo dentro de Buenos Aires (NO "todo el país" — corregido
  2026-08-21, era un error del contenido anterior).
- Contacto real: WhatsApp `https://wa.link/3i3nep`, Instagram
  `@the.waylandclub`.
- Foto real de planta cultivada por el cliente en "Quiénes somos"
  (`assets/about-photo.jpg`) y una foto de cogollo suelto (variedad Black
  Cherry) usada como elemento animado en el hero (`assets/cogollo-hero.png`,
  fondo removido, rota/flota con el scroll).
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
