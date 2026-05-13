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
    mkdir workspace
    pwd
    ls
    cd
    mkdir frontend backend docs scripts backup
    touch frontend/index.html backend/server.js docs/README.md scripts/deploy.sh
    ls scripts
   ls backup
   cp docs/README.md backup/
    ls backup
   mv backend/server.js backend/app.js
    ls backend
    mv frontend/styles.css docs/
    ls docs
    chmod 700 scripts/deploy.sh
    chmod 444 docs/README.md
    ls -l scripts/deploy.sh docs/README.md
    ls -l
    pwd
    ls -R
    history

