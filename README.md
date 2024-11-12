<div align="center">
<h2 align="center">About GEMMA CLAVERO DEL MORAL 👋</h2>


## About me

- 🌱 I’m currently re-skilling learning Html, CSS & JS & a little bit of IA & Cibersecurity Fundamentals
- 👯 I’m looking to collaborate on Programing Teams to achive new skills   
- 📫 How to reach me: + 57 320-83427237 best wapp
- ⚡ Fun fact: I love programing learning now with more than 50 years old!
- 🔭 Early:  My first new programing work! Total convence <br>
</div>

## REPOSITORY SUMMARY

## [eCommece Practice](https://gemmaclaverodelmoral.github.io/vola/) - eCommerce practice with React / Vite / TailwindCss

<div align = "center">  
<img src="" width="800px"/>
</div>
<div align = "center">  
<img src="https://github.com/GemmaClaverodelMoral/vola/blob/master/public/assets/Captura-Vola.png" width="800px"/>
</div>

### eCommerce "simulation" with React, Vite & TailwanCSS

### What does this project contain?
- Asynchronous database access: FireStore
- Product filters by title (input) and categories (navbar) 
- Creation and views of Purchase Order CheckOuts and Show Product
- Deployment to GitHub
- Many things are still missing, but up to this point, this was the exercise:
- WhatsApp button, image enlargement in detail, making the first 8 photos general and accessible for filtering, fixing overlapping components, shopping cart 
### What was used?
 - CSS, HTML, JavaScript, Git, and GitHub, DOM manipulation, React, Vite with TailwindCSS
 - Hooks: useState, useContext, useEffect, ReactRouter, NavLink, useLocation
#
### ¿Que contiene este proyecto?
-	Acceso a base de datos asincronicamente: FireStore
-	Filtros de productos por título (input) y categorías (navbar) 
-	Creacion y vistas de CheckOuts de Ordenes de compra y Show Pruduct
-	Deploy a github
-	Faltan muchas cosas pero hasta este punto era el ejercicio:
- Boton de whatsApp, Ampliacion de imagenes en detalle, que las 8 primeras fotos sean generales y de acceso a filtro, arreglar los componentes que se solapan, carrito de la compra, 
### ¿Qué se usó?
 -	CSS, HTLM, JavaScrip, GiT y GitHub, manipulación del DOM, React, Vite con TailwindCSS
 - Hooks: useState, useContext, useEffect, ReactRouter, Navlink, useLocation

## [TODO's List](https://gemmaclaverodelmoral.github.io/ToDos-List-with-React/) - React.JS Introduction Project
 - 📖🗓

Task List / TO DO's
Interactive Application to add, delete, mark tasks as pending or completed.  
Additionally, it has a window control feature: if two users/windows change the LocalStorage, the other windows are prompted to refresh the page before continuing (in fact, everything is locked until they do).
#
Lista de Tareas / TO DO's  
Aplicacion Interactiva para Ingresar, eliminar, marcar tareas pendientes y ejecutadas.
Adicional tiene un control de ventanas donde en caso de que dos usuarios/ventanas cambien el LocalStorage el resto de ventanas son invitadas a actualizar la pagina antes de seguir ( de hecho todo queda bloqueado hasta no hacerlo)

<div align = "center">  
<img src="https://github.com/GemmaClaverodelMoral/ToDos-List-with-React/blob/main/public/TODOs-vistas.png" width="800px"/>
</div>
<div align = "center">  
<img src="https://github.com/GemmaClaverodelMoral/ToDos-List-with-React/assets/142899102/60525a84-3840-4e6f-ad99-90f8de93fe9b" width="50px"/>
</div>

Using and testing with:
 - React (Components and more)
 - Data persistence with LocalStorage
 - Loading and error handling
 - Hooks: useState, useContext, useEffect
 - Modals
#
Usando y provando con:
 - React (Componentes y demas)
 - Persistencia de datos con LocalStorage.
 - Manejo de carga y error
 - Hooks: useState, useContext, useEffect
 - Modals

## [PRACTICE OF STATE MANAGEMENT in React IN DIFFERENT WAYS](https://gemmaclaverodelmoral.github.io/comparativa-useState-react.component-useRedux/)    

PASSWORD VALIDATION APPLICATION using three state management formats:
- React Hooks: React.useState
- React Hook: React.useReducer
- Classes: React.Component
#
APLICACION DE VALIDACION DE CLAVE usando tres formatos de manejo del estado:
- React Hooks: React.useState
- React Hook: React.useReduce
- Clases: React.component

<div align = "center">  
<img src="https://github.com/GemmaClaverodelMoral/comparativa-useState-react.component-useRedux/blob/main/public/Manejos-del-estado-React.png" width="400px"/>
</div>

Security Code Project where a security code must be requested to confirm performing an action.
Request code: correct or incorrect <<
Request confirmation: Yes or No
Then perform the action, with an undo option to revert to the previous state.

It will be tested with the hooks React.useState and React.useReducer, and with classes using React.Component on the same screen in parallel to practice the similarities and differences.
Features of state in classes compared to React hooks and to practice how complex and declarative states can be managed using Reducer.
#
Proyecto de codigos de seguridad donde se debe poder pedir un codigo de seguridad para
confirmar poder hacer la accion.
Pide codigo. Bien o mal<<
Pide confirmacion . Si o no
Y se hace la accion tener un undo para recuperar el estado anterior.

Se va a probar con los hooks React.useState y React.useReduce y con clases usando React.Component en la misma pantalla en paralelo para practicar las similitures y diferencias
Caracteristicas de los estados en clases comparados con react hooks y para practicar como se pueden seguir estados complejos y declarativos usando Reduce.

## [React.Routes Practice (click to link)](https://gemmaclaverodelmoral.github.io/practica-react-router/)

- Using `<NavLink>` does not require specifying /#/
- Additionally, functions can be called in the tag attributes
- To avoid repeating properties that are repeated in each route, an array of routes is created
- Rendering dynamic routes: slug in the routes using useParams. Hook useNavigate: to switch from one component to another without the need for a link, just placing the slug in the hook
- Hook Outlet: (nested routes) To render multiple routes at once. Things inside things (nested routes).
- Authentication Management: Creation of useAuth: Handling private routes, login, and logout. Usage of React.useNavigate
- Avoid unauthorized navigation from Menu.js using the route attribute: (route.hidden) and useAuth attributes (!auth.user)
- Avoid unauthorized navigation from the URL by creating a ProtectRoutes component to protect route calls in App.js.
- Authorization Management: Delete button is created in the BlogPost component, which is only rendered if you are an administrator (!!auth.user?.isAdmin) or the post creator (auth.user?.userName === blogpost.author)
- A secret route is only rendered if auth.user.userType is an administrator or superAdministrator from the menu and from the URL, and also starts hidden.
- Make the delete Blog button work and delete the blog
- useLocation to return to the page we were on before logging in or logging out
#
- Usando `<NavLink>` no se necesita especificar /#/
- Ademas se puede llamar a funciones en los atributos de la etiqueta
- Para no repetir las propiedades que se repiten en cada ruta se crea un array de rutas
- Renderizacionde de rutas dinamicas :slug en las rutas usando useParams. Hook useNavigate: para cambiar de un componente a otro sin necesidad de link solo poniendo el slug en el hook
- Hook Oulet: ( nested routes )Para renderizar varias rutas a la vez. Cosas dentro de cosas (nested routes).
- Manejo de Autenticaciones: Creacion de useAuth: Manejo de rutas privadas. login y logout. uso de React.useNavigate
- Evitar navegacion no autorizada desde Menu.js usando el atributo de las rutas: (route.hidden) y atrubutos del useAuth (!auth.user) 
- Evitar navegacion no autorizada desde Url creando un componente ProtectRoutes que proteja el llamado a las rutas en App.js.
- Manejo de Autorizaciones: Se crean boton de eliminacion en el componente BlogPost que solo se renderiza si eres administrador (!!auth.user?.isAdmin) o si eres creador del Post (auth.user?.userName === blogpost.author) 
- Un ruta secreta solo se renderiza si el auth.user.userType es de administrador o superAdministradordesde el menu y desde la Url ademas de iniciar ocultamente.
- Hacer el que boton de borrar Blogs funcione y borre el blog
- useLocation para poder devolvernos a la pagina en la que estabamos antes de hacer login o logout

## [Use of CANVAS Practice/ maps. (click to link)](https://gemmaclaverodelmoral.github.io/EjercicioCanvas/)
<div align = "center">  
  <img src="https://github.com/GemmaClaverodelMoral/EjercicioCanvas/blob/main/Dibujar%20CANVAS%20-%20Automatico%20-%20flechas%20teclado%20-%20Mouse%20o%20touch.png" width="600px" align="center"/>
</div>

- 1st map: A geometric shape is drawn with lines
- 2nd map: A shape is drawn with successive lines using:  
  - 🖥️ COMPUTER: Pressing the keyboard keys  
  - 📲 MOBILE: Touching arrow images ⬆️➡️⬇️⬅️
- 3rd map: Curved lines are drawn.  
  - 🖥️ COMPUTER: With the mouse.  
  - 📲 MOBILE: With the finger.  
  - Extra CANVAS: The farm. Handling static and moving images on Canvas. [The FARM](https://gemmaclaverodelmoral.github.io/La-Granja-Canvas/)
  
#

- 1er mapa: se pinta una fugura geometrica con lineas
- 2do mapa: se pinta fugura con lineas succesivas usando: 
  - 🖥️ COMPUTADOR: Presion en las teclas del teclado
  - 📲 CELULAR: Touch en unas imagenes de flechas ⬆️➡️⬇️⬅️
- 3er mapa: se pintas lineas curvas.
  - 🖥️ COMPUTADOR: Con el mouse. 
  - 📲 CELULAR: Con el dedo.
  - Extra CANVAS: La granja. manejo de imagenes en Canvas estaticas y con mov. [La GRANJA](https://gemmaclaverodelmoral.github.io/La-Granja-Canvas/)

## [Mokepon GAME MultiUser/Different devices (click to link Video Simulation)](https://youtu.be/t7RxgL8aQxs) - Responsive Version

Multiplayer game code programmed in HTML, CSS, and JS, where each player connected to a server from their computer, mobile device, or any other device connected to the same local network can enter, choose, search for their opponent through a map, and send attacks with enemy mokepones.  
It was mainly created to practice HTML, CSS, JS skills and understand the basic management of a backend server with requests and responses.  
I show three basic screens.
#
Codigo de Juego multijugador programado en HTML, CSS y JS donde cada jugador conectado a un servidor desde su computador, dispositivo mobil o cualquier otro dispositivo conectado a la misma red local, puede entrar a elegir, buscar a traves de un mapa a su contrincante y mandar ataques con mokepones enemigos.
Basicamente se hizo para poner en practica destrezas html, Css, Js y entender el manejo basico de servidor BackEnd con llamadas y respuestas al mismo.
Muestro tres pantallas basicas.
<div align = "center">  
<img src="https://github.com/GemmaClaverodelMoral/juegomokepon/blob/master/public/assets/mokeponpantallainicio.png" width="400px"/>
<img src="https://github.com/GemmaClaverodelMoral/juegomokepon/blob/master/public/assets/mokeponpantallamapa.png" width="400px"/>
<img src="https://github.com/GemmaClaverodelMoral/juegomokepon/blob/master/public/assets/mokeponpantallabatalla.png" width="400px"/>
</div>
<div align = "center">
<p> *Si quieres jugar sigue las instrucciones del README del repositorio del juego</p>
</div>

## [QuotesMachine - click to link](https://gemmaclaverodelmoral.github.io/Quotes-Machine/)
Screen where different famous quotes appear, and users can access different social media platforms to share the chosen quotes.
#
Pantalla en la que van saliendo diferentes frases celebres y se pueden hacer accesos a diferentes redes sociales para compartir las frases elegidas.
<div align = "center">
<img src="https://github.com/GemmaClaverodelMoral/Quotes-Machine/blob/main/Qutes-Machine-Image.png" width="300px"/>
</div>

# ADITIONAL Challenges - Not relevants

## [Calculator - click to link](https://gemmaclaverodelmoral.github.io/Calculadora-Sencilla/)

<div align = "center">
<img src="https://github.com/GemmaClaverodelMoral/Calculadora-Sencilla/blob/main/Imagen-Calculadora.png" width="200px"/>
</div>

## [FizzBuzz](https://gemmaclaverodelmoral.github.io/FizzBuzz/)
<span>... por todos conocido</span><br>
![学习中GIF](https://github.com/GemmaClaverodelMoral/GemmaClaverodelMoral/assets/142899102/2e7e1be2-335f-4974-8598-6ce53272df5a)

<div align = "center">
<img src="https://github.com/GemmaClaverodelMoral/FizzBuzz/blob/main/Imagen-Reto-FizzBuzz.png" width="400px"/>
</div>

Ejercicio de FIZZBUZZ pero mas elegante del que hice hace meses.

[FIZZ BUZZ ELEGANTE](https://gemmaclaverodelmoral.github.io/NewFizzBuzz/) 

Pongo el codigo JS aqui porque es la gracia de la mejora:
<div align="center">
  <img src="https://github.com/GemmaClaverodelMoral/NewFizzBuzz/blob/main/FIZZBUZZ.png" width="400px" align="center">
</div>

## [Cajero Automatico](https://gemmaclaverodelmoral.github.io/cajero/)

Programa que me da plata segun el valor entrado en un input y me dice cuatos billetes de cada clase me da.
Aplicacion de practica para entender el uso de array de objetos y recorrerlo
Tambien programe un ALERT personalizado (ya que no me gusta el que da el navegador
Se probo con creacion de <p>'s que se llenan en forma dinamica desde JS.
<div align = "center">  
  <img src="https://github.com/GemmaClaverodelMoral/cajero/blob/main/captura-cajero.png" width="300px" align="center"/>
</div>

## [PaseFiesta](https://gemmaclaverodelmoral.github.io/Ejercicio-01-PaseFiesta/)

Codigo JS que determina si una persona puedo o no entrar a una fiesta y si debe de pagar. Se ejecuta para 3 personas.
<div align = "center"><br>
  <img src="https://github.com/GemmaClaverodelMoral/Ejercicio-01-PaseFiesta/blob/main/problema02.png" width="400px"/>
</div>

## [EjercicioB-AssistencaAlumnos](https://gemmaclaverodelmoral.github.io/EjercicioB-AssistencaAlumnos/)
Codigo JS para registrar la asistencia durante 30 dias de los n alumnos de una clase y reprovarlos en caso de mas de 18 inasistencias
<div align ="center">
  <img src="https://github.com/GemmaClaverodelMoral/EjercicioB-AssistencaAlumnos/blob/main/problemaB.png" width="400px"></img>
</div>

## [Calculadora-con-Prompt](https://gemmaclaverodelmoral.github.io/Calculadora-con-Prompt/)
Calculadora para hacer unas pruebas de JS de funciones flecha sencillas
<div align ="center">
  <img src="https://github.com/GemmaClaverodelMoral/Calculadora-con-Prompt/blob/main/calculadora.png" width="600px"></img>
</div>

## [Juego de Piedra 🪨, Papel 🧻 o Tijeras ✂️](https://gemmaclaverodelmoral.github.io/piedrapapelotijera/)
Se juega contra la aletoriedad del computador con un edicion basica con prompts y alerts
<div align ="center">
  <img src="https://github.com/GemmaClaverodelMoral/piedrapapelotijera/blob/main/piedrapapelotijera.png" width="300px"></img>
</div>
