# DIU Examen/Trabajo Final

Autora: Lola Lorite Díaz

Junio 2025

---

# PARTE I - MI EXPERIENCIA UX




---

# PARTE II - CASO DE ESTUDIO: Propuesta de diseño ECO MERCADO UGR
## **[a. Análisis de Mercado Ecológico Guadalhorce](https://guadalhorceecologico.org/)**

Las plataformas dedicadas a la distribución de productos de proximidad persiguen los siguientes objetivos:
- conectar a los consumidores con el entorno agrícola local
- concienciar sobre la sostenibilidad ambiental

En el ámbito de la experiencia de usuario (UX), el éxito se consigue mostrando de manera transparente la oferta comercial junto con la identidad de los agricultores, los puntos de recogida y los pasos para realizar la compra.

### 1. Auditoría de Usabilidad y Experiencia de Usuario
Para evaluar el portal del Mercado Ecológico Guadalhorce de forma clara y estructurada, he agrupado los hallazgos en cinco dimensiones clave de interacción.

#### 📌 Arquitectura de la Información y Navegación
* **Observación:** Al acceder a la versión ordenador, se aprecia una interfaz sumamente limpia y clara que carece de un menú desplegable principal o lateral. En su lugar, los epígrafes principales (Inicio, Calendario, Productores, Sobre Nosotros, Hazte Socio) se encuentran en la cabecera del sitio web (*header*), facilitando un acceso inmediato a la información. Sin embargo, en la versión móvil si aparece el menú desplegable (debido a una cuestión de espacio) con los mismos epígrafes. En el inicio de la página podemos observar una frase motivadora y enlaces para hacernos socios y unirnos a la lista de difusión, y justo debajo encontramos la información para los siguientes eventos.
* **Evaluación UX:** Esta decisión de diseño reduce los pasos necesarios para navegar por la web, además de aprovechar de formaeficiente el espacio superior. No obstante, al no existir una tienda online la página prioriza las llamadas a la acción (CTA) informativas o de registro.

#### 📌 Diseño Visual y Estética
* **Observación:** La página transmite una sensación de orden y claridad gracias al uso inteligente de los espacios en blanco. Se apoya de un carrusel de fotografías del mercado que aportan cercanía y utiliza tonos verdes y tierra ligados al concepto sostenible.
* **Evaluación UX:** La página destaca por tener un estilo minimalista y limpio. Transmite una sensación de orden gracias al inteligente uso de los espacios en blanco. El aspecto visual de la página transmite los valores ecológicos del proyecto utilizando una paleta de colores muy asociada a la naturaleza y la agricultura.

#### 📌 Accesibilidad Web (a nivel de interfaz)
* **Observación:** Al pasar la herramienta Lighthouse, el portal muestra fallos de contraste en la relación entre los colores de fondo y los textos principales o secundarios. También detecta que algunos elementos de encabezado (títulos) no siguen un orden secuencial descendente (por ejemplo, pasar de un \<h1\> a un \<h3\> directamente). Aunque se reportan enlaces sin nombres reconocibles en el logotipo de inicio y áreas táctiles reducidas en los pequeños puntos de navegación del carrusel de opiniones, se consideran elementos secundarios que no bloquean la navegación principal.
* **Evaluación UX:** Los problemas de contraste cromático y el desorden de los encabezados son barreras importantes que incumplen las pautas WCAG (principios Perceptible y Comprensible). Al trasladar esto al Ecomercado UGR, donde el acceso institucional debe ser 100% inclusivo, es obligatorio asegurar que la jerarquía de los títulos sea limpia para que los lectores de pantalla que usan personas ciegas funcionen bien, y que los textos tengan un contraste fuerte sobre el fondo para personas con problemas visuales.

#### 📌 Adaptabilidad (Responsive)
* **Observación:** El comportamiento general de la interfaz en dispositivos móviles está muy bien resuelto. Los epígrafes de la cabecera se recogen correctamente en un menú principal desplegable para salvar espacio. Además, los bloques visuales se reorganizan de forma limpia, colocando las imágenes justo debajo de los textos de manera ordenada. Los botones principales también se expanden para ocupar un buen ancho de la pantalla, facilitando que se puedan pulsar de forma cómoda. Sin embargo, se detecta un fallo crítico al acceder a la página de "Hazte Socio": esta sección concreta no ha sido adaptada a formato responsive, manteniendo la misma configuración visual que en la versión de ordenador.
* **Evaluación UX:** Aunque la landing page cumple con creces el principio *Mobile-First*, la falta de adaptación en la sección de registro rompe por completo la consistencia de la experiencia de usuario. Además, esta sección de registro son simplemente indicaciones de cómo te puedes hacer socio de forma presencial, lo que significa que los usuarios no pueden hacerse socios de forma online. 

#### 📌 Feedback y Gestión del Estado
* **Observación:** La sección inferior anticipa los "Próximos Mercados" con un aviso claro ("¡No te pierdas el siguiente!"), guiando el ojo del usuario hacia lo que va a ocurrir a continuación.
* **Evaluación UX:** Se cumple la heurística sobre mantener al usuario informado del estado del sistema. En lugar de obligarle a buscar las fechas en menús internos, la página le da la información de manera proactiva, disminuyendo la incertidumbre.

---

## **b. Comparación Mercado Ecológico Guadalhorce vs ECO Mercado UGR
















## **c.**
A diferencia de mi práctica de Goiko, que era un sistema transaccional puramente enfocado en la conversión (hacer una reserva de mesa o pedir comida), este caso de estudio me ha permitido explorar el UX institucional e informativo. Me ha hecho ver que, para iniciativas como el Ecomercado UGR, el éxito de la interfaz no se mide en clicks de compra, sino en la claridad para comunicar eventos físicos (calendarios) y en la capacidad de conectar de manera humana al usuario con el productor local.
