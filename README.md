# tmux-config

tmux config including tpm

Screenshot ToDo

## Dependencies

Mac OS

```bash
brew install tmux-mem-cpu-load
```

Linux build from source:

```bash
git clone https://github.com/thewtex/tmux-mem-cpu-load
cd tmux-mem-cpu-load
mkdir build && cd build
cmake ..
sudo make install
```

## Installation

1. clone this repo to .tmux

    ```bash
    git clone https://github.com/nwesem/tmux-config .tmux
    # or ssh
    git clone git@github.com:nwesem/tmux-config.git .tmux
    ```

1. install tmux plugin manager

    ```bash
    git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
    ```

1. link .tmux.conf to home

    ```bash
    ln -s ~/.tmux/.tmux.conf ~/.tmux.conf
    ```

1. if in tmux session source file

    ```bash
    tmux source ~/.tmux.conf
    ```

1. Now tap the rewritten key bindings `CTRL + a` + `I` to install all plugins

1. Done :grin:
