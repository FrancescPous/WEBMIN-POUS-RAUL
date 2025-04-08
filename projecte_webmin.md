**1.- Crear i modificar usuaris**


Has de crear dos usuaris bakalao_X i techno_X on (X és el vostre cognom).
![image](https://github.com/user-attachments/assets/2ce50ea3-7faa-47a2-80fd-742d0a700c72)


Els usuaris et passaran el hash de la seva contrasenya, no la contrasenya real. (podeu fer servir openssl).
![image](https://github.com/user-attachments/assets/b8cccbde-7cbe-4edd-82c4-4c239291e944)


Cada usuari tindrà un directori a home igual al seu nom d'usuari.


Utilitzaran bash com a shell.


Els usuaris estaran dins del grup que tingui el seu mateix nom i dins del grup usuaris_empresa.


L'usuari techno no podrà fer login després del dia 31-03-2025.


Comproveu que els usuaris poden iniciar sessió.


Canvia la data del sistema (utilitzant webmin) i comprova que techno no pot iniciar sessió si estem a dia 01-04-2025.
