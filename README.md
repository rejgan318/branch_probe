# Игры с коммитами, ветками и релизами

## Пролог

Создаю стартовый коммит, начало разработки

## Проверяю 2 коммита с одним пушем

- Коммит 1
- Коммит2 и пуш

**Вердикт на птичьем**: Незапушенные коммиты пушатся позже с последним запушенным коммитом. 
Или пуш можно делать не так часто как коммит

## Branch
Создал в Pycharm новую ветку `feature/step1`. В косоли git это сделалось 
```
checkout -b feature/step1 master^0 --
M	README.md
```

### Коммит feature step1-1
...

### Коммит feature step1-2
...

### Попытался сделать merge

```
git checkout master
git merge feature/step
git push origin master
```
В результате ветка feature/step1 пропала, полностью перетекла в master.
Хочется сохранить красивое ветвление, но его нет
## Branch - вторая попытка

### step2-1
### step2-2

After merge2

## Branch2 - pull request через github

### step3-1
### step2-2
