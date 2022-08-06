---
title: misAlias
description: Archivo alias con los comandos que más utilizo.
author: Daniel G. Samborski
---
Para cargar el archivo de alias al abrir la terminal, se deberá colocar lo siguiente en el archivo RC correspondiente. (`.bashrc`, `.zshrc`, etc...)

```sh
###
# Mi archivo de alias.
[[ -f ~/alias ]] && . ~/alias  # Utilizar el archivo de alias.
```

Luego debe cerrar la terminal y volver a abrirla para que los alias se carguen.

> Si se quiere tener el archivo `alias` oculto, se debe renombrar a `.alias` y cambiar lo siguiente:

```sh
###
# Mi archivo de alias.
[[ -f ~/.alias ]] && . ~/.alias  # Utilizar el archivo de alias.
```
