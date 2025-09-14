# 1.- Lenguajes de marcas

Un **lenguaje de marcas** es un modo de codificar un documento donde, junto con el texto, se incorporan etiquetas, marcas o anotaciones con información adicional relativa a la estructura del texto o su formato de presentación.  

Permiten hacer explícita la estructura de un documento, su contenido semántico o cualquier otra información lingüística o extralingüística que se quiera hacer patente.

Todo lenguaje de marcas está definido en un documento denominado **DTD (Document Type Definition)**. En él se establecen las marcas, los elementos utilizados por dicho lenguaje y sus correspondientes etiquetas y atributos, su sintaxis y normas de uso.

---

### Ejemplo de un documento realizado con un lenguaje de marcas

```html
<carta>
	<fecha>22/11/2006</fecha>
	<presentacion>Estimado cliente:</presentacion>
	<contenido>bla bla bla bla …</contenido>
	<firma>Don José Gutiérrez González</firma>
</carta>
```

Aunque en la práctica, en un mismo documento pueden combinarse varios tipos diferentes de lenguajes de marcas, éstos se pueden clasificar como sigue:

- **De presentación**: Define el formato del texto.  
- **De procedimientos**: Orientado también a la presentación, pero el programa que representa el documento interpreta el código en el mismo orden en que aparece.  
- **Descriptivo o semántico**: Describe las diferentes partes en las que se estructura el documento sin especificar cómo deben representarse.  

---

## 🌟 Lenguajes de marcado por ámbito de uso

| Categoría | Lenguaje | Descripción |
|-----------|----------|------------|
| 📄 **Documentación electrónica** | **RTF** | Formato de texto enriquecido desarrollado por Microsoft, aún usado para intercambio entre procesadores de texto. |
| | **TeX / LaTeX** | Ideal para documentos científicos y académicos con fórmulas matemáticas. LaTeX facilita la estructuración de documentos grandes. |
| | **Markdown** | Lenguaje ligero muy popular para documentación técnica, blogs y GitHub. |
| | **DocBook** | Para documentación técnica y manuales de software, separando contenido de presentación. |
| | **Asciidoc / Asciidoctor** | Formatos modernos para documentación técnica, exportables a HTML, PDF, EPUB y más. |
| 🌐 **Tecnologías de internet** | **HTML5 / XHTML** | Base de la web, con soporte para multimedia, gráficos vectoriales y semántica avanzada. |
| | **RSS / Atom** | Protocolos de sindicación de contenidos web para recibir actualizaciones automáticamente. |
| | **JSON-LD / Microdata / RDFa** | Lenguajes de marcado semántico para describir datos en la web y mejorar SEO e interoperabilidad. |
| ⚙️ **Otros lenguajes especializados** | **MathML** | Expresa matemáticas de forma estructurada, interpretable por navegadores y software científico. |
| | **VoiceXML** | Crea aplicaciones de voz con reconocimiento de habla y síntesis de voz. |
| | **MusicXML** | Formato estándar para intercambio de partituras entre editores musicales. |
| | **SVG** | Gráficos vectoriales escalables en la web y aplicaciones. |
| | **XBRL** | Presentación de información financiera en formato estructurado y legible por máquinas. |
 


