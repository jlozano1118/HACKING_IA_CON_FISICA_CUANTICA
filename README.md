# ∿ Ciencias básicas: los cimientos de la ingeniería

Recorrido **interactivo** que va de una onda de sonido a la **transformada de Fourier**, el **cálculo integral** y la **computación cuántica aplicada a la ciberseguridad**. Pensado para cualquier persona que esté por entrar, esté cursando o ya vaya avanzada en una ingeniería.

> Las ciencias básicas (álgebra, trigonometría, probabilidad, física, cálculo, álgebra lineal) no viven aisladas: este sitio muestra cómo se conectan en tecnologías reales.

## Contenido

| # | Sección | Qué puedes hacer |
|---|---|---|
| 1 | ¿Qué es una onda? | Cambiar frecuencia y amplitud; ver cresta, valle, λ y periodo |
| 2 | Superposición | Sumar dos ondas y ver interferencia constructiva, destructiva y pulsaciones |
| 3 | Transformada de Fourier | Mezclar Do, Re, Mi, Fa; enrollar la señal y ver aparecer el espectro (con audio) |
| 4 | Cálculo integral | Girar `y = sin(x)` y calcular su volumen por discos: `π²/2` |
| 5 | Clásica vs cuántica | Ver por qué simular n cúbits necesita `2ⁿ` amplitudes |
| 6 | Frecuencia (Hz) | Desafinar un pulso de microondas y ver fallar una puerta cuántica |
| 7 | Longitud de onda (λ) | Enviar fotones por fibra a 600, 850, 1310 y 1550 nm |
| 8 | Amplitud (A) | Protocolo de pulsos señuelo: activar a "Eva" y verla delatada |
| 9 | Amplitud de probabilidad | Algoritmo de Grover paso a paso con 8 estados |
| — | Quiz | 8 preguntas de *active recall* |

Además: mapa de ciencias básicas que resalta dónde se usa cada una, modo claro/oscuro y diseño adaptado a celular.

## Cómo verlo

**En línea (GitHub Pages):**
1. Sube `index.html` y `README.md` a la raíz del repositorio.
2. En GitHub: *Settings → Pages → Build and deployment → Source: Deploy from a branch*, rama `main`, carpeta `/ (root)`.
3. En uno o dos minutos queda en `https://jlozano1118.github.io/<nombre-del-repo>/`.

**En tu computador:** descarga `index.html` y ábrelo con doble clic. No necesita instalar nada ni conexión a internet.

## Tecnología

Un solo archivo HTML con CSS y JavaScript puros (Canvas 2D y Web Audio). Sin librerías ni dependencias.

## Notas de rigor

Las simulaciones son modelos educativos simplificados. Dos precisiones que el sitio explica:
- En QKD la **pérdida** de fotones es normal; lo que delata a un espía es la **tasa de errores** o una **estadística de llegadas** que no cuadra.
- Grover da una ventaja **cuadrática** (≈ √N pasos), no rompe claves "en segundos". La amenaza real para RSA/ECC es el algoritmo de **Shor**, basado en la transformada cuántica de Fourier.

## Referencias

- 3Blue1Brown, *But what is the Fourier Transform? A visual introduction* (2018).
- L. K. Grover, *A fast quantum mechanical algorithm for database search* (1996).
- P. W. Shor, *Algorithms for quantum computation: discrete logarithms and factoring* (1994).
- H.-K. Lo, X. Ma, K. Chen, *Decoy State Quantum Key Distribution* (2005).

## Autor

**Juan Lozano** — Ingeniería de Sistemas y Computación, Universidad Católica de Colombia.
[GitHub](https://github.com/jlozano1118) · [Instagram](https://instagram.com/js_lozanocalderon)

Con gratitud a los profesores de ciencias básicas Giovanni Martínez (2022-1), Ruben castaneda (2022-3), Mario Suarez (2022-3), Valery Cely (2024-1), Nelson Fino(2024-1/2024-3/2025-3), Fredy Sierra (2024-3) y Leonardo Silva (2025-3). Construido con IA como copiloto; el entendimiento, las preguntas y las conexiones son trabajo humano.
