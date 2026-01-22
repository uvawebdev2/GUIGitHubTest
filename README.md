# ShiftTask

## Требования
- Java 21
- Maven 3.9.9

## Сборка и запуск

### Командная строка (CMD)

**1. Скачайте проект**

**2. Перейдите в папку проекта**:
```cmd
cd C:\MyProjects\ShiftTask
3. Выполните сборку:

cmd
"C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2025.2\plugins\maven\lib\maven3\bin\mvn.cmd" package
4. Перейдите в папку с собранным .jar файлом:

cmd
cd target
5. Запустите программу (укажите имя .jar файла и параметры согласно заданию):

cmd
java -jar ShiftTask-1.0-SNAPSHOT.jar -f -a -p sample- in1.txt in2.txt
Тестирование в IDEA
В открытом IntelliJ IDEA проекте можно использовать, например:

cmd
java -cp target/classes org.example.Main -f -a -p sample- in1.txt in2.txt
Параметры программы
-f - параметр [описание]

-a - параметр [описание]

-p - префикс для выходных файлов

in1.txt in2.txt - входные файлы

Примечание: Замените [описание] на фактическое описание параметров из вашего задания.

text

**Или если хотите именно с цифрами 1-5, вот альтернатива:**

```markdown
1. **Скачайте проект**

2. **Перейдите в папку проекта**:
```cmd
cd C:\MyProjects\ShiftTask
Выполните сборку:

cmd
"C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2025.2\plugins\maven\lib\maven3\bin\mvn.cmd" package
Перейдите в папку с собранным .jar файлом:

cmd
cd target
Запустите программу (укажите имя .jar файла и параметры согласно заданию):

cmd
java -jar ShiftTask-1.0-SNAPSHOT.jar -f -a -p sample- in1.txt in2.txt
text

**Просто выделите и скопируйте любой из этих вариантов полностью** - в README.md на GitHub все будет выглядеть правильно.