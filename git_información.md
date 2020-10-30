# Git preguntas
1. **¿Qué es Git?**: Es una pieza de tecnologia para rastrear y registrar cambios y alteraciones en los archivos del ordenador
1. **¿Cual es la diferencia entre un "repositorio simple" y un "repositorio de trabajo"?**: Un repositorio simple no cuenta con ningun archivo que se use Git mientras que uno de trabajo sí cuenta con archivos que se use Git.
1. **¿Cual es la diferencia entre una "bifucación" y una "rama"?**: Una bifurcación es una copia del repositorio que esta completamete alejada de la original. Una rama es algo que se usa para cambiar ciertas partes del programa.
1. **Has creado una confirmación y la has enviado, ahora es pública. Sin embargo, has notado que todavía hay cosas que deben cambiarse. ¿Puedes hacerlo en la etapa de confirmación? y si es así, ¿Cómo?**: Sí pueden seguir haciendose cambios con el comando revert.
1. **¿Qué es "cherry-picking"?** Es lo que ocurre cuando haces un merge, basicamente.
1. **¿Qué es un "stash"?** Un stash es un lugar en el cual puedes almacenar lo que estas trabajando y saltar a otra parte del proyecto ya que lo guarda con sus caracteristicas para que vuelvas después de un tiempo.
1. **¿Cómo resuelves "conflictos " en Git?** Cuando ocurre un conflicto entre archivos lo que ocurrirá es que en el archivo que de conflicto creará las lineas del otro archivo para que puedas modificarlo y subirlo. Luego cuando estes en el otro dispositivo tendrás que actualizarlo para que te deje de dar conflicto todo el rato.
1. **¿Cuál es el lenguaje utilizado en Git?** Git utiliza el lenguaje de C ya que lo hace más rápido por lo cual lo hace más efectivo.
1. **¿Qué es una "solicitud de extracción"?** Es cuando tu pillas un archivo y creas una propia rama para modificar ese archivo para al final terminar mergenandolo con la rama principal.
1. **¿Cuál es la manera más eficiente de encontrar una mala confirmación?** Con el comando git bisect.
1. **¿Qué es un "encabezado"?** Se utiliza para referirse al objeto de una confirmación.
1. **¿Se pueden arreglar las confirmaciones rotas?** Con el comando git commit - amend 
1. **¿Cuál es la diferencia entre "obtener" y "extraer"?** Cuando extraes los datos se descargan y ellos mismos se fusionan entre ellos. Si los obtienes, solamente se descargan y cada archivo se queda por separado.

# Git Comandos
* **git init**: habilitamos git en la carpeta en la que estemos situados, creando una carpeta oculta en ese directorio.
* **git add "archivo"**: añadimos el archivo a la lista de la carpeta para cuando lo actualicemos nos lo añada automáticamente. Con un "." añadimos todos los documentos que haya.
* **git status (-s)**: vemos el estado en los cuales tenemos nuestros archivos, con -s acortamos las líneas que nos salen.
* **git commit -m "Texto de prueba**: nos sirve para que podamos hacer el backup del los archivos en la carpeta oculta con un mensaje para diferenciarlos.
* **git remote add origin "enlace del repositorio online**: con este comando vinculamos nuestra carpeta con un repositorio online.
* **git push -u origin master**: con esto subimos los archivos los cuales les hemos hecho un commit.
* **git log --oneline**: nos permite ver los commit hechos hasta ahora
* **git checkout "indentificador commit"**: volver a un commit que ya no tenemos acceso a él.
* **git bisect** nos ordena las confirmaciones de manera fácil y rápida para encontrar el archivo que está causando problemas
* **git config** sirve para configurar git ya se la informacion del usuario o la forma en la que se sube el repositorio
* **git ignore** con este comando indicamos evitar subir basura inecesaria
* **git commit - amend** Este comando nos permite encontrar la confirmación rota y restaura su funcionalidad eliminando el mensaje de error.
* **git fetch** Baja los cambios de una rama determinada y la coloca en espejo.
* **git merge** Fusiona dos ramas en una rama
* **git pull** Hace un git fetch y git merge a la vez

