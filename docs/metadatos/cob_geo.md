#Cobertura geográfica
Elemento Dublin Core: `dc:coverage.spatial`  
<span style="color:#3F72AF">Recursos a los que se aplica: __Libros, revistas y tesis__ </span>

### __Definición__
Extensión o alcance del contenido del recurso en un marco geográfico. 

### __Uso__
Recomendado y repetible  

### __Instrucciones__  
1. Emplear este elemento en caso de el recurso especificar de manera clara la covertura temporal
2. Se empleará el vocabulario controlado [“Getty Thesaurus of Geographic Names”](http://www.getty.edu/research/tools/vocabularies/tgn/)
3. Se consideraran como coberturas geográficas un nombre definido por un diccionario geográfico o coordenadas de un punto

### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc:coverage.spatial>` Cuenca `</dc:coverage.spatial>`  
    `<dc:coverage.spatial>` Ecuador `</dc:coverage.spatial>`  

!!! error "Uso Incorrecto"
    **Nombre no preferido por el tesauro**  
    `<dc:coverage.spatial>` Cantón Cuenca `</dc:coverage.spatial>`  
    `<dc:coverage.spatial>` Provincia Azuay `</dc:coverage.spatial>`  
