code
Code
Iniciar un Repositorio
Para empezar a rastrear un proyecto con Git.
code
Bash
# Iniciar un repositorio nuevo en una carpeta existente
git init
El Flujo de Trabajo Básico
El ciclo más común en Git es: modificar archivos, añadirlos al "staging area", y confirmar los cambios.
1. Ver el estado:
Muestra qué archivos han sido modificados.```bash
git status
code
Code
**2. Añadir archivos al Staging Area:**
Prepara los archivos para el próximo "commit".
```bash
# Añadir un archivo específico
git add nombre_del_archivo.txt

# Añadir todos los cambios en el directorio actual
git add .
3. Confirmar los cambios (Commit):
Guarda una "instantánea" de los cambios en el historial del proyecto.
code
Bash
git commit -m "Un mensaje descriptivo de los cambios"
Trabajar con Repositorios Remotos
Para colaborar o tener una copia de seguridad en servicios como GitHub.
1. Clonar un repositorio existente:
code
Bash
git clone https://github.com/usuario/repositorio.git
2. Enviar cambios al remoto (Push):
Sube tus commits al repositorio remoto.
code
Bash
git push origin main
3. Recibir cambios del remoto (Pull):
Descarga y fusiona los cambios de otros.
code
Bash
git pull origin main