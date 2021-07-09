#Materia
Elemento Dublin Core: `dc:subject`  
<span style="color:#3F72AF">Recursos a los que se aplica: __Libros, revistas y tesis__ </span>

### __Definición__
La  temática  del  recurso se  expresa  típicamente  en  palabras clave,  descriptores  y/o  códigos  de  clasificación  que  describen  el contenido intelectual del recurso. 

### __Uso__
Obligatorio cuando se aplica y repetible  

### __Instrucciones__
1. Deben consignarse tantas ocurrencias del elemento, como descriptores sea necesario asignar.
2. Los términos se consignan como aparecen en los tesauros.  
3. Para nombres personales utilizar el formato invertido de tal forma que la sintaxis sea: “Apellido (s)” + “, “+ “Nombre (s)”.   
4. Si la materia del recurso es una persona o una organización, registrar la misma siguiendo las normas establecidas por las reglas RCAA2r.  
5. Se usará los siguiente vocabularios controlados:
    - [Tesauro de la Unesco](http://vocabularies.unesco.org/browser/thesaurus/es/) 
    - [Tesauro DeCS](https://decs.bvsalud.org/E/homepagee.htm)

  
### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc:subject>` Anatomía `</dc:subject>`
    `<dc:subject>` Desarrollo económico y social `</dc:subject>`
    

!!! error "Uso Incorrecto"
    **Todo en mayúsculas**:  
    `<dc:subject>` CARDIOLOGÍA `</dc:subject>`

    **Uso de término no preferido del tesauro :**    
    `<dc:subject>` Auto `</dc:subject>`  
    Utilizar `Vehículo automotor` que es el término preferido por el [Tesauro de la Unesco](http://vocabularies.unesco.org/browser/thesaurus/es/).

