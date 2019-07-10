Power BI

1. Primeros Pasos

   Instalación de Power BI:

   ​	En caso de no tenerlo se puede descargar de la ruta: https://powerbi.microsoft.com/es-es/desktop

2. Interfaz Grafica y componentes

   ![UI](Images\UI.PNG)

Editor de Power Query:

![](Images\PowerQueryEditor.PNG)



1. Visualizaciones: 

   Fuente de Datos: 

   [P1-OfficeSupplies.csv](Datos\P1-OfficeSupplies.csv)

   Actividades:

   - Mostrar tablas Regiones por Unidades y cambiar rapidamente por grafico de barras y a pie chart y luego a bubble chart del MarketPlace y luego al tree Map


- Stacked Chart 
Crear Stacked Chart de OrdesDate(Axis) vs Region (Legends) y Units(Values)

- Bar chart
Crear Bar chart con REP(Axis) y Units(Value) - Add Region
Explicar la acciones del drill down 
Crear nueva columna: TotalSales = 'P1-OfficeSupplies'[Units]* 'P1-OfficeSupplies'[Unit Price]
Change color - Transparencia a traves del color.
Multiples colores por Legenda(Rep)
Cambiar colores de acuerdo al Theme
Color dependiente de la nueva columna Rojo a Verde (Conditional formatting)
Cambiar valor dependiente de Region
Adicionar Labels o Etiquetas para el campo Valor (Data Labels) y cambiar a tipo moneda.
Modificar estilos de X-axis y Y-axis


Time Series: P1-Long-Term-Unemployment-Statistics.xlsx

Importar los datos. Explicar los pasos que automaticamente hace Power BI.

- Line Chart
Crear grafico de lineas para series de tiempo Unemployment por Periodo 
Visualizar por Año, Mes, Año - Mes unidos - Diferenciar Jerarquias de Periodo
Visualizar en Area Chart
Adicionar Gender para tener dos lineas comparativas
Cambiar el estilo de los Shapes (Lineas) y Markers
Agregar o cambiar a Age
Cambiar SUM por AVG en los values (Unemployed)
Crear Stacked area con Periodo y Age y mirar Legendas

Filtros
- A nivel Visual
- A nivel Pagina
- A nivel reporte
- Basicos y avanzados
Filtro por Age y filtro visible (List, Dropdown, Search)
Filtro por Age y Filtro Herarquico (HierarchySlicer)
Filtros por interacción

- Mapas: P1-SuperStoreUS-2015.xlsx
Fill Map con la BD de Ordenes - Country + State of Province Con Conditional formatting File: P1-SuperStoreUS-2015.xlsx
Navegar por Power BI. Mostrar fuentes de datos, Paginas, Campos (Dimensiones: Independientes y Measures:Dependientes), Visualizaciones, Guardar archivo, Menú, 

- Joins: AmazingMartEU2.xlsx
Relaciones en P1-AmazingMartEU2.xlsx entre: ListOfOrders y OrderBreakdown

Jerarquias: Geography: Countr + State + City
Pintar en el mapa.
Crear una nuevo dato calculado (Measure): Profit Margin = Sum(OrderBreakdown[Profit])/ sum(OrderBreakdown[Sales]) 
Data Color dependiente del Profit Margin
- Scatterplots: 
Profit vs Sales y por Customer Name - Filtro en Report 
Modificar Scatterplots y añadir linea analitica y datos en rojo y verde por encima y debajo de cero. 



- Calculos y Medidas

- Preparación avanzada
- Otras Visualizaciones
- Proceso Banco


Exportar
- PDF
- csv
- Excel
- Power Point
- Recortes

Publicar 
- Archivo
- Nube
- Reporting
- Dashboard y reportes

![Captura](Images\Captura.PNG) 



asdasdasd

![1562724162793](D:\Github\PowerBI\Images\Captura3.PNG)



asdasdasd

asdasd







