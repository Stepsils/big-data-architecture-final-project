# **Инструкция по запуску**

**Для запуска блокнота необходим установленные Python 3.11.9 и Java (OpenJDK 17) !!!**

## 1. Подготовка виртуального окружения
В корне проекта откройте терминал и выполните:

Cоздать venv:
> python3.11 -m venv .venv

Активировать (macOS / Linux)
> source .venv/bin/activate

Активировать (Windows PowerShell)
>.venv\Scripts\Activate.ps1

Проверить версию Python
> python --version   # должно показать Python 3.11.9

## 2. Установка зависимостей 
Выполнить в активированном venv
> pip install --upgrade
> 
> pip pip install -r requirements.txt

***В блокноте есть ячейка c установкой. Но надежнее установить в активном venv из терминала***

## 3. Обновить ячейку блокнота с JAVA_HOME 
Необходимо указать путь к установленному JDK на вашем компьютере

> os.environ["JAVA_HOME"] = "/usr/local/opt/openjdk@17/libexec/openjdk.jdk/Contents/Home"

Замените значение ***"/usr/local/opt/openjdk@17/libexec/openjdk.jdk/Contents/Home"*** на ваш путь

## 4. Запуск Jupyter Notebook

Запустить Jupyter Notebook и выполнить ячейки последовательно друг за другом
