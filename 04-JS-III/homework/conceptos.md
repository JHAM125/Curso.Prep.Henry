

ARRAYs:

      Los arrays (arreglos) son contenedores, compuestos de los elementos necesarios para ejecutar una accion o complementarla segun sea el caso.

      Un array se identifica porque al abrir dicho array lo hacemos con los corchetes []  luego de haberle dado un nombre ej: var miprimerarray [ // EN ESTA ZONA IRAN NUESTROS ELEMENTOS DE CUALQUIER TIPO YA SEAN STRING, BOLEANOS,NUMERICOS, FUNCIONES, ARRAYS SEPARANDO CADA ELEMENTO POR COMAS];

      EJ: VAR MIPRIMERARRAY [("Hola mucho gusto", 1, false, null, function elemento("string"){return string;}, "James"];
        
      podemos llamar a nuestro array para enterarnos del contenido de este, la madera de hacerlo es la siguiente 

      miprimerarray [];

      de igual manera podemos acceder a cada uno de los elementos contenidos en niuestro array invocando al elemento por su numero de ubicacion, la manera de hacerlo es la siguiente

      mi primerarray [1]

      cada array contiene los elementos y les da un numero, comenzando desde 0 hasta el numero de elementos que contenga

      ej: VAR MIPRIMERARRAY [("Hola mucho gusto", 1, false, null, function elemento("string"){return string;}, "James"];
                                     0            1    2      3                         4                         5  
      
      asi entonces para invocar a cualquiera de nuestros elementos debemos da aclarar que numero de ubicacion necesitamos

      miprimerarray [1];

      así el resultado que retornara sera 1 ya que el numero 1 es el elemento que ocupa la posicion numero 1  dentro de nuestro array

      con los arrays vienen diversar funciones que podemos utilizar a nuestro favor
      algunas de ellas son .length; .push(); .pop(); .unshift(); .shift();

      .length(); al igual que los datos de tipo string, los array comparten esta funcion que permite saber la longitud del array ej: 

      miprimerarray.length;
      el resultado sera 6 ya que al utilizar esta funcion, no toma en cuenta que se cuenta desde cero.

      miprimerarray.push("julian");
      esta funcion agregara el string "julian" a nuestro array en la ultima posicion
      aunque tambien podemos agregar elementos a cada posicion asi: miprimerarray [6] = 1 ;

      miprimerarray.pop();
      esta funcion eliminara el ultimo elemento contenido en nuestro array, en este caso el string "julian"
      sin opcion de recuperacion de este elento.

      miprimerarray.unsift 
      cumple la misma funcion que .push(); pero agrega el elemento antes de la primera posicion. 

      miprimerarray.shift
      cumple la misma funcion que .pop(); pero elimina el primer elemento de nuestro array.    