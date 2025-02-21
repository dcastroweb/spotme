# spotme
2. Repositorio de desarrolladores
Para instalar Spotify desde el repositorio para desarrolladores, primero agregue la clave del repositorio a su sistema. Para ello, ejecute el siguiente comando:

sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys D1742AD60D811D58

 

Luego agrega el repositorio en sí:

sudo add-apt-repository "deb http://repository.spotify.com stable non-free"

Para instalar el programa, ejecute el comando:

sudo apt install spotify-client
