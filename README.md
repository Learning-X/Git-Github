# Git-Github - Práctica del curso de git, gitHub y Sourcetree

## ¿Qué comando utilizaste en el paso 11? ¿Por qué?

uso el comando git revert 01c7b76. Es un comando de "deshacer", pero técnicamente es mucho más que eso. Git revert no elimina ninguna confirmación en el historial de este proyecto. En su lugar, invierte los cambios implementados en una confirmación y agrega nuevas confirmaciones con el efecto contrario.

## ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

uso el comando git reset --hard 36f3ad108879341e006cee06fd88effe87ca456e. El propósito del comando "git reset" es mover el HEAD actual al compromiso especificado.

## El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No se produce ningún conflicto y tampoco ningún cambio despues de hacerlo.

## El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Producen conflictos al mezclar htmlify y styled y hecho un commit.

## El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No se produce ningún conflicto porque solo hemos añadido.

## ¿Qué comando o comandos utilizaste en el paso 25?

git log --graph

## El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Podriamos hacerlo cuando es lineal sin ninguna ramificación hasta el commit donde necesitamos hacer el merge

## ¿Qué comando o comandos utilizaste en el paso 27?

git reset HEAD~1

## ¿Qué comando o comandos utilizaste en el paso 28?

git restore .

## ¿Qué comando o comandos utilizaste en el paso 29?

git branch -D title

## ¿Qué comando o comandos utilizaste en el paso 30?

git reset --hard HEAD@{1}

## ¿Qué comando o comandos usaste en el paso 32?

git reflog, git reset e7cda33

## ¿Qué comando o comandos usaste en el punto 33?

git reflog. git reset e4252e2
