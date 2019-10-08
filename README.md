## First Class:
Las expresiones regulares son un gran superpoder
Funcionan para solicitar algo en especifico (cadenas)
Utilizan simbologia particular para poder describir una expresion regulares
Herramienta en linea llamada regex101
Se utilizo el simbolo "." para la primera expresion regulares

## Second Class:
Uso del signo de interrogación para hacer opcionales caracteres
Uso de square Brackets [] para agrupar varios caracteres y validarlos en dicha posicion

## Third Class:
Uso de rangos en las expresiones regulares [A-Z] [0-9] [a-z]

## Fourth Class:
Uso de 
\s (para cualquier tipo de espacios, tab, enter )
\w (para cualquier caracter A-Z, a-z, _)
\d (para cualquier numero )

## Fifth Class:
Repeticiones en expresiones regulares
+ (Tiene que haber 1 o más después de lo solicitado)
* (Puede haber 0 o más )
{} podemos especificar cantidad con las llaves ejemplo
{3} solo 3 
{3,} 3 en adelante
{3,5} 3 entre 5

## Sixth Class:
Excepciones
Podemos excluir caracteres con nuestras expresiones regulares, existen varias formas como:
[^] despues del piquito, se excluira cualquier caracter que coloquemos
\D  excluye todos los que no sean digitos
\W excluye todos los que no sean palabras
\S exluye todo lo que no sea espacios

## Seventh Class:
Alternation
Es como el OR logico en progrmacion
funciona con | 

## Eigth Class:
Agrupaciones
Para realizar sub grupos de cadenas en expresiones regulares usamos los parentesis
()

## Ninth Class:
Uso del simbolo $ para quitar las invalidas expresiones
Uso del simbolo ^ para quitar el inicio de invalidas expresiones

## Tenth Class:
Conclusiones acerca de expresiones regulares
Sus usos y donde colocarlas

### Quizz:
How do yo require the regular expression parser to begin marching at the beginning od the input string?
R// Start with the expression ^

What does a question mark in a regular expression do?
R// It matches zero or one of the previous character.

How do you express alternation (or) in a regular expression?
R// |

What do regular expressions do?
R// Describe patterns in strings

What does the \d character match?
R// It matches a number character.









