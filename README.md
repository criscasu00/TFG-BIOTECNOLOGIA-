# TFG-BIOTECNOLOGIA-
Recopilación, análisis e integración de la información genómica disponible para el organismo modelo Brachionus plicatilis  
Se adjuntan varios archivos correspondientes al material y métodos realizados (scripts de python) y a los resultados del TFG. 

En primer lugar comentaré los archivos de python:  
Después de realizar el BUSCO2 para la anotación estructural de los genomas se les cambió el nombre de los genes que aparecian con el script de python titulado rename_genomes.py. 

Seguidamente, después de obtener los archivos del OrthoMCL lo que hicimos fue crear la base de datos relacional con el script titulado bibliotecas_orthogrupos.py. Los archivos correspondientes a los resultados son:  
- GFF3 
- Ortólogos: correspondientes a los archivos proteinsTokyo1MappedToGroups.txt, proteinsHYR1MappedToGroups.txt y proteinsNH1LMappedToGroups.txt
- Base de datos relacional: corresponde al archivo llamado biblioteca_ortho.
