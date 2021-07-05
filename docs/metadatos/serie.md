Elemento Dublin Core: `dc:relation.isPartOf`

### __Definición__
Un recurso relacionado en el que el recurso descrito se incluye física o lógicamente.  

### __Uso__
Obligatorio cuando se aplica y no es repetible  

### __Instrucciones__  
1. La relación de este campo es esencialmente jerárquica de padra / hijo.
2. Indicar si el libro pertenece a una colección o serie.
3. La estructura sería la siguientes: Coleccion: Subcolección, No.  

### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc:relation.isPartOf>` Economía: Desarrollo global, No. 2 `</dc:relation.isPartOf>`  
    `<dc:relation.isPartOf>` Libros para el pueblo `</dc:relation.isPartOf>`
    `<dc:relation.isPartOf>` Jurisprudencia, No. 10 `</dc:relation.isPartOf>`  


!!! error "Uso Incorrecto"
    **Estrcutura incorrecta**  
    `<dc:relation.isPartOf>` Desarrollo global. No. 2 `</dc:relation.isPartOf>`  
    `<dc:relation.isPartOf>` ISBN-Coleccion Economía `</dc:relation.isPartOf>`  
