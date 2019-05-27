# example-selenium

## Guía de instalación

- Creamos un proyecto Maven https://start.spring.io/ (No hacer este paso, usar este proyecto)
- Agregamos la dependencia de JUnit/TestNG y selenium-java. (Ya agregadas)
- Descargamos chromedriver (tener en cuenta la versión instalada de chrome) o el driver del browser que usen Ej: mi chrome es la version 72 https://chromedriver.storage.googleapis.com/index.html?path=72.0.3626.69/
- Descomprimimos el zip y ejecutamos los siguientes comandos:
  -sudo mv chromedriver /usr/bin/chromedriver
  -sudo chown root:root /usr/bin/chromedriver
  -sudo chmod +x /usr/bin/chromedriver
- Abrimos nuestro IDE y ejecutamos los test.
