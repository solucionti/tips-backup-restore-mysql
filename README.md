# Tips para realizar backup de base de datos Mysql y como restaurarlas

Realizar un backup simple desde terminal:

`mysqldump -u [usuario] -p[password] [database] > yyy-mm-dd_database.sql`
Donde:
  [usuario]= Usuario con permiso de acceso a la base de datos.
  [password]= Contrasena asociada al usuario.
  [database] = Base de datos de cual se quiere hacer backup
  yyy-mm-dd_database.sql = Sera el nombre de salida de la base de datos.
  
<h2>Ejemplo</h2>

`mysqldump -u mi_usuario -pmipassword mibasededatos > yyy-mm-dd_mibasededatos.sql`
