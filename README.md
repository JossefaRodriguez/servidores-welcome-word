# Desafio Servidores Welcome Word
### Para iniciar el programa  es necesario ejecutar en la terminal node `index.js` esperar el listen del localhost y aperturar en el navegador http:localhost:8080

**El presente desafio se basa en lo siguiente :shipit:**
- Servidores con Node   
- Verbos para consultas HTTP   
- Parámetros en una consulta HTTP   
- Formularios HTML y servidores con Node

**Y se responde a los siguientes Requerimientos :woman_technologist:**

- Crear un servidor en Node con el módulo http   
- Disponibilizar una ruta para crear un archivo a partir de los parámetros de la consulta recibida
- Disponibilizar una ruta para devolver el contenido de un archivo cuyo nombre es declarado en los parámetros de la consulta recibida
- Disponibilizar una ruta para renombrar un archivo, cuyo nombre y nuevo nombre es declarado en los parámetros de la consulta recibida
- Disponibilizar una ruta para eliminar un archivo, cuyo nombre es declarado en los parámetros de la consulta recibida
- Devolver un mensaje declarando el éxito o fracaso de lo solicitado en cada consulta recibida
- Agrega la fecha actual al comienzo del contenido de cada archivo creado en formato “dd/mm/yyyy”. Considera que si el día o el mes es menor a 10 concatenar un “0” a la izquierda
- En la ruta para renombrar, devuelve un mensaje de éxito incluyendo el nombre anterior del archivo y su nuevo nombre de forma dinámica
- En el mensaje de respuesta de la ruta para eliminar un archivo, devuelve el siguiente mensaje: “Tu solicitud para eliminar el archivo <nombre_archivo> se está procesando”, y luego de 3 segundos envía el mensaje de éxito mencionando el nombre del archivo eliminado
