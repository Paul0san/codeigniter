###################
Cómo utilizar
###################

1. Clonar repositorio
2. Mover la carpeta a un servidor web local, se trabajo con apache, pero debería funcionar tambien con NGNIX
3. Ejecutar composer update
4. Para la base de datos basta con crear una con el nombre "apptestbd" y una tabla llamada "users" con las columnas id, name, user y password. ó importar la bd que está dentro de apptestbd.zip para este caso existe un usuario registrado como User2022 y su pass admin1234


-URL registro: ['Tu localhost o domain']/codeigniter/index.php/api/user/register
-URL login: ['Tu localhost o domain']/codeigniter/index.php/api/user/login

Acepta solo formato form-data
