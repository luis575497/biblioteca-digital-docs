## __Título Alternativo (R)__
Elemento Dublin Core: `dc:title.alternative`

### __Definición__
Otro nombre por el cual se conoce al recurso.  
!!! Tip "Aclaración"
    Se utiliza para traducciones y títulos en otros idiomas.
      

### __Uso__
Recomendado y repetible  

### __Instrucciones__
1. Transcribir el título del original, en orden y ortografía del recurso. 
2. Utilizar mayúsculas únicamente para la primera palabra del título y los nombres propios. 
3. Los subtítulos deben   separarse del título mediante dos puntos, precedidos y seguidos por un espacio. 
4. Cuando el recurso tenga el título en más de un idioma, colocar cada título en instancias separadas del elemento. 

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

