#Fecha de Modificación
Elemento Dublin Core: `dc:date.modified`  
<span style="color:#CD113B">Recursos a los que se aplica: __Libros, revistas y tesis__ </span>

### __Definición__
Fecha en la que se cambió el recurso.

### __Uso__
Obligatorio cuando aplica y repetible  

### __Instrucciones__  
1. Codificar el valor de la fecha en según lo establecido en la norma ISO-8601 `YYYY-MM-DD`. 
2. Utilizar el formato completo con año, mes y día.
3. Se considera una modificación cuando cuando el documento (pdf,docx,jpg) es modificado y se sustituye el mismo por uno nuevo.  

### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc:date.modified>`2010-05-14`</dc:date.modified>`  
    `<dc:date.modified>`2020-08-04`</dc:date.modified>`


!!! error "Uso Incorrecto"
    **Formato Incorrecto**  
    `<dc:date.modified>` 03-12-2011 `</dc:date.modified>`   
    `<dc:date.modified>` 2002 `</dc:date.modified>`   
