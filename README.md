# lab04groupEDA
<table>
    <theader>
        <tr>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/epis.png?raw=true" alt="EPIS" style="width:50%; height:auto"/></td>
            <th>
                <span style="font-weight:bold;">UNIVERSIDAD NACIONAL DE SAN AGUSTIN</span><br />
                <span style="font-weight:bold;">FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS</span><br />
                <span style="font-weight:bold;">ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMAS</span>
            </th>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/abet.png?raw=true" alt="ABET" style="width:50%; height:auto"/></td>
        </tr>
    </theader>
    <tbody>
        <tr><td colspan="3"><span style="font-weight:bold;">Formato</span>: Guía de Práctica de Laboratorio / Talleres / Centros de Simulación</td></tr>
        <tr><td><span style="font-weight:bold;">Aprobación</span>:  2022/03/01</td><td><span style="font-weight:bold;">Código</span>: GUIA-PRLD-001</td><td><span style="font-weight:bold;">Página</span>: 1</td></tr>
    </tbody>
</table>
</div>
<div align="center">
    <span style="font-weight:bold;"><h2>INFORME DE LABORATORIO 6</h2></span>
</div>


<table>
<theader>
    <tr><th colspan="6" style="width:50%; height:auto; text-align:center">INFORMACIÓN BÁSICA</th></tr>
</theader>
<tbody>
    <tr>
        <td>ASIGNATURA:</td><td colspan="5">Estructuras de Datos y Algoritmos</td>
    </tr>
    <tr>
        <td>TÍTULO DE LA PRÁCTICA:</td><td colspan="5">Árbol B</td>
    </tr>
    <tr>
        <td>NÚMERO DE PRÁCTICA:</td><td>05</td><td>AÑO LECTIVO:</td><td>2022 A</td><td>NRO. SEMESTRE:</td><td>III</td>
    </tr>
    <tr>
        <td colspan="2">FECHA DE PRESENTACIÓN:</td><td>07-Agosto-2022</td><td colspan="2">HORA DE PRESENTACIÓN:</td><td>11:55</td>
    </tr>
    <tr>
        <td colspan="3">INTEGRANTES:
        <ol>
        <li>Blanco Trujillo, Antony Jacob</li>
        <li>Checalla Soto, Edisson Franklin</li>
        <li>Vilca Suelo, Gionvanni Gabriel</li>
        </ol>
        </td>
        <td colspan="2"> NOTA:</td>
        <td>     </td>
    </tr>
    <tr>
        <td colspan="6">DOCENTE:<br>
        Mg. Richart Smith Escobedo Quispe
        </td>
    </tr>
</table>

#
<div align="center">
    <span style="font-weight:bold;"><h2>I. SOLUCIÓN Y RESULTADOS </h2></span>
</div>

#
## SOLUCIÓN DE EJERCICIOS/PROBLEMAS

#
## Ejercicio 1: Modificar el método de obtención de valor dado una clave (5 puntos)

- ¿Como puedo compilar este ejercicio correctamente en mi pc?

Despúes de clonar este repositorio, para poder ejecutar el código sin dificultad es recomendable que se ejecute desde el IDE eclipse, pues su desarrollo se dio en este,y por ello mismo es que se subieron tambien los archivos necesarios para ejecutarse ahí. Tenemos 2 clases, la primera es la proporcionada por el docente, la segunda es un archivo JAVA (Main) en donde se realiza las pruebas.

</div>

- Enlace a código en GitHub : [Ver Código BTree](https://github.com/AntonyBlanco/lab06groupEDA/blob/main/BTree.java)

- Enlace a código en GitHub : [Ver Código Test](https://github.com/AntonyBlanco/lab06groupEDA/blob/main/Test.java)

#

-   Planificamos La Resolución:

-Iniciamos La Implememntación:

Ahora que tenemos la idea más clara de como implementaremos los requerimeintos vamos a ir con ello:


-   Parte 1

Vemos que para lograr una asignación. dividimos en dos el tamaño de la cadena, esto para forzar a que la primera mitad de los caracteres(valores númericos) se vayan a alamcenar en la pila, y la siguiente tanda en de caracteres (valores numericos) en la cola.


#
## Ejercicio 2: Mostrar en un diagrama de árbol gráficamente la estructura final para los datos ingresados. (4 puntos)


-   En esta sección vamos a hacer una implementación manual. para ello le mostramos los pasos realizados.

-   Iniciamos La Resolución...



Parte 1
<div align="center">

![Ejecucion](Ejercicio2/Diagramas/paso-a.JPG)
</div>

Parte 1
<div align="center">

![Ejecucion](Ejercicio2/Diagramas/paso-b.JPG)
</div>

Parte 2
<div align="center">

![Ejecucion](Ejercicio2/Diagramas/paso-c.JPG)
</div>

Parte 3
<div align="center">

![Ejecucion](Ejercicio2/Diagramas/paso-d.JPG)
</div>

Parte 4
<div align="center">

![Ejecucion](Ejercicio2/Diagramas/paso-e.JPG)
</div>

Parte 5
<div align="center">

![Ejecucion](Ejercicio2/Diagramas/paso-f.JPG)
</div>

Parte 6
<div align="center">

![Ejecucion](Ejercicio2/Diagramas/paso-g.JPG)
</div>

Parte 7
<div align="center">

![Ejecucion](Ejercicio2/Diagramas/paso-h.JPG)
</div>


#
## Ejercicio 3: El método toString() del árbol, retorna lo siguiente. ¿Por qué están entre paréntesis ciertas claves? (4 puntos)



-Mostrar paso a paso el arbol-B al eliminar " www.espn.com": (4 puntos)

-Gáfico Postinserciones
<div align="center">

![Ejecucion](Ejercicio%204/Imagenes/ResultadoPosInserciones.png)
</div>

-Gráfico de eliminación:

<div align="center">

![Ejecucion](Ejercicio%204/Imagenes/ResulrtadoPostEliminacionESPN.png)
</div>

se Procede a ubicar el nodo requerido "ESPN" y al no presentar mayor complicacion que implique algun tipo de rehubicación simplemnete una veze necontrado el nodo procedmos a eliminarlo.


#
## Ejercicio 4: Agregar un nodo adicional (www.youtube.com, 134.24.13.78) y mostrarlo paso a paso. (3 puntos)

- ¿Como puedo compilar este ejercicio correctamente en mi pc?

Para este ejercicio en particular no se requiere de compilar algun código, sin embargo, si quisieramos seguir la secuencia de inserciones, deberíamos de agregar la siguiente linea de código post las inserciones de los ejercicios previos. 

```sh 
	//Ejercicio 4: agregamos nodo adicional (www.youtube.com, 134.24.13.78)
	//st.put("www.youtube.com", "134.24.13.78");
```

Este código los podemos ejecutar desde el archivo de java denominado  [test4](https://github.com/AntonyBlanco/lab06groupEDA/blob/echecalla/Test4.java)

-   Gráficamente:

Previamente se nos pedia que eliminasemos el nodo que contenia la clave "www.espn.com, 134.24.13.78". Gráficamente tendríamos:

<div align="center">

![Ejecucion](Ejercicio%204/Imagenes/ResulrtadoPostEliminacionESPN.png)
</div>

-   Ahora podemos proceder a insertar el nodo con la clave requerida, para eso tenemos.

-   Paso 1

<div align="center">

![Ejecucion](Ejercicio%204/Imagenes/InsercionYoutubeP1.png)
</div>
Procedemos a buscar la ubicación correcta para esta clave. Esta se encuentra en la parte final del arbol.procedemos a agregar el nodo, quedando con 4 nodos, lo que significa unas modificaciones más...

-   Paso 2

<div align="center">

![Ejecucion](Ejercicio%204/Imagenes/InsercionYoutubeP2.png)
</div>

Procedemos a reubicar uno de los nodos excedentes, en este caso el de la clave de "yahoo", sin embargo en su reubicación aun hay un desajuste que debemos corregir.

-   Paso 3
<div align="center">

![Ejecucion](Ejercicio%204/Imagenes/InsercionYoutubeP3.png)
</div>

Hacemos una última rehubicación y logramos insertar correctamente la clave solicitada.

#
<div align="center">
    <span style="font-weight:bold;"><h2>III. CONCLUSIONES </h2></span>
</div>

#

- Comprobamos de que el tratamiento de la información con un árbol Btree parece ser más eficientes en temas de velocidad a diferecnia de otras estructuras de datos.


#
<div align="center">
    <span style="font-weight:bold;"><h2>RETROALIMENTACIÓN </h2></span>
</div>

#

-   

#
<div align="center">
    <span style="font-weight:bold;"><h2>REFERENCIAS Y BIBLIOGRAFÍA </h2></span>
</div>

#

-   https://www.w3schools.com/java/
-   https://www.eclipse.org/downloads/packages/release/2022-03/r/eclipse-ide-enterprise-java-and-web-developers
-   https://cmps-people.ok.ubc.ca/ylucet/DS/BTree.html 
