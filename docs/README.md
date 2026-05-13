# 📌 Descripción

Este proyecto es una práctica de fundamentos de Linux donde se aprende a crear y gestionar estructuras de carpetas, archivos, permisos y comandos básicos desde terminal.

El objetivo es familiarizarse con la navegación en Linux y operaciones esenciales de sistema de archivos.

# 📂 Estructura del proyecto

~~~Workspace/
├── frontend/
│   └── index.html
├── backend/
│   └── app.js
├── docs/
│   ├── README.md
│   └── styles.css (movido posteriormente)
├── scripts/
│   └── deploy.sh
└── backup/
    └── README.md (copiado desde docs)
~~~

# 🛠️ Comandos utilizados

~~~  
    mkdir workspace - para crear nueva carpeta
    pwd - muestra ruta completa del directorio
    ls - lista el contenido de directorios 
    cd - navegar entre directorios 
    mkdir frontend/ backend/ docs/ scripts/ backup/ -  creación de carpetas 
    touch frontend/index.html backend/server.js docs/README.md scripts/deploy.sh - creación de archivos
    ls scripts
   ls backup
   cp docs/README.md backup/ - copia de archivo
    ls backup
   mv backend/server.js backend/app.js - cambio de nombre del archivo
    ls backend
    mv frontend/styles.css docs/ - mover el archivo styless.css a la carpeta /docs
    ls docs
    chmod 700 scripts/deploy.sh - cambia el permiso para que el propietario solo pueda ejecutar
    chmod 444 docs/README.md - cambia el permiso para que todos lo puedan leer
    ls -l scripts/deploy.sh docs/README.md - ver permisos y detalles de ambas carpetas/archivos
    ls -l
    pwd
    ls -R
    history - comando para ver el historial de comandos utilizados

