# Домашнее задание к занятию "`8 Git`" - ᗩᒪE᙭ᗩᑎᗪEᖇ ZᗩᖇIᑭOᐯ


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
________________________________________


### Задание 1
Что нужно сделать:
1.	Зарегистрируйте аккаунт на GitHub.

![img](https://github.com/alzarman/gitlab-hw/blob/main/img/scr_61.png)

2.	Создайте публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».
3.	Склонируйте репозиторий, используя https протокол git clone ....
4.	Перейдите в каталог с клоном репозитория.
5.	Произведите первоначальную настройку Git, указав своё настоящее имя и email: git config --global user.name и git config --global user.email johndoe@example.com.
6.	Выполните команду git status и запомните результат.

![img](https://github.com/alzarman/gitlab-hw/blob/main/img/scr_65.png)

7.	Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.

![img](https://github.com/alzarman/gitlab-hw/blob/main/img/scr_63.png)

8.	Ещё раз выполните git status и продолжайте проверять вывод этой команды после каждого следующего шага.

![img](https://github.com/alzarman/gitlab-hw/blob/main/img/scr_64.png)

9.	Посмотрите изменения в файле README.md, выполнив команды git diff и git diff --staged.

![img](https://github.com/alzarman/gitlab-hw/blob/main/img/scr_71.png)

10.	Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой git add README.md.

![img](https://github.com/alzarman/gitlab-hw/blob/main/img/scr_78.png)

11.	Ещё раз выполните команды git diff и git diff --staged.

![img](https://github.com/alzarman/gitlab-hw/blob/main/img/scr_81.png)

12.	Теперь можно сделать коммит git commit -m 'First commit'.

![img](https://github.com/alzarman/gitlab-hw/blob/main/img/scr_82.png)

13.	Сделайте git push origin master.

![img](https://github.com/alzarman/gitlab-hw/blob/main/img/scr_83.png)

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

https://github.com/alzarman/githubdz/commit/1e232ffbe65185f3497165753fc7d32e0ddd5ced

https://github.com/alzarman/githubdz
________________________________________


### Задание 2
Что нужно сделать:
1.      Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
2.      Добавьте файл .gitignore в следующий коммит git add....

![img](https://github.com/alzarman/gitlab-hw/blob/main/img/scr_89.png)

3.      Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.
4.      Сделайте коммит и пуш.
В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

https://github.com/alzarman/githubdz/commit/568fc93ba13926677c5a397c01616c2fb1fdfa6b

________________________________________


### Задание 3
Что нужно сделать:
1.	Создайте новую ветку dev и переключитесь на неё.
2.	Создайте файл test.sh с произвольным содержимым.
3.	Сделайте несколько коммитов и пушей, имитируя активную работу над этим файлом.
4.	Сделайте мердж этой ветки в основную. Сначала нужно переключиться на неё, а потом вызывать git merge.
5.	Сделайте коммит и пуш.
В качестве ответа прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.

https://github.com/alzarman/githubdz/network
________________________________________

   
