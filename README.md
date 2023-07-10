usage:
```bash
git clone https://github.com/shapled/spacemacs-config.git ~/.spacemacs
```

## Setup Spacemacs

1. install emacs
2. download spacemacs

    ```bash
    git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d
    ```

3. open emacs to install packages
4. remove default config of spacemacs

    ```bash
    rm -f ~/.spacemacs
    ```

5. download custom config

    ```bash
    git clone https://github.com/shapled/spacemacs-config.git ~/.spacemacs.d
    ```

6. set environment and eval it

    ```bash
    # ~/.bashrc
    export SPACEMACSDIR=$HOME/.spacemacs.d

    # eval
    source ~/.bashrc
    ```

6. reopen emacs && enjoy it.
