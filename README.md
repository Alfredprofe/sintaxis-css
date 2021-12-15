# 4 Sintaxis básica de CSS

La sintaxis es la siguiente:

![https://i.ibb.co/jGSCyjq/sintaxis-css.png](https://i.ibb.co/jGSCyjq/sintaxis-css.png)

Por sus siglas en inglés **Cascade Style Sheet** o traducido al español *Hojas de Estilo en Cascada*. Este lenguaje se usa para dar estilos a un documento HTML.

El selector apunta al elemento HTML que queremos estilizar. Cada declaración tiene una propiedad con su respectivo valor. En el siguiente ejemplo el elemento `<h1>` tendrá un color rojo con un tamaño de 34px.

![https://i.ibb.co/MGmRr7n/html-css-h1.png](https://i.ibb.co/MGmRr7n/html-css-h1.png)

<aside>
💡 Una declaración = propiedad + valor.

</aside>

Los selectores pueden contener más de una declaración. Estos a su vez son usados para seleccionar los elementos HTML que queremos estilizar.

### Modelo de caja

Todos los elementos HTML pueden considerarse como cajas. El modelo de caja en CSS consiste en: márgen exterior, márgen interior, borde y su propio contenido.

![https://i.ibb.co/wBnVZLp/margin-padding-border.png](https://i.ibb.co/wBnVZLp/margin-padding-border.png)

**Amarillo:** representa el márgen exterior.

**Verde:** representa el márgen interior.

Negro: es el borde.

¿Y para que sirve el modelo de caja? Nos permite agregar bordes, definir el espacio entre los elementos, además de dar un ancho, alto, fondo, etc.

Dentro del modelo de caja existen dos tipos de elementos que son los de tipo **Bloque** y los de tipo **En Línea**

Elemento en Bloque:

![https://i.ibb.co/f8jhjZL/block.png](https://i.ibb.co/f8jhjZL/block.png)

Elemento en Línea:

![https://i.ibb.co/5WdCnvj/linea.png](https://i.ibb.co/5WdCnvj/linea.png)

<aside>
💡 Los elementos en **Bloque** inician en una nueva línea y abarcan todo el ancho disponible del navegador.

</aside>

<aside>
💡 Los elementos en **Línea** no inician en una nueva línea y solo abarcan el ancho necesario del elemento.

</aside>

<aside>
⚠️ Un elemento en **Línea** **NO** puede anidar un elemento en **Bloque**

</aside>

### Unidades de medida

CSS tiene 2 tipos de unidades de medida: **Absoluta** y **Relativa**, las cuales sirven para expresar una longitud.

Las medidas Absolutas son estáticas, no cambian:

| cm | mm |
| --- | --- |
| pt | in |
| px | pc |

Las medidas Relativas son dinámicas y cambian dependiendo de otra unidad de medida:

| em | ch |
| --- | --- |
| vw | vmin |
| vh | vmax |
| ex | rem |
| % |  |

### Unidades de color

Los colores en CSS se específican usando los sistemas de color RGB, HEX y HSL. CSS también tiene palabras clave contando con 140 nombres de color como Chocolate, Coral, Cyan, etc.

<aside>
👉🏼 Aquí los [**140 Nombres de Color**](https://www.w3schools.com/colors/colors_names.asp)

</aside>

Los valores de los sistemas de color son los siguientes a modo de ejemplo.

**RGB:**

![https://i.ibb.co/GkSKxmT/h1-rgb.png](https://i.ibb.co/GkSKxmT/h1-rgb.png)

**HSL:**

![https://i.ibb.co/djh0gpY/h1-hsl.png](https://i.ibb.co/djh0gpY/h1-hsl.png)

**HEX:**

![https://i.ibb.co/vLBrsNw/h1-hex.png](https://i.ibb.co/vLBrsNw/h1-hex.png)

También es posible agregar una transparencia al color con la propiedad RGB o HSL, para esto lo haremos con el canal Alpha llevando el valor de 0 a 1, ejemplo:

![https://i.ibb.co/DbZQ1bs/h1-rgba.png](https://i.ibb.co/DbZQ1bs/h1-rgba.png)

El número 0.5 significa que usaremos una opacidad (transparencia) del 50%. Siendo 1 el 100%.

### Posicionamiento de cajas

El posicionamiento de caja se establece con la propiedad `position` y sus valores pueden ser 5:

- Static (Estático)
- Relative (Relativo)
- Fixed (Fijo)
- Absolute (Absoluto)
- Sticky (Pegajoso)

### Tipografía y texto

La tipografía y texto en CSS están definidos por varias propiedades, pero en este capítulo usaremos las más comunes.

**Para la tipografía**

> "*La palabra tipografía proviene de dos términos griegos: “typos” que significa golpe, marca o forma, y “graphia” que significa cualidad de escribir." (Llasera,2021)*
> 

El autor del blog [imborrable.com](http://imborrable.com) define de una forma más sencilla y digerible el término...

> *"Podemos definir la tipografía como "el arte de diseñar las letras". Se denomina así a la discplina que estudia la **representación gráfica de las letras** para que el lenguaje escrito sea efectivo. Al mismo tiempo, denomimanos también tipografía a la escritura con un conjunto de caracteres alfanúmericos, elaborados previamente y que **cuentan con un estilo y una serie de características en común.**" (Llasera, 2021)*
> 

![https://i.ibb.co/b6FnRLZ/tipografia.png](https://i.ibb.co/b6FnRLZ/tipografia.png)

<aside>
⚠️ Por último te recomiendo siempre acomodar tus propiedades en orden alfabético

</aside>

### **Recursos**

- Lista de elementos en Bloque
    
    ![https://i.ibb.co/RCWN2F2/elementos-bloque.png](https://i.ibb.co/RCWN2F2/elementos-bloque.png)
    
- Lista de elementos en Línea
    
    ![https://i.ibb.co/7KZ6MWT/elementos-linea.png](https://i.ibb.co/7KZ6MWT/elementos-linea.png)
    
- Páginas tipográficas
    
    [http://www.myfonts.com/](http://www.myfonts.com/)
    
    [https://fonts.google.com/](https://fonts.google.com/)
    
    [https://latinotype.com/nltt/](https://latinotype.com/nltt/)
    
    [https://www.goodtypefoundry.com/](https://www.goodtypefoundry.com/)
    
    [https://familytype.co/](https://familytype.co/)
    
    [https://uncut.wtf/](https://uncut.wtf/)
    

### Referencias y bibliografía

- Llasera, J. (2021). Tipografías: ¿Qué son, los diferentes tipos y sus variables tipográficas?. Diciembre 4, 2021, de Imborrable. Sitio web: [https://imborrable.com/blog/tipografias-que-son/](https://imborrable.com/blog/tipografias-que-son/)
- w3schools. (s. f.). *HTML Block and Inline Elements*. Recuperado 9 de diciembre de 2021, de https://www.w3schools.com/html/html_blocks.asp
