                                                     Alura Latam / Challenge: Conversor de monedas
Desarrillador: Jhon Fredy Morales

Descripcion del proyecto:

El proyecto se basa en un Conversor de Monedas. la aplicación permite convertir diferentes divisas utilizando la API externa
(https://www.exchangerate-api.com/) para obtener las tasas de conversión en tiempo real. Adicional guarda un registro de las
operaciones en un archivo JSON,

Estructura del proyecto:
El programa consta con las clases:

1. PrincipalConversor
 - Encargada de llevar el funcionanmiento y interaccion con el usuario
 - Solicita al usuario que seleccione la divisa que desea convertir con el siguente menu
 - ![{2DD9A87F-386D-4EF8-859B-31D5534F80D1}](https://github.com/user-attachments/assets/45192ec2-672b-4084-b60f-721148fed657)
 - Llama la clase ConversorAPI para realizar la conversion y dar resultado
 - Llama la Clase GenerarJson para guardar las operaciones en un archivo JSON







                                                    
