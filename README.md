# Parcial_3-Programación

Dentro del documento .rar se encuentra una carpeta llamada "Parcial No.3", dentro de esta se encuentra
el archivo llamado "programa" el cual ejecuta el problema solicitado, un archivo llamado "__init__",
un archivo .txt llamado "Aspirantes" el cual contiene toda la base de datos usada durante el ejercicio y
una carpeta llamada "Funciones" la cual contiene todas las funciones para que el programa funcione.

\
Archivo programa.py

En este archivo empezamos por importar las funciones creadas para el funcionamiento de este, posteriormente
creamos variables con todos los textos necesarios para el codigo. Creamos la primera funcion llamada
"Inicio" en la cual iniciamos por volver la variable "Var_1" accesible en todo el programa mediante
global, posteriormente solicitamos la ruta de la base datos, ademas solicitamos de la libreria 
las diferentes funciones necesarias para completar la interfaz.

Creamos la segunda funcion llamada "interfaz" en esta desarrolamos la interfaz que vera el usuario
en la terminal, esto a partir de condicionales, se inicia mostrando las opciones que tiene el usuario
para escoger selecionando un valor entre el 1 y el 4, ademas para cada uno de estos se creo su respectiva
respuesta a partir de las funciones creadas en nuestra libreria "Funciones".

\
Archivo funciones.py

Dentro de la carpeta "Funciones" se encuentra un archivo .py llamado "funciones" que contiene todas
las funciones necesarias para el funcionamiento del programa, para su funcionamiento es necesario
importar la libreria numpy. La primera funcion creada se llama "Base_de_Datos", en esta empezamos por
crear dos lista vacias, y creamos una variable llamada "Datos" la cual contiene una tupla con el tamaño
de la lista, que posteriormente se dividira en variables nuevas. Posteriormente se crean dos for los cuales
repasaran todas olas filas y columnas de la base de datos, vuelviendo los datos una cadena las cuales se agregaran
en las listas vacias creadas al inicio

La segunda funcion se llama "Verificacion" la cual verifica la ruta ingresada por el usuario para la base
de datos, de ser correcta se usara con la funcion previamente creada "Base_de_Datos" para continuar con el proceso.

Creamos una clase llamada Datos_principal, la cual contendra 4 funciones, siendo la primera "__init__"
la cual usa la funcion Verificacion y trae la lista creada a partir de la base de datos, ademas se crea una
variable que guardara la primera fila de la lista, es decir la fila con el titulo de las columnas.
La segunda funcion se llama "lista_con_Datos" la cual devuelve la lista con los datos de la base de datos. La 
tercera funcion se llama "Datos_Columnas" la cual devuelve una lista con los titulos de las columnas.
Y la ultima funcion se llama "Dimenciones" la cual nos devuelve las dimensiones de la base de datos.
