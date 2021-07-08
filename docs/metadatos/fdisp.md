#Fecha de Disponibilidad
Elemento Dublin Core: `dc:date.available`  
<span style="color:#CD113B">Recursos a los que se aplica: __Libros, revistas y tesis__ </span>

### __Definición__
Fecha en que el recurso estuvo o estará disponible.

### __Uso__
Obligatorio cuando aplica y no repetible  

### __Instrucciones__  
1. Codificar el valor de la fecha en según lo establecido en la norma ISO-8601 `YYYY-MM-DD`. 
2. Utilizar el formato completo con año, mes y día.

### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc:date.available>`2010-05-14`</dc:date.available>`  
    `<dc:date.available>`2020-08-04`</dc:date.available>`


!!! error "Uso Incorrecto"
    **Formato Incorrecto**  
    `<dc:date.available>` 03-12-2011 `</dc:date.available>`   
    `<dc:date.available>` 2002 `</dc:date.available>`   
