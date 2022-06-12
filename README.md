<div align="center">
<table>
    <theader>
        <tr>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/epis.png?raw=true" alt="EPIS" style="width:50%; height:auto"/></td>
            <th>
                <span style="font-weight:bold;">UNIVERSIDAD NACIONAL DE SAN AGUSTIN</span><br />
                <span style="font-weight:bold;">FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS</span><br />
                <span style="font-weight:bold;">DEPARTAMENTO ACADÉMICO DE INGENIERÍA DE SISTEMAS E INFORMÁTICA</span><br />
                <span style="font-weight:bold;">ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMAS</span>
            </th>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/abet.png?raw=true" alt="ABET" style="width:50%; height:auto"/></td>
        </tr>
    </theader>
    <tbody>
        <tr><td colspan="3"><span style="font-weight:bold;">Formato</span>: Guía de Práctica de Laboratorio</td></tr>
        <tr><td><span style="font-weight:bold;">Aprobación</span>:  2022/03/01</td><td><span style="font-weight:bold;">Código</span>: GUIA-PRLD-001</td><td><span style="font-weight:bold;">Página</span>: 1</td></tr>
    </tbody>
</table>
</div>

<div align="center">
<span style="font-weight:bold;">GUÍA DE LABORATORIO</span><br />
</div>


<table>
<theader>
<tr><th colspan="6">INFORMACIÓN BÁSICA</th></tr>
</theader>
<tbody>
<tr><td>ASIGNATURA:</td><td colspan="5">Programación Web 2</td></tr>
<tr><td>TÍTULO DE LA PRÁCTICA:</td><td colspan="5">Python</td></tr>
<tr>
<td>NÚMERO DE PRÁCTICA:</td><td>05</td><td>AÑO LECTIVO:</td><td>2022 A</td><td>NRO. SEMESTRE:</td><td>III</td>
</tr>
<tr>
<td>FECHA INICIO::</td><td>05-Jun-2022</td><td>FECHA FIN:</td><td>12-Jun-2022</td><td>DURACIÓN:</td><td>04 horas</td>
</tr>
<tr>
<td>INTEGRANTES::</td><td>
<ul>
<li>Suasaca Pacompia Alvaro Gustavo</li>

</ul>
<td>NOTA</td><td></td><td></td><td></td>
</td>
</tr>
<tr><td colspan="6">RECURSOS:
    <ul>
        <li>https://www.w3schools.com/python/python_reference.asp</li>
        <li>https://docs.python.org/3/tutorial/</li>
    </ul>
</td>
</<tr>
<tr><td colspan="6">DOCENTES:
<ul>
<li>Richart Smith Escobedo Quispe - rescobedoq@unsa.edu.pe</li>
</ul>
</td>
</<tr>
</tdbody>
</table>



## EJERCICIOS PROPUESTOS
-   Crea un blog sencillo en un entorno virtual utilizando la guía: https://tutorial.djangogirls.org/es/django_start_project/
-   Especificar paso a paso la creación del blog en su informe.
-   Crear un video tutorial donde realice las operaciones CRUD (URL public reproducible online)
-   Adjuntar URL del video en el informe.
#

## CUESTIONARIO
-   ¿Cuál es un estándar de codificación para Python? Ejemplo:

    https://legacy.python.org/dev/peps/pep-0008/
    PEP8Es una guía de estilo de código compilada por la comunidad de Python para el lenguaje Python. La unificación del estilo de codificación 
    mejora la legibilidad del código y reduce el costo del desarrollo del equipo.
    - 1 Convención de nomenclatura:
        
        En PEP8, la denominación de variables debe ser significativa, evitar nombres de variables sin sentido y evitar usar l (L minúscula), 
        I (i mayúscula) y O (fácil de confundir) como variables de un solo carácter. Las convenciones de nomenclatura para paquetes, clases, 
        funciones y variables globales son las siguientes:
        Las variables, funciones, paquetes y módulos llevan el nombre delower_with_under(Minúsculas y subrayado), como model_test
        Las clases y excepciones llevan el nombre deCapWords(Caso camel, primera letra en mayúscula) formulario, como ModelTest
        Los parámetros de la función llevan el nombrelower_with_underForma (minúsculas y subrayado), como def test (a, b, c)
        
    - 2 Diseño de código:
        
        En el proceso de escribir Python, se usa cada nivel de sangría4 espacios , Evitar el uso deTab Sangría (diferentes editores tienen 
        diferentes anchos de tabulación), no para mezclar Tab y espacios
        1) Al construir listas, diccionarios, tuplas y asignaciones de hiperparámetros, se deben agregar espacios al final de las comas, punto
           y coma y dos puntos, y no se deben agregar espacios al principio
        2) Sin espacio antes del paréntesis izquierdo de la lista de parámetros, índice y sector
        3) Agregue espacios a ambos lados de los operadores binarios (asignación, marioneta, comparación y aritmética)
        4) Cuando se utilizan símbolos de asignación para parámetros o valores de parámetros predeterminados, no utilice espacios en ambos lados
        5) No utilice espacios para alinear verticalmente marcas de varias líneas, lo que aumentará la carga de mantenimiento
    - 3 Estilo de importación
        
        El módulo importado debe estar en la parte superior del archivo, después del comentario del módulo y la cadena de documentos, y antes de la 
        variable o constante global. El orden de importación debe ordenarse de acuerdo con la generalidad del paquete de la biblioteca.
        1) Importación de biblioteca estándar
        2) Importación de biblioteca de terceros
        3) Importación de la biblioteca de aplicaciones locales
    - 4 Comentarios:
        
        1) comentario de línea
        Agregue un comentario después de una oración de código, pero si el significado del código es obvio, no se requieren comentarios en línea. Los 
        comentarios en línea deben estar separados por al menos dos espacios y códigos.
        2) Bloquear comentario
        Comentarios agregados antes del código, cada línea en el bloque de comentarios comienza con # y un espacio, y el bloque de comentarios debe estar 
        en blanco por 1 línea.
    - 5 Cadena de documentación
        
        La cadena de documentos sirve para anotar módulos, funciones y clases. Cuando se anotan funciones / clases, la primera línea de la clase y función 
        se describe generalmente usando caracteres de documento. Después de ser descrita, puede ser extraída por doc. Para mantener la coherencia, utilice 
        tres pares de comillas dobles antes y después de la cadena de documentos, consulte la confirmación correspondientePEP 257. La siguiente es la función 
        y la descripción de los parámetros de la función.
    - 6 Sugerencias de codificación:
        
        Evite el uso de operadores + o + = para acumular cadenas. Puede agregar cada cadena a la lista y, finalmente, unirse a la lista a través de join; use 
        "es" o "es tanto como sea posible
        not ”reemplaza“ == ”, por ejemplo, si x no es None es mejor que si x
        No lo use desnudo excepto en excepciones, excepto en excepciones específicas seguidas de juicio de tipo, se prefiere isinstance ()
        La secuencia de juicio está vacía, use not first, por ejemplo, si not seq es mejor que si len (seq)
        
-   ¿Qué diferencias existen entre EasyInstall, pip, y PyPM?
    
    - Pip : es un gestor de paquetes y  es un contenedor para EasyInstall
    - EasyInstall : es una utilidad de instalacion basada en codigo fuente
    - PyPM : simplifica las tareas de localizacion, instalacion, actualizacion y eliminacion de paquetes de python
    
-   En un proyecto Django que se debe ignorar para usar git. Vea: https://github.com/django/django/blob/main/.gitignore. ¿Qué otros tipos de archivos se deberían
    agregar a este archivo?
    
    Observamos el contenido de .gitignore y algunos archivos extra que pueden entrar seria:
    - eggs
    - parts
    - bin
    - var
    - installed.cfg
    - .settings
    - .project
    - .mo
    - .tox
    - .covarege
    
-   Utilice ```python manage.py shell``` para agregar objetos. ¿Qué archivos se modificaron al agregar más objetos?
    Se observo que los cambios que se hicieron fueron en db.sqlite3

## REFERENCIAS
-   https://www.w3schools.com/python/python_reference.asp
-   https://docs.python.org/3/tutorial/
-   https://developer.mozilla.org/es/docs/Learn/Server-side/Django/Models
-   https://tutorial.djangogirls.org/es/django_models/
-   https://pear.php.net/manual/en/standards.php
-   https://docs.djangoproject.com/en/4.0/
-   https://www.youtube.com/watch?v=M4NIs4BM1dk
-   https://pypi.org/
-   https://pip.pypa.io/en/latest/user_guide/
-   https://packaging.python.org/en/latest/tutorials/installing-packages/

