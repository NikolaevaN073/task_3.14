[<< К Содержанию](./readme.md)

## git pull

**git pull** - является объединением двух последовательных команд [git fetch](fetch.md) и [git merge](merge.md).

Команда *git pull* сразу забирает изменения и проводит слияние с активной веткой. Забирает из репозитория, для которого были созданы удаленные ветки по умолчанию:

```bush=
git pull
```

Забирает изменения и метки из определенного репозитория:

```bush=
git pull username-project --tags
```
