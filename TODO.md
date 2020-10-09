# TODO

- [ ] Paso 0: conseguir materializar workflows (Nextflow o CWL) a partir de 
WorkflowHub. Eso significa descargar el RO-Crate que proporcione WorkflowHub 
(usando la TRS API de WorkflowHub) para descargar el workflow.

- [ ] Paso 1: Materializar todo lo necesario para lanzar el workflow. Tener un 
fichero que contenga los ids o las referencias de datos a los inputs que vayamos a 
usar para instanciar el workflow. 
([execution_files.yaml](https://github.com/inab/WES-backend/tree/main/tests/execution_files.json))

- [ ] Paso 2: Que se pueda lanzar en el entorno de ejecución al que nos van a dar acceso.