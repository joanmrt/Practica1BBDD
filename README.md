# Practica 1 BBDD SQLAlchemy

En este repositorio voy a documentar todo el proceso de instalación y preparación de SQLAlchemy y Flask, 
y también hacer varias consultas especificadas en el tutorial de PrettyPrinted.

## Preparación del Entorno

Empezamos con la creación y activación de un entorno virtual (venv)

![imagen](https://user-images.githubusercontent.com/74322611/208307990-491b443b-d639-494e-892d-491244278b32.png)

Usamos los comandos de creación "python3 -m venv env" env siendo el nombre de nuestro espacio.
En el caso de Windows he tenido que usar un comando diferente para activar el entorno; "env/Scripts/activate", 
que previamente a esta práctica he tenido que activar los scripts, los he conseguido activar gracias a [esta pagina.](https://www.cdmon.com/es/blog/la-ejecucion-de-scripts-esta-deshabilitada-en-este-sistema-te-contamos-como-actuar)

A continuación instalamos Flask y SQAlchemy en nuestro entorno virtual.

![imagen](https://user-images.githubusercontent.com/74322611/208308242-a8f1b8a5-a0ce-4db5-886e-9add368c62b3.png)

Ahora podemos crear un nuevo archivo .py y continuar a nuestro IDE, yo usaré Visual Studio Code.

![imagen](https://user-images.githubusercontent.com/74322611/208308496-f69fdaaa-f0d8-4920-9837-d474f7cce3e9.png)

## Preparaciones del archivo Python

Necesitamos importar las librerias de Flask y SQLAlchemy, usaremos estos comandos para ello.

![imagen](https://user-images.githubusercontent.com/74322611/208309214-bfeed530-b934-47e9-bcbd-59576e06758e.png)

Despues usamos una serie de comandos para conectar nuestra app con la base de datos de SQLite.

![imagen](https://user-images.githubusercontent.com/74322611/208310102-8a084e61-d5e5-4267-bece-ad067426179b.png)

A partir de aqui ya podriamos empezar a trabajar con consultas y modelos relacionales.
