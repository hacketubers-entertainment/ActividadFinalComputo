#

## Glosario Final de Conceptos de Programación

### 1. Algoritmo

Secuencia ordenada de instrucciones para realizar un cálculo o resolver un problema específico.

* **Ejemplo:** Pasos lógicos para calcular el área de un rectángulo.

### 2. Programa

Secuencia de instrucciones en un lenguaje de programación que una computadora interpreta y ejecuta para cumplir una función específica.

* **Ejemplo:** Una aplicación ya compilada que recibe datos e imprime el área de un rectángulo.

### 3. Código fuente

Conjunto de instrucciones escritas por un desarrollador en un lenguaje de programación estructurado que indica al sistema cómo funcionar.

* **Ejemplo:**

```java
public class AreaRectangulo {
    public static void main(String[] args) {
        double base = 6.0;
        double altura = 4.0;
        double area = base * altura;
        System.out.println("El área del rectángulo es: " + area);
    }
}
```

### 4. Lenguaje de programación

Conjunto de reglas sintácticas, símbolos y órdenes que permiten a un ser humano comunicarse con una computadora e impartirle instrucciones.

* **Ejemplo:** Java, JavaScript, Python, C++.

### 5. Sintaxis

Conjunto de normas y reglas que determinan cómo deben escribirse y estructurarse los símbolos, palabras y variables para formar código válido en un lenguaje determinado.

* **Ejemplo:** La declaración explícita de variables o la colocación de punto y coma `;` al final de una sentencia.

### 6. Variable

Símbolo o espacio de memoria reservado cuyo valor puede cambiar o modificarse durante la ejecución del programa.

* **Ejemplo:**

```javascript
let manzanas = 5;
manzanas = manzanas + 1;
```

### 7. Constante

Valor asignado a un identificador que permanece inmutable a lo largo del flujo del programa.

* **Ejemplo:**

```javascript
const PI = 3.1416;
```

### 8. Tipo de dato

Clasificación que indica a la computadora qué valor se va a almacenar, cuánto espacio de memoria requiere y qué operaciones se pueden realizar con él.

* **Ejemplo:**

```typescript
let manzanas: number = 10;
let nombre: string = "Garly";
let cambio: number = 3.5;
```

### 9. Operador

Símbolo que indica al motor del lenguaje que debe realizar una operación matemática, lógica o relacional específica.

* **Ejemplo:**

```javascript
let suma = 10 + 20;
let resta = 10 - 20;
let multiplicacion = 10 * 20;
```

### 10. Expresión

Combinación de valores, variables, operadores y llamadas a funciones que se evalúan para producir un único resultado.

* **Ejemplo:**

```javascript
let area = (base * altura) / 2;
```

### 11. Condicional

Estructura de control que evalúa una sentencia como verdadera o falsa para decidir qué bloque de instrucciones ejecutar.

* **Ejemplo:**

```javascript
if (edad < 18) {
    console.log("Es menor de edad");
}
```

### 12. Bucle

Estructura de control que repite la ejecución de un bloque de código hasta que se cumpla una condición predeterminada.

* **Ejemplo:** Estrategias como `for`, `while` o `do...while`.

### 13. Función

Bloque de código modular y reutilizable diseñado para realizar una tarea específica.

* **Ejemplo:**

```javascript
function sumar() {
    let suma = 10 + 10;
    return suma;
}
```

### 14. Parámetro

Variable especificada en la definición de una función para recibir datos de entrada cuando esta sea invocada.

* **Ejemplo:** `a` y `b` en la siguiente declaración:

```javascript
function sumar(a, b) {
    let suma = a + b;
}
```

### 15. Argumento

El valor real y concreto que se le pasa a una función al momento de ejecutarla.

* **Ejemplo:** Pasar las variables `a` y `b` con valor
`10` a la función `sumar(10, 10)`:

```javascript
let a = 10;
let b = 10;
sumar(a, b);
```

### 16. Retorno

Resultado o valor final que una función devuelve al punto de origen desde donde fue invocada mediante la palabra clave `return`.

* **Ejemplo:**

```javascript
function sumar(a, b) {
    return a + b;
}
```

### 17. Arreglo (Array)

Estructura de datos ordenada que permite almacenar una colección ordenada de elementos dentro de una misma variable.

* **Ejemplo:**

```javascript
const productos = ["escoba", "trapeador", "trapo", "jabón", "detergente"];
```

### 18. Objeto

Unidad de código independiente que agrupa propiedades (atributos) y métodos (funciones) relacionados bajo una misma estructura.

* **Ejemplo:** Un objeto `Coche` con atributos como `color`, `tamaño` y `numeroAsientos`.

### 19. Método

Función definida dentro de una clase u objeto que representa una acción o comportamiento específico de dicho objeto.

* **Ejemplo:** Los métodos `arrancar()`, `acelerar()` y `frenar()` de un objeto `Coche`.

### 20. Evento

Acción o suceso detectado por el programa (como una interacción del usuario o una señal del sistema) que desencadena una respuesta lógica.

* **Ejemplo:** La acción `click` sobre un botón dentro de un formulario web.

### 21. Compilador

Programa especializado que toma el código fuente escrito en un lenguaje de alto nivel y lo traduce por completo a código máquina o binario en un solo proceso antes de su ejecución, generando un ejecutable independiente.

* **Ejemplo:** Al programar en C++, el software GCC traduce todo el archivo `.cpp` a un ejecutable `.exe`. Si hay errores, detiene el proceso antes de crear el archivo.

### 22. Intérprete

Herramienta que lee, traduce y ejecuta el código fuente instrucción por instrucción en tiempo real, sin generar un ejecutable previo.

* **Ejemplo:** El motor de Python lee un script de arriba a abajo; si encuentra un error en la línea 10, ejecuta con éxito las líneas 1 a 9 antes de detenerse.

### 23. Depurador (Debugger)

Herramienta de desarrollo que permite inspeccionar la ejecución paso a paso de un programa para localizar, analizar y corregir fallos o comportamientos inesperados en el código.

* **Ejemplo:** Colocar un punto de interrupción (*breakpoint*) en una función para observar cómo cambian las variables internas en cada iteración de un bucle.

### 24. IDE (Entorno de Desarrollo Integrado)

Software integral que reúne en una sola interfaz todas las herramientas necesarias para desarrollar software, incluyendo editor de código, depurador, compilador/intérprete y gestor de proyectos.

* **Ejemplo:** Android Studio o Apache NetBeans.

### 25. Editor de código

Aplicación liviana enfocada en la escritura y edición de texto plano optimizada para programación, con funciones de resaltado de sintaxis, autocompletado y personalización mediante extensiones.

* **Ejemplo:** Visual Studio Code o Sublime Text.

### 26. Biblioteca (Library)

Conjunto de funciones, métodos y fragmentos de código reutilizables diseñados para resolver tareas específicas, los cuales el desarrollador invoca según los necesite.

* **Ejemplo:** La biblioteca `Math` en JavaScript, que ofrece herramientas predefinidas como `Math.random()`.

### 27. Framework

Estructura de trabajo predefinida que proporciona un conjunto de reglas, patrones de arquitectura y componentes sobre los cuales se construye una aplicación, controlando el flujo del desarrollo.

* **Ejemplo:** Laravel en PHP o NestJS en Node.js.

### 28. API (Interfaz de Programación de Aplicaciones)

Conjunto de reglas y protocolos que permite a dos sistemas o aplicaciones informáticas comunicarse entre sí e intercambiar datos de manera segura y estandarizada.

* **Ejemplo:** Una API meteorológica que un sitio web consulta para obtener y mostrar la temperatura actual de Mérida en formato JSON.

### 29. Repositorio

Espacio digital de almacenamiento donde se guardan los archivos de un proyecto informático, junto con el historial de cambios, versiones y archivos de configuración.

* **Ejemplo:** La carpeta administrada por Git en el disco duro o en la nube que contiene el código fuente, imágenes y assets de una aplicación web.

### 30. Control de versiones

Sistema o práctica que registra los cambios realizados sobre un conjunto de archivos a lo largo del tiempo, permitiendo revertir modificaciones, comparar diferencias y coordinar el trabajo en equipo.

* **Ejemplo:** La capacidad de restaurar un archivo de código a la versión exacta que funcionaba el viernes antes de que un error dañara la función principal.

### 31. Git

Sistema de control de versiones distribuido de código abierto que se ejecuta localmente en la computadora para rastrear el historial de cambios del código fuente de forma rápida y eficiente.

* **Ejemplo:** Ejecutar comandos desde la consola del sistema para registrar hitos en la evolución del software sin depender de conexión a Internet.

### 32. GitHub

Plataforma en la nube que aloja repositorios de Git, añadiendo herramientas avanzadas para la colaboración en equipo, revisión de código, gestión de tareas y despliegue continuo.

* **Ejemplo:** Subir el código de un proyecto para que otros programadores puedan revisarlo, hacer aportaciones o reportar errores.

### 33. Rama (Branch)

Línea de desarrollo independiente dentro de un repositorio que permite trabajar en nuevas funcionalidades o correcciones sin alterar la versión principal del código.

* **Ejemplo:** Crear una rama llamada `feature-login` para programar el inicio de sesión sin arriesgar la versión estable del proyecto.

### 34. Commit

Registro puntual o captura del estado actual de los archivos en el repositorio que guarda los cambios realizados junto con un mensaje descriptivo y un identificador único.

* **Ejemplo:**

```bash
git commit -m "add: Agregue la funcion principal"
```

### 35. Merge

Operación en los sistemas de control de versiones que combina los cambios e historial de una rama secundaria dentro de una rama principal o de destino.

* **Ejemplo:** Fusionar la rama `feature-login` a la rama `main` una vez que las pruebas del módulo de autenticación fueron superadas con éxito.

### 36. Callback

Función que se pasa como argumento a otra función para ser ejecutada más tarde, una vez que se complete una tarea específica.

* **Ejemplo:** Pasar una función a un evento de botón en JavaScript para que se ejecute únicamente cuando el usuario haga clic sobre él.

### 37. Programación síncrona

Modelo de ejecución secuencial en el que cada instrucción debe finalizar por completo antes de pasar a la siguiente, bloqueando la ejecución del programa mientras se completa la tarea activa.

* **Ejemplo:** Un script que lee un archivo pesado del disco y detiene el resto del programa hasta terminar de cargar todo el contenido en memoria.

### 38. Programación asíncrona

Modelo de ejecución en el que las tareas de larga duración (como peticiones a bases de datos o red) se inician en segundo plano, permitiendo que el programa principal continúe respondiendo sin bloquearse.

* **Ejemplo:** Hacer una petición `fetch()` a una API en una aplicación web mientras la interfaz sigue respondiendo al desplazamiento del usuario.

### 39. JavaScript

Lenguaje de programación interpretado, dinámico y multiparadigma, utilizado principalmente para aportar interactividad y dinamismo a las páginas web tanto en el cliente como en el servidor.

* **Ejemplo:** Escribir un script en la web para validar que un campo de correo contenga un `@` antes de enviar un formulario.

### 40. TypeScript

Lenguaje de programación desarrollado por Microsoft que actúa como un superconjunto de JavaScript, añadiendo tipado estático opcional y herramientas avanzadas que se compilan a JavaScript puro.

* **Ejemplo:**

```typescript
let edad: number = 19;
```

---
