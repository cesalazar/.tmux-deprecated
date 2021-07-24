# .tmux-deprecated
My deprecated tmux configuration, including plugins. Replaced by
https://github.com/cesalazar/.tmux, a fork of https://github.com/gpakosz/.tmux
to include my customizations.

```
PROJECT_NAME=.tmux-deprecated git clone https://github.com/cesalazar/${PROJECT_NAME} \
&& cd ${PROJECT_NAME} && git submodule update --init \
&& ln -s "$(pwd)/.tmux.conf" ~/.
```
