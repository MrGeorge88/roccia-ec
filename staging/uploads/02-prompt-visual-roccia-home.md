# Prompt visual maestro · Home de roccia.ec

> Este es el documento de referencia para diseñar la home de Roccia y, por extensión, el lenguaje visual de todo el ecosistema de dominios. Léelo de inicio a fin antes de generar cualquier mockup. Las decisiones aquí están cerradas excepto las marcadas como "explorar".

---

## 1. Contexto del proyecto

**Roccia** es una heladería italo-argentina artesanal en Plaza Briza, Cumbayá (Quito, Ecuador). El proyecto se está rediseñando desde un sitio inicial en Framer hacia un ecosistema de cuatro dominios construidos en Next.js + Vercel. La home de `roccia.ec` es la pieza maestra: define el lenguaje visual que el resto del ecosistema replica con coherencia.

**El reto creativo:** posicionar a Roccia como la heladería artesanal más relevante de Ecuador, comparable en calidad de marca a Salt & Straw (Portland), Van Leeuwen (NYC) o Morgenstern's (NYC), pero con una identidad genuinamente latinoamericana — italo-argentina con anclaje ecuatoriano.

**El resultado debe sentirse:** editorial, cálido, premium sin ser pretencioso, artesanal sin ser rústico, sofisticado sin ser corporativo.

---

## 2. Análisis competitivo: qué tomar de quién

### De Salt & Straw (saltandstraw.com)
**Tomar:** la idea de tratar cada sabor como un artículo editorial con narrativa de origen. Cada sabor en Roccia debe poder contar:
- País de origen del concepto (Italia / Argentina / Ecuador)
- Ingrediente protagonista y su procedencia (cacao de Manabí, pistacho siciliano, dulce de leche cocido lento)
- Una nota corta que despierte el sabor en la imaginación
- Foto cuidada del producto

**No tomar:** su estética whimsical / americana de food cart. Roccia es más sobria y europea.

### De Van Leeuwen (vanleeuwenicecream.com)
**Tomar:** la disciplina visual minimalista. Logo prominente. Paleta limitada y decidida. Anti-clutter. Tipografía con personalidad pero refinada. La idea de que "menos es más" en una categoría visualmente caótica.

**No tomar:** los amarillos pastel y la estética retro americana de los 50s. Roccia es una paleta de cremas y cafés, más europea.

### De Morgenstern's / Aesop / Le Labo
**Tomar:** el lenguaje editorial premium. Espacios amplios. Tipografía con jerarquía clara. Fotografía cálida con tono unificado. Sellos tipográficos como detalles artesanales.

### Del sitio actual de Roccia (Framer)
**Conservar:**
- Estructura de 4 categorías de sabores (Cremas / Dulces de Leche / Chocolates / Frutales Cremosos)
- Nombres en italiano: Pistacchio (con doble c), Stracciatella, Gianduia, Tiramisú, Mascarpone & Berries
- Sabores ecuatorianos como diferenciador: Higo con Queso, Guanábana, Taxo, Mango
- Frase "Tu pausa dulce, donde estés"
- Integración con Uber Eats, Rappi y PedidosYa (no solo una app)

**Reemplazar:**
- Headline "Somos la heladería más cálida del mundo" → demasiado declarativo
- Inglés suelto ("Your perfect spot for coffee, pastries...")
- Footer de Framer
- Estructura aplanada sin jerarquía editorial

---

## 3. Decisiones cerradas (no negociar sin razón fuerte)

### Paleta de marca (literal del manual)

```
Crema (dominante):    #faf4e0
Café oscuro:          #50351c
Café medio:           #846f59
Café neutro:          #66523a
Verde acento:         #335b40
Rojo acento:          #871d08
Azul acento:          #64b0bb
Mostaza acento:       #c6a252
```

**Regla del manual sobre proporción:**
- Café oscuro: 37%
- Crema: 33%
- Café medio: 15%
- Café neutro: 15%

Acentos (verde, rojo, azul, mostaza) solo aparecen como toques puntuales — nunca dominan. Se usan máximo dos colores acento por sección, y siempre acompañados de la cromática principal.

### Tipografía (del manual)

- **Display (Ranade Medium):** titulares y subtitulares. Generalmente en mayúsculas. Tracking -0.025em a -0.01em según tamaño. Para mockups donde Ranade no esté disponible, usar `Familjen Grotesk` como aproximación.
- **Cuerpo (IBM Plex Serif):** todo el cuerpo de texto. Pesos Medium (400-500) y SemiBold (600). Line-height 1.5-1.7 según contexto.
- **Acento manuscrito:** palabras puntuales en cursiva script tipo logo, intercaladas entre los titulares en mayúsculas. Aproximación: `Yellowtail` (Google Fonts). En producción se reemplaza por SVG del logotipo Roccia.

### Voz (del manual, no improvisar)

**Principios:** Gentil, Cercana, Evocativa.

**Reglas duras:**
- Frases cortas, palabras simples
- Punto final, nunca exclamaciones (excepto en raras ocasiones)
- Tú-form ecuatoriano. NUNCA voseo argentino, NUNCA "vos sos", NUNCA "che"
- Lenguaje conversacional pero no confianzudo
- Metáforas y imágenes claras (cosas que se pueden ver, oler, saborear)
- Evitar lugares comunes y descripciones abstractas

**Frases del manual ya establecidas (úsalas literal donde encajen):**
- "El frío es una dulce excusa para buscar abrigo"
- "De los Alpes a los Andes"
- "Una dulce excusa para verse"
- "Siéntate un poco más cerca"
- "Aquí nos gusta estar cerquita"
- "Volvieron tus favoritos"
- "Me gusta que el tiempo pase contigo"
- "Tu pausa dulce, donde estés"
- "Somos un lugar de pausas dulces"
- "Hacemos dulce el frío"

### Datos del local (verificar con Jorge antes de publicar)

```
Dirección:    Plaza Briza, Av. Francisco de Orellana y Tajamar, Cumbayá, Quito
Horario:      Lun - Dom 10:00 - 22:00  ← verificar con Jorge (PDF antiguo decía 11:30-20:00)
Teléfono:     +593 96 399 7478
Email:        hola@rocciaheladeria.com  ← reemplazar la2.heladeria@gmail.com
Instagram:    @roccia_ec
Delivery:     Uber Eats, Rappi, PedidosYa
```

---

## 4. Catálogo de sabores (literal del sitio actual de Roccia)

### Cremas
- **Vainilla Artesanal** — Clásica, suave y elegante
- **Pistacchio** — Intenso, verde y cremoso
- **Stracciatella** — Crema con delicados trozos de cacao ecuatoriano
- **Tiramisú** — Inspirado en el postre italiano
- **Mascarpone & Berries** — Dulce, fresco y frutal
- **Cookies & Cream** — Galletas crocantes con cacao
- **Cappuccino** — Café andino con notas cremosas

### Dulces de Leche
- **Clásico** — El sabor argentino por excelencia
- **Granizado** — Con escamas de chocolate amargo
- **Negro** — Más intenso y profundo
- **Con Almendras Caramelizadas** — Crujiente y acaramelado
- **Súper DDL** — Remolinos de dulzura pura

### Chocolates
- **Tradicional 70%** — Cacao profundo y equilibrado
- **Extra Cacao 85%** — Amargo, elegante y potente
- **Blanco** — Suave, dulce y sedoso
- **Gianduia** — Cremoso, avellana italiana con cacao ecuatoriano
- **Con Naranja** — Fresco, cítrico y aromático

### Frutales Cremosos
- **Fresa** — Dulce y refrescante de altura
- **Guanábana** — Cremoso, ácido y perfumado
- **Coco** — Suave, fresco y delicado
- **Higo con Queso** — Tradición serrana hecha helado
- **Mango** — Dulzura tropical de la costa
- **Taxo** — Ácido y goloso a la vez

---

## 5. Estructura de la home (orden de secciones)

1. **Header sticky** con logo, navegación y CTA "Pedir delivery"
2. **Hero** con statement editorial + foto vertical asimétrica + sello flotante
3. **Marquee horizontal** con frases evocativas (sutil, café oscuro sobre crema)
4. **Statement editorial extenso** — el párrafo narrativo del manual sobre el frío como excusa
5. **Origen Triple** — bloque oscuro con tres países y sus aportes (Italia / Argentina / Ecuador)
6. **Catálogo de sabores por categoría** — 4 categorías colapsables o tabs editoriales (Cremas / Dulces de Leche / Chocolates / Frutales)
7. **Sabor destacado / In Season** — un sabor del mes con foto grande y narrativa larga (estilo Salt & Straw)
8. **Menú de local con precios** — Helados / Café / Creaciones / Combos
9. **Tu pausa dulce, donde estés** — sección de delivery con las tres apps (Uber Eats, Rappi, PedidosYa)
10. **Ubicación + horario + mapa** — Plaza Briza Cumbayá
11. **Hook B2B (mayoristas)** — para llevar tráfico al formulario de mayoristas
12. **Footer con wordmark gigante** — links al ecosistema de dominios, redes, contacto

---

## 6. Especificaciones por sección

### 6.1 Header
- Sticky con backdrop-blur al hacer scroll
- Fondo `rgba(250, 244, 224, 0.85)` con blur
- Border-bottom 1px en café oscuro al 15% de opacidad
- Logo a la izquierda (script "Roccia" o SVG del logotipo)
- Nav central con caps tracking 0.14em, font-size 11px: Menú · Sabores · Historia · Ubicación · Mayoristas
- CTA derecha "Pedir delivery" como pill rellena de café oscuro con texto crema, ícono ArrowUpRight

### 6.2 Hero (asimétrico, validado por Jorge)
**Layout:** grid 12 cols. Texto a la izquierda (col 7). Foto vertical a la derecha (col 5).

**Copy del hero:**
- Pre-headline: sello "Cumbayá · Ec" + caption "Heladería artesanal"
- Headline en display tight, font-size clamp(56px, 9vw, 128px), 3 líneas:
  - "EL FRÍO ES"
  - "UNA *dulce* EXCUSA." (con la palabra "dulce" en script, font-weight normal, font-style normal)
- Subhead body: "En tierras frías hay más calor. En el alma, en la gente, en la comida. Hacemos gelato artesanal con ingredientes reales de Italia, Argentina y Ecuador. Te invitamos a sentarte un poco más cerca."
- CTAs: pill "Ver el menú" + link sutil "Visítanos en Plaza Briza" con ícono MapPin

**Foto:** vertical aspect-[4/5], filtro sepia(0.15) saturate(0.95). Sello rotado 6° en esquina superior derecha con texto "Una dulce excusa". Sello rectangular en esquina inferior izquierda con "Edición Febrero · 26".

**Animación:** rise + fade staggered (delays 0.05s, 0.18s, 0.32s, 0.48s). 0.9s cubic-bezier(0.2, 0.6, 0.2, 1).

**Indicador "scroll":** caption en esquina inferior con ChevronDown animado bouncing.

### 6.3 Marquee horizontal
- Border-y, fondo café oscuro `#50351c`, texto crema
- Padding vertical 32px
- Animación 40s linear infinite, translateX 0 → -50%
- Frases separadas por símbolo "✺" con opacidad 60%
- Lista de frases (rotando):
  - "De los Alpes a los Andes"
  - "Pausas dulces"
  - "Origen triple"
  - "Siéntate un poco más cerca"
  - "Hecho a mano en Cumbayá"

### 6.4 Statement editorial extenso
- Padding y 96px-160px
- Grid 12 cols. Sello "Sobre nosotros" en col 3. Párrafo grande en col 9.
- Font-size clamp(24px, 3vw, 34px), line-height 1.4
- Color principal café oscuro, segunda parte en café medio para crear ritmo:
  > "El frío nos hace sentarnos más cerca, abrazar más fuerte, entrelazar las manos, quedarnos más tiempo juntos. *Argentina y Ecuador, a los que hemos llamado hogar, nos han enseñado la dulzura del frío y el abrigo del encuentro.* Poniendo en práctica técnicas artesanales y usando ingredientes reales de nuestros distintos orígenes, creamos recuerdos comestibles."
- Background con grain sutil (radial-gradient pattern de puntitos al 8% de opacidad)

### 6.5 Origen Triple (validado por Jorge)
- Padding y 80px-128px
- Fondo café oscuro completo, texto crema
- Header: sello "Cap. uno" + headline "ORIGEN *triple.*" + párrafo lateral
- Grid 3 columnas con gap 1px (background crema al 15% para crear divisor)
- Cada columna:
  - Número (01 / 02 / 03) en color acento del país (mostaza / rojo / azul)
  - Caps "País"
  - Nombre del país en display
  - Párrafo body 16px con narrativa específica:
    - Italia: "La técnica del gelato. Cremosidad baja en grasa, sabores reales, pasta madre de pistacho siciliano."
    - Argentina: "Dulce de leche cocido lento. Heredamos la tradición de los maestros heladeros de Buenos Aires."
    - Ecuador: "Cacao de Manabí, Esmeraldas y Los Ríos. Frutas de altura. La tierra que hoy llamamos casa."

### 6.6 Catálogo de sabores por categoría
**Esta es la sección más importante después del hero.** Es donde Roccia compite con Salt & Straw.

**Layout:** tabs o secciones colapsables editoriales con las 4 categorías. Cada categoría tiene:
- Foto hero categórica (la del sitio actual: Cremas, Dulces de Leche, Chocolates, Frutales)
- Sabores listados como pares de "nombre — descripción" con tipografía editorial
- Filtro o navegación rápida entre categorías

**Estilo recomendado:** explorar dos opciones:
- **Opción A:** vista tipo carta italiana — lista tipográfica densa con filete dotted entre items, nombre en display medium izquierda, descripción en serif italic derecha
- **Opción B:** vista tipo grid Salt & Straw — cards con foto pequeña, nombre, descripción, tag de origen

**Decisión:** mostrar ambas opciones a Jorge para validar.

### 6.7 Sabor destacado / In Season
**Inspiración directa Salt & Straw.** Una sección donde un sabor del mes tiene foto grande, narrativa larga y storytelling editorial.

**Ejemplo (febrero 2026):** Stracciatella Triple Origen
- Foto vertical grande aspect-[3/4]
- Título display: "STRACCIATELLA *triple* ORIGEN"
- Bajada body: "Crema italiana con láminas de cacao ecuatoriano. Tres provincias, una sola historia."
- Párrafo de 80-120 palabras sobre el origen del cacao (Manabí, Esmeraldas, Los Ríos), la técnica de las láminas (62% cacao, aceite de coco), y por qué este sabor es especial este mes.
- CTA "Conoce su origen" → link al post del blog (cuando exista)

### 6.8 Menú de local con precios
- Fondo `#f3ead0` (un crema más cálido)
- Header centrado: sello "Menú · Local" + headline "PARA *compartir,* PARA LLEVAR."
- Grid 2 columnas con items:
  - Helados: Simple $2.75 / Doble $3.95 / ½ Litro $8.00 / 1 Litro $15.00 / Para compartir 1L+½L $21.00
  - Café: Affogato $4.90 / Expresso $2.50 / Expresso Doble $3.25 / Macchiato $2.80 / Americano $3.00 / Cappuccino $3.50
  - Creaciones: Brioscia $5.40 / Cornetto $5.40 / Torta helada $4.90 / Frappé $5.50
  - Combos: Expresso + 2 Alfajores $3.49 / Americano + 2 Alfajores $3.99 / Cappuccino + 2 Alfajores $4.49
- Items con dotted border-bottom (puntos espaciados)
- Tags "Insignia" en items destacados (Affogato, Para compartir)
- CTA al final: "Ver carta completa" → /menu

### 6.9 Tu pausa dulce, donde estés (delivery)
**Frase del sitio actual, conservar.**

- Sección con fondo crema o café medio neutral
- Headline: "Tu pausa dulce, *donde estés.*"
- Subhead: "Pide en tu app favorita o ven a visitarnos."
- 3 logos de delivery en línea: Uber Eats / Rappi / PedidosYa con links externos
- Cada logo en su contenedor cuadrado con borde sutil

### 6.10 Ubicación + horario + mapa
**Layout:** grid 2 cols. Info a la izquierda. Foto/mapa a la derecha.

- Sello "Visítanos"
- Headline: "AQUÍ NOS GUSTA *estar cerquita.*"
- Lista de info con íconos lucide (MapPin, Clock, Instagram, Phone):
  - Plaza Briza · Av. Francisco de Orellana y Tajamar · Cumbayá, Quito
  - Lun a Dom · 10:00 — 22:00
  - +593 96 399 7478
  - @roccia_ec
- Foto vertical aspect-[5/6] con filtro sepia. Overlay gradient inferior. Wordmark "Roccia" en script + tagline "Una dulce excusa para verse" sobreimpresos en la parte inferior.

**Versión avanzada:** mapa interactivo de Mapbox/Leaflet centrado en Plaza Briza con marcador custom.

### 6.11 Hook B2B (mayoristas)
- Sección con fondo café oscuro completo
- Grid 12 cols. Texto en col 7. CTA en col 5 alineado a la derecha.
- Caption caps: "Para restaurantes y hoteles"
- Headline: "Roccia *en tu mesa.*"
- Bajada: "Llevamos nuestra técnica artesanal a tu carta. Producción dedicada, sabores a medida, formatos profesionales. Conversemos."
- CTA pill rellena de crema con texto café: "Hablemos" → /mayoristas

### 6.12 Footer (validado por Jorge)
- Fondo crema, texto café oscuro
- Wordmark gigante "Roccia" en script, font-size clamp(80px, 16vw, 220px), line-height 0.9
- Grid de 4 columnas debajo:
  - **Ecosistema:** roccia.ec / heladosroccia.com / momentosroccia.com / rocciaheladeria.com
  - **Marca:** Historia / Sabores / Menú / Mayoristas
  - **Visítanos:** Plaza Briza / Cumbayá, Quito / 10:00 — 22:00 / Cómo llegar
  - **Síguenos:** Instagram / Uber Eats / Newsletter / hola@rocciaheladeria.com
- Línea legal bottom: © Roccia · Cumbayá · 2026 · "De los Alpes a los Andes" · "Hecho en Ecuador con técnica italiana"

---

## 7. Sistema de componentes recurrentes

### 7.1 Sello tipográfico (signature de la marca)
```css
.seal {
  border: 1px solid currentColor;
  padding: 6px 14px 5px;
  font-family: 'IBM Plex Serif', serif;
  font-weight: 500;
  font-size: 11px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  border-radius: 2px;
  position: relative;
}
.seal::before, .seal::after {
  content: '';
  position: absolute;
  width: 1px; height: 8px;
  background: currentColor;
  top: 50%; transform: translateY(-50%);
}
.seal::before { left: -5px; }
.seal::after { right: -5px; }
```

### 7.2 Headline con palabra script
Patrón: línea uno en display tight mayúsculas, palabra clave en medio en script font-style normal, font-weight normal, letter-spacing 0.

Ejemplo: `EL FRÍO ES UNA <em>dulce</em> EXCUSA.`

### 7.3 Botón pill primario
- Padding 16px 28px
- Border-radius 9999px
- Fondo café oscuro, texto crema
- Caps tracking 0.14em, font-size 11px
- Ícono ArrowUpRight 14px que se desplaza on hover (translate-x-1 -translate-y-1)

### 7.4 Filtro sepia para fotografía (validado por Jorge)
- Fotos de producto y ambiente: `filter: sepia(0.1) saturate(0.95)`
- Fotos de paisaje/montaña: `filter: sepia(0.2) saturate(0.85) brightness(0.95)`
- Mantiene unidad visual pero permite que cada foto respire

---

## 8. Lo que NO queremos hacer (anti-patterns)

- **No usar emojis** en ningún copy
- **No usar gradients** decorativos en backgrounds
- **No usar tipografías genéricas** tipo Inter, Roboto, Arial, system-ui
- **No saturar con colores acento** — máximo 2 acentos por sección, siempre acompañados de la cromática principal
- **No usar voseo argentino** ni argentinismos en el copy ("vos sos", "che", "boludo", "dale")
- **No mezclar inglés** suelto en el copy (excepto nombres de productos como "Cookies & Cream")
- **No usar exclamaciones** salvo en circunstancias muy contadas
- **No hacer hero centrado simétrico** — siempre asimétrico editorial
- **No usar fotografía de stock obvia** — todas las fotos deben sentirse propias o tener filtro sepia que las unifique
- **No usar elementos decorativos clichés** (corazones, estrellas, gradientes mesh, blob shapes)
- **No usar shadow-md / shadow-lg** de Tailwind — sombras solo cuando agreguen profundidad real

---

## 9. Criterios de éxito del mockup

Cuando el mockup esté terminado, debe pasar estas pruebas:

1. **Test del 5 segundos:** alguien que ve la home por 5 segundos debe poder decir: "es una heladería artesanal italo-argentina, premium, en Quito".
2. **Test del competidor:** poner el mockup al lado de Salt & Straw y Van Leeuwen y debe sentirse del mismo nivel de calidad de marca, pero con identidad propia.
3. **Test del manual:** cada decisión visual debe poder rastrearse a una guía del manual de marca (paleta, tipografía, voz, sellos, composición).
4. **Test del lector:** un usuario ecuatoriano debe entender todo sin tropezar con argentinismos ni anglicismos.
5. **Test del cliente B2B:** un comprador de un hotel 5 estrellas que llega al sitio por primera vez debe pensar "estos son profesionales".
6. **Test del Lighthouse:** Performance ≥90, SEO 100, Accessibility ≥95.

---

## 10. Decisiones por explorar (esto es lo que vamos a iterar)

Estas son preguntas abiertas que se resolverán generando variantes:

- **Sección de catálogo de sabores:** ¿vista carta italiana o vista grid Salt & Straw?
- **Sabor destacado:** ¿siempre en la home o solo cuando hay una historia que contar?
- **Mapa:** ¿foto del local con overlay tipográfico o mapa interactivo?
- **Hero:** ¿foto vertical de producto o foto wide de ambiente del local?
- **Tipografía display:** una vez tengamos Ranade real, evaluar si necesita ajustes de tracking/leading.

---

## 11. Iteraciones planificadas

**Iteración 1 (entregada):** primer mockup con dirección visual editorial. Validó: hero asimétrico, marquee, origen triple, wordmark gigante, sellos, filtro sepia.

**Iteración 2 (próxima):** aplicar los aprendizajes de este prompt:
- Catálogo de sabores con la estructura de 4 categorías
- Sección "Sabor destacado del mes" estilo Salt & Straw
- Sección de delivery con las 3 apps (Uber Eats, Rappi, PedidosYa)
- Mejorar el menú con datos completos del PDF de precios
- Verificar copy y datos de contacto correctos
- Probar 2 estilos para el catálogo (carta vs. grid)

**Iteración 3:** ajustes finos según feedback de iteración 2, foto de producto real cuando Jorge la tenga, tipografía Ranade real cuando esté disponible.

**Iteración 4:** mockup final aprobado → handoff a Claude Code.

---

## 12. Output esperado del mockup

Un único archivo `.jsx` exportable como artifact React (con Tailwind), de aproximadamente 600-800 líneas, que renderice una home completa, navegable, con todas las secciones detalladas arriba. Imágenes de Unsplash como placeholders curados (no random). Animaciones sutiles solo en el hero. Resto del sitio sin animaciones para mantener la calma editorial.
