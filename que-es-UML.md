UML significa Unified Modeling Language el cual es un lenguaje estándar de modelado de sistemas orientados a objetos.


Esto significa que tendremos una manera gráfica de representar una situación, justo como hemos venido viendo. 

niveles de visibilidad

- private

+ public

# protected

~ default

Una forma de representar las relaciones que tendrá un elemento con otro es a través de las flechas en UML

Asociación
cada vez que esté referenciada este tipo de flecha significará que ese elemento contiene al otro en su definición. La flecha apuntará hacia la dependencia.

Herencia
Siempre que veamos este tipo de flecha se estará expresando la herencia.
La dirección de la flecha irá desde el hijo hasta el padre.

Agregación
Este se parece a la asociación en que un elemento dependerá del otro, pero en este caso será: Un elemento dependerá de muchos otros. Aquí tomamos como referencia la multiplicidad del elemento. Lo que comúnmente conocería en Bases de Datos como Relaciones uno a muchos.

Composición
Este es similar al anterior solo que su relación es totalmente compenetrada de tal modo que conceptualmente una de estas clases no podría vivir si no existiera la otra.
