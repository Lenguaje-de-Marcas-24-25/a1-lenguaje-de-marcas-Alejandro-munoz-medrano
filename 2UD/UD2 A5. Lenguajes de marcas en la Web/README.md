# HTML y XHTML

## 1. ¿Qué es el lenguaje HTML?

HTML (HyperText Markup Language) es el lenguaje de marcado estándar para crear y estructurar el contenido en la web. Utiliza "etiquetas" para definir elementos como párrafos, encabezados, enlaces, imágenes, tablas y otros tipos de contenido que se presentan en los navegadores web. HTML es esencialmente el esqueleto de una página web, permitiendo organizar y estructurar el texto e insertar otros recursos multimedia.

---

## 2. Relación de Tim Berners-Lee con HTML

Tim Berners-Lee, un científico británico, es el creador de HTML. A finales de la década de 1980, mientras trabajaba en el CERN (Organización Europea para la Investigación Nuclear), desarrolló HTML como parte de un proyecto más amplio que incluía el desarrollo de la World Wide Web. En 1991, Berners-Lee publicó la primera versión de HTML, la cual se convirtió en la base para construir páginas web y navegar en la Web mediante enlaces de hipertexto.

---

## 3. Distintas versiones del lenguaje HTML

Desde su creación, HTML ha evolucionado a través de varias versiones:

- **HTML 1.0 (1991)**: Primera versión publicada por Tim Berners-Lee. Limitada en funcionalidad y diseño.
- **HTML 2.0 (1995)**: Estableció una primera estandarización por el IETF, añadiendo nuevas funcionalidades y mayor compatibilidad.
- **HTML 3.2 (1997)**: Incluyó mejoras en tablas, scripts y estilos, con un enfoque en la estructura y diseño visual.
- **HTML 4.0 (1997)**: Añadió soporte para CSS y mejoró el manejo de contenido multimedia. Se convirtió en un estándar formal de la W3C.
- **HTML 4.01 (1999)**: Revisión de HTML 4.0 con mejoras en accesibilidad y corrección de errores.
- **HTML5 (2014)**: Creado por la W3C y el WHATWG como una "Living Standard", añadió capacidades multimedia nativas y APIs modernas, haciéndolo ideal para aplicaciones web interactivas.

---

## 4. ¿Qué es la W3C?

La **W3C** (World Wide Web Consortium) es una organización internacional que desarrolla y mantiene estándares para la Web, como HTML, CSS, y XML. Fundada en 1994 por Tim Berners-Lee, la W3C busca garantizar que la Web esté disponible para todos y siga siendo accesible, interoperable y abierta, promoviendo estándares que faciliten la compatibilidad entre plataformas y dispositivos.

---

## 5. ¿Qué es el WHATWG?

El **WHATWG** (Web Hypertext Application Technology Working Group) es un grupo de trabajo fundado en 2004 por varios navegadores importantes, como Mozilla, Opera y Apple, con el objetivo de desarrollar y mejorar los estándares de la Web, centrándose especialmente en HTML y sus aplicaciones. WHATWG fue responsable de la creación de HTML5 y sigue trabajando en el desarrollo continuo del lenguaje como un "Living Standard", en contraste con los estándares más rígidos de la W3C.

---

## 6. ¿Qué es un "Living Standard"?

Un **Living Standard** (Estándar Vivo) es una especificación que se actualiza continuamente en lugar de versiones definitivas publicadas en intervalos largos. La idea es que, en lugar de tener múltiples versiones, el estándar se mejore y ajuste constantemente en respuesta a las necesidades y avances tecnológicos. HTML5, bajo el cuidado de WHATWG, se considera un Living Standard, ya que se va actualizando de manera progresiva.

---

## 7. ¿Qué es el lenguaje XHTML?

**XHTML** (eXtensible HyperText Markup Language) es una variante de HTML diseñada para cumplir con las reglas de XML (Extensible Markup Language), lo que la hace más estricta y estructurada. XHTML combina las características de HTML con la estructura y normas de XML, facilitando la interoperabilidad entre diferentes sistemas y aplicaciones.

---

## 8. Distintas versiones del lenguaje XHTML

- **XHTML 1.0 (2000)**: Primer estándar XHTML, basado en HTML 4.0, adaptado a la sintaxis de XML.
- **XHTML 1.1 (2001)**: Mejora de XHTML 1.0 con una estructura modular que permite una mayor personalización.
- **XHTML 2.0 (en desarrollo, luego descontinuado)**: Intento de la W3C de llevar el lenguaje a un nivel superior, pero nunca se completó debido a la popularidad de HTML5.

---

## 9. Diferencias sintácticas y estructurales entre XHTML y HTML

XHTML sigue normas de XML, mientras que HTML permite mayor flexibilidad. Estas son algunas diferencias:

- **Etiquetas cerradas obligatorias**: En XHTML, todas las etiquetas deben cerrarse (por ejemplo, `<br />` en lugar de `<br>`).
- **Sensibilidad a mayúsculas y minúsculas**: XHTML es sensible a mayúsculas, por lo que las etiquetas deben estar en minúsculas.
- **Atributos con valores entre comillas**: En XHTML, todos los atributos deben ir entre comillas dobles (`<input type="text" />`).
- **Documentos válidos**: Un documento XHTML debe estar bien estructurado y cumplir estrictamente con la sintaxis XML para ser válido.
- **Declaración XML**: Los documentos XHTML pueden empezar con una declaración `<?xml version="1.0" encoding="UTF-8"?>`.