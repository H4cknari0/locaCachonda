# locaCachonda
Calculadora con la logica loca/cachonda extraido del siguiente video.
https://www.youtube.com/watch?v=bTDu4I-Ewlo

# Intrucciones para su uso
- 1ª. Debe descaragar Java en su versión 19 para poder ejecutar el archivo .jar
- 2ª. Debe descargarse el fichero .jar que está en este repositorio y ponerlo en algún sitio reconocible.
- 3ª. Puede ejecutar el siguiente programa despues de haber descargado Java en su version 19 y teniendo JavaFX extraido en una carpeta. Deberá ejecutar desde la terminal con el comando java -jar --module-path "(ubicación-JavaFX)/lib" --add-modules javafx.controls,javafx.fxml (fichero.jar).

Los enlaces para Java 19 son los siguientes:
- Windows - https://download.oracle.com/java/19/archive/jdk-19.0.1_windows-x64_bin.exe
- Linux Debian x64 - https://download.oracle.com/java/19/archive/jdk-19.0.1_linux-x64_bin.deb
- Linux RPM arch64 - https://download.oracle.com/java/19/archive/jdk-19.0.1_linux-aarch64_bin.rpm
- Linux RPM x64 - https://download.oracle.com/java/19/archive/jdk-19.0.1_linux-x64_bin.rpm

Los enlaces para JavaFX son los siguientes:
- Windows - https://download2.gluonhq.com/openjfx/19/openjfx-19_windows-x64_bin-sdk.zip
- Linux x64 - https://download2.gluonhq.com/openjfx/19/openjfx-19_linux-x64_bin-sdk.zip
- Linux arch64 - https://download2.gluonhq.com/openjfx/19/openjfx-19_linux-aarch64_bin-sdk.zip

Para mayor facilidad de ejecución de la aplicación le recomiendo hacerse un script en bash o batch ejecutando la sentencia que pone arriba:
- java -jar --module-path "(ubicación-JavaFX)/lib" --add-modules javafx.controls,javafx.fxml (fichero .jar)
