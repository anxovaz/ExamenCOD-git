# Examen 1ª Evaluación (2ª Parte) - Control de Versiones

## Nombre

- Anxo Vázquez Lorenzo

---

## Instrucciones
- Los commits de cada apartado deben tener el mensaje *"Apartado X - descripción del cambio realizado"*
- Entrega en la tarea de Moodle tu repositorio
- Solo se corrigen los commits que estén en el repositorio remoto

### Apartado 1

- Clona este repositorio.
- Modifica este Readme, poniendo tu nombre completo, realiza un `commit` con el mensaje *"Apartado 1"* y un `push`.

Pregunta 
- ¿Qué paso es fundamental cuando clonamos un repositorio ajeno para que podamos subir nuestros propios commits? Explícalo y utiliza capturas de pantalla.

### Respuesta

Clono el repositorio con la terminal y creo un directorio llamado `images` para guardar las capturas.

![clonar](./images/clonado_repositorio.png)

Después creo un repositorio en github y elimino el remoto `origin` del repositorio local y agrego el de mi repositorio de github.

![remote](./images/remote.png)

Para terminar realizo el `commit` y el `push` desde `pycharm`.

Para hacerlo desde la terminal sería:

```
git status #modificaciones
git add <archivo1> <archivo2> ...
git commit -m "Mensaje"
git push
```




### Apartado 2

- Realiza una modificación en el código en la web de tu repositorio en GitHub
- Utiliza fetch para descargar los cambios realizados en tu repositorio.

Pregunta
- Explica los pasos para que el código modificado en GitHub, llegue a tu rama principal local. Explícalo con capturas de pantalla.

### Apartado 3

- Realiza otro cambio desde la web de tu repositorio en GitHub.
- Utiliza pull para descargar los cambios realizados en tu repositorio.

Pregunta
- Explica los pasos dados para que el cambio realizado en GitHub, llegue a tu rama principal local. Explícalo con capturas de pantalla.

