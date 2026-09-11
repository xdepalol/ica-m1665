# Mòdul 1665 - Digitalització

## Recursos Educatius Oberts (REA)

Les Activitats d'Ensenyament Aprenentatge (AEA) s'han obtingut com a REAs del intef i s'han adaptat a un curs de 33 hores presencials.

A continuació llista l'origen d'aquests recursos:

* https://descargas.intef.es/cedec/proyectoedia/FP/digitalizacion/contenidos/operacion_digitalizacion/index.html
* https://descargas.intef.es/cedec/proyectoedia/FP/digitalizacion/contenidos/operacion_cloud/index.html
* https://descargas.intef.es/cedec/proyectoedia/FP/digitalizacion/contenidos/operacion_ciberseguridad/index.html
* https://descargas.intef.es/cedec/proyectoedia/FP/digitalizacion/contenidos/operacion_ia/index.html
* https://descargas.intef.es/cedec/proyectoedia/FP/digitalizacion/contenidos/operacion_transformacion/index.html

### REA en un fitxer

Per poder treballar amb algun agent de IA es pot posar tot el contingut de la REA en un sol fitxer.

```shell
# Entrem a la carpeta de la AEA
cd operacion_digitalizacion
# Posem contingut en un fitxer
find . -type f -name "*.html" | while read -r file; do   echo -e "\n\n################################################################\n# PATH: $file\n################################################################\n";   cat "$file"; done > ../REA1.txt
```
