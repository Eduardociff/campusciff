# Practica Git campusciff Eduardociff

## 2.1 Repositorio Campusciff

Creo el repositorio campusciff desde la web de github

```javascript
git clone git@github.com:eduardociff/campusciff.git
```

## 2.2 Readme

readme.md ya creado desde la web de github, incluyo cambios para subirlo

```javascript
echo "git clone git@github.com:edugago/campusciff.git" >> README.md
git add README.md
```

## 2.3 Commit y Push inicial

```javascript
git commit -m "commit inicial"
git push origin master 
```

## 2.4 Ignorar Archivos

```javascript
echo privado > privado.txt
mkdir privada
echo "privado.txt" > .gitignore
echo privada >> .gitignore 
```

## 2.5 Crear Tag

```javascript
echo 1 >> 1.txt
git add 1.txt
git commit -m "subida la parte del tag"
git tag v0.1
git push origin master
```
## 2.6 Crear Rama

```javascript
git branch v0.2
git checkout v0.2
git log --oneline --decorate --graph --all
echo 2 > 2.txt
git add 2.txt
git commit -m "subo 2.txt a la rama v0.2"
git push origin v0.2:v0.2
```
## 2.7 Merge Directo

```javascript
git checkout master
git merge v0.2
```
## 2.8 Merge con conflicto

```javascript
echo Hola >> 1.txt
git add 1.txt
git commit -m "commit merge conflicto 1"
git checkout v0.2
echo Adios >> 1.txt
git add 1.txt
git commit -m "commit merge conflicto 2"
git checkout master
git merge v0.2
git branch --merged
git branch --no-merged
```
Rama que figura como no merged dado que figura sin resolver
```javascript
git commit -am "commit merge conflicto 3"
git merge v0.2
```
ahora nos devuelve up-to-date

## 2.9 Borrar rama
```javascript
git tag v0.2
git log --oneline --decorate --graph --all
git branch -d V0.2
```
## 2.10 Cuentas Git
Subo foto de perfil

activo passkey

activo doble factor de autentificacion (sms)
## 2.11 Uso social Github
Anyado a companyeros de clase con watch
## 2.12 Crear una tabla

| Nombre | Github |
| ------ | ------ |
| Pablo Suarez Manjon | https://github.com/pablosuarezmanjon | $10 |
| Francisco F. Solana Perez | https://github.com/ffsolana | $20 |
| Eduardo Garrido | https://github.com/edugago | $10 |
| Miguel Felipe Cerdan Cojedor | http://github.com/MiguelCerdan | $20 |
## 2.13 Colaborador

anyado a asanzdiego como seguidor
## 2.14 Crear una organizacion

Creo una organizacion que se denomina eduardocifforg e invito asanzdiego como miembro
## 2.15 Crear equipos

Invito asanzdiego y a macarenagaranena
## 2.16 Index.html

creo un index.html
```javascript
echo "Organizacion campusciff-eduardocifforg" > index.html
git add .
git commit -m "primer commit"
git push origin master
```
## 2.16 Crear pull request 


