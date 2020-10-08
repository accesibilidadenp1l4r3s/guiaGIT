# Instalación de git

Como ya se dijo git es software libre y es multiplataforma, se puede descargar desde el [sitio oficial](https://git-scm.com/downloads)

## Instalación en GNU/Linux

En general instalar paquetes en GNU/Linux es muy sencillo dado que cada distribución cuenta con repositorios oficiales y gestores de instalación muy robustos.

En **Arch Linux** y derivados

```
# sudo pacman -Syu git
```

En **Debian y derivados**

```
# sudo apt install git
```

## Instalación en Windows

En el caso de windows es necesario descargar el instalador del siguiente [enlace](https://git-scm.com/download/win).

Una vez descargado el ejecutable dar doble click sobre el y seguir las instrucciones.

(Basicamente, descarga el ejecutable y presiona next... next... next...).

## Instalación de una interfase gráfica

La forma más directa de trabajar con Git es por medio de comandos, sin embargo también es posible hacerlo con una GUI (Interfase Grafica de Usuario).

Git viene de forma predeterminada con una interfase gráfica sencilla, **git-gui** o **gitk** dependiendo del sistema operativo en el que se instaló.

En este [enalce](https://git-scm.com/downloads/guis) se encuentran diferentes muchas otras alternativas de interfases graficas para git.

En la próxima entrega clonaremos nuestro primer repositorio, que justamente es este con el que estamos trabajando.

[03 Clonar](../03clonar)
