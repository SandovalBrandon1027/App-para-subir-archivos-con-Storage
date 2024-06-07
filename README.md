<h1>Para poder ejecutar este programa debemos:</h1>
<h1>1:Descargar las dependencias necesarias</h1>
<h3>npm install --force</h3>
<h3>Utilizamos el --force para forzar la instalacion de las dependecias ya que aveces podemos tener versiones desactualizadas la cual no pueden ser instaladas</h3>
<h1>2:Establecer nuestras credenciales</h1>
![image](https://github.com/SandovalBrandon1027/App-para-subir-archivos-con-Storage/assets/117743657/c69991a7-fa06-4c2b-aa0d-e141e5e532e7) <br>
<h3>Estas credenciales las encontramos disponibles en nuestro Firebase y deben ser declaradas en el archivo environment.ts</h3>
<h1>3:Debemos reconstuir el proyecto </h1>
<h3>ionic build  <br> ocupamos este comando para poder crear la carpeta .www</h3>
<h1>4:Inicializamos Firebase</h1>
<h3>mkdir hosting <br> esto para poder crear una carpeta llamada hosting dentro de nuestro proyecto <br> luego con el comando: firebase init <br>Podemos inicializar eustro proyecto 
leugo debemos copiar los archivos dentro de la carpeta .www y copiarlas dentro de hosting mas especificamente dentro de la carpeta .public</h3>
<h1>5:Deploy</h1>
<h3>Dentro de la carpeta hosting ejecutamos el siguiente comando <br> firebase deploy <br> y con esto tenemos nuestro deploy en web</h3>
<h1>6:Demostracion</h1>
![image](https://github.com/SandovalBrandon1027/App-para-subir-archivos-con-Storage/assets/117743657/eb336d40-ade3-4123-8dc7-99bed0276fba) <br>
![image](https://github.com/SandovalBrandon1027/App-para-subir-archivos-con-Storage/assets/117743657/b9390f29-265e-4d46-bb95-b9899d7331be) <br>


<h2>Deploy web: https://archivos-firebase.web.app/home </h2>
<h2>Deploy movil: </h2>
