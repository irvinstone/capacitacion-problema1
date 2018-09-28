# Ejercicio 1
Capacitación: Git, bash y docker
Integrantes:
- [Carlos Arbildo]
- [Irvin León]
- [Juan Salvardor]

PARTE 1
1. ¿Qué es y para qué sirve GIT?
	Git es un sistema de versionamiento de código, sirve para versionar y hacer seguimiento al código de un proyecto
2. ¿Que es Github o bitbucket?
	Es Git ofrecido como servicio
3. ¿Qué es y para qué sirve el SSH?
	SSH es un protocolo encriptado para la ejecución remota. 	
4. ¿Que pasa si cambio de PC? ¿Tendré que generar el SSH nuevamente?¿Por qué?
	Si se cambia de PC se tiene que generar nuevamente la clave SSH ya que SSH es P2P
5. ¿Qué es markdown? ¿Para qué sirve?
	Es un lenguaje de etiqueado, sirve para escribir notaciones y/o documentación.
6. ¿Cómo inicializo y configuro un proyecto de git?
	Se inicializa con el comando "git init .". Se configura mediante los comandos "git config", "git remote config" 

PARTE 2
1. ¿Para qué ayuda el `git stash`?
	Sirve para generar commits temporales y ajustarlos a la pila.
2. ¿Cuál es la diferencia entre `git stash pop` y `git stash apply`?
	"git stash pop"		->	Aplica el cambio del top  y lo remueve de la pila.
	"git stash apply" 	->	Aplica el cambio del top o a uno específico pero mantiene este en la pila
3. ¿Qué significa el modo interactivo del `git rebase`?
	Provee al usuario de funcionalidades como : "squash", "drop", "pick", etc.  extras previas al rebase
4. ¿Cual es la diferencia entre la shell y la terminal?
	Shell		-> 	Interprete de comandos del core de un sistema operativo tipo linux / unix
	Terminal	->	Punto de acceso a un sistema
	
5. ¿Que hace estos comandos? `git clone`, `git status`, `git add`, `git commit`, `git push`, `git checkout`, `git stash`, `git rebase`, `git merge`, `git branch`, `git push`?
 `git clone`	->	Clona un repositorio
 `git status`	->	Muestra el estado de los archivos en el working directory
 `git add`	->	Agrega y prepara los archivos al stage para un commit
 `git commit`	->	Confirmaciòn de un cambio el cuál necesita una mensaje y guarda en history
 `git push`	->	Envía los cambios del history a un repositorio remoto
`git checkout`	->	Es un comando multifuncional que opera en archivos, commits y ramas
`git stash`	->	Agrega cambios a una pila llamada stash
`git rebase`	->	Iguala commits de una rama padre con una rama hija, y coloca los commits de diferencia sobre el HEAD antiguo.
`git merge`	->	Mezcla dos ramas
`git branch`	->	Gestionar ramas

