# **MARKDOWN**
## **1. GIT**

Git es un sistema de control de versiones distribuido: seguimiento de cambios en cualquier conjunto de archivos, generalmente utilizado para coordinar el trabajo entre programadores que desarrollan en colaboraci�n el c�digo fuente durante el desarrollo del software.
___

## **2. Atajos**
+ ### Atajos de funcionalidad b�sica.
_Ctrl + Shift + P_: abre la paleta de comandos.

_Ctrl + Shift + N_: abre una nueva ventana.  

_Ctrl + Shift + W_: cierra una ventana.

_F11_: pantalla completa.

+ ### Atajos para la gesti�n de archivos.

_Ctrl + O_: permite abrir con VS Code un archivo existente en el dispositivo.

_Ctrl + N_: abre un archivo nuevo.

_Ctrl + S_: guarda el archivo.

_Ctrl + Shift + S_: realiza la acci�n �Guardar Como�.

_Ctrl + K + Ctrl + W_: cierra todas las pesta�as que est�n abiertas.

_Ctrl + Shift + T_: permite abrir la �ltima o �ltimas pesta�as cerradas.

_Ctrl + 2_: divide la pantalla en dos.

+ ### Atajos para programar.
_Ctrl + Alt + Flechas_: cursor se multiplique en diferentes l�neas.

_Ctrl + C_: copia el fragmento de c�digo seleccionado.

_Ctrl + X_: corta el fragmento de c�digo seleccionado.

_Ctrl + V_: pega el fragmento de c�digo copiado o cortado previamente.

+ ### Atajos de busqueda.

_Ctrl + F_: abre el cuadro de di�logo de b�squeda de elementos. Gracias a �l, podremos encontrar los textos que queramos de forma r�pida.

_Ctrl + H_: abre el cuadro de di�logo de b�squeda junto con el de reemplazo. De esta manera, adem�s de localizar un determinado contenido, podremos reemplazarlo por el que indiquemos. 

___
## **3. Caracter�sticas de Git.**
* Git almacena la informaci�n como un conjunto de archivos.

* No existen cambios, corrupci�n en archivos o cualquier alteraci�n sin que Git lo sepa.

* Casi todo en Git es local. Es dif�cil que se necesiten recursos o informaci�n externos, basta con los recursos locales con los que cuenta.

* Git cuenta con 3 estados en los que es posible localizar archivos: Staged, Modified y Committed.
___
## **4. Comandos de Git.**
+ ### Version.
git version

+ ### Identidad.
git config --global user.name "Isaac Proa�o"

git config --global user.email "blurryface0611@gmail.com"

+ ### Verificaci�n.
git config user.name

git config user.email

+ ### Inicio del control de versiones.
git init

git status 

git add .

git add NombreCarpeta/NombreArchivo

git commit -m "Nombre de proyecto"

+ ### Quitar archivos del control.
echo nombreArchivo.ext >> .gitignore

echo *.txt >> .gitignore

+ ### Ver archivos ignorados.
cat.gitignore

+ ### Forzar agregar archivos excluidos.
git add -f NombreArchivo.log

+ ### Pan de cada d�a.
git push

git pull

### PROCESO PARA SUBIR PROYECTOS A GITHUB.

1. Empezar con __git init__ para crear un nuevo repositorio.

2. Luego verificar si hay qu agregar algo en el __gitignore__ para despues agregar todo mediante el __git add .__

3. Para finalizar realizamos un commit con __git commit -m "nombreproyecto"__.

4. Dirigirse al apartado de __Source Contro__ con Ctrl+Shift+G (Opcional) y publicar.

5. Elegir si subimos el proyecto de forma privada o publica 

6. Terminar con un git push. 

___
## __5. IDE de desarollo.__
Un entorno de desarrollo integrado (IDE) es una aplicaci�n de software que ayuda a los programadores a desarrollar c�digo de software de manera eficiente.

En este caso haciendo uso de Visual Studio Code.

### LINKS DE VIDEOS QUE ME AYUDAN A ENTENDER Y USAR VSCODE:

[Aprender VScode desde cero](https://youtu.be/Ei1y51K8jQk)

[Configurar VScode](https://youtu.be/HVzFLw5r2EM)

[Extensiones](https://youtu.be/BO-nhyqpm7A)

[Temas y fuentes](https://youtu.be/AxPfVH4MHH8)

___

# __6. Introducci�n a C.__

C es un lenguaje de programaci�n (considerado como uno de lo m�s importantes en la actualidad) con el cual se desarrollan tanto aplicaciones como sistemas operativos a la vez que forma la base de otros lenguajes m�s actuales como Java, C++ o C#.

~~~
#include <stdio.h>

int main()
{
	printf("Hello world...!"); 

    return 0;
}
~~~
[Programaci�n en C](https://www.youtube.com/watch?v=5O1srQNyJXo&list=PLWtYZ2ejMVJmUTNE2QVaCd1y_6GslOeZ6)

___
## __7. Caracter�sticas del lenguaje C.__
+ Estructura de C - Lenguaje estructurado.

+ Programaci�n de nivel medio (benefici�ndose de las ventajas de la programaci�n de alto y bajo nivel).

+ No depende del hardware, por lo que se puede migrar a otros sistemas.

+ Objetivos generales. No es un lenguaje para una tarea espec�fica, pudiendo programar tanto un sistema operativo, una hoja de c�lculo o un juego.

+ Ofrece un control absoluto de todo lo que sucede en el ordenador.

+ Organizaci�n del trabajo con total libertad.

+ Los programas son producidos de forma r�pida y son bastante potentes.

+ Rico en tipo de datos, operadores y variables en C.

___
## __8. Sintaxis en C.__
La sintaxis en C es una serie de reglas y procesos que lideran la estructura de un programa. 

El comienzo de todo programa en este lenguaje debe comenzar por #include cuya funci�n es inicializar el entorno de trabajo; en este ejemplo, vinculando el archivo stdio.h (biblioteca de C) que contiene varias funciones.

### Funci�n principal.
La funci�n principal representada como __int main()__ va al principio de todo programa la cual hace que el programa vuelva a ese punto de retorno tras ejecutarse y su orden est� delimitada entre { }.


### Funciones importantes de la biblioteca <stdio.h>
_printf_

_gets_

_getchar_

_fflush_

_scanf_

_sscanf_

___

## __9. Bibliotecas de C.__
Las bibliotecas o librerias son usadas en este lenguaje de programaci�n y est�n formadas por una serie de c�digo con el que podemos leer el teclado, realizar operaciones o imprimir en pantalla.

### Librerias mas destacadas.

_stdio.h_: De entrada y salidad.

_conio.h_: Potente gesti�n de textos.

_math.h_: Para realizar operaciones matem�ticas.

_time.h_: Obtener fecha y hora actual.

___
## __10. Variables - palabras reservadas.__
una variable es un lugar donde se puede almacenar temporalmente un dato. En C las variables tienen un nombre que las identifica, y sirve para hacer referencia a ellas. Tambi�n tienen un tipo, que es el __tipo de datos__ que puede almacenar. El valor de las variables es, como su propio nombre indica, variable

+ Las variables pueden ser locales o globales dependiendo de lo que se necesite.

## __11. Tipos de datos.__
+ A simboliza el nombre de la variable.

_Entero_: int A;

_Entero corto_: short int A;

_Entero largo_: Long int A;

_Real_: float A;

_Real doble_: double A;

_Car�cter_: char A;

## __12. Formato para las variables__

__%c__ == Un car�cter.

__%d__ == Real o entero.

__%i__ == Entero.

__%f__: == Real.

__%g__: == Real.

__%s__ == Cadena.

__%%__ == imprime %.

EJEMPLO:

~~~
#include <stdio.h>

int main(){
    int edad;

        printf("%i Coloca tu edad: ", edad);
        scanf("%i", &edad);


    return 0;
}
~~~
___
## __13. Algoritmos - Algoritmia.__
En matem�ticas, l�gica, ciencias de la computaci�n y disciplinas relacionadas, un algoritmo ? es un conjunto de instrucciones o reglas definidas y no-ambiguas, ordenadas y finitas que permite, t�picamente, solucionar un problema.

Los algoritmos estan conformados por: 

<PROBLEMA - SOLUCI�N>

_________1. Pseudoc�digo

Descripci�n de alto nivel compacta e informal? del principio operativo de un programa inform�tico u otro algoritmo.

_________2. Diagrama de flujo

Representaci�n gr�fica de un algoritmo o proceso.

_________3. Codificiaci�n

Almacenar y recuperar informaci�n.

_________4. Trace(seguimiento)

Informe de los elementos activos en la pila de ejecuci�n en un momento determinado durante la ejecuci�n de un programa.
___
## __14. Procedimientos.__
Un procedimiento es un fragmento de c�digo cuya funci�n es la de realizar una tarea espec�fica independientemente del programa en el que se encuentre.

Sintaxis de los procedimientos: 

+ void "Nombre"()

{

}

## __15. Operadores.__
+ ### OPERADOR DE ASIGNACI�N.

Asignaci�n: (=)

+ ### OPERADORES ARITM�TICOS.

Suma: (+)

Resta: (-)

Multiplicaci�n: (*)

Cociente: (/)

+ ### OPERADORES RACIONALES.
Mayor: (>)

Mayor o igual: (>=)

Menor: (<)

Menor o igual: (<=)

Igual: (==)

Diferente: (!=)

+ ### OPERADORES L�GICOS.
And,y,conjunci�n: (&&)

Or,o,disyunci�n: (||)

Not, no, negaci�n: (!)

___
## __16. Controles de flujo.__
El t�rmino control de flujo se utiliza para describir el m�todo en el que un dispositivo serie controla la cantidad de datos que se transmiten al mismo tiempo.

+ La sentencia __if__

+ El bucle __while__

+ El bucle __do - while__

+ El bucle __for__

+ Las sentencias __break y continue__

+ La selecci�n multiple __switch__

Son algunos de los controles de flujo que tengo que usar.

___
## __17. Array.__
Los arrays son variables estructuradas, donde cada elemento se almacena de forma consecutiva en memoria. Las cadenas de caracteres son declaradas en C como arrays de caracteres y permiten la utilizaci�n de un cierto n�mero de notaciones y de funciones especiales.

## __18. Arrays en una dimensi�n.__
Un array (unidimensional, tambi�n denominado vector) es una variable estructurada
formada de un n�mero "n" de variables simples del mismo tipo que son denominadas
los componentes o elementos del array.

### FORMATO PARA DECLAR UN ARRAY UNIDIMENSIONAL:

tipo nombre[n];

donde: n >= 1

Para acceder a un elemento del array:

nombre[i];

donde: 0 <= i < n

Por ejemplo, la declaraci�n:

int A[4];

define un array de tipo entero de dimensi�n 4. Y ya podr�amos acceder al primer
componente del array por medio de: A[0], al segundo elemento por: A[1] y al �ltimo
elemento por A[3]. 

## __19. Arrays de dos dimensiones.__
Los arrays de dos dimensiones tambien conocidos como matrices.

int nombre[f][c]�;

donde: f,c...>= 1;

Para acceder a un elemento del array multidimensional:

nombre[i][j];

donde: 0 <= i < f ; 0 <= j < c;
2

Durante la declaraci�n de un array multidimensional tambi�n podemos inicializar sus
componentes indicando la lista de los valores entre llaves. En el interior de la lista, los
componentes de cada l�nea del array son encerrados nuevamente entre llaves. Para hacer
m�s cara la visibilidad de los elementos del array, podemos indicarlos en varias l�neas.

int A[3][4] =

{{ 0,1,2,3},

 { 1,2,3,4},

 { 2,3,4,5}}; 

## __20. Cadena de caracteres.__

Una cadena en C es un array de caracteres de una dimensi�n (vector de caracteres) que
termina con el car�cter especial �\0� (cero). 

El formato para declarar una cadena es:

char nombre[n];

donde: n >= 1 y representa a la longitud-1 real de la cadena.

Un ejemplo de declaraci�n de cadena:

char cadena [5];

Debido a que en la representaci�n interna de una cadena de caracteres es terminada por
el s�mbolo '\0', para un texto de "n" caracteres, debemos reservar "n+1�. El car�cter '\0',
aunque pertenece a la cadena, no aparece al utilizar funciones como printf.

En el caso especial de los arrays de caracteres, podemos utilizar varias formas de
inicializaci�n:

char cadena[] = "Hola";

char cadena[] = {'H','o','l','a',0};

char cadena[] = {'H','o','l','a','\0'};

sin especificar el tama�o de la cadena, o especificando el tama�o:

char cadena[5] = "Hola";

char cadena[5] = {'H','o','l','a',0};

char cadena[5] = {'H','o','l','a','\0'};

__*EJEMPLO DE UN EJERCICIO QUE USA UNA MATRIZ*__
~~~
#include <stdio.h>
// Isaac Proa�o
// deber matrices

void InicialNombre()
{
   
    char mc [7] [7] = {
                         {'*', '*', '*', '*', '*', '*', '*'}
                        ,{'*', '*', '*', '*', '*', '*', '*'}
                        ,{'*', '*', '*', '*', '*', '*', '*'}
                        ,{'*', '*', '*', '*', '*', '*', '*'}
                        ,{'*', '*', '*', '*', '*', '*', '*'}
                        ,{'*', '*', '*', '*', '*', '*', '*'}
                        ,{'*', '*', '*', '*', '*', '*', '*'}              
                     };
                     
    int fila = sizeof(mc)/sizeof(mc[0]);
    int columna = sizeof(mc[0])/sizeof(mc[0][0]);
    
         printf("Primera letra del nombre \n\n");

 
for( fila = 1; fila <= 7; fila++) //-----> W
    {
        for (columna = 1; columna <= 5; columna++)
            if ((fila == 1 && columna > 1 && columna < 5 ) || (fila == 7 && columna > 1 && columna < 5 ) || (columna == 3))
                printf (" + ",columna);
            else
                printf("   ");
        printf("\n");
    }
}

int main ()
{
    InicialNombre();
}
~~~
___
## __21. Enumeradores.__

+ #define VTAB'\013'
+ define BELL'\007'
+ define ENTER'\n'
+ define ALERT'\a'

## __22. Expresiones.__
+ \a caracter de alarma 
+ \b retroceso
+ \f avance de hoja
+ \n nueva l�nea
+ \r retorno de carro
+ \t tabulador horizontal
+ \v tabulador vertical

## __23. Nuevas funciones.__

______strindex(linea, pattern);

______int i=atoi(line);

______char line[]="123";

## 24. Funciones interesantes para manejar caracteres.
No s�lo __string.h__ contiene funciones utiles para manejar cadenas de caracteres. En __ctype.h__ que sirve para hacer varias preguntas acerca de los caracteres.

+ isalnum(car�cter): Devuelve un entero.

+ isalpha(car�cter): devuelve __cierto__ si car�cter es una letra, caso contrario __falso__.

+ isdigit(car�cter): Devuelve cierto si car�cter es un __digito__.

+ isupper(car�cter): Devuelve __cierto__ si car�cter es una letra minuscula. 
___
# __25. Introducci�n a C++.__
C++ es un lenguaje de programaci�n que proviene de la extensi�n del lenguaje C para que pudiese manipular objetos. A pesar de ser un lenguaje con muchos a�os, su gran potencia lo convierte en uno de los lenguajes de programaci�n m�s demandados.
~~~
#include <iostream>
using namespace std;

int main(){

	cout<<"Hello world...!";


	return 0;
}
~~~

[Programaci�n en c++](https://www.youtube.com/watch?v=dJzLmjSJc2c&list=PLWtYZ2ejMVJlUu1rEHLC0i_oibctkl0Vh)
___
## __26. Caracter�sticas de C++.__
_Compatibilidad con bibliotecas_: A trav�s de bibliotecas hay muchas funciones que est�n disponible y que ayudan a escribir c�digo r�pidamente.

_Orientado a Objetos:_ El foco de la programaci�n est� en los objetos y la manipulaci�n y configuraci�n de sus distintos par�metros o propiedades.

_Rapidez:_ La compilaci�n y ejecuci�n de un programa en C++ es mucho m�s r�pida que en la mayor�a de lenguajes de programaci�n.

_Compilaci�n:_ En C++ es necesario compilar el c�digo de bajo nivel antes de ejecutarse, algo que no ocurre en otros lenguajes.

_Punteros:_ Los punteros del lenguaje C, tambi�n est�n disponibles en C++.

_Did�ctico:_ Aprendiendo programaci�n en C++ luego es mucho m�s f�cil aprender lenguajes como Java, C#, PHP, Javascript, etc.
___
## __27. Sintaxis de C++.__
De la misma manera que en C, en C++ se debe iniciar con __#include__ mas la libreria estandar de c++ que es el __<"iostream">__ 

+ Los archivos que se creen en un proyecto de C++ deben terminar con .cpp

+ El equivalente al __printf__ viene a ser el __cout<<__

+ El equivalente al __scanf__ es el __cin>>__

+ Para ahorrarme trabajo debo poner el (using namespace std;) antes de empezar con el programa. 
## __28. Bibliotecas de C++.__
+ iostream.h == Biblioteca principal.

+ string.h == Crear y manipular facilmente cadenas.

+ cmath == operaciones matem�ticas.

+ fstream.h == Operaciones de lectura y escritura de archivos.

___
## __29. Archivo.__
Los archivos o ficheros son la forma en la que C++ permite el acceso al disco. Todos los procesos tienen abiertos, por defecto, los archivos 0(entrada), 1(salida) y 2(salida de errores), de manera que en C++ se corresponden con los objetos cin, cout y cerr.


## __30. Archivos.__

### LECTURA Y ESCRITURA DE ARCHIVOS.

~~~
#include<iostream>
#include<stdlib.h>
#include <string.h>
#include<fstream>
using namespace std;

void escribirArchivo();
void lecturaArchivo();
int main(){
	// escribirArchivo();
	lecturaArchivo();
	system("pause");
	return 0;
} 

void escribirArchivo(){
	ofstream escribirArchivo;
	string nombreArchivo,frase; // funcion para poder colocar el nombre que quiero que se cree el archivo y la frase
	char rpt;
	
	cout<<"Digite el nombre del archivo: ";
	getline(cin,nombreArchivo); //guardar e indicar donde guardarse
	
	escribirArchivo.open(nombreArchivo.c_str(),ios::out); //Creamos el archivo
	
	if(escribirArchivo.fail()){ //Si a ocurrido algun error
		cout<<"No se pudo abrir el archivo";
		exit(1);
	}
	
	do{
		fflush(stdin);
		cout<<"Digite una frase: ";
		getline(cin,frase);
		escribirArchivo<<frase<<endl;
		
		cout<<"\nDesea agregar otra frase(S/N): ";
		cin>>rpt;
	}while((rpt == 'S') || (rpt == 's'));
	
	escribirArchivo.close(); //Cerramos el archivo
}
void lecturaArchivo(){
	ifstream leerArchivo;
	string texto;

	leerArchivo.open("fichero.txt",ios::in); //abrimos el archivo en modo lectura

	if(leerArchivo.fail()){
		cout<<"no se pudo abrir el archivo";
		exit(1);
	}

	while(!leerArchivo.eof()){ // mientras no sea el final del archivo 
		getline(leerArchivo,texto);
		cout<<texto<<endl;

	}
leerArchivo.close(); //cerramos el archivo

}
~~~