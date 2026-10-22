# Prompts de óleo con empaste

Plantilla en español para pedir imágenes con aspecto de **óleo figurativo sobre lienzo, empaste grueso y trabajo de espátula**, con iluminación dramática y composición cinematográfica.

![Referencia visual de empaste grueso: Bruce Wayne ante la armadura de Batman](referencias/bruce-wayne-empaste.png)

## Qué contiene

- [`estilo.json`](estilo.json): la plantilla original de instrucciones de estilo.
- [`ejemplos/costa-mediterranea.json`](ejemplos/costa-mediterranea.json): una versión completa con una escena y una paleta elegidas.
- [`ejemplos/prompt-listo.txt`](ejemplos/prompt-listo.txt): un ejemplo listo para copiar como texto.
- [`referencias/`](referencias/): imagen aportada como referencia visual de textura y acabado.

## Cómo usarlo

1. Abre `estilo.json` y copia su contenido.
2. Sustituye el campo `escena` por el sujeto, el lugar y la acción que quieras representar.
3. Elige una de las paletas o describe otra coherente con tu escena. Las paletas alternativas son opciones, no una petición de mezclarlas todas.
4. Pega el JSON en una herramienta de generación de imágenes que permita instrucciones en lenguaje natural. Puedes acompañarlo de la referencia visual si la herramienta admite imágenes.
5. Pide: «Genera una imagen siguiendo esta especificación. Usa la referencia para la textura pictórica y representa la escena indicada».
6. Si la herramienta tiene un selector de formato, selecciona también 16:9.

El JSON organiza un prompt: **no es un programa, un modelo de IA ni una API ejecutable**. No requiere instalar dependencias. La interpretación y el resultado dependen de la herramienta utilizada; la plantilla no garantiza una reproducción exacta de la referencia.

## Ejemplo de escena

> Una villa mediterránea de terracota junto al mar, con dos palmeras en primer plano, una pequeña embarcación en la bahía y luz dorada de última hora de la tarde.

Para empezar directamente, copia [`ejemplos/prompt-listo.txt`](ejemplos/prompt-listo.txt).

## Qué buscar en el resultado

- Pinceladas cortas, densas, irregulares y superpuestas.
- Crestas de pintura visibles y sensación de relieve material.
- Sujetos reconocibles con detalles concentrados en el foco principal.
- Sombras profundas, acentos luminosos y una paleta limitada.
- Una única escena horizontal, sin texto ni elementos de interfaz.

Si el resultado parece una fotografía con textura, refuerza la indicación: «Construye las formas con manchas y trazos de pintura visibles; simplifica los detalles secundarios».

## Referencia visual

La imagen aportada muestra a Bruce Wayne ante la armadura de Batman. Se incluye como referencia del acabado pictórico. La plantilla de estilo puede aplicarse a otras escenas y personajes. Este proyecto no declara afiliación oficial con los titulares de esos personajes ni concede derechos sobre ellos o sobre la imagen de referencia.
