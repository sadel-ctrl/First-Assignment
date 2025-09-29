# Primer trabajo
Esta es la parte 1 del primer tarbajo del curso, aquí voy a mostrar uuna rutina para ejecutar en Pyhton, que permite transformar archivos de formato .gtf a formato .tsv.

La rutina mostrada fue generada con ayuda la IA, específicamente de Chatgpt y Gemini.

## Acerca del archivo

- El archivo que voy a utilizar hace parte del genoma de el platelminto japonés flatSchistosoma japonicum, que fue tomado de la página web de la UCSC Genome Browser.
- La idea al transformar este archivo a formato .tsv es poder visualizar la información de manera más organizada y organizada en 11 columnas diferentes, separadas claramente, cada una conteniendo la siguiente información:

  - seqname: nombre de la secuencia de referencia.
  - source: base de datos donde fue generada.
  - feature: característica a la que se refiere.
  - start: posición inicial del cromosoma.
  - end: posición final del cromosoma.
  - score: valor numérico de confianza en la predicción (en este caso, no se utliza, aparece un .).
  - strand: hebra de ADn en la que se encuentra(+ o -).
  - frame: Marco de lectura (0, 1, 2) para las regiones codificantes, o . si no aplica.
  - gene_id: es el identificador único de este gen.
  - transcript_id: identificador del transcrito.
  - gene_name: el nombre de este gen, en este caso, no aplica, ya que en el archivo no se encuentra ninguno.

Adicionalmente, se adjuntan dos fotografías evidenciando el cambio generado al tranformar el formato del archivo; en la primera, se observa cómo se visualiza el archivo con el formato .gtf en Pycharm, y en la segunda, cómo se ve cuando ya se transformó a formato .tsv.

  

  



