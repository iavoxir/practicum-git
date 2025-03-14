# Git — заметки

## Основные команды Git:
```bash
git init                # Инициализация репозитория
git clone <URL>         # Клонирование репозитория
git add <file>          # Добавление файла в индекс
git commit -m "Сообщение"  # Создание коммита
git push origin main    # Отправка изменений
git pull origin main    # Получение обновлений
git status              # Проверка состояния
git log                 # История коммитов
git log --oneline       # История коммитов (кратко)
git branch              # Просмотр веток
git checkout -b new-branch  # Создание и переход в новую ветку
git merge new-branch    # Слияние ветки
```

## Работа с файлами и папками:
```bash
pwd                    # Показать текущую папку
cd ~/dev/first-project # Перейти в проект
cd .git/               # Перейти в папку Git
rm readme.txt          # Удалить файл
touch README.md        # Создать файл
echo "Hello, Git!" > README.md  # Записать в файл
cat README.md          # Посмотреть содержимое
mv oldname.txt newname.txt  # Переименовать файл
cp file.txt copy.txt   # Скопировать файл
ls -l                 # Показать файлы в папке
```

## Откат изменений:
```bash
git reset --hard HEAD~1  # Удалит последний коммит локально
git push --force         # Перезапишет удалённый репозиторий (⚠ Опасно, изменит историю)
```