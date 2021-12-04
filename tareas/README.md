# Nombre del proyecto:
busqueda_autores.py

# Autores:
Jose Rodelmar Ocampo Luna <joserodelmar@gmail.com>
Daniela Goretti Castillo León <danigore22@gmail.com>
Zara Paulina Martínez Sánchez <zaram042001@gmail.com>

# Descripción:
Este programa determina el número de publicaciones de autores obtenidos de 10 artículos sobre un tema en específico.

# Requerimientos:
python3

## REPORTE

# Diseño:  

Mediante el uso de Entrez se accedió a la base de datos  
PubMed donde se obtuvieron hasta los primeros 10 artículos  
más relevantes referentes a cierto tema de interés del usuario,  
publicados en el país y año de preferencia también dado por el  
usuario. Mediante el uso de pandas, seaborn y matplotlib se  
graficaron los artículos obtenidos usando los nombres de los  
primeros autores. Después nuevamente mediante el uso de Entrez  
se buscaron el numero total de artículos publicados por cada uno  
de los primeros autores obtenidos con anterioridad referentes al  
tema de interés y se graficaron los datos obtenidos.  

# Objetivo:  

Obtener el nombre de los principales autores que publicaron en  
cierto año y país sobre algún tema de interés, y con base en  
ello obtener el número total de artículos que esos autores han  
publicado acerca del tema de interés del usuario. Así el usuario  
estará informado de cual(es) autor(es) ha realizado mayor  
investigación del tema que le interesa.  

# Resultados  

Búsqueda ejemplo :  
tema: RNA   
país: Rusia  
año: 2021  

![image-20211204010127452](C:\Users\OL\Desktop\python_class\tareas\image-20211204010127452.png)

En la primera gráfica vemos que el investigador Vzorov AN es  
el autor que mas artículos tiene de esa tema en el año  
determinado.  

Mientras que en la segunda, vemos que si se cuentan todos los  
artículos de este tema relacionados a los autores sin el año,  
vemos que la autora Sokolova TM es la que más artículos tiene.  

![image-20211204010033256](C:\Users\OL\Desktop\python_class\tareas\image-20211204010033256.png)

# Conclusión  

El programa cumple con el objetivo de mostrar a los autores más  
relevantes de un tema de interés que tenga el usuario. Y lo hace  
en dos perspectivas que pueden cambiar entre sí, ya sea por  
actualidad (al determinar un año) o por trayectoria (resultados  
de la segunda gráfica) del autor, dándole al usuario información  
sobre la investigación de su tema tanto en tiempos contemporáneos  
como en un lapso de tiempo más grande, brindando una mayor  
perspectiva.

# Contacto
Si tiene alguna duda con respecto al programa contactar a los correos de los autores (mencionados
en la parte superior del archivo).
