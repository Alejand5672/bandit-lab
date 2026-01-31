## Bandit nivel 0
**objetivo:**
encontrar la contraseña del siguiente nivel
**Comandos utilizados**
```bash
ls 
ls -l 
cat

## explicación 
Se listaron los archivos ocultos y luego use cat para para saber la contraseña.

## Coontraseña obtenidad:
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

## Bandit nivel 1
**Objetivo:**
encontrar la contraseña del siguiente nivel 
**comandos utilizados**
```bash
ls
ls -l
cat ./

## explicación
se listaron los archivos y luego use esa configuración de cat para poderlo abrir y me dio la contraseña.

## contraseña obtenida:
263JGJPfgU6LtdEvgfWU1XP5yac29mFx

## Bandit nivel 2
**Objetivo:**
encontrar la contraseña del siguiente nivel en un archivo con un nombre raro igual con - y espacios.
**Comandos utilizados** 
``` bash
ls
ls -l
cat ./ separado asi --spaces\ ... \

## Explicación
Se listaron los archivos y luego use cat para poder abrirlo y se puso ./ porque sino los - confunden a cat según lo que investige.


## Contraseña obtenida:
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

## Bandit nivel 3
**Objetivo:**
encontrar la contraseña del siguiente nivel con un directorio y un archivo oculto.
**Comandos Utilizados**
```bash
ls
cd
ls -la
find 
cat 

## Explicación
Se listaron las carpetas y luego al entrar se encontro  el archivo oculto y se pudo encontrar la contraseña.

# Contraseña obtenida: 
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
