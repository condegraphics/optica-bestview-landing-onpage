---
proyecto: Óptica Best View
paleta:
  fire-red: "#F23E02"
  light-cream: "#FFFDF1"
  teal-blue: "#7BBBC0"
  dark-navy: "#013750"
  black: "#000000"
  neutral-surface: "#FFFFFF"
  line: "rgba(1, 55, 80, 0.20)"
tipografia:
  titulos: Bricolage Grotesque, 400–800
  parrafos-interfaz: Roboto, 400–700
cta:
  enlaces-de-accion: botones-solidos
  texto: mayusculas
  iconos: no
  fondo: dark-navy
  texto-color: "#FFFFFF"
  borde: ninguno
  margin-top: 2.6rem
  excepcion-margin: header
  hover: black
---

# Dirección visual — Óptica Best View

## Dirección
Landing editorial de moda óptica, moderna y cercana. La fotografía del cliente conduce la experiencia; el sistema cromático aporta contraste, energía y jerarquía sin competir con las imágenes. Prioridad: orientación rápida, confianza local y consulta por WhatsApp. El contenido sigue siendo HTML estático y no depende de JavaScript.

## Paleta aprobada

| Color | HEX | Uso principal |
|---|---|---|
| Fire Red | `#F23E02` | Acentos visuales y señales de acción |
| Light Cream | `#FFFDF1` | Fondo claro, superficies y texto sobre navy |
| Teal Blue | `#7BBBC0` | Tintes de sección, acentos e interacción |
| Dark Navy | `#013750` | Secciones de alto contraste, títulos y botones CTA |
| Negro | `#000000` | Texto principal, sobreimpresiones y CTA sobre tonos vivos |
| Blanco neutro | `#FFFFFF` | Uso moderado en tarjetas y superficies para separar planos |

Las líneas y las superficies tenues se construyen con transparencias derivadas de estos tonos; no incorporan una paleta cromática paralela.

## Contraste y componentes
- Fire Red con texto negro: **5,47:1**.
- Teal Blue con texto negro: **9,71:1**.
- Dark Navy con Light Cream: **12,37:1**.
- Todo enlace de conversión se presenta como botón sólido Navy con texto blanco, en mayúsculas y sin iconos.
- Los botones CTA no tienen borde y usan un margen superior de 2.6rem; el botón del encabezado queda exceptuado. El hover pasa a negro.
- `:focus-visible` conserva un indicador claramente distinguible en fondos claros y oscuros.

## Tipografía y composición
- **Títulos:** Bricolage Grotesque, pesos 400–800.
- **Párrafos e interfaz:** Roboto, pesos 400–700.
- Contenedor máximo de 1220 px; gutters, tamaños y espacios fluidos con `clamp()`.
- Tarjetas de esquinas suaves, secciones respiradas y fotografías reales aportadas por el cliente.
- Los fondos y tintes de secciones se derivan de Cream, Teal, Fire Red, Navy y negro. Los degradados quedan reservados para mejorar la lectura sobre fotografía.

## Accesibilidad y comportamiento
- HTML semántico, enlaces con destino explícito, controles de teclado y foco visible.
- Menú móvil y FAQ con elementos nativos (`details`/`summary`).
- Estados de movimiento reducidos según `prefers-reduced-motion`.
- Sin autoplay de video, scripts funcionales, trackers ni formularios externos.

## Criterios de contenido
- Priorizar imágenes del proyecto; no agregar stock ni visuales generados.
- No mostrar promociones, reseñas, rating ni condiciones comerciales sin verificación vigente.
- La vista de revisión permanece `noindex` hasta una decisión de publicación.
