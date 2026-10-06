# Resumen Personal de Comandos Git

### 1. `git status`
Muestra el estado actual del repositorio: qué archivos han sido modificados, cuáles están preparados para el siguiente commit (staging) y cuáles no están siendo rastreados (untracked).

### 2. `git add`
Envía archivos a la zona de preparación (staging area). Le indica a Git qué cambios específicos se incluirán en la siguiente "fotografía" o commit.

### 3. `git commit`
Guarda una instantánea permanente de los cambios preparados en el historial local, acompañada de un mensaje descriptivo que explica lo que se hizo.

### 4. `git push`
Sube y sincroniza los commits locales con el repositorio remoto en GitHub para que los demás puedan verlos.

### 5. `git pull`
Descarga e integra automáticamente los cambios más recientes del repositorio remoto de GitHub en el repositorio local.

### 6. `git log`
Muestra el historial cronológico de commits realizados, incluyendo sus identificadores (hash), autores, fechas y mensajes.

### 7. `git diff`
Compara el estado actual de los archivos en el directorio de trabajo contra lo que está preparado en staging, mostrando línea por línea qué cambió.

### 8. `git restore`
Descarta cambios no preparados en un archivo regresándolo al estado del último commit, o restaura un archivo que fue borrado accidentalmente.

### 9. `git restore --staged`
Saca un archivo de la zona de preparación (staging area) sin borrar el contenido que se editó; vuelve a dejar el cambio como pendiente de preparar.
