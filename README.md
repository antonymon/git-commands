# Comandos útiles de Git

1. git init                         :   Crea un nuevo directorio.
2. git add .                        :   Tomar todos los archivos desde el init o útimo commit para prepararlos para una fotografía (Commit). 
3. git reset .                      :   Revierte el git add .
4. git commit -m "msg"              :   Efectua una fotografía sobre los archivos preparados.
5. git checkout -- .                :   Revierte los cambios al último commit.
6. git log                          :   Histórico de commit.
7. git commit --amend               :   Arregla el último commit (i= Permite editar, Esc= Salir de edición, :wq!=Escribir, salir inmediatamente ).
8. git checkout -b nombre-rama      :   Crea una rama con el nombre especificado. 
9. git branch                       :   Muestra la rama en la cual estamos trabajando.
10. git checkout nombre-rama        :   Cambiar a otra rama.
11. git merge nombre-rama           :   Tomar cambios de rama y funcionar.
12. git branch -d nombre-rama       :   Eliminar rama.
13. git remote add origin url-repo  :   Agrega el origen del despliegue. 
14. git remote rm origin            :   Remover origen de despliege agregado.
15. git push                        :   Subir cambios al origin establecido (Remoto).
16. git commit -am "msg"            :   Permite un git add . y git commit a la vez cuando git le esta dando seguimiento al proyecto o archivo.
