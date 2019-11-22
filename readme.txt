Para que todo funcione bien se deberá haber una carpeta llamada rovipo en la carpeta donde se lance el vagrant.
Tambien mover el Vagrantfile, el provision y la carpeta llamada "rovipo" a dicha carpeta creada anteriormente.

Modificamos el archivo hosts que se encuentra en:
C:\Windows\System32\drivers\etc

En el archivo host deberemos añadir:
192.168.33.10 www.examen.es

Comprobar que el enlace http://www.examen.es te muestra el contenido del documento llamado "rovipo.html"
