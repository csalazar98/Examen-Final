GIT_Markdown - Christian Salazar Ayala
    Ejercicio1-Ejercicio2
        -Crearemos la carpeta B_Ejercicios, donde guardaremos los ficheros Ejercicio1.md y Ejercicio2.md que hemos creado con VS Code
    Ejercicio3-Git Bash here
        -Si tenemos Git instalado en la carpeta que hemos creado haremos clic derecho y seleccionaremos Bash Here. Se nos abrirá una consola.
    Ejercicio4-Git init
        $ git init
        Initialized empty Git repository in C:/Users/Christian/Desktop/FHAR/B-Ejercicios/.git/
    Ejercicio5-Git status
        $ git status
        On branch master
        Initial commit
        Untracked files:
        (use "git add <file>..." to include in what will be committed)
                Ejercicio1.md
                Ejercicio2.md
        nothing added to commit but untracked files present (use "git add" to track)
        Que una archivo sea untracked significa que Git ve un archivo que no estaba en la instantánea anterior. Actualmente no hay ningún archivo untracked.
     Ejercicio6-Git add
        $git add Ejercicio1.md
     Ejercicio7-Git status
        $ git status
        On branch master
        Initial commit
        Changes to be committed:
        (use "git rm --cached <file>..." to unstage)
                new file:   Ejercicio1.md
        Untracked files:
        (use "git add <file>..." to include in what will be committed)
                Ejercicio2.md
    Ejercicio8-Git commit
        $ git commit -m "Inicio texto 1"
        [master (root-commit) 172eb0f] Inicio texto 1
        1 file changed, 2 insertions(+)
        create mode 100644 Ejercicio1.md
    Ejercicio9-Git log
        $ git log
        commit 172eb0fcfaf034fbf86432c6edc38fadf7de9b95
        Author: Christian <csalazaryala@gmail.com>
        Date:   Fri Jun 1 16:35:09 2018 +0200
        Inicio texto 1
    Ejercicio10-Edición del archivo Ejercicio1.md
        Abriremos el archivo y escribiremos "Colaborar online es posible gracias a GitHub"
    Ejercicio11-Git status
        $ git status
        On branch master
        Changes not staged for commit:
        (use "git add <file>..." to update what will be committed)
        (use "git checkout -- <file>..." to discard changes in working directory)
                modified:   Ejercicio1.md
        Untracked files:
        (use "git add <file>..." to include in what will be committed)
                Ejercicio2.md
        no changes added to commit (use "git add" and/or "git commit -a")
        Podemos ver que si se ha dado cuenta ya que pone modified: Ejercicio1.md
    Ejercicio12-Git add + Git status
        $ git add Ejercicio1.md
        $ git status
        On branch master
        Changes to be committed:
        (use "git reset HEAD <file>..." to unstage)
                modified:   Ejercicio1.md
        Untracked files:
        (use "git add <file>..." to include in what will be committed)
                Ejercicio2.md
    Ejercicio13-Git add
        $ git add Ejercicio2.md
    Ejercicio14-Git commit
        $ git commit -m "Actualización Ejercicio1.md y de Ejercicio2.md"
        [master 5daa2ea] Actualización Ejercicio1.md y de Ejercicio2.md
        2 files changed, 3 insertions(+)
        create mode 100644 Ejercicio2.md
    Ejercicio15-Git status
        $ git status
        On branch master
        nothing to commit, working tree clean
    Ejercicio16-Git log
        $ git log --pretty=oneline
        5daa2eaf8c696316880e77193696213c7d4669c0 Actualización Ejercicio1.md y de Ejercicio2.md
        172eb0fcfaf034fbf86432c6edc38fadf7de9b95 Inicio texto 1
    Ejercicio17-Git checkout
        $ git checkout <Inicio>
    Ejercicio18-Linea del tiempo
        Estamos justo antes de realizar el primer commit
    Ejercicio19-Git checkout
        $ git checkout master
    Ejercicio20-Comprobar B-Ejercicios
        Volvemos a estar justos en el último commit





