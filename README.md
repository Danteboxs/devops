# devops
devops

### Urls
Página estática [http://18.188.88.231/](http://18.188.88.231/)

Página estática [http://www.santiagorodriguez.xyz/](http://www.santiagorodriguez.xyz/)

App Nodepop [http://nodepop.santiagorodriguez.xyz/](http://nodepop.santiagorodriguez.xyz/)

### Pasos ->
(Fijo que se me olvida algo que he hecho por el camino, pero bueno son los pasos principales que he seguido)
1) Crecion instancia, asignacion de ip.
2) Cambio puerto SSH
3) Instalacion de Ngingx
3) Creacion de usuario web
4) Desplegar página estatica con ruta del usuario web
5) Instalación de Base de Datos MongoDb, securización, solo acceso con usuarios.
5) Creacion del usuario Node
6) Desde el usuario node, instalacion de nvm
7) Instalacion de nodejs con nvm
8) Desplegar la aplicacion nodepop con rutas del usuario node
9) Instalar pm2 para gestion del proceso de la aplicacion de nodejs
10) Configurar pm2 para que salve las app y se arranque desde el principio.
11) Desde el user ubuntu modificacion para que carge los estaticos desde nginx en vez de nodejs, añadido x-owner: https://github.com/Danteboxs
12) Instalacion de fail2ban

Notas:
El https queda deshabilitado debido a que la aplicacion de nodepop cargaba urls http y las bloqueaba por temas de mezclar protocolos no seguros.
