# SabujCha
![image](https://user-images.githubusercontent.com/114613889/197328116-ebef928e-1770-482f-b059-bf132ef2b2c0.png)

Sabujcha es una nueva marca de té matcha que busca incursionar en el mercado a través de una tienda virtual fácil de navegar y que muestre los beneficios de su producto, Andrea y Diana que son las emprendedoras tras esta marca, quieren que el sitio web tenga un look fresco y que su producto sea el principal protagonista.

**Requerimientos:**
El proyecto DEBE utilizar la metodología Scrum.
La página DEBE ser responsive (se evaluará tanto en desktop como en
mobile)
El diseño DEBE ser fiel al mockup y utilizar las imágenes e íconos
dejados en los recursos.
Se debe maquetar la Homepage fiel a la maqueta presentada en
recursos, revisar todas las imágenes de la carpeta donde se encuentran
las maquetas.
No se pueden utilizar frameworks, la maquetación debe ser 100% en
HTML y CSS, (recomendamos hacer uso de CSS GRID y/o Flexbox)
El repositorio DEBE tener un Readme muy específico, con capturas de
pantalla y documentación del proyecto.

**Desarrollo del proyecto:**

Primeramente descargue los recursos a utilizar y creé el repositorio para despues proseguir a elaborar el proyecto.

**HTML**
Realicé la estructura HTMl conforme interpreté el diseño, disponiendo los elementos de forma que fuesen faciles de manipular, además pensando en que la estructura séa entendida por futuros desarrolladores.

1.-Creé una carpeta y un index.html para trabajar sobre él.

![52414167-5eca-4ce7-a006-374ef6ff70ac](https://user-images.githubusercontent.com/114613889/197327294-258b85ca-eb2f-4d68-953d-03afa185c17e.jpg)

2.-Creé el repositorio en gitHub.
![b043b757-1a2c-42ce-a1fe-fcd51ba8e9a8](https://user-images.githubusercontent.com/114613889/197327321-17c679d2-1860-4da6-bc6e-f673c0ea8e36.jpg)


3.-Comencé la estructura con el header donde coloqué el menú de navegación, el logo de SabujCha , y una sección donde iría la moneda en la que se visualizarian los precios USD.
![a6a26ab2-e5bc-4052-90bd-f075b5fe0658](https://user-images.githubusercontent.com/114613889/197327328-60d62cdb-8ac2-48fb-a131-2dc4df54e2f5.jpg)

4.- Ubicar los div y secciones que conformarán la página
![be134f49-1480-432b-bde5-6bfe9e070c24](https://user-images.githubusercontent.com/114613889/197327342-5ff17c9b-4350-4449-873c-8b7785f5c983.jpg)

5.-Div Imagen principal con título.
![b9208d50-b3f3-48e3-9b5c-ca68a2339a8d](https://user-images.githubusercontent.com/114613889/197327352-bc9e6bd5-50ea-4fd1-b162-6e35026f6076.jpg)

6.-Sección con las dos ofertas debajo de la imágen principal
![22569211-5225-432f-8eb4-ab316a4469e4](https://user-images.githubusercontent.com/114613889/197327362-5036a154-c764-40d3-a760-f722aa9a59ec.jpg)

7.-Seccion de Cards de productos 1(contiene 4 productos)
![35c449eb-e950-40f7-908d-e6416dbebc55](https://user-images.githubusercontent.com/114613889/197327374-9c4382b0-e7a6-4aaa-9af0-4cb743da35fb.jpg)

8.- Realicé la sección de la cita e imágen de las hojitas de té
![0534011f-9f43-44e2-be44-4e66328e0173](https://user-images.githubusercontent.com/114613889/197327399-7cf21dc8-9b9f-4b1f-9c40-8d1ea5c82ba9.jpg)

9.-Sección cards de productos 2 (Contiene 8 productos)
![6a51dc2c-294c-44ac-bc84-fb8b958609f2](https://user-images.githubusercontent.com/114613889/197327405-c48ed21d-2e64-4985-8df2-9bfbd5526fe0.jpg)

10.-Formulario de suscripción
![a85fd2bb-aa1c-4e09-93b8-7c6e7aa7fa5e](https://user-images.githubusercontent.com/114613889/197327419-715551ae-8481-4a1c-bff7-83173e273ccf.jpg)

11.- Articulos referentes al Té (Latest New) 3 articulos
![7da8bb00-1d4a-4495-9f3f-278a58214f0b](https://user-images.githubusercontent.com/114613889/197327427-0a08faf6-9d04-4748-8f77-15ec8febe046.jpg)

12.- Seccion de Imágenes patrocinadores
![da11392f-0544-4e45-99b7-08e231107c9d](https://user-images.githubusercontent.com/114613889/197327434-97f88e18-d0e3-4bb4-a2c8-73dadc255f53.jpg)

13.-Footer con informacíon y contacto
![6a08a780-46a0-49e4-9f88-70ca3f607e80](https://user-images.githubusercontent.com/114613889/197327438-fed70afa-d5b9-4ebd-be34-6b412ccd2858.jpg)

14.-Sección del footer , Copyright
![c20d2234-1b91-415f-a49e-ac7a5c44d192](https://user-images.githubusercontent.com/114613889/197327443-1cbb4739-9d62-4d97-a02e-a2478e126e96.jpg)

**CSS**

Decidí comenzar a dar los estilos a la página Desktop First, seguí la estructura fiel al mockups

1.-Coloque las fuentes al principio del código, padding:0, margin:0
![11e4b061-fb6a-464e-a09d-9641e7169df0](https://user-images.githubusercontent.com/114613889/197327855-c5929253-b656-4a71-87da-bfc12224290a.jpg)

2.-Apliqué estilos al menú, utilicé flexbox

3.-En en header tuve 3 elementos (menu,logo,moneda) utilicé flexbox para organizarlos, le dí un display flex y justify-content: space-between.
![4d8b8285-b831-48a8-a8f7-e557e4ffc6c6](https://user-images.githubusercontent.com/114613889/197327866-09b872a8-5ece-4122-a015-ea72935c9600.jpg)
![f553404d-19f4-4547-9d0c-1ecf31e32093](https://user-images.githubusercontent.com/114613889/197327875-0f17174e-1cd1-44e9-ac96-660f20ad8cfc.jpg)

4.- En el div que contenía el título (H1) coloqué un background-image y coloqué la imagen principal, background-size:cover, background-position:center, heigth y width.
![76c5b9ef-7ce4-40cc-89e4-7a97b1d58ecb](https://user-images.githubusercontent.com/114613889/197327926-1788b16c-3e17-44fb-b442-07356527ffa9.jpg)


5.- En dos div coloqué parrafos con el descuento, a estos div le coloqué el backgroun-image de cada sección respectivamente, le añadi, ancho y alto y lo coloue en el centro.
![61e65c06-2c9f-444f-9385-a0b2b73a05df](https://user-images.githubusercontent.com/114613889/197327979-8fa0a913-bb67-41fb-83b9-b966c5cdcc18.jpg)


6.- Al body le añadi un width del 95% para que quedara el ligero margen que está en la foto guía

7.-Para la sección de productos coloqué el background correspondiente a esa seccion, alineé el titulo y parrafos iniciales, y colóque una grid con las card, les coloqué borde ancho alto y les di un column-gap para que tuviesen una separación
![d03730b9-1d62-4a91-91c0-7cb0cf9df9e7](https://user-images.githubusercontent.com/114613889/197327990-d9222d8c-6532-44fc-b456-9b712b21d244.jpg)

8.- En la seccón de la cita, centré la imagen de las hojas y a la cita la coloqué cursiva y jugue con los tamaños de los elementos
![535b302e-ea37-44d0-9c54-f831c488e05f](https://user-images.githubusercontent.com/114613889/197328002-12ed12a9-4e3f-4356-9dd1-0d636598b15f.jpg)

9.- Para la sección de productos 2, le coloque las clases de la primera sección del producto, lo que si es diferente es el background por lo que es un color sólido asi que se lo coloque.
![5593626c-abbf-4242-acea-6e223a94b147](https://user-images.githubusercontent.com/114613889/197328012-0eb14b2f-d876-413c-945e-01087819ee67.jpg)

10.-Realicé la sección del formulario igual a las demas secciones aplicando el background y centrando el contenido, le di ancho alto y cambie el color del boton a negro con un hover verde como se especifico en los requerimientos.
![42e1a34c-974c-4230-bbef-a2241f81e895](https://user-images.githubusercontent.com/114613889/197328028-fed95104-2f0a-48ce-bf22-622300a77585.jpg)


11.-La seccion latest news, articulos referentes a la pagina, hice una grid, coloque el background de la sección y le dí un column-gap para generar separación entre los elementos
![78ba872e-2771-43ae-9017-2e8307409072](https://user-images.githubusercontent.com/114613889/197328039-78e6f307-670b-4a92-9423-180e319a3c53.jpg)

12.- La seccion de las imágenes de patrocinios solo coloqué una debajo de otra y utilicé flexbox para ordenarlas con un justify-content: center. le coloque margen y especifiqué un tamaño para las imágenes.
![35b48157-59fe-45e0-8938-20db313d50bd](https://user-images.githubusercontent.com/114613889/197328051-626f54d4-b572-4638-b682-f6975765553e.jpg)

13.- Para el footer, utilicé flexbox
![604ff7ae-19d0-4f38-b693-99b8bc771ea6](https://user-images.githubusercontent.com/114613889/197328078-8a88b484-5c68-480e-b2f4-c0b224df20ee.jpg)

14.- Para la ultima sección del footer(copyrigth) utilicé flexbox y le coloqué un background color mas oscuro en comparación al la sección anterior del footer

**Responsive**

Estructuré el CSS en Desktop First por lo tanto usaré la media query "@media (max-width: 780px)" para que a partir de esta medida sea responsive.

1.- El menú como primer elemento responsive no se me dificultó en lo absoluto, especifiqué que el menú tuviese un display:none al cumplir la condicion de estar en una pantalla menor a 780px

2.-la imagen principal no tuvo mayor dificultad para hacerse responsive, por lo que por esa sección fue rapido, le cambié el alto y ya quedó.

3.-En la sección de tarjetas de ofertas, cambié la dirección del flexbox, especifiqué ancho alto y tamaño de las letras.

4.-En la sección 1 de productos tuve mucha dificultad por lo que se me hizo complicado hacer el responsive, miré un video y utilicé la función grid-template-columns:repeat(auto-fit, minmax(400px,1fr) ), me sirvió hasta que me di cuenta que en los mockup desaparecían así que le di una clase en html llamada display none y les comoqué display :none al cumplir la condición de la media query.
![46416094-9b77-4841-b79b-5d205d0988cf](https://user-images.githubusercontent.com/114613889/197328260-f8f38479-74c0-4f51-b605-1876f971de30.jpg)

5.- La cita e imagen, solo ajuste que siguieran en el centro.

6.-La sección de productos 2 seguí los pasos de la seccion de productos 1, solo que esta vez dejé visibles 2 productos.

7.- La sección de email. le especifiqué el ancho el largo y padding del input y button 

8.- La sección de los articulos no me dió problemas en los estilos en css, pero si en el responsive, utilicé flexbox pero tuve dificultades para centrarlos y tulilicé un margin en porcentajes.

 9.- La sección de imágenes de patrocinadores solo se refleja una en el mockups movil por eso le coloqué la misma clase de display none y desaparecieron cuando se cumple la condición especificada en la media query.

10.- Al footer le cambié la propiedad para ordenarlo, le coloqué flexbox, no tuve gran problema al realizar esta sección.

11.- La sección final del footer le coloque display flex y le especifiqué flex-direction:column para poder llegar al resultado obtenido, y al 
![84421bc8-21d7-4ac8-9802-a60c6bc067c1](https://user-images.githubusercontent.com/114613889/197328316-8a4d5b32-8090-4b8b-a17a-1119f9956e74.jpg)
texto le añadí la propiedad text- align:center;

**Repositorio y despliegue**
Realicé los commit de el avance, actualicé el repositorio y el readme del paso a paso y luego hice el despliegue del repositorio en netlify puesto que untente por github y tuve un error.



