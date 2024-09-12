# RESPUESTAS
1. git reset --hard HEAD~1
	Me permite deshacer el último commit y lo que había en mi working copy de manera que todo queda como antes. Nuestro Staging area queda vacío.
2. git reflog + git reset --hard <id>
	Con reflog, veo todo el registro y puedo resetear al commit con el hash que quiera

3. Si, la rama styled no tiene commits adicionales desde que se creo a partir de main, con lo cual esta actualizada. Para hacerlo mas limpio habría que pasar a main y hacer un merge fast-forward hasta styled

4. No, porque generamos un commit adicional que luego cambiándonos a styled nos permite unir

5. No, nos ha permitido hacer un fast-forward tal y como comentaba en el punto 3, para actualizar la información.

6. git log --graph

7. Si, podríamos haber hecho un FF pero hemos forzado el no hacerlo. Podríamos simplemente actualizar la información.

8. git reset HEAD~1

9. git checkout -- git-nuestro.md

10. git branch -D title

11. git checkout -b title a487ec9

12. git checkout b24db39

13. git checkout
