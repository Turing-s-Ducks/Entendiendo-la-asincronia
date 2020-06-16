# Entendiendo la asincronia

En esta ocacion aprenderemos que es la asincronia, cuales son sus ventajas, desventajas y la forma en que se comportan los patrones asincronos.

# Seccion 1: Que es la asincronia?

La asicronia se puede entender como '###' y es contraria a la asincronia a la cual comprenderemos como una serie de acciones realizadas una tras otra en orden de ejecucion, lo cual lo hace simple para la gran mayoria de los desarrolladores, sin embargo esto repercute en la funcionalidad de nuestro software y la experiencia de usuario, creando cadenas que no permiten ejecutar otros procesos o metodos a la par debido a que se ejecutan de manera escalonada, instruccion por instruccion y operacion por operacion. 
Javascript cuenta con ... lo que nos permita trabajar con ...
so veamos un ejemplo de esto

Un ejemplo de codigo asincrono es como el siguiente:
```js 
contents = readFile(' ')
```

Por otra parte un ejemplo de codigo asincrono es como el siguiente:
```js
```

### En resumen:
* El codigo **Sincrono** es simple de usar y predecir.
* El codigo **Asincrono** puede ser dificil de predecible pero tener un mejor performace.

# Seccion 2: Non-Blocking
Para entender mejor los conceptos de programacion asincrona es necesario entender los conceptos de bloking y non-blocking. 

### En resumen:

* El codigo **Blocking** es simple de usar y lo podemos encontrar en los procesos **Sincronos**.
* El codigo **Non-blocking** puede puede resultar confuso, pero tiene mejor performance dependiendo el uso que se le de y este se encuentra principalmente en procesos **Asincronos**.

# Programacion multi hilo
**Que son los hilos?**, piensa en tres eficicios de oficinas, en cada uno de estos edificios hay personas trabajando, haciendo diferentes actividades al mismo tiempo, estos edificios a su vez pertenecen a un corporativo, el cual depende de las distintas operaciones que se llevan a cabo en cada una de las oficinas y actividades, dentro de cada edificio. Los hilos son elementos muy similares a los edificios, en estos podemos tener diferentes tareas y operaciones que se realizan al mismo tiempo, y el resultado de las acciones terminara regresandonos algun resultado. So ... vamos a ver un ejemplo.

En el caso del codigo Sincrono el uso de Hilos es sumamente funcional y nos ayuda a optimizar el performance de nuestro software debido a que podemos ocuparlos dentro de un proceso linear para realizar actividades azincronas, requiriendo un coste minimo de memoria.
 #### En resumen
 Los treads o hilos son una forma de procesar actividades de manera asincrona dentro de un codigo sincrono con un coste minimo de memoria.
# Programacion dirigida por eventos.

### Lecturas chidas ...
* [](https://lemoncode.net/lemoncode-blog/2018/1/29/javascript-asincrono)
* []()
