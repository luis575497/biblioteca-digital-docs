# Libros 
Esta sección describe cada uno de los metadatos que deben ser considerados para el registro de libros en la Biblioteca Digital de la Universidad de Cuenca.  
### Nivel de obligatoriedad para cada propiedad:  
    
__Obligatorio (M)__: La propiedad siempre debe estar presente en los metadatos. No se permite un valor vacío en esta propiedad.  
__Obligatorio cuando se aplica (MA)__: Cuando se puede obtener el valor de la propiedad, debe estar presente en los metadatos.  
__Recomendado (R)__: Se recomienda el uso de la propiedad.  
__Opcional (O)__: No es importante si la propiedad se usa o no, pero si se usa puede proporcionar información complementaria sobre el recurso.  
  
  

|  ID |             Campo         | Repetible | Uso |   Vocabulario                    |
| --- | ------------------------- | --------- | --- | -------------------------------- |
|1    | [Título](titulo.md)                    | No        | M   |                                  | 
|2    | [Título alternativo](tit_alter.md)        | Si        | R  |                                  | 
|3    | [Autor](autor.md)                     | Si        | M   |       [VIAF](http://viaf.org/)   | 
|4    | Materia                   | Si        | MA  | [Tesauro Unesco](http://vocabularies.unesco.org/browser/thesaurus/es/)                   | 
|5    | Palabras Clave            | Si        | MA  |                                  | 
|6    | Resumen                   | No        | MA  |                                  | 
|7    | Abstract                  | No        | MA  |                                  | 
|8    | Fuente                    | Si        | R   |                                  | 
|9    | Tipo de Publicación       | No        | M   | info:eu-repo/semantic            | 
|10   | Publicaciones relacionadas| S         | O   |                                  | 
|11   | Serie o Colección         | No        | MA  |                                  | 
|12   | Edición                   | Si        | MA  |                                  | 
|13   | Cobertura Temporal        | Si        | R   |                                  | 
|14   | Cobertura geográfica      | Si        | R   | [Tesauro del Gettys](https://www.getty.edu/research/tools/vocabularies/tgn/)               | 
|15   | Colaborador               | Si        | MA  |      [VIAF](http://viaf.org/)    | 
|16   | Identificador             | No        | M   |                                  | 
|17   | Identificador alternativo | Si        | R   | info:eu-repo/semantics/altidentifier             | 
|18   | Editorial                 | Si        | MA  |                                  | 
|19   | Nivel de Acceso           | No        | M   |                                  | 
|20   | Condición de la licencia  | No        | R   | [Copyright](https://rightsstatements.org/), Creative Commons   | 
|21   | Fecha de Publicación      | No        | O   |        ISO 8601                  | 
|22   | Fecha de Copyright        | No        | R   |        ISO 8601                  | 
|23   | Fecha de Disponibilidad   | No        | MA  |          ISO 8601                | 
|24   | Fecha de Modificación     | Si        | MA  |          ISO 8601                | 
|25   | Fecha de Aceptación       | No        | MA  |          ISO 8601                | 
|26   | Formato                   | No        | R   | MIME Types                       | 
|27   | Páginas (extensión)       | No        | R   |                                  | 
|28   | Idioma                    | Si        | M   |                                  | 
|28   | Audiencia                 | Si        | O   | ISO 639-2                        | 