# Configuración de git

```Shell
# Para ver la version de git
git version

# Para ver la configuracion de git
git config --list

# Para crear un repositorio desde donde estoy
git init

# Para vincular el repositorio remoto con el local
git remote add origin <enlace de git al crear un repo nuevo>
```

# Comandos de git básicos

```Shell
# Para crear una nueva rama:
git branch nueva-rama

# Para ver un listado de tus ramas en local
git branch

# Para ver un listado de tus ramas locales y remotas
git branch -a

# Para fusionar dos ramas (ESTANDO EN LA RAMA DE DESTINO)
git merge rama-origen

# Para subir cambios de una rama a Github 
git push origin nombre-rama

# Para cambiar de rama 
git checkout nombre-rama

# Para borrar una rama
git branch -d nombre-rama

# Para borrar una rama remota
git push origin --delete rama-a-borrar

################### GIT MERGE #######################

# Para fusionar dos ramas (ESTANDO EN LA RAMA DE DESTINO)
git merge rama-origen

# Para crear una Pull Request
### HAZLO DESDE GITHUB, TEN CUIDADO AL SELECCIONAR LA RAMA ORIGEN Y LA RAMA DESTINO

# SI ENCUENTRAS CONFLICTO, DEBES SOLUCIONARLO EN UN EDITOR DE TEXTO COMO, POR EJEMPLO, VISUAL STUDIO CODE
```

# Otros comandos interesantes
    
```Shell
########## hay 3 formas de hacerlo ############
# soft  vuelve al commit anterior dejando los cambios en la staging area
git reset --soft ce3276f9e808 (valor hash del commit al que queremos ir)

# mixed  vuelve al commit anterior dejando los cambios en la staging area
git reset --mixed ce3276f9e808 (valor hash del commit al que queremos ir)

# hard borra el commit anterior pero se pierden las modificaciones en los archivos
git reset --hard ce3276f9e808 (valor hash del commit al que queremos ir)
```

# Para pasar un commit de una rama a otra

```Shell	
# habria que copiar el commit id de la rama origen
# movernos a la otra rama

git cherry-pick 9f0aa3f1c60d92165f (valor hash)
```