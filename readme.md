# Ejercicio 1

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
  *git reset --hard HEAD~1* 
  Con este comando deshago el último commit ,accesible a través de HEAD~1 y con el comando hard tambien se modifica el working copy.
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
  *git reflog*
  *git reset --hard f6d2fb7*
  Con reflog listo las referencias de todos los commit y con git reset vuelvo al commit con dicha referencia.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
  No se mergea ya que la rama master es la rama por defecto.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
  Causó conflicto ya que el fichero se encuetra modificado en las mismas lineas.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
  No causó ningun conflicto porque lo que se mergeo era el mismo contenido y añadidos elementos htmls.

- ¿Qué comando o comandos utilizaste en el paso 25?
  *git log --graph --decorate --pretty=oneline*

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
  Si podria ser Fast forward, mientras se estaba en la rama Title nadie ha hecho un commit en la rama master.

- ¿Qué comando o comandos utilizaste en el paso 27?
  *git reset HEAD~1* (No utilizo el parametro hard para mantener el working copy)

- ¿Qué comando o comandos utilizaste en el paso 28?
  *git checkout -- git-nuestro.md*

- ¿Qué comando o comandos utilizaste en el paso 29?
  *git branch -D title*

- ¿Qué comando o comandos utilizaste en el paso 30?
  *git reflog*
  *git reset --hard f4b267b*

- ¿Qué comando o comandos usaste en el paso 32?
  *git checkout 829f32c*

- ¿Qué comando o comandos usaste en el punto 33?
   Como estamos en un estado "detached HEAD", podemos volver al estado final con *git checkout master*
