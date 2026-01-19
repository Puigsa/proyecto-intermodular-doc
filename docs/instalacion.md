---
title: Instalación
nav_order: 3
---

# Instalación

## Requisitos
Antes de su instalación, es preciso contar con:

- Servidor web Apache
- PHP 8.0 o superior
- MySQL
- Navegador web moderno

## Pasos de instalación

1. Clonar el repositorio
2. Importar la base de datos
3. Configurar el archivo `.env`
4. Acceder a la aplicación desde el navegador

### Instalación del servidor web Apache

```bash
sudo apt update
sudo apt install apache2 -y
```
## Variables de entorno
- DB_HOST=localhost
- DB_USER=root
- DB_PASSWORD=contraseña
- DB_NAME=escuela_musica
