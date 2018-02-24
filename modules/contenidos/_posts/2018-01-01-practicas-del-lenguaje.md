---
title: Prácticas del Lenguaje
published: false
---

## Prueba de tabla mejorada

{% for contenidos in site.data.contenidos %}
|{{contenidos.proyecto}}|
{% endfor %}
### viendo liquid
<table>
  {% tablerow contenidos in site.data.contenidos  %}
    {{ contenidos.mes }}
  {% endtablerow %}
  {% tablerow contenidos in site.data.contenidos  %}
    <td rowspan="{{contenidos.duracion}}">{{contenidos.proyecto}}</td> 
  {% endtablerow %}

</table>


## Distribución de contenidos

{% for contenidos in site.data.contenidos %}
<table>
<tr>
<th colspan="7" align="center"> Primer Cuatrimestre 2018</th>
</tr>

<tr>
  <th rowspan="7"> Modalidades Organizativas</th>
  <th rowspan="4" valign="bottom">Situaciones habituales</th>
  <th>Marzo</th>
  <th>Abril</th>
  <th>Mayo</th>
  <th>Junio</th>
  <th>Julio</th>
</tr>

<tr>
<td rowspan="3" colspan="5">Portfolio de producciones del año <br/> {{ contenidos.proyecto }} <br/> Asamblea de grado<br/> Biblioteca institucional</td>
</tr>

<tr>
</tr>

<tr>
</tr>

<tr>
  <th rowspan="3"> Secuencias y Proyectos</th>
  <td colspan="2">Antología de cuentos</td>
    <td></td>
    <td colspan="2">Lectura de novela por episodios</td>
</tr>

<tr>
  <td border="0"></td>
  <td colspan="2">Leer y escribir para estudiar</td>
  <td colspan="2"></td>
</tr>

<tr>
  <td colspan="2"></td>
  <td colspan="3">Leer en medios digitales</td>
</tr>
</table>

<table>
<tr>
<th colspan="7" align="center"> Segundo Cuatrimestre 2017</th>
</tr>
<tr>
  <th rowspan="7"> Modalidades Organizativas</th>
  <th rowspan="4" valign="bottom">Situaciones habituales</th>
  <th>Agosto</th>
  <th>Septiembre</th>
  <th>Octubre</th>
  <th>Noviembre</th>
  <th>Diciembre</th>
</tr>
<tr>

<td rowspan="3" colspan="5">Portfolio de producciones del año <br/> Biblioteca del aula <br/> Asamblea de grado <br/> Biblioteca institucional</td>

</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
  <th rowspan="3"> Secuencias y Proyectos</th>
  <td colspan="3">Seguir un autor</td>
    <td></td>
  <td></td>
</tr>

<tr>
  <td border="0"></td>
  <td colspan="2">Leer y escribir para estudiar</td>
  <td colspan="2"></td>
</tr>

<tr>
  <td colspan="2"></td>
  <td colspan="3">Leer en medios digitales</td>
</tr>
</table>
{% endfor %}

{{page.situaciones-habituales}}
{{page.situaciones-habituales[3]}}
{{site.data.contenidos.sh[2]}}


{% for contenidos in site.data.contenidos %}
{{ contenidos.proyecto }}
{% endfor %}
