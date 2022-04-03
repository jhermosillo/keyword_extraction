Esta notebook contiene los algoritmos de Grado de Fractalidad y TextRank los cuales obtienen de acuerdo a su metodología, las palabras "importantes".

El proceso es el siguiente:
DEFINICIÓN DEL NOMBRE DEL ARCHIVO A PROCESAR
1. Cargar la notebook en google colab
2. Ejecutar las celdas 1 - 3, que contiene librerías para el uso de los algoritmos
3. Ejecutar la celda 4 que contiene el algoritmo de TextRank
4. Ejecutar la celda 5 - 7 que contiene el algoritmo de grado de fractalidad

DEFINICIÓN DEL NOMBRE DEL ARCHIVO A PROCESAR
5. Para poder procesar un documento plano (txt), hay que crear en raíz en colab una carpeta InputData/ y colocar el txt a procesar. Para la salida de datos procesados, se tiene que crear una carpeta Results/

6. Definir en la celda 8 el nombre del documento a procesar: filename='data.txt'
7. Ejecutar la celda 9 para cargar la info del archivo a procesar

Resultados

8. Ejecutar la última celda (9) para obtener los resultados de procesar el documento plano. Este proceso genera en la carpeta Results/ dos documentos de csv uno para cada resultado de cada algoritmo. Estos documentos tendrán un listado de las palabras rankeadas de mayor a menor valor de acuerdo a la metodología de cada algoritmo.