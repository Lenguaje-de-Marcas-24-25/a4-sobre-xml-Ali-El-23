[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/fGeLcsqO)
# A5-SOBRE-XML

## 1. Características propias del lenguaje XML
- **Extensible Markup Language (XML)** es un lenguaje de marcado utilizado para almacenar y transportar datos.
- Es **legible por humanos** y **fácil de analizar** por las máquinas.
- XML es **extensible**, lo que significa que no tiene un conjunto predeterminado de etiquetas, permitiendo a los usuarios definir sus propias etiquetas.
- Es **independiente de la plataforma** y puede ser usado en diferentes sistemas y aplicaciones.
- **Estructura jerárquica**: Los datos se organizan en una estructura de árbol con nodos, donde hay un solo nodo raíz.
- **Separación de contenido y presentación**, el formato de los datos está separado de cómo se presentan.

## 2. Estructura de un documento XML y sus reglas sintácticas
- Un documento XML está compuesto por elementos que comienzan con una **etiqueta de apertura** y terminan con una **etiqueta de cierre**.
  - Ejemplo: `<elemento>Contenido</elemento>`
- Las etiquetas deben estar correctamente **anidadas**.
- Debe haber un único **nodo raíz** que contenga todos los demás elementos.
- Todos los atributos deben estar **entre comillas**.
- Los nombres de las etiquetas distinguen entre **mayúsculas y minúsculas**.
- Los documentos XML deben estar **bien formados**, es decir, cumplir con todas las reglas sintácticas.

## 3. ¿Qué es un nodo raíz en XML?
Un **nodo raíz** es el elemento principal de un documento XML que contiene todos los demás elementos. Solo puede haber un nodo raíz en cada documento XML. Es el **inicio** y **fin** de la estructura jerárquica.

## 4. ¿Qué es un elemento vacío? Ejemplos
Un **elemento vacío** es un elemento que no contiene contenido ni otros elementos. Se define con una sola etiqueta que se cierra automáticamente.
- Ejemplo: `<imagen />` o `<br />`

## 5. ¿Qué sentido tiene crear documentos XML bien formados?
Crear documentos XML **bien formados** asegura que sean **legibles** tanto por humanos como por máquinas, y que cumplan con las **reglas sintácticas** establecidas. Esto permite una correcta **interoperabilidad** y facilita la validación, procesamiento y transformación de los datos.

## 6. ¿Qué es un espacio de nombres? Ventajas de uso.
Un **espacio de nombres** en XML es un mecanismo que permite **distinguir elementos** o atributos que pueden tener el mismo nombre pero diferentes significados o provenir de diferentes fuentes. Se define utilizando un **prefijo** asociado a una URL.
- **Ventajas**:
  - Evita **conflictos de nombres** entre elementos de diferentes vocabularios XML.
  - Facilita la integración de **múltiples esquemas** XML en un mismo documento.

## 7. Entidades en XML. Crea un XML con las entidades vistas en clase.
Las **entidades** en XML son atajos para caracteres especiales o secuencias de caracteres. Algunas entidades predefinidas son:
- `&lt;` : Representa `<` (menor que)
- `&gt;` : Representa `>` (mayor que)
- `&amp;` : Representa `&` (ampersand)
- `&apos;` : Representa `'` (comilla simple)
- `&quot;` : Representa `"` (comilla doble)

## 8.Comentarios en XML. Muestra uno de los ejercicios anteriores con el enunciado dentro de un comentario.
```xml
<contenido>
<!-- El siguiente XML muestra el uso de entidades -->
Esto es una prueba
</contenido>
