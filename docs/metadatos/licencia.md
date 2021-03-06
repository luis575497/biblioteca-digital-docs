#Condición de la licencia
Elemento Dublin Core: `dc:rights`  
<span style="color:#3F72AF">Recursos a los que se aplica: __Libros, revistas y tesis__ </span>

### __Definición__
Información acerca de los derechos contenidos en y sobre el recurso.

### __Uso__
Obligatorio y no repetible  

### __Instrucciones__  
1. Típicamente, un recurso contendrá una declaración de gestión de derechos para su acceso o uso, también se puede hacer referencia a un servicio que proporcione dicha información sobre los derechos que a menudo abarca los derechos de propiedad intelectual (DPI), el copyright y los derechos de propiedad diferentes. 
2. Se prefiere para referirse a un servicio de derechos donde se hacen claros los derechos de uso y reutilización para el usuario final mediante una URL. 
3. Utilizar las licenicas [Creative Commons](https://creativecommons.org/) para las obras que lo requieran y para las obras bajo derecho de autor utilizar las [declaraciones de derecho de autor](https://rightsstatements.org/).

### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc:rights>`https://creativecommons.org/licenses/by/4.0`</dc:rights>`  
    `<dc:rights>`http://rightsstatements.org/vocab/InC/1.0/`</dc:rights>`


!!! error "Uso Incorrecto"
    `<dc:rights>` BY-NC 3.0 `</dc:rights>`   
    `<dc:rights>` Creative Commons BY 4.0 `</dc:rights>`   
