# nephila

Nephila is subprojects pack for staic single page web application.

## How to add

```shell
git submodule add https://github.com/wraith13/nephila nephila
git submodule update --recursive --merge --init
```

## How to update

```shell
cd ./nephila
git pull -f
cd ..
git submodule update --recursive --merge --init
```

## How to remove

```shell
git submodule deinit -f nephila
git rm -f nephila
rm -rf .git/modules/nephila
```

## Subprojects

|subproject|description|
|---|---|
|[build.js](https://github.com/wraith13/build.js)|node.js based builder.|
|[evil-commonjs](https://github.com/wraith13/evil-commonjs)|evil-commonjs is a simple commonjs implement.|
|[minamo.js](https://github.com/wraith13/minamo.js)|minamo.js is a necessary and sufficient and simple JavaScript/TypeScript library.|
|tektite.js|...|

## Projects using this subprojects pack

- [Cyclic ToDo](https://github.com/wraith13/cyclic-todo) (via nephila )
- [Clockworks](https://github.com/wraith13/clockworks) ( via nephila )
