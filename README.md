## Reglas de challange_psg


Para probar sus habilidades y demostrar que la ciencia y el deporte no tienen secretos para usted, le ofrecemos un conjunto de datos proporcionado por la empresa Opta.

El resultado debe proponerse en el lenguaje de programación Python o R, desde los archivos Opta F24. Tu código tendrá que ser rápido y corto. El jurado se basará en el rendimiento de su código para clasificar a los finalistas. Tiempo de cálculo del archivo de prueba: máximo 5 segundos para el archivo de base de datos de prueba en una computadora portátil. 

Encuentra las reglas del juego de desafío en la pestaña " Reglas del juego ". 


INSTRUCCIONES DE PYTHON:

Versión 3.5.
Paquetes permitidos: Sin restricciones, sin embargo, utiliza paquetes que se pueden instalar usando
Haz una carpeta que contenga al menos estos 3 archivos: main_psgx. py , install_psgx.py , readme.txt . 

1) El archivo main_psgx. py debe contener una función "Resultado" que debe tomar como argumento un archivo XML idéntico al del archivo de prueba proporcionado y hacer un archivo .csv  (sin encabezado) llamado res_psgx.csv en la misma carpeta, con las siguientes 4 cantidades separadas por una coma
- La identidad del jugador debe ser una real correspondiente a su ID.
- El próximo evento es un real que vale 1 o 0.
- Las siguientes yyx son reales.

2) El archivo install_psgx. Py debe contener la lista de paquetes a instalar. Para cada paquete utilizado, escriba el comando os.system () . ¿Tienes experiencia? No dudes en utilizar el paquete pipenv e indicarlo. 

3) El archivo readme. txt debe contener:
 - Los paquetes utilizados.
 - Una breve descripción de cada subarchivo contenido en el directorio enviado. 

INSTRUCCIONES EN R:

Versión 3.4
Paquetes permitidos: Paquetes disponibles en CRAN.  
Haz una carpeta que contenga al menos estos 3 archivos: main_psgx. R , install_psgx.R , readme.txt . 

1) El archivo main_psgx.R debe contener una función "Resultado" que debe tomar como argumento un archivo XML idéntico al archivo de prueba provisto y  hacer un archivo  .csv  (sin encabezado) llamado res_psgx.csv en la misma carpeta, con las 4 cantidades Los siguientes están separados por una coma:
- La identidad del jugador debe ser una real correspondiente a su ID, que es un número entero. 
- El siguiente evento es 1 o 0, que es real. 
- Las siguientes yyx son reales. 

2) Instrucciones de uso de los paquetes: el archivo. install_psgx.R debe contener la lista de paquetes para instalar. Para cada paquete utilizado, escriba el comando install.packages () .  
 
3) El archivo readme.txt debe contener:
- Los paquetes utilizados. 
- Una breve descripción de cada subarchivo contenido en el directorio enviado.
Buena suerte ! 
El equipo de Sports Analytics Challenge.
