# 🥔 Potato

Potato is a little utility script to boost yout potato PC / laptop.

This is to be taken as a joke of course, the main purpose of this script is to display funny fake logs of installing weird features that are totally useless or impossible.

# Install

Simply run the install script:

```sh
> sudo ./install
```

This will copy potato in `/usr/local/bin/`, which should be in your PATH. If not, simply run the following:

```sh
> export PATH=$PATH:/usr/local/bin
```

After that, potato is ready to use ! You can now head over the [how to use](#how-to-use) section.

## Uninstall

To remove potato, simply delete the potato script located in `/usr/local/bin/`. The installer can handle this for you by running:

```sh
> sudo ./install -r 
```

# How to use

Typing `potato` with no arguments in your shell will display the global usage :

```sh
> potato
Potato laptop booster
Commands:
    add-ram <size>          Increase the amount of ram by <size> Gb
    enable-shell-rtx        Enable ray-traced shell
    increase-resolution     Change screen resolution to 4K
    add-cores               Increase CPU core count
    add-cpu <count>         Add <count> CPUs to the system
    add-gpu                 Add a GPU to the system
    increase-disk <size>    Increase disk space by <size> Tb
    optimize                Run various optimizations
```

There are several features available, feel free to try them all !