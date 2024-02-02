# HTML STRUCTURE 

 <title>Mi Presentacion</title>
    </head>
    <body>
        <!-- Hipervinculos -->
        <h1>Mi informacion Personal</h1>
        <p>En esta pagina web podemos encontrar un poco sobre: Mi informacion personal, mi experiencia laboral y mi nivel educativo.</p>
        <a href="storage/data/datosPersonales.json" target="_blank" rel="noopener noreferrer">
    	@@ -31,12 +32,14 @@ <h2> Ejercicio 1</h2><main>
        <article>
            <!-- Listas e Hipervinculos-->
            <li><a href=#Campus>Campus</a></li>
            <h3 id="Campus">Campus</h3>
            <!-- Multimedia imagen -->
            <picture >
                <source media="(min-width: 500px)" srcset="storage/img/campus.jpg">
                <img src=""
    @@ -50,8 +53,9 @@ <h3 id="Barcelona">Barcelona</h3>
            </picture >
            <h3 id="Setup">Setup Gamer</h3>
            <picture >
                <source media="(min-width: 500px)" srcset="storage/img/setup.png" >
                <img src=""
                width="200px"
                alt="Imagen del Setup">
            </picture>
            <h3 id="pokemon">Charizard</h3>
    @@ -68,5 +72,184 @@ <h3 id="Hamburguesa">Hamburguesa</h3>
            </picture>
        </article>
    </main>
    <!-- Tablas -->
    <table border="solid"> 
        <thead>
            <tr>
                <th>#Empleado</th>
                <th>Nombre</th>
                <th>Apellido</th>
            </tr>
        </thead>  
        <tbody>
            <tr>
                <td>1</td>
                <td>Juan</td>
                <td>Lopez</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Ana</td>
                <td>Gonzalez</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Pedro</td>
                <td>Sanchez</td>
            </tr>
        </tbody>
    </table>
    <table border="solid">
        <thead>
            <tr>
                <th>_id</th>
                <th>index</th>
                <th>guid</th>
                <th>isActive</th>
                <th>balance</th>
                <th>picture</th>
                <th>age</th>
                <th>eyeColor</th>
                <th>name</th>
                <th>gender</th>
                <th>company</th>
                <th>email</th>
                <th>phone</th>
                <th>address</th>
                <th>about</th>
                <th>registered</th>
                <th>latitude</th>
                <th>longitude</th>
                <th>greeting</th>
                <th>favoriteFruit</th>
                <th>tags</th>
                <th>friends</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>65a91fee68576587b3ab7aa1</td>
                <td>0</td>
                <td>f4e26a01-bb4c-4477-93b7-8e399da8643c</td>
                <td>true</td>
                <td>$1,146.25</td>
                <td><img src="http://placehold.it/32x32" alt="Imagen de la chica"></td>
                <td>31</td>
                <td>blue</td>
                <td>Rita Elliott</td>
                <td>female</td>
                <td>IMPERIUM</td>
                <td>ritaelliott@imperium.com</td>
                <td>+1 (835) 526-2886</td>
                <td>587 Bedford Place, Springhill, Pennsylvania, 289</td>
                <td>Sint ea cillum fugiat nostrud exercitation adipisicing quis esse veniam tempor aliquip reprehenderit ipsum minim. Duis sunt ullamco do non. Laboris officia est Lorem pariatur aute excepteur officia cillum proident tempor commodo magna deserunt Lorem. Sint laboris laborum commodo cupidatat dolore adipisicing culpa amet. Nulla ad pariatur pariatur esse dolor dolor ullamco non anim esse nisi cillum.\r\n</td>
                <td>2018-04-05T12:34:52 +05:00</td>
                <td>-13.515649</td>
                <td>-61.415535</td>
                <td>Hello, Rita Elliott! You have 1 unread messages.</td>
                <td>apple</td>
                <td>
                    <ul>
                        <li>est</li>
                        <li>consequat</li>
                        <li>voluptate</li>
                        <li>in</li>
                        <li>nollist</li>
                        <li>pariatur</li>
                        <li>velit</li>
                    </ul>
                </td>
                <td>
                    <ul>
                        <li>
                            <dl>
                                <dt>Id:</dt>
                                <dd>0</dd>
                                <dt>name:</dt>
                                <dd>Janie Byers</dd>
                            </dl>
                        </li>
                        <li>
                            <dl>
                                <dt>Id:</dt>
                                <dd>1</dd>
                                <dt>name:</dt>
                                <dd>Bowers Harper</dd>
                            </dl>
                        </li>
                        <li>
                            <dl>
                                <dt>Id:</dt>
                                <dd>2</dd>
                                <dt>name:</dt>
                                <dd>Dixon Page</dd>
                            </dl>
                        </li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>65a91fee6358989762dcb207</td>
                <td>1</td>
                <td>b4908048-01d1-4910-883e-75512a41f872</td>
                <td>false</td>
                <td>$1,217.76</td>
                <td><img src="http://placehold.it/32x32" alt="Imagen no disponible"></td>
                <td>24</td>
                <td>brown</td>
                <td>Jeannine Valencia</td>
                <td>female</td>
                <td>QIAO</td>
                <td>jeanninevalencia@qiao.com</td>
                <td>+1 (818) 577-2234</td>
                <td>612 Brigham Street, Brookfield, Massachusetts, 2424</td>
                <td>Eu consequat ipsum amet reprehenderit reprehenderit aliqua eu. Non anim ullamco exercitation cillum cupidatat eiusmod sint officia cupidatat id dolor officia dolore ea. Culpa deserunt adipisicing officia sit in sit. Culpa nostrud laboris commodo labore irure. Pariatur velit aliqua amet voluptate do cupidatat aliquip amet veniam esse pariatur labore. Eu occaecat incididunt nulla incididunt. Adipisicing consectetur reprehenderit ex et ullamco.\r\n</td>
                <td>2021-11-04T08:20:46 +05:00</td>
                <td>24.434721</td>
                <td>-158.88911</td>
                <td>Hello, Jeannine Valencia! You have 1 unread messages.</td>
                <td>strawberry</td>
                <td>
                    <ul>
                        <li>eu</li>
                        <li>dolor</li>
                        <li>pariatur</li>
                        <li>eiusmod</li>
                        <li>sunt</li>
                        <li>velit</li>
                        <li>non</li>
                    </ul>
                </td>
                <td>
                    <ul>
                        <li>
                            <dl>
                                <dt>Id:</dt>
                                <dd>0</dd>
                                <dt>name:</dt>
                                <dd>bartlett Valenzuela</dd>
                            </dl>
                        </li>
                        <li>
                            <dl>
                                <dt>Id:</dt>
                                <dd>1</dd>
                                <dt>name:</dt>
                                <dd>Shannon Lowery</dd>
                            </dl>
                        </li>
                        <li>
                            <dl>
                                <dt>Id:</dt>
                                <dd>2</dd>
                                <dt>name:</dt>
                                <dd>Salazar Mcguire</dd>
                            </dl>
                        </li>
                    </ul>
                </td>
            </tr>
        </tbody>
    </table>
    </body>
    </html>


# TABLAS Y LISTAS

```
@import url(variables.css);
body{
    background: var(--bg-PrimaryColor);
}


.box {
    color: var(--colorPrimary);
    margin: 30px;
    background: var(--bg-PrimaryColor);
    border: dotted;
    display: grid;
    place-content: center;
}
.box:nth-child(1){
    position: relative;
    width: 45%;
    height: 200px;
}
.box1{
    position: absolute;
    width: 10%;
    height: 40%;
    border: dotted var(--colorSecundary);
    margin: auto;
    right: 0;
    top: 0;
    bottom: 0;
    display: grid;
    place-content: center;
}
.box:nth-child(2){
    position: absolute;
    width: 45%;
    height: 200px;
    top: 0;
    right: 0px;
}

.box2_1{
    position: absolute;
    width: 10%;
    height: 40%;
    border: dotted var(--colorSecundary);
    margin: auto;
    left: 0;
    bottom: 0;
    display: grid;
    place-content: center;
}
.box2_2{
    position: absolute;
    width: 10%;
    height: 40%;
    border: dotted var(--colorSecundary);
    margin: auto;
    left: 10%;
    bottom: 0;
    display: grid;
    place-content: center;
}
.box:nth-child(3){
    height: 200px;
    width: 45%;
    position: absolute;
    margin: auto;
    top: 0px;
    bottom: 0px;
    right: 0px;
    left: 0px;  
}
.box3{
    position: absolute;
    width: 20%;
    height: 40%;
    border: dotted var(--colorSecundary);
    margin: auto;
    bottom: 0;
    left: 0;
    display: grid;
    place-content: center;
}
.box:nth-child(4){
    height: 200px;
    width: 40%;
    position: absolute;
    margin: auto;
    bottom: 0px;
    right: 0px;
    left: 0px;
} 
.box4_1{
    position: absolute;
    width: 20%;
    height: 40%;
    border: dotted var(--colorSecundary);
    margin: auto;
    display: grid;
    place-content: center;
}
.box4_2{
    position: absolute;
    width: 20%;
    height: 40%;
    border: dotted var(--colorSecundary);
    margin: auto;
    right: 0;
    top: 0;
    display: grid;
    place-content: center;
}


```



# SELECTORES

```css
/* CSS Selectores :
Universal: *
de tipo: etiqueta
clases: .nombreClase
ID: #nombreID
por atributo: [NombreAtributo]
descendiente: etiqueta etiqueta 
pseudo-clases: 
    etiqueta:link
    etiqueta:visited
    etiqueta:hover
    etiqueta:active
*/
.titulo-h2 {
    color: red;
```



# ESPECIFICIDAD

```css
/* Jerarquia
    Important  $$
    estilos en linea  ¨¨
    Identificadores   **
    Clases  #
    Pseudo-clases  #
    Atributos   #
    Elementos    &
    Pseudo-elementos    &
*/
```



# PARRAFOS Y TEXTO

```
/* Letra
    color: asignar color a letra;
    font-size: Asignarle tamaño a la letra;
    text-align: Ajustar texto Eje X;
    Text-decoration: 
        Underline: Subrayar;
        line-through: tachar;
        Overline: Linea encima;
    text-shadow: sombreado de texto
        X Y Difuminado Color 
    font-family: Cambiar la fuente de la letra;
*/
```



# CONFIGURACION DE BORDER

```
/* Border
Border: Colocar borde a la caja
    Estilo Tamaño Color
    dotted
    dashed
    solid
    double
    groove 3D
    ridge 3D
    inset 3D
    outset 3D
    none
    hidden
border-style: seleccionar solo el estilo del borde;
border-color: seleccionar solo el color del borde;
border-radius: Hacer esquinas redondas;
*/
```



# CONFIGURACION BACKGROUND



```
/* Background:
Background-color: Definir color del fondo;
Opacity: Regular opacidad de la caja;
Background-image: Definir imagen como imagen Con URL
background-size: Definir como se organiza la imagen en el fondo
    Cover
    Contain
    Auto
background-repeat: Definir si el fondo se repite o no
background-position: Define desde que parte se muestra el fondo;
```



# SETTING BOX MODEL

```
/* Box model:
Margin: separacion de la box exterior;
Padding: separacion de la box interna;
    top Right Bottom Left
OverFlow: 
    hidden
    Scroll
Outline: Linea entre border y margin;
Position: Define la posicion de la caja
    Absolute
    Relative
*/
```



# CONF LISTAS Y TABLAS

```css
/* Listas,tablas y Links:
list-style-type: Define el estilo de la lista
    none
    Circle
list-style-position
Tablas: 
    Border-Collapse: Collapse: acomodar mejor los margenes de la tabla
    tr: hover: 
        background-color: ocasiona que cambie de color al colocar el mouse encima
Links:
a:Link: Propiedades antes de entrar en el 
a:visited: Propiedades de el luego de ser visitado
a:Hover: Propiedades de el con el mouse encima
a:active: Propiedades de el mientras se esta oprimiendo
*/
```



# CONF FLEX BOX

```css
/* FlexBox:
Flex-direction: 
    Row
    row-reverse
    Column
    Column-reverse
Flex-wrap: 
    wrap: Reparte el contenido adecuadamente
    nowrap: Acumula el contenido
Flex-flow:
    Direction Wrap
Justity-content: 
    Space-between
    Space-around
    Space-evenly
    Center
    Flex-start
    Flex-end
Align-itemns:
    Flex-start
    Flext-end
    Center
    Stretch
Align-content:
    Space-between
    Space-around
    Space-evenly
    Center
    Flex-start
    Flex-end
Order: Cambiar de lugar
Flex-grow: Expanden segun cuanto coloquemos modificando widht
flex-basis: Como un widht es compatible
*/
```



# CONF GRID

```css
/* Grid:
grid-template-columns:
    Asignar columnas
    Unidades: %, px, auto, V, fr;
grid-template-rows:
    Asignar Valores a filas y las crea
    Unidades: %, px, auto, V, fr;
grid-auto-rows:
    Para asginar altura a las filas automaticas
grid-auto-flow:
    Para asignar row
                 row-reverse
                 column
                 column-reverse
repeat: (#, Valor)
minmax(minimo, mayor)
Column-gap:
    Separacion de Columnas
row-gap:
    Separacion de filas
gap:
    row  column
Auto-fill: Ajsuta el numero de columnas mientras sea el ancho minimo
Auto-fit: ocupa todo el espacio, ajusta al limite;
Grid-column-start: Para decir en cual inicia;
Grid-column-end: Decir en cual finaliza;
span: Define el numero de cuadros
Grid-column: 
    start/end
Grid-row-start:
    Dice en que fila inicia
Grid-row-end:
    Dice en que fila termina
Grid-row: 
    start/end
Grid-area:
    row-start/column-start/row-end/column-end
Order: 
Cambia el orden de los elementos
Grid-template:
    altura de la columna / ancho
*/
```



# FORMULARIO 

<body>
    <div class="formulario">    
        <h3>Formulario</h3>
        <p>Ingresa tus datos para que te enviemos mas informacion.</p>
        <div class="username">
            <input type="text" >
            <label>Nombre de Usuario</label>
        </div>
        <div class="email">
            <input type="email">
            <label >Email</label>
        </div>
        <div class="text">
            <input type="text">
            <label >Texarea</label>
        </div>
        <button>Enviar</button>
    </div>

</body>
</html>

```CSS
.formulario .username{
    position: relative;
    border-bottom: 2px solid #adadad;
    margin: 30px 0;
}
input{
    width: 100%;
    padding: 0 5px;
    height: 40px;
    font-size: 16px;
    border: none;
    background: none;
    outline: none;
}
label{
    position: absolute;
    top: 50%;
    left: 5px;
    color: #adadad;
    transform: translateY(-50%);
    font-size: 16px;
    pointer-events: none;
}
input:focus ~ label,
input:focus ~ label{
    top: -5px;
}

.formulario .email{
    position: relative;
    border-bottom: 2px solid #adadad;
    margin: 30px 0;
}
.formulario .text{
    position: relative;
    border-bottom: 2px solid #adadad;
    margin: 30px 0;
}
.formulario button{
    padding-inline: 22px;
    padding-block: 12px;
    color: white;
    border: none;
    outline: none;
    border-radius: 980px;
    background: rgb(0,113,227);
    font-weight: 300;
}
```

