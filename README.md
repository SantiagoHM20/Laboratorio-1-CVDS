
# CVDS-introGIT
Introducción a GIT de la materia CVDS


PARTE I (Trabajo Individual).

Crea un repositorio localmente.

Agrega un archivo de ejemplo al repositorio, el README.md puede ser una gran opción.

![image](assets/creación%20repo%20local.png)


 Averigua para qué sirve y como se usan estos comandos git add y git commit -m “mensaje”


#### _Git add manda los cambios al área de preparación, son los cambios que se subirán con un commit_

#### _Git commit – m guarda los archivos que están en el área de preparación, además añade un comentario._


Abre una cuenta de github, si ya la tienes, enlazala con el correo institucional.

![image](assets//Config%20correos.png)



Crea un repositorio en blanco (vacío) e GitHub.

![image](assets//creación%20repo%20en%20blanco.png)



Configura el repositorio local con el repositorio remoto.

![image](assets//subir%20cambios.png)
![image](assets//subir%20cambios%202.png)



Sube los cambios, teniendo en cuenta lo que averiguaste en el punto 3 Utiliza los siguientes comando en el directorio donde tienes tu proyecto, en este orden:

![image](assets//cambios%20subidos.png)

Configura el correo en git local de manera correcta

![image](assets/correoEnTerminal.png)

### Parte 2 en parejas

El owner agrega al colaborador con permisos de escritura en el repositorio que creó en la parte 1
#### _Se mandó la solicitud al colaborador por correo_
![image](assets/añadirColaborador.png)

Owner y Colaborador editan el archivo README.md al mismo tiempo e intentan subir los cambios al mismo tiempo.
¿Que sucedió?
#### _Salió el siguiente error:_
![image](assets/error%20al%20subir.png)

La persona que perdió la competencia de subir los cambios, tiene que resolver los conflictos, cúando haces pull de los cambios, los archivos tienen los símbolos <<< === y >>> (son normales en la resolución de conflictos), estos conflictos debes resolverlos manualmente. 

![image](assets/Conflicto%20resuelto.png)

Cambio al tiempo Calderon