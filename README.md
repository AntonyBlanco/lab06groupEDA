# lab06groupEDA
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
    <span style="font-weight:bold;"><h2>INFORME DE LABORATORIO</h2></span>
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
        <td>TÍTULO DE LA PRÁCTICA:</td><td colspan="5">Árboles</td>
    </tr>
    <tr>
        <td>NÚMERO DE PRÁCTICA:</td><td>05</td><td>AÑO LECTIVO:</td><td>2022 A</td><td>NRO. SEMESTRE:</td><td>III</td>
    </tr>
    <tr>
        <td colspan="2">FECHA DE PRESENTACIÓN:</td><td>28-Jun-2022</td><td colspan="2">HORA DE PRESENTACIÓN:</td><td>11:55</td>
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
</tdbody>
</table>

<table>
    <theader>
        <tr>
            <th style="text-align:center">SOLUCIÓN Y RESULTADOS</th>
        </tr>
    </theader>
    <tbody>
        <tr>
            <td>
            I. SOLUCIÓN DE EJERCICIOS/PROBLEMAS<br>
                <ul>
                    <li>3. El método toString() del árbol, retorna lo siguiente. ¿Por qué están entre paréntesis
ciertas claves? (4 puntos)
                        <pre>
        www.amazon.com 207.171.182.16
        www.apple.com 17.112.152.32
        www.cnn.com 64.236.16.20
    (www.cs.princeton.edu)
        www.cs.princeton.edu 128.112.136.12
        www.cs.princeton.edu 128.112.136.11
        www.dell.com 143.166.224.230
    (www.ebay.com)
        www.ebay.com 66.135.192.87
        www.espn.com 199.181.135.201
        www.google.com 216.239.41.99
    (www.microsoft.com)
        www.microsoft.com 207.126.99.140
        www.nytimes.com 199.239.136.200
    (www.princeton.edu)
        www.princeton.edu 128.112.128.15
        www.simpsons.com 209.052.165.60
    (www.slashdot.org)
        www.slashdot.org 66.35.250.151
        www.weather.com 63.111.66.11
    (www.yahoo.com)
        www.yahoo.com 216.109.118.65
        www.yale.edu 130.132.143.21
                        </pre>
                        Los parentesis aparecen por que son la representadción del primer elemento "Entry" de los respectivos nodos "Node" que no sean la raíz
                        Esto puede observarse en la linea 217 donde encontramos los paréntesis:
                        <pre>
if (j > 0) 
    s.append(indent + "(" + children[j].key + ")\n");
                        </pre>
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>
            III. CONCLUSIONES<br>
                <ul>
                    <li>Colocar conclusiones</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

<table>
    <theader>
        <tr>
            <th style="text-align:center">RETROALIMENTACIÓN GENERAL</th>
        </tr>
    </theader>
    <tbody>
        <tr>
            <td>
            </td>
        </tr>
    </tbody>
</table>

<table>
    <theader>
        <tr>
            <th style="text-align:center">REFERENCIAS Y BIBLIOGRAFÍA</th>
        </tr>
    </theader>
    <tbody>
        <tr>
            <td>
                <ul>
                    <li>Lista</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
