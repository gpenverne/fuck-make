# fuck-make
Override makefile using custom makefile.


## Install
```bash
$ git clone git@github.com:gpenverne/fuck-make.git
$ cd fuck-make
$ sudo cp fmake /usr/bin/fmake
```

## Usage
- First, launch fmake from your project dir to create a `.makefile.override`:
```bash
$ fmake
```

- Edit the `.makefile.override` file, and write custom commands, or override commands, or override variables :)

- Play your make commands using fmake instead of make:
```bash
$ fmake my-command
```
