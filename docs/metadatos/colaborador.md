Elemento Dublin Core: `dc:contributor`  
<span style="color:#CD113B">Recursos a los que se aplica: __Libros, revistas y tesis__ </span>  

### __Definición__
Institución o persona responsable de recolectar, administrar, distribuir o contribuir de alguna otra manera al desarrollo del recurso.

### __Uso__
Obligatorio cuando aplica y repetible  

### __Instrucciones__
1. Para el caso de nombres personales utilizar el formato “Apellido (s), Nombre(s)”.
2. Para el nombre de un organismo, entidad o dependencia se deberá respetar la estructura organizacional ingresando esta información de menor a mayor jerarquía, separadas por una coma.
3. Se recomienda no utilizar abreviaturas, acrónimos o siglas, a menos que sean necesarias como parte lógica del colaborador
4. Se recomienda el uso adecuado de mayúsculas y minúsculas,
5. Usualmente, un colaborador puede confundirse con una editorial o el nombre de alguna dependencia de donde provenga el recurso.
6. Se utilizará la forma normalizada del autor según el Catálogo Internacional de Autoridades (VIAF).
7. Si existe duda, es necesario recordar que un colaborador contribuye al contenido del recurso, no al proceso para hacer disponible este

 !!! info "Colaboradores en las tesis"
    Para las tesis se considera como colaborador al director o tutor de la tesis

### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc:contributor>` Di Pierro, Maria Clara `</dc:contributor>`    

    `<dc:contributor>`Consejo Nacional de Investigaciones Científicas y  Técnicas. Complejo Astronómico “El Leoncito”`</dc:contributor>`  

    `<dc:contributor>`Argentina. Ministerio de Ciencia, Tecnología e  Innovación productiva.`</dc:contributor>`  


!!! error "Uso Incorrecto"
    **Orden Incorrecto**:  
    `<dc:contributor>` Andrés Felipe Marmolejo `</dc:contributor>`  

    **Uso de grado académico `:`**:  
        `<dc:contributor>` Dr. Sorensen Michael, James  `</dc:contributor>`

