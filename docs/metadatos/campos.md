# Descripción General 
Esta sección describe cada uno de los metadatos que deben ser considerados para el registro de recursos de información en la Biblioteca Digital de la Universidad de Cuenca.  
En cada campo se especifíca a que tipos de recursos puede aplicarse.

### Nivel de obligatoriedad para cada propiedad:  
    
__Obligatorio (M)__:   
La propiedad siempre debe estar presente en los metadatos. No se permite un valor vacío en esta propiedad  

__Obligatorio cuando se aplica (MA)__:  
Cuando se puede obtener el valor de la propiedad, debe estar presente en los metadatos.  

__Recomendado (R)__:  
Se recomienda el uso de la propiedad.  

__Opcional (O)__:  
 No es importante si la propiedad se usa o no, pero si se usa puede proporcionar información complementaria sobre el recurso.  
  
  

|  ID |             Campo         | Repetible | Uso |   Vocabulario                    |
| --- | ------------------------- | --------- | --- | -------------------------------- |
|1    | [Título](titulo.md)                     | No        | M   |                                  | 
|2    | [Título alternativo](tit_alter.md)      | Si        | R  |                                  | 
|3    | [Autor](autor.md)                       | Si        | M   |       [VIAF](http://viaf.org/)   | 
|4    | [Materia](materia.md)                   | Si        | MA  | [Tesauro Unesco](http://vocabularies.unesco.org/browser/thesaurus/es/)                   | 
|5    | [Palabras Clave](pclave.md)             | Si        | MA  |                                  | 
|6    | [Resumen](resumen.md)                   | No        | MA  |                                  | 
|7    | [Abstract](abstract.md)                 | No        | MA  |                                  | 
|8    | [Fuente](fuente.md)                     | Si        | R   |                                  | 
|9    | [Tipo de Publicación](tipo_pub.md)      | No        | M   | info:eu-repo/semantic            | 
|10   | [Publicaciones relacionadas](pub_rel.md)| Si        | O   |                                  | 
|11   | [Serie o Colección](serie.md)           | No        | MA  |                                  | 
|12   | [Edición](edicion.md)                   | No        | MA  |                                  | 
|13   | [Cobertura Temporal](cob_temp.md)       | Si        | R   |                                  | 
|14   | [Cobertura geográfica](cob_geo.md)      | Si        | R   | [Tesauro del Gettys](https://www.getty.edu/research/tools/vocabularies/tgn/)               | 
|15   | [Colaborador](colaborador.md)           | Si        | MA  |      [VIAF](http://viaf.org/)    | 
|16   | [Identificador](identif.md)             | No        | M   |                                  | 
|17   | [Identificador alternativo](identif_alter.md) | Si        | R   | info:eu-repo/semantics/altidentifier             | 
|18   | [Editorial](editorial.md)               | Si        | MA  |                                  | 
|19   | [Nivel de Acceso](acceso.md)            | No        | M   |                                  | 
|20   | [Condición de la licencia](licencia.md) | No        | M   | [Copyright](https://rightsstatements.org/),  Creative Commons   | 
|21   | [Fecha de Publicación](fpublicacion.md) | No        | M   |        ISO 8601                  | 
|22   | [Fecha de Copyright](fcopyright.md)     | Si        | R   |        ISO 8601                  | 
|23   | [Fecha de Disponibilidad](fdisp.md)     | No        | MA  |          ISO 8601                | 
|24   | [Fecha de Modificación](fmodif.md)      | Si        | MA  |          ISO 8601                | 
|25   | [Fecha de Aceptación](facept.md)        | No        | MA  |          ISO 8601                | 
|26   | [Formato](formato.md)                   | Si        | M   | MIME Types                       | 
|27   | [Extensión](paginas.md)                 | Si        | R   |                                  | 
|28   | [Idioma](idioma.md)                     | Si        | M   | ISO 639-2                                 | 
|29   | [Audiencia](audiencia.md)               | Si        | R   |                         | 
