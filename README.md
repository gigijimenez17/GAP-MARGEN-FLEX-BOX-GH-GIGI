# GAP-MARGEN-FLEX-BOX-GH-GIGI

**_Propiedades de espaciados en Flexbox_**

Existen tres propiedades de espaciados en Flexbox, también conocidas como las propiedades gap. El término gap se traduce como brecha en español y, en este conjunto de propiedades, se refiere al espacio entre los elementos HTML de un contenedor. A diferencia de las propiedades justify-content o align-content de Flexbox, esta propiedad se concentra solamente en el espacio entre lo elementos. Esto quiere decir que no controla su relación con los bordes del contenedor.

__*Importante*__ tener en cuenta que las propiedades de espaciados en Flexbox s han añadido al sistema de forma reciente, por lo que algunos navegadores todavía no las soportan.

Te recomendamos ir a la página web https://caniuse.com/ciu/about 
para revisar el soporte de cada navegador con esta propiedad. Aunque se pierden pocos navegadores, siempre es bueno que revises la compatibilidad de nuevas propiedades antes de implementarlas a tu proyecto.

A continuación te presentamos las tres propiedades de espaciados en __Flexbox__:

* *__row-gap__*
Esta propiedad nos ayuda a determinar los espacios o brechas entre las filas de elementos. Podemos determinar este espacio usando cualquiera de las unidades de medida de CSS, ya sea con píxeles, porcentajes o unidades relativas. Al darle un valor a esta propiedad, estamos definiendo el espacio vertical entre los elementos. Ten en cuenta que las propiedades de espaciados en Flexbox deben tener un valor positivo.

* *__column-gap__*
Esta propiedad es la contraparte de row-gap. Como su nombre indica, nos ayuda a determinar los espacios o brechas entre las columnas de elementos. Esto quiere decir que definimos el espacio horizontal entre los elementos o columnas de elementos.

## _gap_
La propiedad gap es una abreviatura para las otras dos propiedades de espaciados en Flexbox. Así como flex-flow es una abreviatura para unir las propiedades flex-direction y flex-wrap en una sola etiqueta, la propiedad gap nos permite determinar los valores de row-gap y column-gap en una sola línea de código. Entonces, basta con que escribamos los dos valores que queremos en esta propiedad: el primer valor será el row-gap y el segundo valor será el column-gap.

