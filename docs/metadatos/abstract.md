#Abstract
Elemento Dublin Core: `dc:description.abstract`  
<span style="color:#3F72AF">Recursos a los que se aplica: __Libros, revistas y tesis__ </span>

### __Definición__
Este elemento se utiliza para una descripción textual del contenido del recurso. 

### __Uso__
Obligatorio cuando se aplica y repetible  

### __Instrucciones__  
1. La  descripción generalmente se remite a un resumen. 
2. También se puede incluir la tabla de contenido o sumario, referencias a representaciones gráficas del contenido o texto libre con información del contenido. 
3. Se consignará solamente para el resumen o tabla de contenidos en otros idiomas y para poder usarlo tendrá que estar presente el campo resumen. 
4. En caso de poner la tabla de contenido separar por “ -- ” cada parte.

### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc: description.abstract>` Foreword Hazel Anderson -- Introduction -- Scientific heresy: the transformation of a society -- Consciousness as a causal reality `</dc:description.abstract>` 
        
    `<dc: description.abstract>`A series of problems in the quantum state and identification of the directed system `</dc:description.abstract>`

!!! error "Uso Incorrecto"
    **No se realiza una descripción**:  
    `<dc:description.abstract>` WoS,SCI,SSCI,AHCI `</dc:description.abstract>`
