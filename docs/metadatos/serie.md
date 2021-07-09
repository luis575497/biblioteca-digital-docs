#Serie o Colección
Elemento Dublin Core: `dc:relation.isPartOf`  
<span style="color:#3F72AF">Recursos a los que se aplica: __Libros, revistas y tesis__ </span>

### __Definición__
Un recurso relacionado en el que el recurso descrito se incluye física o lógicamente.  

### __Uso__
Obligatorio cuando se aplica y no es repetible  

### __Instrucciones__  
1. La relación de este campo es esencialmente jerárquica de padre / hijo.
2. Indicar si el recurso pertenece a una colección o serie.
3. La estructura sería la siguientes: Coleccion: Subcolección, No.  

!!! tip
    **Libros:** Indicar la colección a la que pertenece.  
    **Revistas:** Indicar el número o volumen de la revista.  
    **Tesis:**Indicar la signatura asignada a la tesis.  


### __Ejemplos__

!!! done "Uso Correcto:"  
    **Libros:**  
    `<dc:relation.isPartOf>` Economía: Desarrollo global, No. 2 `</dc:relation.isPartOf>`  
    `<dc:relation.isPartOf>` Libros para el pueblo `</dc:relation.isPartOf>`
    `<dc:relation.isPartOf>` Jurisprudencia, No. 10 `</dc:relation.isPartOf>`  
      
    **Revistas:**  
    `<dc:relation.isPartOf>` Volumen 7. Número 4`</dc:relation.isPartOf>`  
    `<dc:relation.isPartOf>` Número 27  `</dc:relation.isPartOf>`  
      
    **Tesis:**  
    `<dc:relation.isPartOf>` TGH 153  `</dc:relation.isPartOf>` 

!!! error "Uso Incorrecto"
    **Estrcutura incorrecta**  
    `<dc:relation.isPartOf>` Desarrollo global. No. 2 `</dc:relation.isPartOf>`  
    `<dc:relation.isPartOf>` ISBN-Coleccion Economía `</dc:relation.isPartOf>`  
