# Proyecto: Bitácora de Seguimiento - ADSO

**Aprendiz:** Karen Dayana Villamizar Reyes
**Ficha:** 3381732
**Programa:** Análisis y Desarrollo de Software - SENA

## 📝 Descripción del Proyecto
Este repositorio contiene la transformación digital de la bitácora de seguimiento (originalmente en Excel) a un sitio web estático estructurado únicamente con HTML5 puro. El objetivo es documentar de manera cronológica y accesible las actividades, evidencias e impedimentos presentados durante el mes de Agosto en el desarrollo del proyecto formativo.

## 📂 Estructura de las Vistas
El proyecto está dividido en tres vistas principales que simulan las hojas del libro de Excel original, accesibles desde un menú de navegación principal:

1. **Vista de Información (`informacion.html`):** Contiene los datos generales del aprendiz, la competencia y el periodo de formación.
2. **Vista de Reglas (`reglas.html`):** Detalla las reglas de oro para el llenado de la bitácora y la guía de cada una de las columnas de la tabla.
3. **Vista de Trazabilidad (`trazabilidad.html`):** Es la tabla principal donde se registran cronológicamente las actividades. Está dividida por semanas (Semana 1, Semana 2, Semana 3 y Semana 4), cada una en su respectivo archivo HTML, para facilitar la lectura y el mantenimiento del código.

*(Nota: El menú de navegación permite ir y volver entre estas tres vistas sin usar el botón "atrás" del navegador).*

## ♿ Prácticas Semánticas y de Accesibilidad Implementadas
Para garantizar que el sitio sea inclusivo y cumpla con los estándares web, se implementaron las siguientes prácticas:

**Semántica HTML:**
* Uso de etiquetas estructurales claras como `<header>`, `<nav>`, `<main>` y `<footer>` para delimitar las zonas de la página.
* Uso correcto de la jerarquía de encabezados (`<h1>`, `<h2>`, `<h3>`) para crear un índice lógico del contenido.
* Uso de la etiqueta `<table>`, junto con `<thead>`, `<tbody>`, `<tr>` y `<th>` para representar datos tabulares de manera estructurada, permitiendo a los navegadores entender la relación entre filas y columnas.
* Uso de la etiqueta `<caption>` para darle un título descriptivo a las tablas.

**Accesibilidad (a11y):**
* **Atributo `lang="es"`:** Declarado en la etiqueta `<html>` para que los lectores de pantalla pronuncien el texto con fonética española.
* **Atributo `scope`:** Utilizado en los encabezados de la tabla (`<th scope="col">`) para que los lectores de pantalla asocien correctamente cada celda con su columna correspondiente.
* **Enlaces descriptivos:** Los textos de los enlaces (como "Ir al Mes de Agosto" o "Volver al menú") son claros y describen exactamente a dónde llevan, sin usar frases genéricas como "Haz clic aquí".

## 🛠️ Tecnologías Utilizadas
* **HTML5:** Para la estructura y el contenido.
* **Git y GitHub:** Para el control de versiones y el despliegue del proyecto.
* **GitHub Pages:** Para la publicación del sitio web en producción.
