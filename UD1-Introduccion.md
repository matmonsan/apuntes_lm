# 1.- Lenguajes de marcas

Un **lenguaje de marcas** es un modo de codificar un documento donde, junto con el texto, se incorporan etiquetas, marcas o anotaciones con información adicional relativa a la estructura del texto o su formato de presentación.  

Permiten hacer explícita la estructura de un documento, su contenido semántico o cualquier otra información lingüística o extralingüística que se quiera hacer patente.

Todo lenguaje de marcas está definido en un documento denominado **DTD (Document Type Definition)**. En él se establecen las marcas, los elementos utilizados por dicho lenguaje y sus correspondientes etiquetas y atributos, su sintaxis y normas de uso.

---

### Ejemplo de un documento realizado con un lenguaje de marcas:

```xml
&lt;carta&gt;
    &lt;fecha&gt;22/11/2006&lt;/fecha&gt;
    &lt;presentacion&gt;Estimado cliente:&lt;/presentacion&gt;
    &lt;contenido&gt;bla bla bla bla …&lt;/contenido&gt;
    &lt;firma&gt;Don José Gutiérrez González&lt;/firma&gt;
&lt;/carta&gt;
