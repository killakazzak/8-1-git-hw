# Домашнее задание к занятию "`Git`" - `Тен Денис`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

#### Создание репозитория
![Создание репозитория](https://github.com/killakazzak/8-1-git-hw/blob/main/img/2024-02-28_16-32-21.jpg)

```
git clone https://github.com/killakazzak/netology.git
```
![(https://github.com/killakazzak/8-1-git-hw/blob/main/img/1.jpg)](https://github.com/killakazzak/8-1-git-hw/blob/main/img/1.png)
```
git config --global user.name "Denis Ten"
git config --global user.email "denis.a.ten@gmail.com"
git status
```
![](https://github.com/killakazzak/8-1-git-hw/blob/main/img/2.png)
```
echo "Hello World!" >> README.md
git status
```
![](https://github.com/killakazzak/8-1-git-hw/blob/main/img/3.png)
```
git diff
```
![](https://github.com/killakazzak/8-1-git-hw/blob/main/img/4.png)

```
git add README.md
git diff --staged
git status
```
![](https://github.com/killakazzak/8-1-git-hw/blob/main/img/6.png)
```
git commit -m 'First commit'
```
![](https://github.com/killakazzak/8-1-git-hw/blob/main/img/7.png)
![](https://github.com/killakazzak/8-1-git-hw/blob/main/img/8.png)
```
git remote set-url origin https://killakazzak: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@github.com/killakazzak/netology.git
git push origin main
```
![](https://github.com/killakazzak/8-1-git-hw/blob/main/img/9.png)

[Ссылка на commit](https://github.com/killakazzak/netology/commit/22f3d2506c1b15c3ab6f0682a188c405f8e54892)

---

### Задание 2

```
touch .gitignore
git status
```
```
git add .gitignore
git status
```
```
echo "*.pyc" >> .gitignore && echo "cache/" >> .gitignore
```
```
git add .gitignore
git commit -m "Second Commit"
```
```
git push origin main
```

[Ссылка на README.md](https://github.com/killakazzak/netology/blob/0d2269d19d0a4587a9e5c471208812acfdc84ecc/README.md)

### Задание 3

`Приведите ответ в свободной форме........`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`

### Задание 4

`Приведите ответ в свободной форме........`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`
