# Front-End-Web-UI-Frameworks-and-Tools-
##TRABAJO
### paso1
Instalar las dependencias
```
npm install
npm install bootstrap@4.0.0 --save
npm install jquery@3.3.1 popper.js@1.12.9 --save

```
    "bootstrap": "^4.npm install0.0",
    "jquery": "^3.3.1",
    "popper.js": "^1.12.9"
    "lite-server": "^2.3.0"
### paso2

agregar a index.html la referencia de los modulos
en la parte del header
```  <!-- Required meta tags always come first -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta http-equiv="x-ua-compatible" content="ie=edge">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css">
```
BAJO LA ETIQUETA DE CIERRE DEL BODY
```
    <!-- jQuery first, then Popper.js, then Bootstrap JS. -->
    <script src="node_modules/jquery/dist/jquery.slim.min.js"></script>
    <script src="node_modules/popper.js/dist/umd/popper.min.js"></script>
    <script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>
```
