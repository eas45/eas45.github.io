# Cosas Esteban

## Veganeli

> La idea principal es poder comprender el funcionamiento de [Shopify][shopifyurl] y el uso de archivos CSV para poder mantener el stock actualizado.

### Gestión de productos con CSV

#### Visualización de un fichero CSV

[CSV Editor and Viewer][CSVurl] es un editor/visualizador con el que comprender mejor la información que contiene el archivo.

En el ejemplo que proporciona Shopify para añadir productos desde un CSV que ellos mismo proporcionan, se puede ver de forma más clara la información, e incluso guardar como Excel.

También se puede ver el contenido en una tabla a la hora de importar el CSV a Shopify. Antes de pulsar el botón ***Importar productos***, arriba, aparece una especie de nota en la que comenta que estás importando un archivo a Shopify. Al final de este mensaje hay un enlace con el texto *cambiar el orden de los encabezados de las columnas*. Esto permite ver toda la información y modificar la manera en que se quiere interpretar cada columna o campo del CSV.

#### Ejemplos de ficheros CSV

El plugin de WordPress, [*WP ALL IMPORT*][WPurl], ofrece una colección de ejemplos tanto en formato XML como en CSV. El fichero descargado es un fichero `.zip`.

### Gestión de productos con Oberlo

[Oberlo][Oberlourl] es una aplicación que Shopify menciona en su [guía sobre dropshiping y Oberlo][guiadropshipinoberlogurl]. En principio, esta plataforma facilita la búsqueda de productos para vender online.

Su integración en la tienda es sencilla.

**1. Conectar la tienda** - Desde el apartado de *Aplicaciones* en el panel de administrador de Shopify, buscar la palabra "Oberlo" en la barra de búsqueda:

![image](https://user-images.githubusercontent.com/32059653/111033132-00a3a580-8410-11eb-88ef-c22d384456e8.png)

Después se siguen los pasos para registrarse en Oberlo y poder conectar ambas plataformas.

**2. Añadir productos** - Oberlo muestra varias formas importar productos a la tienda de Shopify. A primera vista, se ve que están bastante relacionados con AliExpress, por lo que no hay demasiada información sobre otra forma de encontrar proveedores. De todas formas, he seleccionado la primera opción para poder ver qué ofrece realmente haciendo uso de la plataforma.

Llegados a este punto, me doy cuenta de que su proveedor es AliExpress, así que no es de interés.

### Gestión de productos con Stock Sync

Este gestor tiene más proveedores, así que con él sí que puedo hacer la prueba. A la conclusión que he llegado es que cada proveedor aparece en diferentes plataformas de este tipo, por lo que va a ser complicado unificar una tienda en la que cada proveedor funcione de forma diferente.

El funcionamiento parece sencillo, se selecciona el proveedor y se descarga automáticamente el catálogo. Además, los productos aparecen automáticamente en la tienda de Shopify.

- - -

You can use the [editor on GitHub](https://github.com/eas45/eas45.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/eas45/eas45.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.


[shopifyurl]: https://www.shopify.es/prueba-gratis?&term=shopify&Network=Search&SiteTarget=&mt=e&adid=284664788774&adpos=&CampaignId=1338883573&gclid=CjwKCAiA4rGCBhAQEiwAelVti9rdmBRP6VYkFJfYtJ9P40KZDarnsll1_wLo3dSnloecpYwK74ijIRoCtMsQAvD_BwE&gclsrc=aw.ds
[CSVurl]: https://www.convertcsv.com/csv-viewer-editor.htm
[WPurl]: https://www.wpallimport.com/documentation/woocommerce/example-files/
[Oberlourl]: https://www.oberlo.es/
[guiadropshipinoberlogurl]: https://help.shopify.com/es/manual/products/dropshipping/oberlo
