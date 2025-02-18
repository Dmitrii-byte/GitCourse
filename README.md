# Что такое __Git__? 

### Git - инструмент для реализации больших проектов, требующий установки и настройки.


Командная строка - основной инструмент для работы с Git.


Git позволяет сохранять и "склеивать" труд разных программистов, облегчая работу над проектами.


Системы контроля версий помогают разработчикам контролировать изменения в проектах и сохранять историю.


Git является примером системы контроля версий и помогает хранить, изменять и анализировать историю проекта.

Графический интерфейс и командная строка - два способа взаимодействия с программами.

## Некоторые команды для работы с Git через консоль

Командная строка - текстовый интерфейс, пользователь вводит команды.

Команда _pwd_ показывает путь к текущей директории.

вывод содержимого директории с помощью _ls_.

Смена директории с помощью _cd (change directory)_.

Для перехода на уровень выше использовать __cd ..__.

### Дополнительные возможности ls: 

расширенный список с помощью флага -a, отображение . и .. файлов.

### Работа с файлами и папками:

команда _touch_, указание расширения для определения программы для создания файла.

Создание директорий: команда _mkdir_, использование флага -p для создания структуры директорий.

Копирование файлов: команда _cp_ (copy), возможно указание нескольких файлов через запятую.

Перемещение файлов и папок: команда mv, указание списка файлов и папок, затем папки назначения.

Пример использования команд: создание папки, создание двух файлов, копирование одного из них в домашнюю

директорию, перемещение файла в другую папку.

Чтение файлов: команда _cat_, работает только с текстовыми файлами.

Удаление файлов и папок: команда _rm, rmdir, rm -r_.

Команда rm удаляет файлы и папки, rmdir - директории.

Если в папке есть файлы, то командная строка не удаляет её, а выводит сообщение о том, что папка не пуста.

Команда _rm -r_ рекурсивно удаляет файлы и папки, удаляя их последовательно.

Удаление объектов командами _rm_ и _rmdir_ необратимо.

Несколько команд можно указать сразу, разделив их двумя амперсандами _(&&)_.

Символ тильда _(~)_ хранит ссылку на домашнюю директорию, поэтому для перехода в неё достаточно 
напечатать ~ и нажать Enter.

### Работа с Git

Для превращения простой папки в Git-проект нужно выполнить команду _git init_.

Git-репозиторий создается один раз и используется долго.

Не рекомендуется создавать репозиторий Git внутри другого Git-репозитория.

После инициализации репозитория можно проверить его состояние с помощью команды _git status_.

Если случайно сделали Git-репозиторием не ту папку, ее можно "разгитить", удалив скрытую подпапку .git c помощью _rm -rf .git_.

В Git можно сохранять исходный код программ и другие текстовые файлы.

Файлы в Git не имеют специальной логики для хранения кода, но могут быть использованы разработчиками и техническими писателями.

Команда _git add_ не сохраняет содержимое файлов, а только запоминает текущее состояние.

Сохранение файлов называется коммитом.

Команды _git add --all, git add ._ подготавливает к сохранению все файлы в репозитории.

Если отредактировать файл, он перейдет в состояние modified и будет в "зелёном" и "красном" списках.

Чтобы запомнить новое состояние файла, нужно снова ввести команду git add и передать в качестве параметра имя изменённого файла или ключ --all.

Коммит в Git - это список файлов с их контентом, который гарантирует сохранение изменений в истории.

Команда _git commit_ выводит информацию о коммите, включая ветку, корневой коммит и идентификатор.

Проверка статуса команда _git status_.

Команда _git add_ сохраняет файлы и их версии, а _git commit_ сохраняет результат.

Коммит должен описывать изменения, чтобы было понятно, что было сделано.

Команда для просмотра истории коммитов: _git log_.
