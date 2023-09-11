# Dashboard Comercial - EXCEL
<p>Base de datos con más de 3000 líneas con las siguientes columnas: fechas,vendedor, región, producto, valor y tipo de pago </p>

![Alt text](/02.Dashboards/img/dashboard.png)

## 1. Formatación de Base de datos:

* Tamaño de los campos
* Valores: fecha y valor
* Alinear todos los campos a la izquierda.
* Crear nuevas columnas: més y año
```
ctrl + 'space' -> sellecciona toda la columna
ctrl + '+' -> añade nueva columna a la izquierda de la seleccionada

Año fórmula: 
=YEAR(A2)

Més Fórmula:
=TEXT(A2,"mmm")
```
<p> <b>Importante:</b> </p>

* Table - formatear como tabla única para hacer tablas dinamicas
* Tabela dinámica : inserir Table dinamica

## 2. Formatación de Tabla dinámica:

<p> Para ayustar las medidas de las columnas en la tabla dinamica, con el botón derecho del ratón sobre la tabla, quitar la opción de autofit column.

![Alt text](/02.Dashboards/img/dynamicformat.png)

## 3. Facturación por més:
![Alt text](/02.Dashboards/img/factmes.png)

## 4. Facturación por región:
<p> Copia y pega la tabla de facturación por més y crea a la de región.</p>
<p> Solo tendría que cambiar el campo més por región. </p>
<p> De esta manera, los filtros de segmentación, funcionará para las dos tablas </p>

![Alt text](/02.Dashboards/img/factregion.png)

## 4. Facturación por vendedor:
<p> Copia y pega la tabla de facturación por región y crea a la de vendedores.</p>
<p> Se puede dar nombres a tablas: analise vendedor </p>

![Alt text](/02.Dashboards/img/factvendedor.png)

## 5. Preparar dashboard:

1. Insertar forma rectangular (100%) y ocupar todo el espacio (ctrl * F1) y quitar grid, Formula Bar y Heading
![Alt text](/02.Dashboards/img/formatbar.png)




### Referencias:
* https://www.youtube.com/watch?v=SQeiimHmYcU
* https://thenounproject.com/