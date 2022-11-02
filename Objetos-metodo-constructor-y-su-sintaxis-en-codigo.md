Los objetos nos ayudan a crear instancia de una clase, el objeto es el resultado de lo que modelamos, de los parámetros declarados y usaremos los objetos para que nuestras clases cobren vida.

Los métodos constructores dan un estado inicial al objeto y podemos añadirle algunos datos al objeto mediante estos métodos. Los atributos o elementos que pasemos a través del constructor serán los datos mínimos que necesita el objeto para que pueda vivir.

**Objetos, método constructor y su sintaxis en código en Java y Python**
---------------------------------------------------------------------  
Un objeto es una instancia de la clase. Los objectos ayudan a crear instancias de una clase, es el resultado de lo que moldeamos, de los parametros declarados y usaremos los objetos para que nuestras clases cobren vida.
---------------------------------------------------------------------
- *Java*
Person juan = new Person();

Al momento de crear objetos en Java, debemos tener claras dos cosas indispensables, la primera es el nombre de la clase para la cual vamos a crear el objeto y segundo el contructor que dicha clase posee, es decir, si el contructor recibe o no parametros. Para crear objetos en Java, el lenguaje proporciona comando *new*, con este comando le decimos a Java qyue vamos a crear un nuevo objecto de una clase en especifico y le enviamos los parámetros (en caso de ser necesario) según el constructor. 
NombreClase miObjeto = new NombreClase();


- *Python*
persona = Person()

Haciendo valer su fama como un lenguaje flexible, para declarar un objeto es bastante sencillo ya que solo necesita el nombre del objeto y la clase a la que hará instancia.
miObjeto = nombreClase()


- *JavaScript*
const person = new Person();

Al igual que con muchas cosas en javaScript, la creación de un objeto es bastante sencillo ya que sólo necesita el nombre del objeto y la clase a la que hará instancia.
var miObjeto = new NombreClase();


- *php*
$person = new Person();

Para crear una instancia de una clase, se debe emplear la palabra reservada *new*.Un objeto se creará siempre a menos que el objeto tenga un constructor que arroje una excepcion en caso de error. Las clases deberian ser definidas antes de la instanciacion (y en algunos casos esto es un requerimiento).
$miObjeto = new NombreClase();

----------------
**Metodo Constructor**

Un contructor es un metodo especial de una clase que se llama autmáticamente siempre que se declara un objeto de esa clase, su función es inicializar el objeto y sirve para asegurarnos que los objetos siempre contengan valores válidos.

Los Paréntesis en OPP representan métodos. Y estos métodos se escriben en mayúscula y tienen el mismo nombre de la clase, a estos se les llama método constructor.

El método constructor se encarga de dar un estado inicial al objeto. Le da una vida en memoria. Además podemos añadirles los datos al objeto a través del método constructor.

De hecho, los datos que le pasaremos a través del constructor serán los datos mínimos que necesita el objeto para que pueda vivir.

Para crear este método constructor lo hacemos:

- *Java*
public Person(String name){
    this.name = name;
}

En el lenguaje Java, si para una clase no se define ningun método contructor se crea uno autmáticamewnte por defecto. El contructor por defecto es un contructor sin parámetros que no hace nada, Los atributos del objeto son iniciados con los valores predeterminados por el sistema.

public nombreClase(String parametro) {
    this.variable = parametro;
}

- *Python*
def_init_(self,name):
    self.name = name

En Python, el metodo condstructor siempre se llama _init_ 

def_init_(self,parametro):
    self.variable = parametro

- *JavaScript*
// A partir de ES6 el constructor se hace dentro de class, así:
class Square {
  // Este es el construtor
  constructor(length) {
    this.name = 'Square';
  }
}

En JavaScript, la función sirve como el constructor del objeto, por lo tanto, no hay necesidad de definir explìcitamente un método constructor.
Cada acción declarada en la case es ejecutada en el momento de la creación de la instancia.

function nombreClase(parametro) {
    this.variable = parametro;
}

- *php*
$person = new Person();
public function __construct($name) {
    $this->name = name;
}

Debemos definir un metodo llamado __contruct (dos caracteres de subrallado y la pakabra construct). El contructor debe ser un metodo publico (public function).

public function__construct($parametro){
    this->variable = parametro;
}
