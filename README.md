-   ¿Qué comando utilizaste en el paso 11? ¿Por qué?
    git reset --hard HEAD~1 para deshacer el ultimo commit y la opcion hard para cambiar tambien el working directory

-   ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
    Primero el comando git reflog para tener los identificadores de todos los cambios que habiamos hecho, luego utilice el identificador del estado anterior al reset realizado anteriormente git reset --hard 1c08dcc

-   El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
    No, porque la rama styled ya contiene los cambios de master

-   El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
    Si porque las dos ramas contienen cambios sobre un mismo archivo y son dos historias diferentes

-   El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
    No, solo actualizó el contenido del archivo porque estaba un commit mas adelante

-   ¿Qué comando o comandos utilizaste en el paso 25?
    git log --decorate --graph --all --oneline para visualizar todas las ramas a manera de grafico

-   El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
    Si porque las ramas comparten historico

-   ¿Qué comando o comandos utilizaste en el paso 27?
    git reset para devolverme en ese merge

-   ¿Qué comando o comandos utilizaste en el paso 28?
    git reset

-   ¿Qué comando o comandos utilizaste en el paso 29?
    git branch -D title

-   ¿Qué comando o comandos utilizaste en el paso 30?
    git reset con ayuda de reflog para saber el identificador del estado que necesitaba

-   ¿Qué comando o comandos usaste en el paso 32?
    git reset con ayuda de reflog para saber los identificadores de los estados que necesitaba

-   ¿Qué comando o comandos usaste en el punto 33?
    git reset con el identificador del primer commit
