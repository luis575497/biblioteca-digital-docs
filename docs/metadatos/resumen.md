Elemento Dublin Core: `dc:description`

### __Definición__
Este elemento se utiliza para una descripción textual del contenido. Cuando un recurso se compone de varios archivos de objetos físicos separados, no use dc:description para enumerar las direcciones URL de estos archivos. 

### __Uso__
Obligatorio cuando se aplica y repetible  

### __Instrucciones__  
1. La  descripción generalmente se remite a un resumen. 
2. También puede ser la tabla de contenido o sumario, referencias a representaciones gráficas del contenido o texto libre con información del contenido. 
3. Se escribirá preferentemente el idioma de la obra. 
4. En caso de poner la tabla de contenido separar por “ -- ” cada parte.

### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc:description>` rólogo Hazel Anderson -- Introducción -- La herejía científica:  la transformación  de  una  sociedad --  La  conciencia  como  realidad causa `</dc:description>`   
      
    `<dc:description>`Una serie de problemas en el estado cuántico e identificación del sistema dirigido `</dc:description>`

!!! error "Uso Incorrecto"
    **No se realiza una descripción**:  
    `<dc:description>` WoS,SCI,SSCI,AHCI `</dc:description>`
