Elemento Dublin Core: `dc:description.abstract`

### __Definición__
Este elemento se utiliza para una descripción textual del contenido. Cuando un recurso se compone de varios archivos de objetos físicos separados, no use dc:description para enumerar las direcciones URL de estos archivos. 

### __Uso__
Obligatorio cuando se aplica y repetible  

### __Instrucciones__  
1. La  descripción generalmente se remite a un resumen. 
2. También puede ser la tabla de contenido o sumario, referencias a representaciones gráficas del contenido o texto libre con información del contenido. 
3. Se consignará solamente para el resumen o tabal de contenidos en otros idiomas y para poder usarlo tendrá que estar presente el campo resumen. 
4. En caso de poner la tabla de contenido separar por “ -- ” cada parte.

### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc: description.abstract>` Foreword Hazel Anderson -- Introduction -- Scientific heresy: the transformation of a society -- Consciousness as a causal reality `</dc:description.abstract>` 
        
    `<dc: description.abstract>`A series of problems in the quantum state and identification of the directed system `</dc:description.abstract>`

!!! error "Uso Incorrecto"
    **No se realiza una descripción**:  
    `<dc:description.abstract>` WoS,SCI,SSCI,AHCI `</dc:description.abstract>`
