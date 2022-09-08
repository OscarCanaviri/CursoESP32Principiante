# Uso básico de GIT y markdown
## Creación de clave SSH

ingresar mediante GIT Bash console y crear este archivo

```
$ ssh-keygen -t ed25519 -C "oscarcanaviriv@gmail.com"

```

> https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

agregar a la configuración inicial el nombre del usuario y el correo electronico

```
git config --global user.email "oscarcanaviriv@gmail.com"

git config --global user.name "Oscar Canaviri"
```


## Como copiar proyectos desde Github

Acceder a la carpeta local donde se guarda los proyectos de Github

Copiar la dirección del navegador 
![Direccion de Navegador](/imagenes/imagen.png)

Escribir en la consola GIT 

```
$ git clone git@github.com:OscarCanaviri/PasosBasicosParaUtilizarGIT.git

```

