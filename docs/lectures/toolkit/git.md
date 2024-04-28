# Tutorial de Git

## Introducción a Git

Git es un sistema de control de versiones distribuido que permite a los desarrolladores llevar un registro de los cambios en sus proyectos de software. Facilita la colaboración, el seguimiento de versiones y la gestión de código de manera eficiente.

## Instalación de Git

### Windows

1. Descarga el instalador desde [git-scm.com](https://git-scm.com/).
2. Ejecuta el instalador y sigue las instrucciones del asistente de instalación.
3. Abre el terminal de Git Bash para usar Git.

### macOS

1. Instala Git a través de Homebrew:
   ```bash
   brew install git
   ```

2. Verifica la instalación:
   ```bash
   git --version
   ```

### Linux (Ubuntu/Debian)

1. Instala Git desde el repositorio oficial:
   ```bash
   sudo apt update
   sudo apt install git
   ```

2. Verifica la instalación:
   ```bash
   git --version
   ```

## Configuración de Git

Antes de comenzar a usar Git, configura tu nombre de usuario y dirección de correo electrónico.

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

## Conceptos Básicos de Git

### Inicialización de un Repositorio

Para iniciar un nuevo repositorio Git en tu proyecto existente:

```bash
cd /ruta/al/proyecto
git init
```

### Ciclo Básico de Trabajo

1. **Agregar Archivos al Área de Preparación**

   Para agregar todos los archivos modificados y nuevos al área de preparación:

   ```bash
   git add .
   ```

2. **Confirmar Cambios**

   Para confirmar los cambios en tu repositorio:

   ```bash
   git commit -m "Mensaje del commit"
   ```

### Revisión de Historial y Estado

1. **Ver el Estado del Repositorio**

   Para ver qué archivos han cambiado y están listos para ser confirmados:

   ```bash
   git status
   ```

2. **Ver el Historial de Confirmaciones**

   Para ver el historial de confirmaciones:

   ```bash
   git log
   ```

### Ramas en Git

1. **Crear una Nueva Rama**

   Para crear una nueva rama y cambiarte a ella:

   ```bash
   git branch nombre_rama
   git checkout nombre_rama
   ```

2. **Fusionar Ramas**

   Para fusionar una rama específica en la rama actual:

   ```bash
   git merge nombre_rama
   ```

### Repositorios Remotos

1. **Agregar un Repositorio Remoto**

   Para agregar un repositorio remoto:

   ```bash
   git remote add origin url_del_repositorio
   ```

2. **Enviar Cambios al Repositorio Remoto**

   Para enviar tus cambios al repositorio remoto:

   ```bash
   git push -u origin nombre_rama
   ```

3. **Clonar un Repositorio Remoto**

   Para clonar un repositorio existente a tu máquina local:

   ```bash
   git clone url_del_repositorio
   ```

### Resolución de Conflictos

Si hay conflictos durante la fusión de ramas, Git te informará. Deberás editar los archivos para resolver los conflictos manualmente y luego confirmar los cambios.

## Conclusiones

¡Has completado el tutorial completo de Git! Ahora tienes una comprensión básica de cómo usar Git para gestionar tu código de manera efectiva, colaborar con otros desarrolladores y mantener un historial de versiones de tus proyectos.

