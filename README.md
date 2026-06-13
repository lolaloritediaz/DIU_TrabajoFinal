# DIU Examen/Trabajo Final

Autora: Lola Lorite Díaz :octocat:

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

### Auditoría de Usabilidad y Experiencia de Usuario
Para evaluar el portal del Mercado Ecológico Guadalhorce de forma clara y estructurada, he agrupado los hallazgos en cinco dimensiones clave de interacción.

#### :pushpin: Arquitectura de la Información y Navegación
* **Observación:** Al acceder a la versión ordenador, se aprecia una interfaz que carece de un menú desplegable principal o lateral. En su lugar, los epígrafes principales (Inicio, Calendario, Productores, Sobre Nosotros, Hazte Socio) se encuentran en el *header*, facilitando los accesos directos. En la versión móvil sí aparece el menú desplegable con los mismos epígrafes. En el inicio podemos observar una frase motivadora y enlaces para hacernos socios y unirnos a la lista de difusión, y justo debajo encontramos la información para los siguientes eventos.
* **Evaluación UX:** Esta decisión de diseño reduce los pasos necesarios para navegar por la web, ya que el usuario ve todas las opciones sin tener que recordar dónde están. No obstante, al no existir una tienda online, la página prioriza las llamadas a la acción (CTA) informativas o de registro.

#### :pushpin: Diseño y Estética
* **Observación:** La página hace un uso notable de los espacios en blanco como separador entre bloques de contenido. Se apoya en un carrusel de fotografías del mercado y utiliza tonos verdes y tierra.
* **Evaluación UX:** El uso del espacio en blanco actúa como separador semántico entre bloques, facilitando la agrupación perceptiva según la ley de proximidad de la Gestalt. La paleta cromática refuerza la asociación con el dominio ecológico de forma coherente.

#### :pushpin: Accesibilidad Web (a nivel de interfaz)
* **Observación:** Lighthouse detecta fallos de contraste entre los colores de fondo y los textos principales o secundarios. También detecta que algunos encabezados no siguen un orden secuencial descendente. Se reportan además enlaces sin texto reconocible en el logotipo y áreas táctiles reducidas en los puntos de navegación del carrusel.
* **Evaluación UX:** Los fallos de contraste y el desorden de encabezados incumplen los principios Perceptible y Comprensible de las WCAG. En el EcoMercado UGR, al ser una iniciativa institucional de la UGR, estos criterios son de cumplimiento legal obligatorio.

#### :pushpin: Adaptabilidad (Responsive)
* **Observación:** La interfaz en móvil reorganiza los bloques en columna única, los botones se expanden al ancho de la pantalla y el menú se recoge en un desplegable. Sin embargo, la sección "Hazte Socio" no tiene estilos responsive aplicados, manteniéndose igual que en escritorio.
* **Evaluación UX:** La landing page sigue el principio Mobile First, pero la falta de adaptación en la sección de registro rompe la coherencia de la experiencia en ese flujo concreto.

#### :pushpin: Feedback y Gestión del Estado
* **Observación:** La sección inferior anticipa los "Próximos Mercados" con un aviso claro, guiando al usuario hacia lo que va a ocurrir a continuación.
* **Evaluación UX:** Se cumple la heurística sobre mantener al usuario informado del estado del sistema. En lugar de obligarle a buscar las fechas en menús internos, la página le da la información de manera proactiva, reduciendo la incertidumbre.

---

## **b. Comparación Mercado Ecológico Guadalhorce vs EcoMercado UGR**

Para fundamentar la propuesta de diseño, es necesario contrastar las soluciones de la plataforma de Guadalhorce con el estado actual del sitio informativo del EcoMercado UGR.

#### :bar_chart: La Página de Inicio (Home)
* **Mercado Guadalhorce:** Título claro, dos CTAs definidos y carrusel de fotos reales. Publica los próximos mercados e incluye testimonios. Aplica la heurística H1 de Nielsen al anticipar la próxima cita sin requerir navegación adicional.
* **Eco Mercado UGR:** Predomina el texto plano sobre lo visual. La falta de jerarquía visual eleva la carga cognitiva en la primera visita y dificulta identificar rápidamente qué ofrece el sitio.

#### :bar_chart: Arquitectura de Navegación
* **Mercado Guadalhorce:** Cabecera con los cinco enlaces esenciales a la vista, sin menús ocultos en escritorio, reduciendo la profundidad de clic para llegar al calendario o los productores.
* **Eco Mercado UGR:** Varios menús con demasiados apartados mezclados en el primer nivel, lo que eleva la carga cognitiva y dificulta encontrar información específica.

#### :bar_chart: Diseño Visual y Jerarquía
* **Mercado Guadalhorce:** Paleta cromática consistente y títulos diferenciados por peso tipográfico, facilitando el barrido visual. Las fotos de eventos refuerzan la identidad del proyecto.
* **Eco Mercado UGR:** La alta densidad de texto y la falta de contrastes visuales generan un patrón de lectura poco eficiente. Las imágenes, agrupadas al final y fuera del recorrido visual natural, no cumplen función de anclaje de atención.

#### :bar_chart: Diagnóstico de Accesibilidad (Lighthouse)
* **Mercado Guadalhorce:** Presenta fallos corregibles en el contraste de algunos textos secundarios y pequeños descuidos en el orden secuencial de las etiquetas de encabezado.
* **Eco Mercado UGR:** Presenta imágenes de noticias sin la etiqueta de texto alternativo (`alt`), enlaces repetidos con el mismo destino o con nombre poco descriptivo y problemas de legibilidad por el tamaño de la tipografía en párrafos densos.

#### :bar_chart: Comportamiento Responsive y Adaptabilidad
* **Mercado Guadalhorce:** Se adapta bien en móvil: columna única, botones amplios y menú recogido. El único fallo es la sección de socios sin estilos responsive
* **Eco Mercado UGR:** La adaptación móvil presenta déficits que afectan a la legibilidad y la operabilidad en pantallas estrechas. Al tener tanto volumen de texto, los párrafos se vuelven eternos en pantallas estrechas y los márgenes laterales se reducen demasiado, provocando que el contenido quede pegado a los bordes.

---

### 📝 Conclusión del Diagnóstico Comparativo

Mientras que el Mercado Ecológico Guadalhorce ofrece una experiencia de usuario ágil y visual, con un enfoque orientado a reducir la carga cognitiva del visitante gracias a su arquitectura minimalista y su jerarquía visual clara, la web actual del Eco Mercado UGR presenta una densidad informativa elevada, con carencias de legibilidad en dispositivos móviles y una ausencia de jerarquía visual que dificulta la orientación del usuario en el sitio.

Por lo tanto, nuestra propuesta de diseño para el Eco Mercado UGR no debe replicar el modelo corporativo actual. Debe importar la filosofía limpia y directa de Guadalhorce, resolviendo además sus puntos débiles: garantizando que el 100% de los flujos sean accesibles y responsive conforme al nivel AA de las WCAG 2.1, y convirtiendo la plataforma en un espacio dinámico que dé protagonismo a los agricultores locales y a las alertas de las próximas citas en el campus.

El resultado de WAVE (Web Accessibility Evaluation Tool) se encuentra en los siguientes enlaces:
* **[EcoMercado UGR](https://github.com/lolaloritediaz/DIU_TrabajoFinal/blob/6640d691937f6a3260af14807ee173696a7305e1/wave/El%20Ecomercado%20UGR%20celebra%20una%20nueva%20edici%C3%B3n%20el%2028%20de%20mayo%20con%20produ_%20-%20%5Bimprontagranada.es%5D.png)**
* **[Mercado Guadalhorce](https://github.com/lolaloritediaz/DIU_TrabajoFinal/blob/6640d691937f6a3260af14807ee173696a7305e1/wave/Inicio%20-%20Mercado%20Ecol%C3%B3gico%20Guadalhorce%20-%20%5Bguadalhorceecologico.org%5D.png)**

---

## **c. Propuesta de valor y diseño de Eco Mercado UGR**

Para la representación de la nueva plataforma interactiva del **Eco Mercado UGR**, se ha diseñado una estrategia centrada en el usuario que transforma el actual tablón informativo institucional en una web útil, práctica y accesible para la comunidad universitaria.

### :star: Matriz de Definición Estratégica (UX Strategy)

*   **Meta Principal:** Fomentar e incentivar el consumo responsable, la alimentación saludable y el conocimiento de los productos ecológicos de proximidad dentro del campus de la Universidad de Granada.
*   **Público Objetivo:** Principalmente alumnado de la UGR, personal docente e investigador, personal de administración y servicios, y ciudadanos granadinos interesados.
*   **Propuesta de Valor:** Una plataforma web que ofrece información sobre quiénes cultivan los alimentos, qué fechas se celebrará y mapas sobre las ediciones en los campus.
*   **Funcionalidades Críticas:**
    *   **Calendario Dinámico:** Agenda interactiva con las próximas citas del ecomercado.
    *   **Fichas de Productores:** Espacio dedicado a humanizar y conocer la historia de cada agricultor local junto con un enlace que nos lleva a su página.
    *   **Localizador de Puestos:** Mapa interactivo simplificado del campus correspondiente para ubicar los stands físicos.

---

### :pencil: Requisitos UX

La definición de los requisitos interactivos de nuestra propuesta se basa en los datos objetivos obtenidos tras realizar la auditoría de accesibilidad con la herramienta **WAVE**, cuyos resultados específicos están enlazados en el apartado anterior. 

Los informes de WAVE revelan fallos críticos de accesibilidad en ambas plataformas, siendo la web actual de la UGR la más perjudicada. En base a estos hallazgos, el nuevo diseño del Eco Mercado UGR implementará de manera estricta las siguientes directrices WCAG 2.1 AA para corregir estas deficiencias:

*   **Contraste y Legibilidad:** WAVE reporta múltiples problemas de contraste tipográfico. Nuestra propuesta utilizará una paleta de colores natural (verdes y tierras) pero ajustando estrictamente los ratios cromáticos para garantizar que los textos informativos sean legibles para personas con baja visión.
*   **Estructura Semántica Sólida:** Ante la inconsistencia detectada en la jerarquía de los títulos de la UGR, el nuevo layout web respetará escrupulosamente el orden de los encabezados (`<h1>`, `<h2>`, `<h3>`), permitiendo que los usuarios que navegan mediante lectores de pantalla puedan escanear la web de forma lógica y fluida.
*   **Etiquetado Limpio y Descritivo:** Se eliminarán por completo los enlaces sin nombre reconocible o redundantes que detectó WAVE. El logotipo de la cabecera tendrá un atributo `alt` correcto para volver al inicio, y las imágenes de los agricultores incluirán descripciones alternativas.
*   **Áreas de Interacción Optimizadas (Mobile-First):** Para solucionar las áreas táctiles reducidas observadas en los elementos deslizantes del mercado analizado, todos los componentes interactivos del Eco Mercado UGR poseerán un área de pulsación mínima, facilitando una navegación cómoda y sin errores en dispositivos móviles.

---

## **d. Bocetos Low-Fi**

En el siguiente enlace podemos observar nuestros [bocetos Low-Fi](https://github.com/lolaloritediaz/DIU_TrabajoFinal/tree/ae3c03cc60ba917f976e5c886f8afbbc4372eb42/low-fi)









## **e. Autoevaluación crítica y reflexión personal**
A diferencia de mi práctica de Goiko, que era un sistema transaccional enfocado en la conversión (reservar mesa o pedir comida), este caso me ha permitido analizar el UX institucional e informativo. En sistemas como el EcoMercado UGR, el éxito de la interfaz no se mide en clics de compra, sino en la claridad para comunicar eventos físicos (calendarios) y en la capacidad de conectar al usuario con el productor local.

Las técnicas aplicadas en Goiko —auditoría heurística, evaluación de accesibilidad con Lighthouse y WAVE, y análisis del flujo de tareas— son directamente transferibles a este caso. Sin embargo, el EcoMercado UGR añade una dimensión que Goiko no requirió: al ser una iniciativa de la UGR está obligada a cumplir el nivel AA de las WCAG 2.1, algo que en una web comercial privada no es un requisito legal sino una buena práctica.
