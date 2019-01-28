# fuck-make
Override makefile using custom makefile.


## Install
### Copy the fmake binary:
```bash
$ git clone git@github.com:gpenverne/fuck-make.git
$ sudo cp ./fuck-make/binaries/fmake /usr/bin/fmake
```

### Or install using .deb file
```bash
$ git clone git@github.com:gpenverne/fuck-make.git
$ sudo dpkg -i ./fuck-make/binaries/fmake.deb
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
