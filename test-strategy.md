linea - error - solucion

87 - el metodo "addeventlistener" mal escrito - inovar el metodo de manera correcta "addEventListener" 

48 - el numero generado era decimal y no estaba en el rango solicitado - se multiplico el numero por 101 paara poder obtener valores dentro del rango y se utilizo la funcion "ceil"
para quitar los decimales del numero generado

56 - no se indicaba que era un selector de clase por lo cual no se podia hacer referencia al elemento en cuestion - se coloco se coloco el identificador de calase en el query selector

76 - la validacion para verificar que el ususrio adivinara era incorrecta ya que compraba el numero de intentos con el contador - la validacion correcta seria la compracion del numero generado con el numero ingresado por el usuario

65 - el valor retornado era un string lo que impedia hacer la compracion del mismo dentro del if donde se utilizaba - se procede a realizar una exprecion regulara para la validacion del texto y luego se realiza el cast a integer para poder hacer la validacion correspondiente al if

93 - se corrige el estilo para la validacion de numero mayores y menores ingresados por el usurio ya que el estilo no era el indicado - se añade al css una nueva clase la cual se llama desde el elemento que la requiere  class name "upto"

90 - el mensaje que se muestra al momento de perder no cumple con el estilo solicitado - se corrige el estilo por medio de agregar una clase al css y se invoca desde el elemento que la requiere class name "gameover"

90 - el mensaje que se muestra al momento de ganar no cumple con el estilo solicitado - se corrige el estilo por medio de agregar una clase al css y se invoca desde el elemento que la requiere class name "win"

126 - el metodo "addeventlistener" mal escrito - inovar el metodo de manera correcta "addEventListener" 

146 - fallo en el metodo resetGame ya que la variable con la que se generaba el nuevo numero random no hacia referncia a la variable global con la que se trabaja desde el inicio del programa - se elimina la declacion de la variable quitando el let y haciendo referencia a la variable global 

23 - se elimino el padding del estilo css ya que no permitia limpiar la vista de manera correcta al iniciar un nuevo juego - eliminar el padding de la clase lasresult del css

puntos de mejora 

 -- reestructuracion del codigo separando HTML, CSS, JS 

 -- omologar funcinalidades redundantes



