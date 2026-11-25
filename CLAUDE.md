# Landing "Freestyle al Natural" — Mati (Mamba)

Landing de venta del curso online de freestyle de barbería de Mati (Matías), barbero, artista y educador, fundador de Mamba Barber Studio.
Se trabaja por pasos: cada sesión recibe un prompt y hace cambios en esta carpeta. Leé este archivo antes de tocar nada.

## Estructura
- `index.html`: la landing, construida sobre el HTML base del equipo (ver abajo). Un solo archivo, sin build ni frameworks.
- `assets/cortes/*.webp`: 6 fotos de diseños (verticales, 675x1200).
- `assets/personales/*.webp`: 6 fotos de Mati (1280x1600; `aleboscov-144` es horizontal 1600x675).
- `Marca Personal MATIMAMBA/`: material original del cliente. **No modificar.** Fuente de verdad para el copy:
  - `Copy of CLIENTE IDEAL.docx`: público, dolores, deseos, objeciones con sus respuestas.
  - `Copy of SECCIONES DE LA LANDING.docx`: copy de las secciones y FAQs.
  - `Manual de Marca Mamba.pdf`: identidad visual.
  - `index_backup_*.html`: landing que armó el equipo y funciona (originalmente para The Line Project). **Es la BASE de `index.html`**: se conserva su estructura, su JS y sus componentes (acordeón FAQ, video, garantía, botones de checkout, píxel), y encima se ponen el contenido y el diseño de Mati. Lo que hay que sacar sí o sí: textos, imágenes, colores y marca de The Line, y el ID del píxel y el link de Hotmart de ese proyecto (dejarlos como placeholder `TODO`).

## Producto
- Curso online **"Freestyle al Natural"**, método **"ARTE EN LÍNEAS"** (se aprende en papel, se plasma en el cabello).
- 12 clases: 4 teórico-prácticas (de 0 a 100) + 8 demostrativas en modelos reales (distintos diseños, tamaños, dificultades).
- +8 h de contenido, material en PDF y acceso de por vida. Acceso inmediato por invitación al mail.
- Diseños sin pigmento ni edición: solo pelo, limpieza de trazo y uso correcto de las herramientas.
- Frase gancho: "Entra un barbero bloqueado, sale un artista en líneas."
- Precio: **USD 40**, pago único, acceso de por vida. Sección de precio en `#comprar` (todos los CTAs llevan ahí).
- Medios de pago: Argentina → Mercado Pago (tarjeta, dinero en cuenta, transferencia; precio en ARS a definir). Resto del mundo → Hotmart (OXXO y tarjetas en México, PSE en Colombia, PIX y boleto en Brasil, tarjetas y PayPal en USA). PayPal directo como alternativa.
- Ojo: los docs dicen "+4 modelos" y "+6 modelos". Confirmar con el cliente antes de publicar; mientras tanto, usar "+4".

## Público
- Barberos de 18 a 32 años (pico de 20 a 28) que YA cortan profesionalmente. No es para principiantes.
- Experiencia: de 1 a 3 años si quieren aprender, de 3 a 5 si quieren mejorar.
- Países: Argentina, México, USA, Colombia y Brasil. Escribir en español rioplatense neutro (vos, querés).
- Quieren diferenciarse, crecer en redes, competir y tener portfolio. No buscan aprender a cortar.

## Marca (del manual)
- Colores: negro `#101010` (base), morado profundo `#0E002C`, Morado Mamba `#301764`, morado energía `#764CFF`, blanco `#FFFFFF` y acento naranja `#FF7800` (con moderación, por ejemplo en CTAs).
- "El negro sostiene la identidad. El morado concentra la energía. El blanco garantiza respiración y contraste."
- Tipografía: **Giga Sans** (todavía no tenemos los archivos de la fuente). Mientras tanto usar una geométrica parecida de Google Fonts (p. ej. Montserrat o Outfit) con un fallback fácil de cambiar.
- Logo: isotipo "M" (versiones isotipo / contorno / frontal / creativo). Solo existe dentro del PDF: pedir SVG/PNG al cliente o usar texto "MAMBA" mientras tanto.
- Estética: oscura, con brillos y gradientes morados, y "concepto urbano" con graffiti morado.
- Valores: Precisión. Actitud. Constancia. Inspirado en la "Mamba mentality" (Kobe Bryant).

## Secciones previstas
Hero → Qué vas a aprender → Lo que te llevás → Este curso es para vos si… → Galería de diseños → Quién soy → Objeciones/FAQ → CTA final.

## Pendientes (se hacen al final, no bloquean)
- Links reales de pago (hoy `#TODO-mercadopago`, `#TODO-hotmart`, `#TODO-paypal`) y precio en pesos para Argentina.
- Testimonios y métricas de alumnos, video de presentación, garantía (¿sí o no?), logo vectorial, archivos de Giga Sans y píxel de Meta.

## Reglas
- Mobile first: la mayoría del tráfico llega desde Instagram.
- El usuario prueba en **iPhone (Safari iOS)**, por el servidor Vite del puerto 5173. Todo efecto (máscaras CSS, sticky, animaciones atadas al scroll, parallax) tiene que andar bien en iOS Safari, también mientras el dedo arrastra la pantalla.
- Imágenes siempre desde `assets/` en webp, con `loading="lazy"` (excepto el hero) y `alt` descriptivo.
- No inventar testimonios, cifras ni premios.
- Publicación: la web está en GitHub Pages (https://contrinij-alt.github.io/mamba-landing/, repo `contrinij-alt/mamba-landing`, rama `main`). Al terminar cada paso, hacer commit y `git push` para que el link quede actualizado. `Marca Personal MATIMAMBA/` está en `.gitignore`: nunca subirla.
- Bitácora: cada prompt del usuario se anota solo en `BITACORA.md` (hook). Al terminar cada prompt, agregar debajo un bloque "**Hecho:**" con lo que se cambió y lo que quedó pendiente.
