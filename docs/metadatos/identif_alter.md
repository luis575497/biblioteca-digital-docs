#Identificador alternativo
Elemento Dublin Core: `dc:relation`  
<span style="color:#CD113B">Recursos a los que se aplica: __Libros, revistas y tesis__ </span>

### __Definición__
Identificadores alternativos que no son el identificador primario

### __Uso__
Recomendado y repetible  

### __Instrucciones__  
1. Los tipos de identificadores se definen por el vocabulario controlado `info:eurepo/semantics/altIdentifier`.
2. Seleccionar primeramente el tipo de identificador de la lista controdala y posteriormente asignar el valor.
3. Este identificador sirve para identificar al recurso digital no para identificar autores o colaboradores.

### __Vocabulario Controlado__
|URI| Nombre |
|---|--------|
|info:eurepo/semantics/altIdentifier/ark/   | [ARK](https://arks.org) |
|info:eurepo/semantics/altIdentifier/arxiv/ | [Arxiv](https://arxiv.org/help/arxiv_identifier) |
|info:eurepo/semantics/altIdentifier/doi/   | [DOI](https://www.doi.org/) |
|info:eurepo/semantics/altIdentifier/hdl/   | [Handle](https://en.wikipedia.org/wiki/Handle_System) |
|info:eurepo/semantics/altIdentifier/isbn/  | ISBN  |
|info:eurepo/semantics/altIdentifier/pissn/ | ISSN (print) |
|info:eurepo/semantics/altIdentifier/eissn/ | ISSN (electronic) |
|info:eurepo/semantics/altIdentifier/pmid/  | [PMID](https://www.bvsspa.es/profesionales/node/358) |

### __Ejemplos__

!!! done "Uso Correcto:"  
    `<dc:relation>`info:eurepo/semantics/altIdentifier/hdl/14873/2131  `</dc:relation>`  
    `<dc:relation>`info:eurepo/semantics/altIdentifier/pissn/1390-0862  `</dc:relation>`


!!! error "Uso Incorrecto"
    **No se usa un identificador persistenete del vocabulario controlado**   
    `<dc:relation>`http://www.youtube.com/hsgb5/asdo `</dc:relation>`   
