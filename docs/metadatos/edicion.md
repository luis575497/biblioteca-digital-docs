Elemento Dublin Core: `dc:relation.isVersionOf`  
<span style="color:#CD113B">Recursos a los que se aplica: __Libros__ </span>

### __Definición__
Referencia a la edición del recurso que se describe.  

### __Uso__
Opcional y no repetible  

### __Instrucciones__  
1. Escribir la versión de con valores no literales.
2. Para las reimpresiones utilizar el siguiente formato: `edición / reimpresión`
3. Se toma en cuenta la primera edición

### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc:relation.isVersionOf>` Primera edición `</dc:relation.isVersionOf>`  
    `<dc:relation.isVersionOf>` Segunda edición / tercera reimpresión `</dc:relation.isVersionOf>`


!!! error "Uso Incorrecto"
    **Se utilizan literales**  
    `<dc:relation.isVersionOf>` 2da `</dc:relation.isVersionOf>`   
    `<dc:relation.isVersionOf>` 4 `</dc:relation.isVersionOf>`   
    **Se utilizan abreviaturas**  
    `<dc:relation.isVersionOf>`Primera ed. / segunda reimpr. `</dc:relation.isVersionOf>`   
