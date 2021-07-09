#Título Alternativo
Elemento Dublin Core: `dc:title.alternative`  
<span style="color:#3F72AF">Recursos a los que se aplica: __Libros, revistas y tesis__ </span>  

### __Definición__
Cualquier título utilizado como sustituto o alternativo al título oficial por el cual se conoce al recurso.  
!!! Tip "Aclaración"
    Se puede utilizar para traducciones de los títulos en otros idiomas o para abreviaturas del mismo.
      

### __Uso__
Recomendado y repetible  

### __Instrucciones__
1. Se utiliza para facilitar el acceso a títulos secundarios y solo se puede usar cuando el campo `dc:title` está presente 
2. Transcribir el título del original, en orden y ortografía del recurso. 
3. Utilizar mayúsculas únicamente para la primera palabra del título y los nombres propios. 
4. Los subtítulos deben   separarse del título mediante dos puntos, precedidos y seguidos por un espacio. 
5. Cuando el recurso tenga el título en más de un idioma, colocar cada título en instancias separadas del elemento. 

!!! error "Signos de puntuación"
    Los signos de puntuación que estén al inicio del título se deben **OMITIR**  (signos de pregunta, admiración, comillas, etc.)

### __Ejemplos__

!!! done "Título con subtítulo:"  
    `<dc:title.alternative>` Título principal: Subtítulo `</dc:title.alternative>`    


!!! error "Uso Incorrecto"
    **Todo el título en mayúsculas**:  
    `<dc:title>` LOGICAL AND MATHEMATICAL FUN `</dc:title>`  

    **Usar un separador entre título y subtitulo diferente a `:`**:  
    `<dc:title>` Logical and mathematical fun / an análisis `</dc:title>`

