# Curso de GIT

## [Introducción](https://github.com/pepellou/CursoGit/blob/master/tema1.markdown) [30 min]
- Qué es un SCV y qué un SCV distribuido
- Historia de GIT: C, kernel linux, contexto (SVN, Mercurial, ...)
- Anatomía de un SCV distribuido | diferencias/parecidos con centralizados
- Instalación: sudo apt-get install git-core
- CheatSheets y Libros recomendados

## Quick Start [30 min]
- Primer repo (init), primer commit
- Configuración inicial: email y name
- add/commit y status/log/show
- Mensajes de commit
- Anatomía de un repositorio git: staging area, index and cache

## Aprendiendo a referenciar revisiones y paths [30 min]
- Anatomía de comandos típicos, referencias VS paths
- HEAD, master, HEAD~1 y otras referencias útiles
- Números de commit: SHA1, subcadena de SHA1
- Nombres de tags, de heads y de branches
- Referencias por mensaje de commit (:/cadena)
- Para saber más: SPECIFYING REVISIONS en "man git-rev-parse"
- --author

## Herramientas para preparar un buen commit en cualquier situación [30 min]
- git add -p
- git rm, git mv
- git reset path
- git diff
- git blame | git log -Sstring
- .gitignore

## Rescribiendo la historia [45 min]
- amend
- checkout
- reset
- stash
- git clean -n | git clean -f
- revert
- rebase
- git bisect

## Trabajando en paralelo [1 h]
- branches
crear, borrar, intercambiar
crear desde ref (git checkout -b mybranch master~1)
- tags
 * crear, usar
- patches
 * crear, aplicar
- remotes: 
 * remote -v
 * push/pull
 * clones
 * repos bare
 * push branch, push tag
- resolución de conflictos
- merge VS rebase VS cherry-pick

## Utilidades [15 min]
- GitK, GitG y git gui | git log --graph | formato git log
- Eclipse EGit

## Configuracion de git [30 min]
- alias
- .gitconfig
 * editor
 * coloreado comandos
 * formato salida comandos
 * otras opciones
- HOOKS
 * cómo crear
 * hooks de lado cliente: commits, emails, rebase, ...
 * hooks de lado servidor: pre-receive, post-receive, update

## Subproyectos [30 min]
- crear submodules
- workflow de commits
- git submodule status --recursive
- git submodule foreach ...

## Integración con otras herramientas [30 min]
- Subversion: git-svn
- Jenkins, beanstalk
- Github, Bitbucket

## Buenas prácticas [30 min]
- Commits atómicos
- Commits frecuentes
- No commits de trabajo a medias
- Test antes de commit
- Buenos mensajes de commit
- Usar branches, feature-branching
- Fijar un workflow común


References:

> [1] [http://git.or.cz/course/svn.html](http://git.or.cz/course/svn.html)  
> [2] [http://www.vogella.com/articles/Git/article.html](http://www.vogella.com/articles/Git/article.html)  
> [3] [http://git-scm.com/book](http://git-scm.com/book)  
> [4] [http://cheat.errtheblog.com/s/git/](http://cheat.errtheblog.com/s/git/)  
> [5] [http://www.git-tower.com/files/cheatsheet/Git_Cheat_Sheet_grey.pdf](http://www.git-tower.com/files/cheatsheet/Git_Cheat_Sheet_grey.pdf)  
> [6] [http://enabling-tech.com/wp-content/uploads/2010/12/gitcheat_thumb.png](http://enabling-tech.com/wp-content/uploads/2010/12/gitcheat_thumb.png)  
> [7] [https://iis.uibk.ac.at/_media/collab/git_revisions_without_branches.png?w=400](https://iis.uibk.ac.at/_media/collab/git_revisions_without_branches.png?w=400)  
