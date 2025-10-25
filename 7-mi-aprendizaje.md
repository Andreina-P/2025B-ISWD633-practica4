# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado al realizar la práctica también se debe documentar.

Con esta práctica aprendí cómo hacer y ver el *healthcheck*, también aprendí cómo se limita el uso de memoria en contenedores y que no se puede aplicar esto a contenedores ya creados, sino que se debe establecer al momento de crearlos. También aprendí cómo ver cuántos procesadores se usan en Linux (se ve con `nproc`). Además, aprendí cómo crear una imagen a partir de un archivo Dockerfile y cómo hacer que, con esta imagen, se pueda crear un contenedor con un sistema operativo nuevo.

Utilicé conocimientos de prácticas anteriores, como el mapeo de puertos, la creación de directorios y la verificación del estado de contenedores en ejecución. 

Tuve problemas al querer crear el contenedor con CentOS usando el Dockerfile original del GitHub, ya que esa versión de CentOS estaba deprecada y sus repositorios oficiales dejaron de funcionar. Esto causaba errores durante la construcción de la imagen al ejecutar yum update. Para solucionarlo, modifiqué el Dockerfile redirigiendo los repositorios al sitio vault.centos.org, lo que permitió completar la instalación y continuar con la práctica sin inconvenientes.
