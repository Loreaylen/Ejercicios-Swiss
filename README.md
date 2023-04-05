Métodos HTTP:

GET: Permite recibir la información que está contenida en el endpoint que se indica en el request. La información viene en formato JSON y debe parsearse antes de poder manipular los datos.

POST: Se utiliza para enviar información hacia la API, en este caso se crea un recurso nuevo o se agregan datos a uno que ya existe.

Al realizar ambas peticiones se pueden devolver diversos estados, los más frecuentes son 200 OK (solicitud exitosa) o 404 (solicitud fallida)