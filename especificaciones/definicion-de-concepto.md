# Definición de Concepto

### Definiciones <a id="definiciones"></a>

Las especificaciones son propiedades adicionales que se pueden registrar en los productos o SKUs de su tienda. En VTEX, estas especificaciones se registran en la pestaña **Categorías** y se denominan **Campo**.

### Especificación de Producto <a id="especificacion-de-producto"></a>

La especificación de producto se utiliza generalmente para crear filtros de navegación en el sitio web o para exhibir información adicional en la pantalla del producto.

En una tienda del sector moda, podría crear una especificación de producto para informar a su cliente cuál es el **tejido** de un ítem vendido en su tienda.

Esta información podría exhibirse como un filtro en una barra lateral o como un texto informativo dentro de la página del producto.

Las especificaciones de producto pueden recibir datos como strings y números, pudiendo ser consumidas por las APIs de VTEX para ser utilizadas en la personalización del front-end o en el envío de informaciones para integraciones externas.

### Especificación de SKU <a id="especificacion-de-sku"></a>

La especificación de SKU se utiliza para crear filtros de navegación en el sitio web y para diferenciar los SKUs dentro de la página de producto.

En una tienda de camisas, podría crear una especificación de SKU para diferenciar sus productos por tamaño, por ejemplo.

Las especificaciones de SKU tendrían los valores **PP, P, M, G y GG**. Estas podrían utilizarse como filtro de navegación del sitio web. Además, las especificaciones funcionarían como selectores de SKU en la página del producto.

{% hint style="warning" %}
En VTEX, las especificaciones de SKU son campos obligatorios para concluir el registro de un SKU. Esto significa que, si se crea una nueva especificación dentro de una categoría, todos los SKUs dentro de esta categoría necesitan tener registrada esta nueva especificación. Así, todos estos SKUs estarán inactivos hasta que el registro de esta nueva especificación se haga en los SKUs de la categoría en cuestión.
{% endhint %}

