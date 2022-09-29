# APP_Interactiva_backend_crud

El API APP_Interactiva_backend_crud proporciona interfaces para la manipulación (CRUD) de los datos almacenados en una base de datos relacional postgresql. 

## Especificaciones Técnicas

### Tecnologías Implementadas y Versiones

- [Golang](https://github.com/udistrital/introduccion_oas/blob/master/instalacion_de_herramientas/golang.md)
- [BeeGo](https://github.com/udistrital/introduccion_oas/blob/master/instalacion_de_herramientas/beego.md)
- [Docker](https://docs.docker.com/engine/install/ubuntu/)
- [Docker Compose](https://docs.docker.com/compose/)

### Variables de Entorno

```shell
# Ejemplo que se debe actualizar acorde al proyecto
```

### Ejecución del Proyecto

```shell
#1. Obtener el repositorio con Go
go get github.com/udistrital/plan_cuentas_mid

#2. Moverse a la carpeta del repositorio
cd $GOPATH/src/github.com/udistrital/plan_cuentas_mid

# 3. Moverse a la rama **develop**
git pull origin develop && git checkout develop
bee run

```
## Arquitectura

![](arquitectura.png)

## Dependencias Utilizadas

### CLIENTES

## Estado CI

| Develop | Release 1.0.1 | Master |
| -- | -- | -- |
| [![Build Status](https://hubci.portaloas.udistrital.edu.co/api/badges/udistrital/plan_cuentas_mid/status.svg?ref=refs/heads/develop)](https://hubci.portaloas.udistrital.edu.co/udistrital/plan_cuentas_mid) | [![Build Status](https://hubci.portaloas.udistrital.edu.co/api/badges/udistrital/plan_cuentas_mid/status.svg?ref=refs/heads/release/1.0.1)](https://hubci.portaloas.udistrital.edu.co/udistrital/plan_cuentas_mid) | [![Build Status](https://hubci.portaloas.udistrital.edu.co/api/badges/udistrital/plan_cuentas_mid/status.svg?ref=refs/heads/master)](https://hubci.portaloas.udistrital.edu.co/udistrital/plan_cuentas_mid) |
