# IOT4
Práctica de Laboratorio: Motor de reglas

# Rule Engine and AuthenticationRule


## Creating a Database

Para el desarrollo de “Rule Engine and AuthenticationRule” se levanto los servicios de:

[![N|Node-red](https://i.ibb.co/Q62QZpv/logoigm1.png)](https://nodered.org/) [![N|Postman](https://i.ibb.co/mhFCN4d/postman.png)](https://www.postman.com/) [![N|MySql](https://i.ibb.co/PjLxDCC/logoigm3.png)](https://www.mysql.com/) [![N|phpMyAdmin](https://i.ibb.co/cypsdgy/logoigm4.png)](https://www.phpmyadmin.net/)

Primero creamos la base de datos RuleEngine según la siguiente estructura, esto junto a la tabla thingData que tiene datos de los ejercicios anteriores del libro:

![N|Img1](https://lh3.googleusercontent.com/cBLQ0Ue_aIUESboEgmyDIRbWeUC25NpDhtzYxhv8BaRLe2UvHmxHHC2V3si7zHVx3o8tWV7ZWWBIv24-Fkmr_o2Y51oXqw91KC9kycUvMVbjydkVIltv02g0X3FaEm1Jorv_MqIY)

## Building the Flow Sequence

Luego debemos dirigirnos a nuestro node-red y armar la siguiente estructura de servicios, puede encontrar el archivo para importar esta configuración con el nombre de Cap10_1.json:

![N|Img2](https://lh5.googleusercontent.com/Madn5n3FMbCpIQsAO12JSUh1YDmfdJ-oHqJi4wh6jRVpKNBXSy3cdwf0cP0cdkeYyjNDHR4PxgSw2iMBM0FP-jrhxp0HuY-7La0TdBDwxyohj0QQe5XW4pUgN0Sn1eYrNbTs2J_q)

## Testing the Rule Engine

Para esta etapa se utilizará Postman, como servicio de peticiones POST, donde veremos que el apartado ‘Creaty Query’ funciona con normalidad al hacer la consulta por método GET como muestra la siguiente imagen

![N|Img3](https://lh3.googleusercontent.com/txT-Rac10owPr5gFwhIyivlsE-2mWH45YvdYbC_jI5jgF_RebZapMOVLf0N6HZh25uL_R7q9bLbVCNg21jSdVM9BoICXUSyS19Cw7YWHY245Ux0GKtmIuJ6Z-bqs4fkZLSyoXtmw)

Ahora veremos algunas reglas que el libro nos indica que agreguemos a nuestra tabla para que sean consultadas, la siguiente imagen muestra 3 ejemplos de regla.

![N|Img4](https://lh6.googleusercontent.com/gmdJVhxspaW2r-6oPkBja8w5jR-w_7g5uT3dgp-uzPxqzuk_vQqyyOiJ41Fxpl4hQGsivmjO88118yIaI_aTUQC5n34dztnCNS15e__v_PNWyTnjlrmYFHElviUEB6fV4r0OLKbm)
  
Y el resultado en Postman es el siguiente al hacer la petición por método POST como indica el libro:

![N|Img5](https://lh5.googleusercontent.com/DlP966HGEjxpRA5I57rljMcDNTycgl1xPeFHEmdob-D6TjVU7Mebw1GRbyRZVmczpOou5spTH5DCK6cYbiYpWtHcNHx9fgq28N2pHdVbrw_uysFm264pwvXJ9W0zDP6NkWNEJNwx)

Además, podemos ver en la consola de node-red el siguiente mensaje apenas ejecutamos la URL anterior.

![N|Img6](https://lh5.googleusercontent.com/x4hQ8GPIBYVpqhZAwkUY3AsGco0Ua6iqo4dDNfNOVEtpNLJUBa2g6Zp0f6xEFQ_r33V6xPrFQiiNINEjbl46GZau6xSr4wlHZwPfXDUkkxs9Ro_OWMsV_BeIoniJ8yo2w_jUYmet)

Todos los archivo necesarios para la ejecución del ejercicio se encontrará en un repositorio para su fácil replicación.
