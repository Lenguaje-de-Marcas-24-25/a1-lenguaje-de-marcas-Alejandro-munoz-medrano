# Lenguajes de Marcas

## 1. ¿Qué es un Lenguaje de Marcas?

Un **lenguaje de marcas** es un sistema de notación que utiliza etiquetas (o "marcas") para describir la estructura y el contenido de un documento. Los lenguajes de marcas permiten a los desarrolladores definir elementos, atributos y la jerarquía del contenido, facilitando así su presentación y procesamiento en aplicaciones.

---

## 2. Características Generales de los Lenguajes de Marcas

- **Estructura Jerárquica**: Los documentos están organizados en una estructura de árbol, donde los elementos pueden contener otros elementos.
- **Etiquetas**: Utilizan etiquetas para definir elementos, que pueden ser anidadas y contener atributos.
- **Extensibilidad**: Muchos lenguajes de marcas permiten a los usuarios definir sus propios elementos y atributos, como es el caso de XML.
- **Interoperabilidad**: Facilitan la integración y el intercambio de datos entre diferentes sistemas y plataformas.
- **Legibilidad**: Los documentos son generalmente legibles tanto por humanos como por máquinas.

---

## 3. Clasificación de los Lenguajes de Marcas

Los lenguajes de marcas se pueden clasificar en varias categorías:

### 3.1. Lenguajes de Marcas Estructurales
- **HTML (HyperText Markup Language)**: Utilizado para crear páginas web.
- **XML (eXtensible Markup Language)**: Utilizado para el almacenamiento y transporte de datos.

### 3.2. Lenguajes de Marcas Específicos
- **iCalendar**: Utilizado para el intercambio de información sobre eventos y calendarios.
- **vCard**: Utilizado para representar información de contacto.
- **KML (Keyhole Markup Language)**: Utilizado para representar datos geoespaciales.
- **RSS (Really Simple Syndication)**: Utilizado para la distribución de contenido web.

### 3.3. Lenguajes de Marcas Semánticos
- **Microdata**: Utilizado para agregar semántica a HTML mediante la inclusión de metadatos.

---

## 4. Ámbitos de Aplicación de los Lenguajes de Marcas

Los lenguajes de marcas se aplican en diversos ámbitos, tales como:
- **Desarrollo Web**: HTML y CSS para la creación de sitios web.
- **Intercambio de Datos**: XML, JSON y otros lenguajes para el transporte de datos entre aplicaciones.
- **Geolocalización**: KML para mostrar datos en sistemas de información geográfica.
- **Calendarios y Eventos**: iCalendar para gestionar eventos y citas.
- **Syndication de Contenido**: RSS para permitir que los usuarios se suscriban a actualizaciones de contenido en línea.

---

## 5. Ejemplos de Código

### 5.1. HTML
```html
<!DOCTYPE html>
<html>
<head>
    <title>Mi Página Web</title>
</head>
<body>
    <h1>Bienvenido a mi página</h1>
    <p>Esta es una página de ejemplo en HTML.</p>
</body>
</html>

### 5.2. iCALENDAR
BEGIN:VCALENDAR
VERSION:2.0
BEGIN:VEVENT
SUMMARY:Reunión de equipo
DTSTART:20231025T090000Z
DTEND:20231025T100000Z
END:VEVENT
END:VCALENDAR

### 5.3. vCARD
BEGIN:VCARD
VERSION:3.0
FN:Juan Pérez
ORG:Ejemplo S.A.
TEL;TYPE=WORK,VOICE:+123456789
EMAIL:juan.perez@ejemplo.com
END:VCARD

### 5.4. xml
<?xml version="1.0" encoding="UTF-8"?>
<kml xmlns="http://www.opengis.net/kml/2.2">
    <Placemark>
        <name>Parque Central</name>
        <Point>
            <coordinates>-73.9857,40.7484,0</coordinates>
        </Point>
    </Placemark>
</kml>


### 5.5. RSS
<?xml version="1.0" encoding="UTF-8"?>
<rss version="2.0">
    <channel>
        <title>Noticias de Ejemplo</title>
        <link>http://www.ejemplo.com</link>
        <description>Últimas noticias de Ejemplo</description>
        <item>
            <title>Título de la Noticia</title>
            <link>http://www.ejemplo.com/noticia</link>
            <description>Descripción breve de la noticia.</description>
        </item>
    </channel>
</rss>
