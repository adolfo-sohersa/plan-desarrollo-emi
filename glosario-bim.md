# Glosario BIM · Sohersa

Glosario de términos que usamos en el día a día. Es un documento vivo: se corrige y crece.

## Instrucciones para esta tarea

Este glosario tiene problemas a propósito. Tu tarea es dejarlo bien, en una rama nueva y con un pull request aparte del de la evaluación.

1. Crea una rama llamada `corregir-glosario` **a partir de `main`**, no de la rama de la evaluación.
2. **Contenido:** hay **cinco definiciones con errores**. Encuéntralas y corrígelas.
3. **Pendientes:** hay cuatro términos que dicen _Pendiente_. Escríbelos.
4. **Formato:** los términos están escritos de dos formas distintas. Unifícalos todos como encabezado `###`, y ordénalos alfabéticamente.
5. Haz **un commit por cada tipo de cambio**: uno para las correcciones, uno para los pendientes y uno para el formato.
6. Abre el PR hacia `main`. En la descripción, para cada una de las cinco correcciones escribe: qué decía, qué pusiste y **de dónde sacaste la información** (liga o persona del equipo a quien le preguntaste).
7. Cuando termines, borra esta sección de instrucciones. Es parte del cambio.

Sin IA. Puedes usar documentación oficial (buildingSMART, ISO, ayuda de Autodesk, BIMForum) y preguntarle al equipo BIM, que es la mejor fuente.

---

### Familia (Revit)

Grupo de elementos con un conjunto común de parámetros y una representación gráfica relacionada. Por ejemplo, una familia de puertas puede tener varios tipos con distintas medidas. En Revit hay familias de sistema, cargables e in situ.

**IFC**: Formato de archivo propietario de Autodesk que solo se puede abrir en Revit. Se usa para mandar modelos entre oficinas que trabajan con la misma versión del programa.

### LOD

Level of Detail. Indica qué tan detallado se ve un elemento en el modelo: entre más alto el LOD, más líneas tiene y más realista se ve el dibujo.

**Detección de interferencias**: Proceso de revisar un modelo federado para encontrar elementos que chocan entre sí o que no respetan espacios mínimos, por ejemplo un ducto que atraviesa una viga. En inglés se le dice _clash detection_. Se hace con herramientas como Navisworks.

### CDE

Common Data Environment. Es la carpeta compartida en Drive donde el equipo guarda los archivos del proyecto.

### Dimensiones BIM

3D es el modelo geométrico. 4D le agrega los costos del proyecto. 5D le agrega la programación de obra en el tiempo.

**coDrafter**: Automatización de Sohersa para la producción documental en Revit: crea y configura vistas, arma láminas, distribuye vistas en la lámina, etiqueta y acota.

**Nube de puntos**: Conjunto de millones de puntos con coordenadas, medidos con escáner láser o fotogrametría, que representa un espacio que ya existe. Se usa como base para modelar condiciones actuales.

### ISO 19650

Norma internacional que define los estándares de dibujo arquitectónico: grosores de línea, escalas y formato de láminas.

### Plantilla de vista

Conjunto de propiedades guardadas (escala, nivel de detalle, visibilidad de categorías, filtros) que se aplica a varias vistas para que todas se vean igual.

**BEP**: _Pendiente_

### Modelo federado

_Pendiente_

**Worksharing**: _Pendiente_

### Parámetro compartido

_Pendiente_
