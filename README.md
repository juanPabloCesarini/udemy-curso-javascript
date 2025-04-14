# udemy-curso-javascript
Curso para afianzar mis conocimientos en Javascript.

Extensiones necesarias para trabajar en **VSC**:

- Live Server
- HTML CSS Support

Siempre vamos a trabajar en el explorador haciendo click derecho y activando la opcion ***inspeccionar*** esto permite ver la estructura de html, css (dentro de elementos) y en la opción consola podemos ir testeando todo el funcionamiento de js.

También se tiene que ver el apartado de ***aplicaciones*** donde se utilizara el localStorage.

**RECOMENDACION**: 

Siempre trabajar con archivos .js, salvo que sea una minúscula función donde hay podemos escribir código javascritpt dentro del html, con las etiquetas script. Ejemplo:
```html
<script>
  console.log("Hola, Juan!");
</script>
```



#   VARIABLES
  En la actualidad solo se usan let y const para definir las variables.

  Si bien var se puede seguir utilizando pero ya no siguen las buenas prácticas actuales.

  ### Declaración de las variables

  ```javascript
    let mascota;
  ```

   ### Inicialización de las variables

  ```javascript
    mascota = "perro";
  ```

  También podemos declarar e inicializar

   ```javascript
    let mascota = "perro";
  ```

  Para comprobarlo buscamos la consola en inspeccionar a travès de console.log() enviamos la variable para que nos muestre el contenido.

  ```javascript
    let mascota = "perro";
    console.log(mascota); 
  ```

  ## let no permite declarar 2 veces una variable.

  ## let ermite declarar e incializar en cualquier lugar en código luego de declararla.

  ### Variable undefined o variable null
  El primer caso se da cuando se declara la variable pero no se ha asignado un valor o bien la variable no existe, se puede dar el caso de no tener acceso a la misma.

  En el segundo caso null es una opción nuestra de inicializar una variable sin un valor.

## const no permite declarar una variable sin inicializarla.
Al igual que let no podes declarar 2 veces la variable con el mismo nombre. Lo más importante es comprender que **const** es una constante, o sea no cambia su valor.