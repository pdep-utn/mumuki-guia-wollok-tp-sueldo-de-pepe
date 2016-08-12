Implementar en Wollok los objetos necesarios para calcular el sueldo de pepe.

El sueldo se pepe se calcula así: _sueldo = neto + valor bono por presentismo + valor bono por resultados_.

El **neto** depende de la categoría, hay varias categorías. Por ejemplo, los gerentes que ganan $1000 de neto, y cadetes que ganan $1500, aunque puede haber más categorías.

Hay dos **bonos por presentismo**:

* en uno es $100 pesos si la persona a quien se aplica no faltó nunca, $50 si faltó un día, $0 en cualquier otro caso;
* hay otro tipo de bono por presentismo que siempre es $0, independientemente de las faltas.

_Nota: sólo para distinguir el monto del bono por presentismo (si es $100, $50 ó $0) se puede usar `if` y sus derivados. En el resto del ejercicio no se puede._

Hay tres posibilidades para el **bono por resultados**:

* 10% sobre el neto,  
* $80 fijos,  
* o nada

**Antes** de subir el TP, **Hagan los tests que se piden en el ejercicio 2**

_Acá aparecen un montón de objetos, piensen bien a qué objeto le piden cada cosa que hay que saber para poder llegar al sueldo de pepe._

> Subir el archivo **.wlk** que tiene los objetos correspondientes. 