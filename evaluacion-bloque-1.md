# Evaluación · Bloque 1

Este archivo comprueba lo que aprendiste en el bloque 1. La forma de entregarlo también es parte de la evaluación: vas a trabajar en una rama, hacer commits separados y mandar un pull request que alguien más revisa.

## Instrucciones

1. Clona este repositorio y crea una rama llamada `evaluacion-bloque-1`.
2. Contesta cada pregunta abajo de ella, reemplazando el texto _Tu respuesta aquí_. No borres las preguntas.
3. Haz **un commit por sección** (A, B, C y D). Son cuatro commits en total, cada uno con un mensaje que diga qué sección contestaste.
4. Sube la rama y abre un pull request hacia `main` con el título `Evaluación bloque 1`. En la descripción del PR escribe cuánto tiempo te tomó y cuál pregunta te costó más.
5. **No hagas merge tú.** Espera la revisión. Es probable que te pidan cambios; los haces en la misma rama y los subes, y el PR se actualiza solo.

## Reglas

- Secciones A y B: **sin Google, sin IA, sin tus notas.** Contesta con lo que sabes. Si no sabes algo, escribe qué crees y por qué. Una respuesta razonada e incompleta vale más que una perfecta copiada.
- Sección C: necesitas correr comandos. Ahí sí puedes usar la terminal.
- Todo con tus palabras. Respuestas cortas están bien: dos a cinco líneas por pregunta es suficiente.

---

## A · Conceptos

**1. ¿Cuál es la diferencia entre Git y GitHub? ¿Podrías usar uno sin el otro?**

>Git es un sistema de control donde ves los proyectos, ramas y cambios q puedes hacer en ellos.
>GitHub es una pagina en internet donde puedes visualizar los proyectos de mejor manera y asi compartiendolos y publicandolos.

**2. ¿Cuál es la diferencia entre guardar un archivo, hacer commit y hacer push? ¿Dónde vive el cambio después de cada uno?**

>Almacena la informacion.
>Tomas los cambios seleccionados y los registra como una version local de git.
>Envia los commits del repositorio local al remoto en la pagina.
>El cambio vive en las acciones entre cada uno como las intersecciones que comparten.


**3. `git add` y `git commit` son dos pasos separados. ¿Por qué? ¿Qué ganas con que no sean uno solo?**

>Son pasos separados porque introducen el concepto del area de formas diferentes.

**4. ¿Qué es una rama? ¿Por qué no conviene trabajar directo en `main`?**

>Una rama es donde puedes ir arreglando o agregando informacion de muchas maneras sin afectar a los demas y sirve 1 para compartir ideas y no equivcarse con los demas q trabajan en ese pryecto y 2 por si sale algun tipo de bug q solo se vea afectada esa rama y no todo el proyecto desde main.

**5. En tu propio repositorio podías hacer merge sin abrir un pull request. ¿Entonces para qué sirve un PR?**

>Por si encuentras un error a tiempo intentar cambiarlo sin hacer pr ya que si lo haces y no existiese un pr automaticamente se veria afectado tu proyecto, en cambio al hacer pr estarias aceptando tando el error como identifacando el erro a tiempo.

---

## B · Qué harías

**6. Modificaste un archivo, todavía no has hecho `add`, y te arrepentiste. Quieres que quede exactamente como estaba en el último commit. ¿Qué comando usas?**

>Git restore

**7. Hiciste `git add` a un archivo que no querías incluir, pero todavía no haces commit. ¿Cómo lo sacas sin perder los cambios del archivo?**

>git reset HEAD nombre-del-archivo

**8. Hiciste un commit con el mensaje `asdf`. Todavía no haces push. ¿Cómo lo corriges?**

>git commit --amend

**9. Ahora imagina que ese commit con `asdf` ya lo subiste con push, y otras personas ya descargaron el repositorio. ¿Sigue siendo buena idea usar `--amend`? ¿Por qué?**

>git commit -m "Corrige mensaje o cambios de asdf"

**10. Haces `git push` y Git lo rechaza con un mensaje que dice que el remoto tiene cambios que tú no tienes. No te ha pasado todavía, así que razónalo: ¿qué crees que pasó y qué harías?**

>git pull

**11. Abres un archivo después de un merge y ves esto. Explica qué significa cada parte y qué tienes que hacer para terminar el merge.**

```
<<<<<<< HEAD
La torre tiene 12 niveles.
=======
La torre tiene 14 niveles.
>>>>>>> actualizar-datos
```

>Es un conflicto de merge en Git, las marcas indican las dos versiones diferentes del archivo, HEAD es la version actual y actualizar-datos es la version de la otra rama, Para terminar, debes elegir que version conservar, borrar las marcas del conflicto, guardar el archivo y hacer git add y git commit.

**12. Tienes un archivo `claves.txt` con una contraseña. (a) ¿Cómo evitas que Git lo suba? (b) Si ya lo subiste por error, ¿basta con borrarlo y hacer un commit nuevo? ¿Por qué?**

>agregandolo al archivo .gitignore pero si ya se subio, borrar el archivo no elimina la contraseña del historial de Git. Hay que eliminarla tambien del historial y cambiar la contraseña por seguridad.

---

## C · Evidencia

**13. Antes de abrir el PR, corre este comando en tu rama y pega la salida completa dentro del bloque de código:**

```
git log --oneline --graph -10
```

```
pega aquí la salida
```

Explica en una línea qué muestra el dibujo de la izquierda.

> _Tu respuesta aquí_

**14. Pega la liga al pull request donde resolviste el conflicto en tu repositorio `bitacora-txdx`, y el código corto (hash) del commit de merge.**

> _Tu respuesta aquí_

---

## D · Reflexión

**15. ¿Qué fue lo que más te costó del bloque 1 y por qué? Si lo volvieras a hacer desde cero, ¿qué harías distinto?**

> _Tu respuesta aquí_
