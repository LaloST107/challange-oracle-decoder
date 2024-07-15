# 💰 challange-oracle: Conversor de Monedas  💰


Código de la aplicación de un Conversor de Monedas como parte del Challenge-based learning de AluraLatam y Oracle ONE. 
Este proyecto es parte del desafío de conversión de monedas, y utiliza la ExchangeRate-API (https://www.exchangerate-api.com) para realizar las conversiones.

En esta aplicación, el usuario puede seleccionar su moneda inicial, la moneda de destino (a la que desea convertir), e ingresar el monto a convertir. Esto se logra utilizando la clase Scanner para la entrada de datos.
La funcionalidad de conversión se basa en la ExchangeRate-API, que realiza la conversión automáticamente. Los parámetros seleccionados por el usuario se utilizan para crear una URI que se envía a la API, la cual devuelve el resultado de la conversión.
El proyecto también utiliza la librería Gson (https://mvnrepository.com/artifact/com.google.code.gson/gson) para manejar el formato JSON de las respuestas de la API.

El menú se presenta de manera sencilla para facilitar su uso, incluso para alguien que no esté familiarizado con el código y los métodos empleados:

![imagen](https://github.com/user-attachments/assets/93eac426-6c58-4d53-a109-5650c0ca0142)


#NOTA:# Solo se pueden utilizar las monedas disponibles en: https://www.exchangerate-api.com/docs/supported-currencies
#Tecnologías utilizadas ✔️:
- Java - GSON de Google 
