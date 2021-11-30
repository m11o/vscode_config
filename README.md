# vscode_config

Configures of vscode for my development.

# How to use

## case1: use Make

```shell
$ make mac_build  # for mac
```

## case2: manually build

### git clone

```shell
$ git clone `this repogitory`
```

### add synbolic link

```shell
$ cd ~/Library/Application Support/Code/User

# if there settings.json and keybindings.json, these're removed
$ rm settings.json
$ rm keybindings.json

# add symbolic link
$ ln -s settings.json /this/repository/path/settings.json
$ ln -s keybindings.json /this/respository/path/keybindings.json
```

### save extensions

```shell
$ code --list-extensions > extensions
```
