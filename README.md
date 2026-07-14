# Bot Fiora — releases

Este repositorio contiene **únicamente los binarios** de las versiones publicadas del
**Bot Fiora**, la herramienta interna de causación contable de Russell Bedford DSA.

**Aquí no hay código.** El código fuente vive en un repositorio privado.

## Por qué existe

GitHub no permite publicar un *release* público desde un repositorio privado: el asset
hereda la visibilidad del repo. Como el bot necesita descargar sus actualizaciones sin
credenciales — directo del CDN, sin que ~90 MB atraviesen un servidor intermedio — los
binarios se publican aquí, y el código se queda privado donde debe estar.

## Cómo se actualiza el bot

El bot consulta este repositorio al arrancar y muestra un aviso si hay una versión más
nueva. No hay que instalar nada a mano.
