#Publicaciones relacionadas
Elemento Dublin Core: `dc:relation`  
<span style="color:#3F72AF">Recursos a los que se aplica: __Libros, revistas y tesis__ </span>

### __Definición__
Referencia a un recurso relacionado.  

### __Uso__
Opcional y repetible  

### __Instrucciones__  
1. Este metadato proporciona información sobre las relaciones del recurso que se describe con otros, por ejemplo, una relación cronológica, la relación del mismo recurso en otro formato u otros idiomas, pero con el mismo contenido intelectual, etcétera.
2. Puede duplicar el campo para ingresar múltiples relaciones.
3. Utilizar identificadores únicos preferiblemente.
4. Es recomendable utilizar el estilo APA para agregar los datos bibliográficos del recurso relacionado.
5. No confundir con el metadato `<dc:source>`

### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc:relation>` http://hdl.handle.net/1012/237/12 `</dc:relation>`  
    `<dc:relation>` Watty, J. M. (2014). La eficacia versus la emancipación del sujeto. Panamá: Dynkinson `</dc:relation>`


!!! error "Uso Incorrecto"
    **No se escribe la referencia en formato APA o no se usa un identificador persistente**  
    
    `<dc:relation>`juan.perez@ucuenca.edu.ec `</dc:relation>`   
    `<dc:relation>`pdf `</dc:relation>`   
    `<dc:relation>`Acrobe Adobat `</dc:relation>`   
