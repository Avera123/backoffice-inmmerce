# Como registrar

Siga el siguiente procedimiento para registrar una nueva colección:

1. Haga clic en **CMS**
2. Haga clic en **Layout**
3. Dentro de la carpeta CMS, haga clic en **Product Clusters \(Collections\)**
4. Haga clic en **New Collection**
5. Rellene los campos del formulario de Colección. Para entender mejor el significado de cada campo, acceda a nuestro artículo sobre cómo rellenar campos de registro de colección.
6. Haga clic en **Save Product Cluster**

![gif-cadastro-cole&#xE7;&#xE3;o es](https://images.ctfassets.net/alneenqid6w5/TppDUPdNugcOUHZ0wY9c1/7ff5cebc2b94d6afd171c9d6cc0e7072/gif-cadastro-cole____o_es.gif)Cuando la cantidad de colecciones creadas sobrepasa el límite de veinte, las colecciones excedentes pueden encontrarse en la interfaz a través del campo de búsqueda. La búsqueda en este campo debe realizarse en base al nombre de la colección deseada.

La elección de los productos que van a hacer parte de una colección se hace a través de la creación de un **grupo**. Para esto, basta hacer clic en **New Group** dentro de la colección deseada.

![2019-06-06 16 22 46-Layout](https://images.ctfassets.net/alneenqid6w5/1HELFm1eBsSZVpq6EEQQJ4/29c77be34d91e4eac14b7bf3d4597fa4/2019-06-06_16_22_46-Layout.png)

Antes de escoger qué productos harán parte del grupo, como veremos a continuación, es necesario atribuir un nombre y especificar el tipo de grupo creado.

### Tipos de grupo <a id="tipos-de-grupo"></a>

Existen apenas 2 valores posibles para el tipo de un grupo: _**Inclusive**_ y _**Exclusive**_. Un grupo tipo _Inclusive_ tiene como objetivo incluir todos los productos en la colección a la cual está vinculado. En este mismo sentido, un grupo tipo _Exclusive_ excluye de la colección sus productos componentes.

Para ejemplificar, suponga una colección _Celulares_ con dos grupos: uno tipo _Inclusive_ A y otro tipo _Exclusive_ B. Los productos que hacen parte de esta colección serán el resultado de los productos del grupo A _menos_ los productos del grupo B.

Esta lógica sirve para cualquier cantidad de grupos creados dentro de una misma colección. Los productos de los grupos tipo _Exclusive_ siempre serán sustraídos de los productos que componen los grupos tipo _Inclusive_. De esta forma:

Productos componentes de una colección = \(A+B\) - \(C+D\)

Siendo:

* A y B grupos tipo _Inclusive_
* C y D grupos tipo _Exclusive_

Por eso, el primer grupo creado para cualquier colección debe ser obligatoriamente del tipo _Inclusive_.Esté siempre atento al tipo de grupo definido en el registro. Al incluir productos en un grupo tipo Exclusive, por ejemplo, estos **no** serán incluidos a una colección por causa de la naturaleza de su grupo.

### Selección de productos <a id="seleccion-de-productos"></a>

Dentro de un grupo, la selección de los productos puede hacerse en base a:

* Departamento, Categoría o Subcategoría
* Marca
* SKU
* Fecha de lanzamiento en el mercado

Entre las opciones anteriores, es posible seleccionar más de una para alcanzar un escenario especifico deseado. En estos casos, **apenas los productos que se encuadren en la intersección de las opciones seleccionadas serán incluidos en el grupo**.

Por ejemplo: al seleccionar la categoría A y la marca B, apenas los productos que sean de esta categoría y marca al mismo tiempo serán incluidos en el grupo. Los productos de la categoría A de marcas diferentes de B, por ejemplo, no estarán en la colección, así como los productos de la marca B de otras categorías.

#### Productos por Departamento, Categoría o Subcategoría <a id="productos-por-departamento-categoria-o-subcategoria"></a>

Para agregar todos los productos de un determinado Departamento a un grupo, basta seleccionar el Departamento deseado y hacer clic en **Save Group**, como muestra la imagen a continuación.

![sele&#xE7;&#xE3;o-departamento ES](https://images.ctfassets.net/alneenqid6w5/dpKPktmtrMoOqVwdkTgGe/6c5ecc0f0446688acbe62f725811830b/sele____o-departamento_ES.png)

Lo mismo aplica para los productos de una determinada Categoría o Subcategoría.

![sele&#xE7;&#xE3;o-categoria-subcategoria ES](https://images.ctfassets.net/alneenqid6w5/669cvCxhxCDtUObugHirqT/41a3b8cccc9e832a74452ce97256f8d5/sele____o-categoria-subcategoria_ES.png)

### Productos por Marca <a id="productos-por-marca"></a>

Para crear un grupo con productos de una o más marcas, basta seleccionar la marca deseada en la lista correspondiente.

![sele&#xE7;&#xE3;o-marca-cole&#xE7;&#xE3;o ES](https://images.ctfassets.net/alneenqid6w5/7iBwt7BrU46rtjQagSZCtg/9b061b4b72ae669caa7b510e7db8f29f/sele____o-marca-cole____o_ES.png)

Las marcas se encuentran dispuestas en orden alfabética. Al hacer clic en la letra correspondiente a la inicial de la marca deseada, la lista se expande y exhibe las marcas existentes.

### Productos por SKU <a id="productos-por-sku"></a>

#### Manualmente <a id="manualmente"></a>

Al agregar un SKU a un grupo, el producto al cual está vinculado también será agregado. En un escenario en el que un producto tenga más de un SKU atribuido, agregar un único SKU hará con que todos los otros también sean agregados al grupo.

![selecao-sku-manual en &amp; es](https://images.ctfassets.net/alneenqid6w5/1GZTDTmU26MOuQ5u3dpOe7/04f1623d9c52bd939e4fabb455fab8ff/selecao-sku-manual_en.png)

En el campo **Find SKUs**, es posible digitar el ID de cuantos SKUs se deseen, escribiendo los valores entre comas.

> Ex: 2000004,2000009,2000005.

Para excluir un SKU de la lista, basta hacer clic en el botón rojo al lado de este.Cuando el número de SKUs en la lista supere los 10 ítems, un control de paginación estará disponible.

**Por plantilla**

Obtenga el modelo de archivo para la inclusión y exclusión de SKUs de la colección aquí.Si tiene dificultad con la visualización de los botones para la importación de la plantilla, acceda a nuestro artículo Botón de upload de archivos no aparece en CMS.

**Inclusión masiva**

En el campo **Bulk Insert SKUs**, es posible importar por plantilla \(formato .xls\) una lista de SKUs que harán parte del grupo.

![selecao-sku-planilha-insert en &amp; es](https://images.ctfassets.net/alneenqid6w5/9SITcqeeZNYTlAz5wi6IA/6765c51947698f35bf4ad198a51bcdc0/selecao-sku-planilha-insert_en.png)

En la plantilla importada, todos los IDs de los SKUs deben estar dispuestos en la primera columna, con el encabezado, como se ejemplifica en la siguiente figura:

![exemplo-planilha-sele&#xE7;&#xE3;o-sku-cole&#xE7;&#xE3;o](https://images.ctfassets.net/alneenqid6w5/5E2rtjyWArzeGjr27smF4o/bd66f1ea64d4e0d104471fac71bd98ab/exemplo-planilha-sele____o-sku-cole____o.png)

**Exclusión masiva**

Para evitar la exclusión manual de un SKU a su vez, también es posible usar el recurso de importación de plantilla para la exclusión masiva.

![exclusao-skus-manualmente-planilha-cole&#xE7;&#xE3;o-cms en &amp; es](https://images.ctfassets.net/alneenqid6w5/moziGpjShzDpFw63tyDOa/ebfb61d2a2d2e09d494690ad0dc0ab62/exclusao-skus-manualmente-planilha-cole____o-cms_EN.png)

En este caso específico, los SKUs listados en la plantilla importada se excluirán del grupo. Para esto, haga clic en la opción **excluir skus** después que el archivo sea cargado.No se considerarán los IDs de los SKUs inactivos para inclusión o exclusión aunque estén listados en la plantilla.\#\# Productos por fecha de lanzamiento en el mercadoEn la sección de **Other options**, las opciones **Pre-sales** y **Launches** son un complemento a la elección de los productos por Categorías, Marcas o SKUs. Esto significa que estos flags solo funcionarán si ya se seleccionaron anteriormenteNote que apenas es posible seleccionar una de las dos opciones. Si quiere que ambos escenarios sean contemplados, cree dos grupos y configure cada uno con la respectiva opción.

![other-options-cms-cole&#xE7;&#xF5;es ES](https://images.ctfassets.net/alneenqid6w5/4MijWxcZbcIjsVvHl3AcCB/14a9f700d992c28b2afb959829609bd1/other-options-cms-cole____es_ES.png)

#### Pre-sales <a id="pre-sales"></a>

Para crear una colección de productos que aún no fueron lanzados en su tienda, seleccione la opción **Pre-sales**. El sistema considerará todos los productos con la fecha de lanzamiento posterior al día vigente, conforme se define en el campo _Fecha de lanzamiento en el mercado_ en el registro de producto.

#### Launches <a id="launches"></a>

La opción **Launches** permite crear una colección de productos recientemente lanzados. Al seleccionar esta opción, el sistema considerará todos los productos lanzados dentro del periodo de 30 días anteriores al vigente. La fecha de lanzamiento considerada es también aquella definida en el campo _Fecha de lanzamiento en el mercado_ en el registro del producto.Si quiere entender cómo funciona la exclusión de una colección de productos, acceda a nuestro artículo sobre cómo eliminar colecciones.

