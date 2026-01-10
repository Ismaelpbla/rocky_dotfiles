NOTAS DE DESARROLLO

- Para enlazar un archivo de configuración (por ejemplo zsh) con el que tenemos en nuestro equipo local utilizaremos un enlace simbolico
```console
ln -s ~/dotfiles/zsh/zshrc ~/.zshrc
```
Esto permite sincronizar ambos archivos, de tal forma que si modificamos el archivo original, modificaremos tambien el enlace simbolico.

- Para gestionar los plugins de tmux debemos clonar el repositorio de Tmux Plugin Manager en el archivo .tmux.config de nuestro entorno local
```console
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```