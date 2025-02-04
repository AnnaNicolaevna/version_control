# Инструкция по работе с текстовым редактором Markdown

## Заголовки

Чтобы поместить текст в заголовок документа, необходимо перед ним поставить знак "#", а перед заголовками разделов первого уровня необходимо поставить "##".

## Перенос текста на новую строку

Чтобы текст начался с новой строки, необходимо писать его, пропуская пустую строчку.
Если не пропустить одну пустую строчку, то текст продолжится на этой же строке.

## Выделение текста

Чтобы выделить тукст курсивом, надо поставить слева и справа "*", вот так *курсив*.
Или поставить по знаку нижнего пробела "_", вот так _курсив_.

## Списки

Чтобы создать ненумерованный список, необходимо с каждой новой строки перед текстом ставить "*", вот так:
* Элемент 1
* Элемент 2
* Элемент 3

Чтобы создать нумерованный список, необходимо пронумеровать каждую строку, вот так:

1. Элемент 1

2. Элемент 2

3. Элемент 3

## Изображения

Чтобы вставить в текст изображение, необходимо поставить восклицательный знак и скобки, прямые и круглые, в прямых указать текст, который будет отображаться, если картинка не выведется, а в круглых указать имя файла изображения. Изображение размещают в той же папке, где инструкция, только чтобы оно не занимало места, его затем помещают в файл, который Гит игнорирует. Например,

![здесь должна быть картинка](image.jpg)

## Работа с удаленными репозиториями

1. Выбрать уделённо расположенный чужой епозиторий, с которым мы хотим работать (например, в который мы хотим предложить изменения)

2. Создать свой аккаунт на GitHub.com и  свой удалённый репозиторий

3. Создать свой локальный репозиторий

4. "Подружить" свой локальный и удалённый репозитории

5. Чтобы полностью "списать" удалённый репозиторий в свой локальный (нужно чтоб чужой имел свойство public), клонируем его, т.е. набираем git clone и указываем адрес удалённого репозитория (он под кнопкой kode)

6. Чтобы работать с удалённым репозиторием.

6.1. Сначала на сайте GitHub нажать кнопку Fork, это мы "сфоркаем" чужой репозиторий в свой аккаунт на GitHub, сделаем ответвление для своей версии. Он будет такой же как "родной" исходник на тот момент, но уже наша копия. Уже с ним мы можем работать. 

6.2. Командой git pull берем его к себе из своего удалённого репозитория на GitHub в локальный, внесем какие-то изменения, зафиксируем их коммитами, чтобы можно было отслеживать.  

6.3. Дальше нужно отправить (push) из своего локального репозитория в свой удалённый на GitHub, а уже оттуда можно предложить свои изменения в чужой репозиторий. 

6.4. Для этого надо на сайте GitHub нажать кнопку Pull Request, тогда в чужом репозитории увидят предложения и смогут их рассмотреть и решить, принимать или нет.