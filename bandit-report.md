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

##Contraseña obtenida: 
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ


## BANDIT NIVEL 4
**Objetivo:**
Encontrar la contraseña del siguiente nivel con un directorio en la que hay muchas carpetas y solo encontramos la legible por humanos.
**Comandos utilizados**
```bash
ls
cd
ls -la
cat

## Explicación 
Se listaron las carpetas, entre al directorio y revise todas las carpetas hasta encontrar la única legible por humanos.

## Contraseña obtenida: 
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw

## BANDIT NIVEL 5
**objetivo**
Encontrar al contraseña del nivel 5 al 6 cuando te dicen que "La contaseña te da las propiedades
**Comandos utilizados**
```bash
cd
ls
ls -la
find .
cat

## Explicacion
se listaron las carpetas, se busco con find y luego se fue directo a la carpeta solicitada

## Contraseña:
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

## BANDIT NIVEL 6
**Objetivo**
Encontrar la contraseña del nivel cuando te dan las propiedades
**Comandos utilizados**
```bash

ls 
ls -la
find .
cd dando la ruta del find
cat

## Explicacion 
esta estuvo complicada por los permisos y todo pero investige el comando de find que me dejara encontrarlo

## Contraseña
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
