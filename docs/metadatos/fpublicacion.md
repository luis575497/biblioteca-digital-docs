#Fecha de Publicación
Elemento Dublin Core: `dc:date.created`  
<span style="color:#CD113B">Recursos a los que se aplica: __Libros, revistas y tesis__ </span>

### __Definición__
Fecha de creación del recurso.

### __Uso__
Obligatorio y no repetible  

### __Instrucciones__  
1. Codificar el valor de la fecha en según lo establecido en la norma ISO-8601 `YYYY-MM-DD`. 
2. Si no hay fecha de publicación disponible se utilizará una aproximada

### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc:date.created>`2010-05-14`</dc:date.created>`  
    `<dc:date.created>`1990-08`</dc:date.created>`
    `<dc:date.created>`2015`</dc:date.created>`


!!! error "Uso Incorrecto"
    **Formato Incorrecto**  
    `<dc:date.created>` 03-12-2011 `</dc:date.created>`   
    `<dc:date.created>` 10-2002 `</dc:date.created>`   
