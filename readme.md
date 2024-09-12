## Práctica Git & GitHub

1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?

    - Use el comando `git reset --hard HEAD~1` porque no quiero mantener 
    los cambios realizados en el último commit. 

1. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
    - Primero use el comando `git reflog` para obtener el id del commit que quiero restaurar.
    - `git reset --hard id-commit` para movernos al commit y recuperar la información borrada.

1. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
    - No causo conflictos porque main no tiene commits nuevos.

1. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
    - Si hay conflictos porque ambas ramas modificaron el mismo archivo 
    en las mismas lineas. Eso hace que tenga diferente contenido y que git 
    no sepa con cual de los dos quedarse.

1. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
    - No hay conflictos. Git fue capaz de reconocer que son nuevas modificaciones
    al contenido así que solo se quedo con lo que necesitaba.

1. ¿Qué comando o comandos utilizaste en el paso 25?
    - `git log --graph --decorate --pretty=oneline`

1. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
    - Si podría ser fast forward porque title partio desde main y despúes de eso no 
    se han agregado mas cambios.

1. ¿Qué comando o comandos utilizaste en el paso 27?
    - `git reset HEAD~1` 

1. ¿Qué comando o comandos utilizaste en el paso 28?
    - `git restore git-nuestro.md` 

1. ¿Qué comando o comandos utilizaste en el paso 29?
    - `git branch -D title`

1. ¿Qué comando o comandos utilizaste en el paso 30?
    - `git reflog`
    - `git reset --hard id-commit`

1. ¿Qué comando o comandos usaste en el paso 32?
    - `git log`
    - `git reset --hard id-commit`

1. ¿Qué comando o comandos usaste en el punto 33?
    - `git reflog`
    - `git reset --hard id-commit`