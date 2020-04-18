# Docker_MySQL

Dentro de la carpeta Docker se encuentran 2 carpetas, una de ellas lleva como nombre "Creación de volumen", los primeros pasos que se realizaron para crear el Volume y correr una imagen con su volume.
La imagen "BD(create db, create table, insert, select)" corresponderia al segundo paso en este proceso que es donde creamos la tabla de prueba y realizamos registros en la BD desde la linea de comandos de MYSQL, para despues consultar estos datos y corroborar que se realizron correctamente las consultas.

Despues de haber creado la base de datos, tabla y registros. Se detuvo la imagen, para volver a iniciarla y comprobar que se guardaron correctamente los datos y que los datos estan siendo persistentes.

En la carpeta Contenedor, la imagen corrersponde al proceso para la comprobación de que los datos se estan guardando correctamente y que si se detiene el sistema, los datos siguen siendo persistentes y pueden ser consultadaos despues del reiniciar el contenedor.
