# Установка Node-red и IOT control center

Есть два способа установки Node-red. Попробуйте первый, если не выйдет, попробуйте второй

## Установка Node-red (способ 1, прямая, <500 мб)

1\) Скачайте и установите Node.js (кнопка Get Node.js, затем кнопка Windows installer): [https://nodejs.org/en/](https://nodejs.org/en/). При установке согласитесь со всем предлагаемым, в т.ч. нажмите галочку "install necessary tools":

<figure><img src="../.gitbook/assets/image (247).png" alt=""><figcaption></figcaption></figure>

После основной части установки появится окно PowerShell, в котором установится несколько пакетов. Дождитесь, пока это окно пропадет (либо там будет написано, что все установлено, либо там несколько раз подряд будет появляться одна и та же строчка с ошибкой)

2\) Откройте командную строку. Напишите и выполните команду:

```
node --version && npm --version
```

Это проверка установки node js. Если все ок, то увидите что-то типа:

```
v18.15.0
9.5.0
```

3\) Установка Node-red. Для этого в командной строке выполните команду:

```
npm install -g --unsafe-perm node-red
```

4\) готово. Теперь вы можете запустить node-red как в "Смене" (откройте командную строку и выполните node-red или нажмите на пуск, напишите node-red и нажмите enter)

5\) зайдите в веб-интерфейс. Для этого откройте браузер и запустите localhost:1880

6\) устанавливаем библиотеки

## Установка Node-red (способ 2, на виртуальную машину, 8 гб)

1\) Скачайте файл (образ системы с уже установленным node-red и библиотеками) [https://drive.google.com/file/d/1AfVdII33FMgfsmDHc1MqGLo\_tSIbCCd5/view?usp=drive\_link](https://drive.google.com/file/d/1AfVdII33FMgfsmDHc1MqGLo_tSIbCCd5/view?usp=drive_link)

2\) Скачайте и установите Virtual Box [https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads) (в левой части экрана ссылка Windows hosts)

3\) Откройте Virtual Box. В интерфейсе нажмите кнопку Import:

<figure><img src="../.gitbook/assets/image (246).png" alt=""><figcaption></figcaption></figure>

4\) В открывшемся окне выберите файл .ova скачанный в пункте 1
