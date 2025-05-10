# Comandos de Git
Aquí es donde se explica todo lo referente a los **comandos** que usamos en **Git** para gestionar el historial de versiones de un proyecto de software.  

---

![Git, la herramienta líder en control de versiones](https://tincode-django.s3.amazonaws.com/media/uploads/2022/07/15/introduccion-a-git-para-principiantes-1.gif)

---

## Configuración

### `git config`
Configura opciones de Git a nivel global o local.

- `git config --global user.name "Tu Nombre"`  
- `git config --global user.email "tu@email.com"` 
- `git config --global core.editor nano`
- `git config --global init.defaultBranch main`

> Establece tu identidad para los commits.

---

## Inicio del Repositorio

### `git init`
Inicializa un repositorio Git en el directorio actual.

- `git init`

> Crea una carpeta `.git` con toda la información del repositorio.

---

## Agregar Cambios

### `git add`
Agrega archivos al área de preparación (staging area).

- `git add archivo.txt`  
- `git add .` (agrega todos los archivos modificados)

---

## Confirmar Cambios

### `git commit`
Guarda los cambios agregados al repositorio con un mensaje.

- `git commit -m "Descripción del cambio"`

---

## Ver Historial

### `git log`
Muestra el historial de commits.

- `git log`  
- `git log --oneline` (resumen en una línea)

---

## Navegación y Versiones

### `git checkout`
Cambia de rama o restaura archivos a un estado anterior.

- `git checkout nombre-rama`  
- `git checkout archivo.txt` (restaura archivo desde último commit)

---
