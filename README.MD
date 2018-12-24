Este comando crea el nuevo repositorio en Documents/Repos, si desea cambiar la ruta ingrese en el archivo mkrepo y modifique

Mover la carpeta GitInit a Documents.

**Instalar hub con el comando**

~~~
     brew install hub
~~~

Cualquier duda, [Documentacion de hub](https://github.com/github/hub)

**Agregar la funcion al perfil del bash**

Si esta instalado zsh
~~~
     cat mkrepo >> ~/.zshrc
~~~
Despues usar nano .zshrc y ver que modificaciones hacer respecto a los paths


Si no tienes instalado zsh:
~~~
     cat mkrepo >> ~/.bash_profile
~~~
Despues usar nano .bash_profile y ver que modificaciones hacer respecto a los paths
