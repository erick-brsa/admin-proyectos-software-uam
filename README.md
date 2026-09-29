# Administración de Proyectos de Software

## Requisitos

- Docker Desktop
- WSL
- Virtualización Activida (administrador de tareas > CPU > virtualización)

## Instrucciones

1. Abrir Docker Desktop
2. Ingresar al directorio en el cual tenemos compose.yaml y Dockerfile
3. Ejecutar los siguientes comandos:
```bash
docker --version
docker compose up -d
docker compose exec db bash
```

Ahora nos encontramos en la consola del contenedor o máquina virtual, ahora podemos ingresar a postgre

```bash
psql -U proyecto -h localhost
```

