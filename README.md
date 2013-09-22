#GUI для Tox на языке ObjectPascal.

Разработка кроссплатформенного GUI для мессенджера Tox на языке ObjectPascal. В качестве компилятора используется FreePascal в составе Lazarus. Код проекта также полностью совместим с Delphi 7 и Delphi XE3 и новее.

## Графический интерфейс
Цель данного проекта - разработать настраиваемый графический интерфейс, который выглядит одинаково под разными платформами. Изначально хочется разработать GUI полностью похожий на тот, который представлен на официальном сайте проекта: http://tox.im/. Как он будет выглядеть, можно посмотреть на этом шаблоне: http://tox.im/assets/ss.png

## Скриншот
Добавлю, как только будет что показать.

## Взаимодействие
Разрабатываемое приложение взаимодействует с Tox по средствам загрузки его из скомпилированной библиотеки DLL (Windows) SO (Linux).

## Разработка / TODO
* заголовочный файл для взаимодействия с библиотекой Tox [почти завершено]
* класс-обертка над заголовочным файлом [разрабатывается]
* виджет состояния пользователя [почти завершено]
* список друзей [в планах]
* панель быстрого доступа [почти завершено]
* виджет чата [в планах]
* поддержка множества языков [в планах]
* поддержка Unicode в GUI [разрабатывается]
* поддержка настраиваемых смайлов [в планах]

## Исходный код
Будет опубликован в ближайшие дни.

## Лицензия
Лицензия на исходный код The MIT License (MIT).
Лицензию на дополнительные ресурсы смотрите в папках с этими ресурсами.
