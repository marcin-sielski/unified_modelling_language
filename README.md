# Unified Modeling Language

This repository in playground for UML.

## Install Dependencies

```bash
sudo apt update
```

```bash
sudo apt upgrade
```

```bash
sudo apt install pylint3
```

```bash
pip3 install playsound
```

## Install UML Tools Under Ubuntu/Debian

* Visual Studio Code

```bash
wget https://go.microsoft.com/fwlink/?LinkID=760868 -O code-amd64.deb

```

```bash
sudo apt install ./code-amd64.deb
```

* diagrams.net

```bash
wget https://github.com/jgraph/drawio-desktop/releases/download/v20.8.16/drawio-amd64-20.8.16.deb \
    -O drawio-amd64.deb
```

```bash
sudo apt install drawio-amd64.deb
```

## Download Repository And Run Oven Model Example

```bash
git clone https://github.com/marcin-sielski/unified-modeling-language.git
```

```bash
cd unified-modeling-language
```

```bash
python3 oven/src/oven.py
```

## Generate UML Class Diagrmas From Source Code

```bash
cd oven/doc && pyreverse3 -o png ../src/oven.py
```

## Oven Documentation

![Oven UML diagrams](https://github.com/marcin-sielski/unified-modeling-language/blob/main/oven/doc/oven.drawio.png)

![Oven UML class diagrams](https://github.com/marcin-sielski/unified-modeling-language/blob/main/oven/doc/classes.oven.png)

## License

MIT License

Copyright (c) 2023 Marcin Sielski <marcin.sielski@gmail.com>
