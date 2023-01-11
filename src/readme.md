# **MARKDOWN**
## **1. GIT**

Git es un sistema de control de versiones distribuido: seguimiento de cambios en cualquier conjunto de archivos, generalmente utilizado para coordinar el trabajo entre programadores que desarrollan en colaboración el código fuente durante el desarrollo del software.
___

## **2. Atajos**
+ ### Atajos de funcionalidad básica.
_Ctrl + Shift + P_: abre la paleta de comandos.

_Ctrl + Shift + N_: abre una nueva ventana.  

_Ctrl + Shift + W_: cierra una ventana.

_F11_: pantalla completa.

+ ### Atajos para la gestión de archivos.

_Ctrl + O_: permite abrir con VS Code un archivo existente en el dispositivo.

_Ctrl + N_: abre un archivo nuevo.

_Ctrl + S_: guarda el archivo.

_Ctrl + Shift + S_: realiza la acción «Guardar Como».

_Ctrl + K + Ctrl + W_: cierra todas las pestañas que estén abiertas.

_Ctrl + Shift + T_: permite abrir la última o últimas pestañas cerradas.

_Ctrl + 2_: divide la pantalla en dos.

+ ### Atajos para programar.
_Ctrl + Alt + Flechas_: cursor se multiplique en diferentes líneas.

_Ctrl + C_: copia el fragmento de código seleccionado.

_Ctrl + X_: corta el fragmento de código seleccionado.

_Ctrl + V_: pega el fragmento de código copiado o cortado previamente.

+ ### Atajos de busqueda.

_Ctrl + F_: abre el cuadro de diálogo de búsqueda de elementos. Gracias a él, podremos encontrar los textos que queramos de forma rápida.

_Ctrl + H_: abre el cuadro de diálogo de búsqueda junto con el de reemplazo. De esta manera, además de localizar un determinado contenido, podremos reemplazarlo por el que indiquemos. 

___
## **3. Características de Git.**
* Git almacena la información como un conjunto de archivos.

* No existen cambios, corrupción en archivos o cualquier alteración sin que Git lo sepa.

* Casi todo en Git es local. Es difícil que se necesiten recursos o información externos, basta con los recursos locales con los que cuenta.

* Git cuenta con 3 estados en los que es posible localizar archivos: Staged, Modified y Committed.
___
## **4. Comandos de Git.**
+ ### Version.
git version

+ ### Identidad.
git config --global user.name "Isaac Proaño"

git config --global user.email "blurryface0611@gmail.com"

+ ### Verificación.
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

+ ### Pan de cada día.
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
Un entorno de desarrollo integrado (IDE) es una aplicación de software que ayuda a los programadores a desarrollar código de software de manera eficiente.

En este caso haciendo uso de Visual Studio Code.

### LINKS DE VIDEOS QUE ME AYUDAN A ENTENDER Y USAR VSCODE:

[Aprender VScode desde cero](https://youtu.be/Ei1y51K8jQk)

[Configurar VScode](https://youtu.be/HVzFLw5r2EM)

[Extensiones](https://youtu.be/BO-nhyqpm7A)

[Temas y fuentes](https://youtu.be/AxPfVH4MHH8)

___

# __6. Introducción a C.__

C es un lenguaje de programación (considerado como uno de lo más importantes en la actualidad) con el cual se desarrollan tanto aplicaciones como sistemas operativos a la vez que forma la base de otros lenguajes más actuales como Java, C++ o C#.

~~~
#include <stdio.h>

int main()
{
	printf("Hello world...!"); 

    return 0;
}
~~~
[Programación en C](https://www.youtube.com/watch?v=5O1srQNyJXo&list=PLWtYZ2ejMVJmUTNE2QVaCd1y_6GslOeZ6)

___
## __7. Características del lenguaje C.__
+ Estructura de C - Lenguaje estructurado.

+ Programación de nivel medio (beneficiándose de las ventajas de la programación de alto y bajo nivel).

+ No depende del hardware, por lo que se puede migrar a otros sistemas.

+ Objetivos generales. No es un lenguaje para una tarea específica, pudiendo programar tanto un sistema operativo, una hoja de cálculo o un juego.

+ Ofrece un control absoluto de todo lo que sucede en el ordenador.

+ Organización del trabajo con total libertad.

+ Los programas son producidos de forma rápida y son bastante potentes.

+ Rico en tipo de datos, operadores y variables en C.

___
## __8. Sintaxis en C.__
La sintaxis en C es una serie de reglas y procesos que lideran la estructura de un programa. 

El comienzo de todo programa en este lenguaje debe comenzar por #include cuya función es inicializar el entorno de trabajo; en este ejemplo, vinculando el archivo stdio.h (biblioteca de C) que contiene varias funciones.

### Función principal.
La función principal representada como __int main()__ va al principio de todo programa la cual hace que el programa vuelva a ese punto de retorno tras ejecutarse y su orden está delimitada entre { }.


### Funciones importantes de la biblioteca <stdio.h>
_printf_

_gets_

_getchar_

_fflush_

_scanf_

_sscanf_

___

## __9. Bibliotecas de C.__
Las bibliotecas o librerias son usadas en este lenguaje de programación y están formadas por una serie de código con el que podemos leer el teclado, realizar operaciones o imprimir en pantalla.

### Librerias mas destacadas.

_stdio.h_: De entrada y salidad.

_conio.h_: Potente gestión de textos.

_math.h_: Para realizar operaciones matemáticas.

_time.h_: Obtener fecha y hora actual.

___
## __10. Variables - palabras reservadas.__
una variable es un lugar donde se puede almacenar temporalmente un dato. En C las variables tienen un nombre que las identifica, y sirve para hacer referencia a ellas. También tienen un tipo, que es el __tipo de datos__ que puede almacenar. El valor de las variables es, como su propio nombre indica, variable

+ Las variables pueden ser locales o globales dependiendo de lo que se necesite.

## __11. Tipos de datos.__
+ A simboliza el nombre de la variable.

_Entero_: int A;

_Entero corto_: short int A;

_Entero largo_: Long int A;

_Real_: float A;

_Real doble_: double A;

_Carácter_: char A;

## __12. Formato para las variables__

__%c__ == Un carácter.

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
En matemáticas, lógica, ciencias de la computación y disciplinas relacionadas, un algoritmo ? es un conjunto de instrucciones o reglas definidas y no-ambiguas, ordenadas y finitas que permite, típicamente, solucionar un problema.

Los algoritmos estan conformados por: 

<PROBLEMA - SOLUCIÓN>

_________1. Pseudocódigo

Descripción de alto nivel compacta e informal? del principio operativo de un programa informático u otro algoritmo.

_________2. Diagrama de flujo

Representación gráfica de un algoritmo o proceso.

_________3. Codificiación

Almacenar y recuperar información.

_________4. Trace(seguimiento)

Informe de los elementos activos en la pila de ejecución en un momento determinado durante la ejecución de un programa.
___
## __14. Procedimientos.__
Un procedimiento es un fragmento de código cuya función es la de realizar una tarea específica independientemente del programa en el que se encuentre.

Sintaxis de los procedimientos: 

+ void "Nombre"()

{

}

## __15. Operadores.__
+ ### OPERADOR DE ASIGNACIÓN.

Asignación: (=)

+ ### OPERADORES ARITMÉTICOS.

Suma: (+)

Resta: (-)

Multiplicación: (*)

Cociente: (/)

+ ### OPERADORES RACIONALES.
Mayor: (>)

Mayor o igual: (>=)

Menor: (<)

Menor o igual: (<=)

Igual: (==)

Diferente: (!=)

+ ### OPERADORES LÓGICOS.
And,y,conjunción: (&&)

Or,o,disyunción: (||)

Not, no, negación: (!)

___
## __16. Controles de flujo.__
El término control de flujo se utiliza para describir el método en el que un dispositivo serie controla la cantidad de datos que se transmiten al mismo tiempo.

+ La sentencia __if__

+ El bucle __while__

+ El bucle __do - while__

+ El bucle __for__

+ Las sentencias __break y continue__

+ La selección multiple __switch__

Son algunos de los controles de flujo que tengo que usar.

___
## __17. Array.__
Los arrays son variables estructuradas, donde cada elemento se almacena de forma consecutiva en memoria. Las cadenas de caracteres son declaradas en C como arrays de caracteres y permiten la utilización de un cierto número de notaciones y de funciones especiales.

## __18. Arrays en una dimensión.__
Un array (unidimensional, también denominado vector) es una variable estructurada
formada de un número "n" de variables simples del mismo tipo que son denominadas
los componentes o elementos del array.

### FORMATO PARA DECLAR UN ARRAY UNIDIMENSIONAL:

tipo nombre[n];

donde: n >= 1

Para acceder a un elemento del array:

nombre[i];

donde: 0 <= i < n

Por ejemplo, la declaración:

int A[4];

define un array de tipo entero de dimensión 4. Y ya podríamos acceder al primer
componente del array por medio de: A[0], al segundo elemento por: A[1] y al último
elemento por A[3]. 

## __19. Arrays de dos dimensiones.__
Los arrays de dos dimensiones tambien conocidos como matrices.

int nombre[f][c]…;

donde: f,c...>= 1;

Para acceder a un elemento del array multidimensional:

nombre[i][j];

donde: 0 <= i < f ; 0 <= j < c;
2

Durante la declaración de un array multidimensional también podemos inicializar sus
componentes indicando la lista de los valores entre llaves. En el interior de la lista, los
componentes de cada línea del array son encerrados nuevamente entre llaves. Para hacer
más cara la visibilidad de los elementos del array, podemos indicarlos en varias líneas.

int A[3][4] =

{{ 0,1,2,3},

 { 1,2,3,4},

 { 2,3,4,5}}; 

## __20. Cadena de caracteres.__

Una cadena en C es un array de caracteres de una dimensión (vector de caracteres) que
termina con el carácter especial ‘\0’ (cero). 

El formato para declarar una cadena es:

char nombre[n];

donde: n >= 1 y representa a la longitud-1 real de la cadena.

Un ejemplo de declaración de cadena:

char cadena [5];

Debido a que en la representación interna de una cadena de caracteres es terminada por
el símbolo '\0', para un texto de "n" caracteres, debemos reservar "n+1”. El carácter '\0',
aunque pertenece a la cadena, no aparece al utilizar funciones como printf.

En el caso especial de los arrays de caracteres, podemos utilizar varias formas de
inicialización:

char cadena[] = "Hola";

char cadena[] = {'H','o','l','a',0};

char cadena[] = {'H','o','l','a','\0'};

sin especificar el tamaño de la cadena, o especificando el tamaño:

char cadena[5] = "Hola";

char cadena[5] = {'H','o','l','a',0};

char cadena[5] = {'H','o','l','a','\0'};

__*EJEMPLO DE UN EJERCICIO QUE USA UNA MATRIZ*__
~~~
#include <stdio.h>
// Isaac Proaño
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
+ \n nueva línea
+ \r retorno de carro
+ \t tabulador horizontal
+ \v tabulador vertical

## __23. Nuevas funciones.__

______strindex(linea, pattern);

______int i=atoi(line);

______char line[]="123";

## 24. Funciones interesantes para manejar caracteres.
No sólo __string.h__ contiene funciones utiles para manejar cadenas de caracteres. En __ctype.h__ que sirve para hacer varias preguntas acerca de los caracteres.

+ isalnum(carácter): Devuelve un entero.

+ isalpha(carácter): devuelve __cierto__ si carácter es una letra, caso contrario __falso__.

+ isdigit(carácter): Devuelve cierto si carácter es un __digito__.

+ isupper(carácter): Devuelve __cierto__ si carácter es una letra minuscula. 
___
# __25. Introducción a C++.__
C++ es un lenguaje de programación que proviene de la extensión del lenguaje C para que pudiese manipular objetos. A pesar de ser un lenguaje con muchos años, su gran potencia lo convierte en uno de los lenguajes de programación más demandados.
~~~
#include <iostream>
using namespace std;

int main(){

	cout<<"Hello world...!";


	return 0;
}
~~~

[Programación en c++](https://www.youtube.com/watch?v=dJzLmjSJc2c&list=PLWtYZ2ejMVJlUu1rEHLC0i_oibctkl0Vh)
___
## __26. Características de C++.__
_Compatibilidad con bibliotecas_: A través de bibliotecas hay muchas funciones que están disponible y que ayudan a escribir código rápidamente.

_Orientado a Objetos:_ El foco de la programación está en los objetos y la manipulación y configuración de sus distintos parámetros o propiedades.

_Rapidez:_ La compilación y ejecución de un programa en C++ es mucho más rápida que en la mayoría de lenguajes de programación.

_Compilación:_ En C++ es necesario compilar el código de bajo nivel antes de ejecutarse, algo que no ocurre en otros lenguajes.

_Punteros:_ Los punteros del lenguaje C, también están disponibles en C++.

_Didáctico:_ Aprendiendo programación en C++ luego es mucho más fácil aprender lenguajes como Java, C#, PHP, Javascript, etc.
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

+ cmath == operaciones matemáticas.

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