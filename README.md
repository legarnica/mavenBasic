# CREACIÓN DE UN PROYECTO SIMPLE UTILIZANDO MAVEN.

+ Se crea el repositorio nuevo en GitHub. El nombre que le demos al repositorio es muy importante, ya que debemos llamar al proyecto de la misma forma cuando lo iniciemos en nuestro computador local.
+ Clonamos el proyecto en nuestro local, en el espacio de trabajo que configuramos en `Spring tool suite`, así quedará con el nombre del repositorio. Qué para el caso de este ejemplo es `mavenBasic`.
+ Nos dirigimos entonces a nuestro IDE y creamos un nuevo proyecto maven.
+ En la primera ventana, `STS-4` nos pregunta la opción `create a simple project`. Lo marcamos, ¿por qué?, por que los arquetipos son plantillas, estas plantillas ayudan a los desarrolladores que dependiendo del tipo de proyecto, les ahorra tiempo añadiendo por defecto características necesarias para desarrollar dichos proyectos. Como lo que queremos es crear un proyecto simple, marcaremos la opción que significa que usaremos el arquetipo: `maven-arquetype-quickstart`.
+ Siguiente ventana:
    + Group id: Es el nombre del paquete, para el caso de ejemplo, se usa : `cl.lherrera`.
    + Artifact id: Es el nombre del proyecto, es importante que tenga el mismo nombre que el repositorio que acabamos de clonar (asumiendo que se clona en el `work space`). Con esto el proyecto se crea en el repositorio que clonamos, evitando tareas manuales que tan mal resultan como copiar el contenido del proyecto creado y pegándolo dentro del repositorio clonado, para hacer un `commit` luego `push`, pueden salir las cosas bien o mal, es mejor ir seguros. (img)
+ Creamos una nueva clase en: `src/main/java` (img)    
+ Llamamos a esta clase con el nombre de `Saludo` y finalizamos. 
+ El código de la clase debería ser el siguiente: 

package mavenBasic;

public class Saludo {
    
    public static void main(String[] args) {
        System.out.println("Hola mundo");
    }

}

+ Guardamos y compilamos. 
+ Finalmente hacemos el `add` y el `push`.

## Conclusiones 
+ Se crea un proyecto básico Maven, a pesar de no aprovechar las utilidades que nos proporciona Maven, ya tenemos un proyecto inicial con el cual poder comenzar algo más complejo.
