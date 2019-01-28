# fuck-make
Override makefile using custom makefile.


## Install
### Copy the fmake binary:
```bash
$ wget https://github.com/gpenverne/fuck-make/raw/master/binaries/fmake
$ sudo mv ./fmake /usr/bin/fmake
```

### Or install using apt-get
```bash
$ echo "deb https://github.com/gpenverne/fuck-make/binaries ./" | sudo tee --append /etc/apt/sources.list.d/fuck-make
$ sudo apt-get update
$ sudo apt-get install fuck-make
```

### Or install using .deb file
```bash
$ wget https://github.com/gpenverne/fuck-make/raw/master/binaries/fmake.deb
$ sudo dpkg -i ./fmake.deb && rm ./fmake.deb
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
