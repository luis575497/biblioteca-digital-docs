#Fecha de Aceptación
Elemento Dublin Core: `dc:date.dateAccepted`  
<span style="color:#3F72AF">Recursos a los que se aplica: __Tesis__ </span>

### __Definición__
Fecha de aceptación del recurso.

### __Uso__
Obligatorio cuando aplica y no repetible  

### __Instrucciones__  
1. Codificar el valor de la fecha en según lo establecido en la norma ISO-8601 `YYYY-MM-DD`. 
2. Utilizar el formato completo con año, mes y día.
3. Ejemplos de recursos para los que una fecha de aceptación puede ser relevante son una tesis (aceptada por un departamento universitario) o un artículo (aceptado por una revista).

### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc:date.dateAccepted>`2010-05-14`</dc:date.dateAccepted>`  
    `<dc:date.dateAccepted>`2020-08-04`</dc:date.dateAccepted>`


!!! error "Uso Incorrecto"
    **Formato Incorrecto**  
    `<dc:date.dateAccepted>` 03-12-2011 `</dc:date.dateAccepted>`   
    `<dc:date.dateAccepted>` 2002 `</dc:date.dateAccepted>`   
