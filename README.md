# LABORATORIO 1- INTRODUCCIÓN GIT
ESCUELA COLOMBIANA DE INGENIERÍA - CICLOS DE VIDA DE DESARROLLO DE SOFTWARE

 ![image](https://github.com/PDSW-ECI/labs/assets/118181543/7b7bba48-cbfb-4327-bec8-f72dc0d258e0)

- En el presente laboratorio vamos a aprender los manejos básicos de GitHub, esto con el propósito de que entiendas y comiences a trabajar con esta herramienta. Para este laboratorio se trabajará de manera individual la primera parte y con dos integrantes en la segunda parte.

## INTEGRANTES

*MARÍA PAULA RODRÍGUEZ MUÑOZ*

*JACOBO DIAZ ALVARADO*


## RESPUESTAS

## PARTE I (Trabajo Individual). 

1.	Crea un repositorio localmente.

![img](image.png)

2.	Agrega un archivo de ejemplo al repositorio, el **README.md** puede ser una gran opción.

![img1](image-1.png)

![img2](image-2.png)

![img3](image-3.png)

3.	Averigua para qué sirve y como se usan estos comandos **git add** y **git commit -m “mensaje”**
#### git add
Sirve para agregar archivos nuevos o modificados en el directorio que deben incluirse en la proxima confirmación. Se usa escribiendo *git add [file name]*.

#### git commit -m "mensaje"
Sirve para guardar los cambios de un proyecto capturando el estado actual de los archivos, creando así una confirmación del mismo que puede ir acompañada de un mensaje descriptivo. Va seguido del **git add** que prepara los cambios y con el **git commit** los cambios ya preparados se guardan.

4. Abre una cuenta de github, si ya la tienes, enlazala con el correo institucional.

Ya la tenia enlazada desde el semestre pasado

![img4](image-4.png)
   
5.	Crea un repositorio en blanco (vacío) e GitHub.

![img5](image-5.png)  

6.	Configura el repositorio local con el repositorio remoto.

![img6](image-6.png)

7.	Sube los cambios, teniendo en cuenta lo que averiguaste en el punto 3

![img8](image-8.png)

8.	Configura el correo en git local de manera correcta

![img9](image-9.png)

9.	Vuelve a subir los cambios y observa que todo esté bien en el repositorio remoto (en GitHub).

![img11](image-11.png)
![img12](image-12.png)

## PARTE II (Trabajo en parejas)

1.	Se escogen los roles para trabajar en equipo, una persona debe escoger ser "Owner" o Propietario del repositorio y la otra "Collaborator" o Colaborador en el repositorio.
   
* Jacobo Diaz Alvarado - <b>Colllaborator</b>
* Maria Paula Rodriguez Muñoz -  <b>Owner</b>

2.	El owner agrega al colaborador con permisos de escritura en el repositorio que creó en la parte 1

![img10](image-10.png)
   
3.	El owner le comparte la url via Teams al colaborador
4.	El colaborador acepta la invitación al repositorio

![img13](image-13.png)

5.	Owner y Colaborador editan el archivo README.md al mismo tiempo e intentan subir los cambios al mismo tiempo.

Edición del Owner:

![img14](image-14.png)

Edición del Colaborador:

![img15](image-15.png)

6.	¿Que sucedió?

El que se demoró más no pudo hacer el commit y salió el siguiente error

![img16](image-16.png)
![img17](image-17.png)

7.	La persona que perdió la competencia de subir los cambios, tiene que resolver los conflictos, cúando haces pull de los cambios, los archivos tienen los símbolos `<<<` `===` y `>>>` (son normales en la resolución de conflictos), estos conflictos debes resolverlos manualmente.

En nuestro caso no salieron esos símbolos
         
8.	Volver a repetir un cambio sobre el README.md ambas personas al tiempo para volver a tener conflictos.

Esta vez se decidió editar sobre la misma línea

![img18](image-18.png)
   
9.	Resuelvan el conflicto con IntelliJ si es posible,  [Resolver conflictos en IntelliJ]( https://www.jetbrains.com/help/idea/resolving-conflicts.html#distributed-version-control-systems)

Si fue posible conectar git/github con IntelliJ.

Lo primero que apereció fue esto:

![img19](image-19.png)

Luego salió esto:

![img20](image-20.png)

Aquí IntelliJ permite elegir con cuál versión quedarnos:

![img21](image-21.png)

Se decide quedarse con la version del Owner:

![img22](image-22.png)

## PARTE III (Trabajo de a parejas)
1.	¿Hay una mejor forma de trabajar con git para no tener conflictos?

Si, usando ramas separadas para cada una de las funcionalidades del proyecto, evitando asi la interferencia con el trabajo del otro y cuando este todo terminado se fusiona con la rama main.

2.	¿Qué es y como funciona el **Pull Request**?

Es una solicitud para proponer cambios a un proyecto entre ramas separadas que una vez revisados y aprobados son fusionados con la rama principal (main).

Si no es el propietario del repositorio, primero se debe crear un fork (copia del repositorio), clonar el proyecto, crear una rama y realizar los cambios con commits. Luego hacer push al fork y desde GitHub crear el Pull Request. El dueño del repositorio revisa la propuesta. Si la aprueba, se fusiona con la rama principal, si no, se rechaza con comentarios.


3.	Creen una rama cada uno y suban sus cambios

![img23](image-23.png)

![img24](image-24.png)

4.	Tanto owner como colaborador hacen un cambio en el README.md y hacen un Pull Request (PR) a la rama main/master

### Cambios hechos por Owner (Maria)

![img25](image-25.png)

![img26](image-26.png)

![img30](image-30.png)

### Cambio hechos por Colaborator (Jacobo)

![img28](image-28.png)

![img27](image-27.png)

![img29](image-29.png)

 **(Recomendación : deben trabajar en equipo y distribuirse de mejor manera quien va a modificar qué, para evitar modificar los mismos archivos al mismo tiempo, si no se editan los mismos archivos la resolución de conflictos es automática)**

5.	Teniendo en cuenta la recomendación, mezclen los cambios a la rama main a través de PR con el check/review/approval del otro compañero (Cuando se hace merge se deberían borrar las ramas en github)

![img35](image-35.png)
![img36](image-36.png)

![img31](image-31.png)
![img32](image-32.png)

![img33](image-33.png)
![img34](image-34.png)





