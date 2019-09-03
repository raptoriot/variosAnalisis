# variosAnalisis
programas varios para analizar datos

**Programa leerDatosPresionBSA**
    Programa para extraer los datos de l bd que llegan de Lo blanco presion, por medio de placa 3G. los datos llegan a un servidor 
    TCP y se publican mediant pub/ sub. los datos se almacena mediante la forma
    b'{"corriente": "191\\r\\n"}'
    
**googlecloudSQL**
Este proyecto tiene una consola SQL, para conexion a BD de google, para esta conexion se requiere levantar el proxy gcc,
con este proxy el pc ve la bd como 127.0.0.1, se levanta una url para la conexion:
 jdbc:mysql://127.0.0.1:3306/prueba_appengine