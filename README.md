# 💻 Formación Web Dev – Comandos básicos  
**Fecha:** 06/10/2025  

## 🖥️ Comandos de terminal

La terminal (o línea de comandos) permite moverse entre carpetas y ejecutar acciones sin usar el ratón.  
Aquí tienes los comandos más comunes:

| Comando | Qué hace |
|----------|-----------|
| `ls` | Muestra los archivos y carpetas dentro del directorio actual. |
| `cd <directorio>` | Entra en la carpeta indicada. Ejemplo: `cd proyectos` te lleva a la carpeta “proyectos”. |
| `cd ..` | Sube una carpeta hacia atrás. Por ejemplo, de `proyectos/app` a `proyectos`. |
| `mkdir <nombre>` | Crea una nueva carpeta. Ejemplo: `mkdir portfolio`. |
| `rmdir <nombre>` | Borra una carpeta vacía. Si tiene archivos dentro, se usa `rm -r <nombre>` (con cuidado). |
| `code .` | Abre la carpeta actual en **Visual Studio Code**. |
| `ii .` | (Solo en Windows) Abre la carpeta actual en el explorador de archivos. |

---

## 🧩 Comandos básicos de Git

Git es la herramienta que permite **guardar versiones de tu proyecto** y **colaborar con otros desarrolladores** sin perder cambios.

### 🔹 Ramas (branches)

Las ramas sirven para trabajar en nuevas funciones o ideas sin afectar el código principal.

| Comando | Qué hace |
|----------|-----------|
| `git branch` | Muestra todas las ramas del proyecto. |
| `git branch <nombre>` | Crea una nueva rama. Ejemplo: `git branch dev`. |
| `git branch -d <nombre>` | Borra una rama local (usa `-D` para forzar el borrado). |
| `git switch <nombre>` | Cambia a la rama indicada. Ejemplo: `git switch dev`. |

---

### 🔹 Guardar y subir cambios

| Comando | Qué hace |
|----------|-----------|
| `git add <archivo>` | Añade un archivo para guardarlo en el próximo commit. Ejemplo: `git add index.html`. |
| `git add .` | Añade **todos los cambios** del proyecto. |
| `git commit -am "mensaje"` | Guarda los cambios con un mensaje explicando qué hiciste. Ejemplo: `git commit -am "Agregado el formulario de contacto"`. |
| `git merge <rama>` | Fusiona la rama indicada con la actual. Ejemplo: `git merge dev`. |
| `git push origin <rama>` | Sube la rama al repositorio remoto (por ejemplo, GitHub). Ejemplo: `git push origin main`. |

---

## 🧠 Consejos útiles

- Usa nombres claros para tus ramas.  
- Haz commits pequeños y frecuentes. Así es más fácil corregir errores.  
- Escribe mensajes de commit descriptivos.  
- Antes de subir (`push`), asegúrate de haber guardado (`commit`) todo.  
- Si algo se rompe, **Git te permite volver atrás** sin problema.  
