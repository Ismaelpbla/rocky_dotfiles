NOTAS DE DESARROLLO

- Para enlazar un archivo de configuración (por ejemplo zsh) con el que tenemos en nuestro equipo local utilizaremos un enlace simbolico
```console
ln -s ~/dotfiles/zsh/zshrc ~/.zshrc
```
Esto permite sincronizar ambos archivos, de tal forma que si modificamos el archivo original, modificaremos tambien el enlace simbolico.

