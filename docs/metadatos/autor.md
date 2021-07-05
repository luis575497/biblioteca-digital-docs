Elemento Dublin Core: `dc:creator`

### __Definición__
Entidad  principal  responsable  del  contenido  del  recurso.  Puede designar a un autor personal, institucional o evento  (Conferencia, reunión, etc.).   En  caso  de  múltiples  responsables repetir tantas veces como sea necesario. 

### __Uso__
Obligatorio y repetible  

### __Instrucciones__
1. Para nombres personales utilizar el formato invertido de tal forma que la sintaxis sea: “Apellido (s)” + “, “+ “Nombre (s)”.   
2. En  el  caso  de  organizaciones  donde  exista  una  jerarquía  clara, enumerar   las   partes   de   la   jerarquía   de   mayor   a   menor   y separarlas con puntos seguidos de un espacio. Si no queda clara la existencia de una jerarquía, o si se desconoce cuál es la parte más  grande  y  más  pequeña  del  cuerpo,  facilitar  el  nombre  tal como aparece en la copia electrónica.   Cuando el recurso posea más de  un autor, colocar en instancias separadas del elemento.
3. En ningún caso las funciones deben ir agregadas a los Apellidos, Nombres (Dr. etc.)  
4. En  los  casos  de  menor  responsabilidad,  con  excepción  de  la autoría, se utilizará dc:contributor. 
5. Si la naturaleza de la responsabilidad es ambigua, las mejores prácticas recomendadas es utilizar dc:publisher para organizaciones
6. Se utilizará la forma normalizada del autor según el Catálogo Internacional de Autoridades (VIAF).
  
### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc:creator>` Di Pierro, Maria Clara `</dc:creator>`    

    `<dc:creator>`Consejo Nacional de Investigaciones Científicas y  Técnicas. Complejo Astronómico “El Leoncito”`</dc:creator>`  

    `<dc:creator>`Argentina. Ministerio de Ciencia, Tecnología e  Innovación productiva.`</dc:creator>`  


!!! error "Uso Incorrecto"
    **Orden Incorrecto**:  
    `<dc:creator>` Andrés Felipe Marmolejo `</dc:creator>`  

    **Uso de grado académico `:`**:  
    `<dc:creator>` Dr. Sorensen Michael, James  `</dc:creator>`

