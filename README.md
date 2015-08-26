# it4biz-sales-dashboard
IT4biz Sales Dashboard


## MDX Example with filter

WITH
SET [~FILTER] AS
    {${filter_productParameter}}
SET [~ROWS] AS
    {[Clientes.Cliente].[Nome do Cliente].Members}
SELECT
NON EMPTY {[Measures].[Valor]} ON COLUMNS,
NON EMPTY [~ROWS] ON ROWS
FROM [Vendas com o PSW]
WHERE [~FILTER]

##Tools for Dashboards Mockups

Desktop
http://pencil.evolus.vn/

Web
https://www.gliffy.com/

https://wrapbootstrap.com/

Learn how to create these 11 amazing dashboards
http://chandoo.org/wp/excel-dashboards/
http://chandoo.org/wp/2014/02/14/dashboard-training-course/

JSON Formatter
https://jsonformatter.curiousconcept.com/

JSON Viewer
http://codebeautify.org/jsonviewer


