# 🐳 Docker Multi Database Development Environment

Este proyecto proporciona un entorno de desarrollo con múltiples bases de datos usando Docker, ideal para trabajar con aplicaciones backend (por ejemplo .NET 8, Laravel, Node.js, etc.).

---

## 📦 Servicios incluidos

- MySQL
- PostgreSQL
- SQLserver

*(Puedes extenderlo fácilmente con Redis, pgAdmin, etc.)*

---

## ⚙️ Requisitos

Antes de comenzar asegúrate de tener instalado:

- Docker
- Docker Compose

Verifica con:

```bash
docker --version
docker compose version
```

##  Uso (clonación)
```bash
git clone https://github.com/TU_USUARIO/TU_REPO.git
cd TU_REPO
```

##  Configuracion variables de entorno
Generar en archivo ".env" para configurar las variables de entorno que configuran las conexiones, dentro de este archivo se configura contraseña db por default.
```bash
cp .env.example .env
```


##  Levantar el contenedor
Desde la carpeta o raiz del repositorio ejectar el siguiente comando.
```bash
docker compose up -d
```

##  Verificar funcionamiemto del  contenedor
Desde la carpeta o raiz del repositorio ejectar el siguiente comando.
```bash
docker compose ps
```
