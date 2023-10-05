un proyecto en java al crearlo te daras cuenta que tiene las lineas
public static void main(String[] args) 
o tambien
public class proyecto extends javax.swing.JFrame {

la primera es principalmente cuando se crean proyectos con main class
la segunda cuando se usan jframe form
aqui una explicacion parte por parte de cada uno de ellos
#### public
public se refiere a que es publico es algo que se puede tener acesso desde todo el proyecto  puede ser una clase o un metodo 
#### private
private se refiere a que ese codigo solo es acessible desde la clase o metodo que creaste osea que ninguna parte de codigo externo puede acedder a el

estas tambien se pueden aplicar a variables o otro tipo de cosas 
por ejemplo si ponemos una variable tipo private no puedes aceder a ellas y modificarlas donde quieras tienes que especificar que quieres que se modifique esa variable puede ser desde otra clase publica pero tienes que especificar

#### void  
en este caso significa que el metodo main no devolvera valor o no necesita ningun valor de regreso en pocas palabras no produce ningun resultado que deba ser usado en otra parte del programa

#### main
este seria el metodo que vamos a usar al referise como main se refiere a que es el punto de entrada de un programa en cuanto se ejecute el programa buscara el main para iniciar desde ahi
por eso no se puede tener main class y jframe en el mismo amenos que elimines la main class del jframe en si  
#### string[]args
se refiere a que aceptara arreglo de caracteres o cadena o conocido como string y indica que args es un arreglo tipo string

#### extends javax.swing.JFrame
significa que el proyecto hereda la clase javax.swing.jframe lo que genera una biblioteca swing para poder crear la interfaz de usuario  y al heredar jframe dice que adquerira todas las propiedades y metodos de jframe lo que hace que podamos tener una interfaz grafica de usuario o GUI



