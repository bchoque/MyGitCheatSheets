# Aprendiendo comandos Git

![Logo](https://git-scm.com/images/logo@2x.png)

Para todo comando ejecutado en la terminal debe antecederle siempre la palabra clave `git`:

##### Ejemplo (Ubuntu):

```bash
$ git [comando]
```

## Comandos básicos

### Versión de Git
Muestra la versión de Git instalada en nuestro ordenador:

##### Sintaxis:
```bash
git [-v | --version]
```
Para obtener esta `información` podemos usar (02) tipos de comandos:

| Comando     | Tipo       | 
| :---------- | :--------- | 
| `-v`        | abreviado  |
| `--version` | extendido  |

##### Ejemplo (Ubuntu):
```bash
$ git --version
git version 2.43.0
```
### Crear u obtener un repositorio
Podemos crear (`inicializar`) un repositorio o tambien es posible obtener (`clonar`) un repositorio desde algun gestor de repositorios de internet ([GitHub](https://github.com/), [GitLab](https://about.gitlab.com/) u otros).

#### Inicializar un repositorio (init)
Permite crear un repositorio en un nuevo directorio o inicializar el repositorio sobre un directorio ya existente.

##### Sintaxis:
```bash
$ git init [<directorio>]
```
Es posible iniciar un repositorio en un nuevo directorio.

##### Ejemplo:
```bash
$ git init mi-nuevo-directorio

```

## Autor
- [@bchoque](https://github.com/bchoque/)

