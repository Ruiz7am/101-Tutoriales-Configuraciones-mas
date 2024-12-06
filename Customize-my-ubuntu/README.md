# Personaliza tu Ubuntu Desktop

1. Extensiones
2. Apariencia.
    - Instalar temas.
  

## 1. Extensiones

Para poder comenzar con la customización de mi Ubuntu Desktop, necesito instalar algunas extensiones. Para eso necesitamos instalar unos programitas que nos ayudaran a gestionar estas extensiones.

### Instalar Flatpak

Flatpak es un gestor de paquetes de software de uso libre y open source, desarrollado por una comunidad independiente. De los repositorios de flatpak descargaremos los gestores de extensiones.

Para instalarlo, nos vamos a una terminal e instalamos flatpak:

```console
sudo apt install flatpak
```

Si lo deseamos podemos instalar la interfaz gráfica para instalar apps sin la terminal:

```console
sudo apt install gnome-software-plugin-flatpak
```

Por último agregamos el repositorio flathub:

```console
flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
```

Y ya estamos listos para instalar apps.

### Instalar gestores de extensiones

Aquí podemos hacerlo de dos formas, desde terminal o desde la interfaz gráfica. A mi me gusta hacerlo desde la terminal, se me facilita y considero que es mas rapido.


Instalamos el gestor de extensiones de gnome

```console
sudo flatpak install org.gnome.Extensions
```



## Instalación de temas