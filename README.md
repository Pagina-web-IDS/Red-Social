# Red-Social (Manual de Usuario)
Proyecto escolar


Crearemos una red social con el fin de entender su procedimiento y funcionalidad.

En ella podremos registranos, iniciar sesion, enviar mensajes, seguir a los usuarios, entre otras cosas.

Documentación: Ubicado en la rama **Otium**.
```
  •	Documento de visión

  •	Casos de uso

  •	Diagrama Pert y Gantt

  •	Diagramas UML
```
Versiones de Base de datos: Ubicado en la rama **Base-de-datos**.
```
  •	Diagramas de versiones
```
Versiones de Pagina Web: Ubicado en la rama **Pagina-Web**.
```
  •	Imágenes de versiones

  •	Código de algunas versiones
```
Codigo Actual de la pagina: Ubicado en **Codigo-Final**
```
  •	Link del repositorio hacia el código Final para la ejecución 
```

## **Requisitos para la correcta ejecución**
```
Instalar:

•	Angular

•	NodeJs

•	MongoDB
```

## **Como ejecutar**

Abrir la carpeta Backend desde el cmd.

Ejecutar los siguientes comandos:
```
•	npm install

•	npm start
```

![image](https://user-images.githubusercontent.com/77498360/115334553-3bac9d80-a161-11eb-8fd8-71fb32b3b725.png)


Abrir la carpeta Frontend desde el cmd.

Ejecutar los siguientes comandos:
```
•	ng build

•	ng serve
```
![image](https://user-images.githubusercontent.com/77498360/115335154-3e5bc280-a162-11eb-83dd-c8ee72d7f6ce.png)

![image](https://user-images.githubusercontent.com/77498360/115335184-4e73a200-a162-11eb-882f-75dac94a8aec.png)



Abrir el servidor Mongo.

![image](https://user-images.githubusercontent.com/77498360/115335089-24ba7b00-a162-11eb-85a5-c6fd2ed46e9d.png)

Este proceso es para la primera vez en ejecutar el Proyecto.
Despues solo se deben ejecutar estos comandos en su respectivo directorio:
```
•	npm start
•	ng serve
•	mongod
```


# **Video: Funcionalidad de Otium**
link: https://www.youtube.com/watch?v=Rx7K1ISQjlM


# **Notas para el Uso de la _Red Social_**

### **Registrarse**
```
• Todos los campos deben llenarse
• No se aceptan Nicks y correos iguales
• El correo debe ser valido
  - No iniciar con mayúsculas
  - Tener un provedor
  - No usar caracteres especiales
```
![image](https://user-images.githubusercontent.com/77498360/115337328-65b48e80-a166-11eb-927a-d390aede7826.png)


### **Iniciar sesión**

```
• Todos los campos son obligatrios
• Ingresar un Email ya registrado
• Ingresar correctamente la contraseña del usuario
![image](https://user-images.githubusercontent.com/77498360/115628262-01104580-a2c6-11eb-841d-ba12a62ef684.png)
• Una vez realizado lo anterior hacer click en Enviar
![image](https://user-images.githubusercontent.com/77498360/115628410-37e65b80-a2c6-11eb-83e9-6ad11c76d53f.png)
```

### **Perfil**

• Podemos Ingresar a unestro perfil desde la pestaña **Home** al darle click sobre el recuadro Titulado: **Mi perfil**

![1](https://user-images.githubusercontent.com/77498360/115629107-4c772380-a2c7-11eb-8f6b-b7d6e211471d.png)

• En este apartado se podrán ver el número de seguidores que tengas, número de publicaciones y número de publicaciones tuyas en tiempo real

• Se podra ver tu **Nombre**, **Apellido** y **Estado actual**

![image](https://user-images.githubusercontent.com/77498360/115629243-9d871780-a2c7-11eb-9ebe-8709f7cf7bdc.png)

• Abajo del apartado de arriba se encontrarán todas las **Publicaciones** que has publicado (No aplican publicaciones eliminadas)

![image](https://user-images.githubusercontent.com/77498360/115629611-52b9cf80-a2c8-11eb-9e67-f79b1764693d.png)


• En la parte derecha se encontrara el apartado nombrado **Tus Datos** en el cual es un resumen de tu perfil ademas de tener el apartado para **Publicar**

![image](https://user-images.githubusercontent.com/77498360/115629977-e7bcc880-a2c8-11eb-8283-1dcc4bb09abb.png)

### **Editar tus datos de Perfil**

• Sobre la barra de navegacion ubicada en la parte superior derecha de la pagina dar **click sobre tu nombre**

![2](https://user-images.githubusercontent.com/77498360/115630475-ad9ff680-a2c9-11eb-93e3-cfad2f23c86b.png)

• Se desplegara una barra donde daremos click nuevamente sobre **Mis Datos**

![3](https://user-images.githubusercontent.com/77498360/115630715-1d15e600-a2ca-11eb-8d9f-e15c1d7f1ce0.png)

• En este apartado podrás actualizar tu **Nombre**, **Apellido**, **Nick**, **Email** y configurar tu **Estado Actual**

![image](https://user-images.githubusercontent.com/77498360/115630765-36b72d80-a2ca-11eb-98b2-ac40aabb261a.png)

• Cualquier cambio sobre tus datos se guardarán después de dar click sobre **Actualizar*

![tempsnip](https://user-images.githubusercontent.com/77498360/115631043-b34a0c00-a2ca-11eb-8820-23178f582388.png)

### **Publicar**

• Para publicar primero debemos estar en el Apartado **Tus Datos**, ubicado en **Mi perfil**, **Timeline** y **Gente**

![image](https://user-images.githubusercontent.com/77498360/115631280-218ece80-a2cb-11eb-9b44-63c1827bf064.png)

• Estando en el apartado mencionado, en la parte inferior de este se podrá ver una parte llamada **Publicar**
• Para publicar es obligatorio ingresar algun texto en el recuadro del mismo

![image](https://user-images.githubusercontent.com/77498360/115631551-aaa60580-a2cb-11eb-8390-a717a490378b.png)

• Al finalizar para guardar la publicación solo es darle click sobre el boton **Publicar**

![4](https://user-images.githubusercontent.com/77498360/115631865-46d00c80-a2cc-11eb-90ee-e3ef9a9ab762.png)

### **Seguir Usuario**

• En la barra de navegación dar click sobre **Gente**

![image](https://user-images.githubusercontent.com/77498360/115632127-b34b0b80-a2cc-11eb-810f-0ec319af5a31.png)

• Para encontrar a tu amig@ debes navegar con los botones **<<Anterior** y **Siguiente>>**

![image](https://user-images.githubusercontent.com/77498360/115632140-b9d98300-a2cc-11eb-990e-4e03e7fdc1b8.png)

• Al encontrar a tu amig@ solo debes dar click en **Seguir**

![image](https://user-images.githubusercontent.com/77498360/115632354-25bbeb80-a2cd-11eb-8cd8-f83a95db76ff.png)


### **Mensajes**

• En la barra de navegación dar click sobre **Mensajes**

![image](https://user-images.githubusercontent.com/77498360/115632476-6ca9e100-a2cd-11eb-8943-eb3d145f05d6.png)

• Para enviar un mensaje debemos dar click sobre **Enviar Mensajes**

![5](https://user-images.githubusercontent.com/77498360/115632532-8d723680-a2cd-11eb-8606-1e910ead9cbc.png)

• Debemos seleccionar un destinatario en la opción **Para**. Al dar click sobre **Para** se desplegará una barra ahí se debe buscar el destinatario

• Después se debe escribir el mensaje en su respectivo apartado y dar click en enviar

![image](https://user-images.githubusercontent.com/77498360/115634381-23f32780-a2cf-11eb-99e1-29a0712ff582.png)

• Para ver los **Mensajes Enviados**, dar click en **Mensajes Enviados** 

![6](https://user-images.githubusercontent.com/77498360/115634725-c6aba600-a2cf-11eb-9bea-8bd286d3bc08.png)


![image](https://user-images.githubusercontent.com/77498360/115634547-6f0d3a80-a2cf-11eb-8b4c-a5430480f5ab.png)

• Para ver los **Mensajes Recibidos**, dar click en **Mensajes Recibidos** 

![6](https://user-images.githubusercontent.com/77498360/115634803-f2c72700-a2cf-11eb-98f1-49b9fa01d639.png)

![image](https://user-images.githubusercontent.com/77498360/115634638-a1b73300-a2cf-11eb-8ed9-de09738293e8.png)

