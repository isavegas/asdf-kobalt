# asdf-kobalt

A simple plugin for [ASDF](https://github.com/HashNuke/asdf) to add the [Kobalt](https://github.com/cbeust/kobalt) build tool.


## Install

```
asdf plugin-add kobalt https://github.com/isavegas/asdf-kobalt.git
```

## Use

```
asdf install kobalt 1.0.114
asdf global kobalt 1.0.114

mkdir kotlin_project
cd kotlin_project
kobaltw --init kotlin

kobaltw run
```
