# Экспертная система по выбору языка программирования

## Описание проекта
Данное приложение представляет собой экспертную систему, которая помогает пользователям выбрать наиболее подходящий язык программирования на основе их предпочтений и требований. Приложение имеет графический интерфейс, разработанный с использованием PyQt6, и включает в себя интерактивный опрос, результаты которого анализируются с помощью механизма вывода на основе базы знаний.

## Основные возможности
- **Интерактивный опрос**: Пользователь проходит серию вопросов, связанных с его предпочтениями в области программирования.
- **Учет приоритетов**: Система позволяет пользователю указывать важность различных аспектов, таких как тип проектов, парадигма программирования, производительность и другие.
- **Персонализированные рекомендации**: На основе ответов и указанных приоритетов система предоставляет список рекомендуемых языков программирования с процентом соответствия.
- **Простой и интуитивно понятный интерфейс**: Приложение имеет удобный графический интерфейс с анимированным фоном для улучшения пользовательского опыта.

## Технологии
- **Python 3**
- **PyQt6** для создания графического интерфейса
- **QMovie** для отображения анимированного фона (GIF)
- **Объектно-ориентированный подход** для организации кода

## Требования
- Python 3.8 или выше
- Установленные библиотеки из `requirements.txt`

## Установка
1. Клонируйте репозиторий или скачайте исходный код:
    ```bash
    git clone https://github.com/WETQV/Expert-system-lite-PL.git
    ```
2. Перейдите в директорию проекта:
    ```bash
    cd Expert-system-lite-PL
    ```
3. Создайте и активируйте виртуальное окружение (рекомендуется):
    ```bash
    python -m venv .venv
    ```
4. Для активации виртуального окружения:
   - **Windows**:
     ```bash
     .venv\Scripts\activate
     ```
   - **Linux/MacOS**:
     ```bash
     source .venv/bin/activate
     ```
5. Установите необходимые зависимости:
    ```bash
    pip install -r requirements.txt
    ```

## Запуск приложения
1. Убедитесь, что виртуальное окружение активировано (если вы его используете).
2. Запустите файл `main.py`:
    ```bash
    python main.py
    ```
3. Приложение должно открыться с главным окном. Следуйте инструкциям на экране.

## Структура проекта
```
├── main.py
├── README.md
├── requirements.txt
├── Gifka.gif
├── data
│   └── knowledge_base.py
├── src
│   ├── app.py
│   ├── inference_engine.py
│   └── screens
│       ├── __init__.py
│       ├── main_window.py
│       ├── question_window.py
│       └── result_window.py
```
- `main.py`: Точка входа в приложение.
- `README.md`: Документация проекта.
- `requirements.txt`: Список зависимостей проекта.
- `Gifka.gif`: Анимированный фон приложения.
- `data/knowledge_base.py`: База знаний с вопросами и характеристиками языков.
- `src/app.py`: Инициализация и запуск приложения.
- `src/inference_engine.py`: Механизм вывода экспертной системы.
- `src/screens/`: Модули для графического интерфейса приложения.

## Настройка и кастомизация
- **Замена фона**: Вы можете заменить файл `Gifka.gif` на свой собственный GIF-файл. Убедитесь, что новый файл также называется `Gifka.gif` или измените пути в коде соответствующим образом.
- **Обновление базы знаний**: Файл `knowledge_base.py` содержит базу знаний системы. Вы можете добавить новые языки, вопросы или изменить веса характеристик для настройки системы под свои требования.

## Пример использования
1. Запустите приложение.
2. Нажмите кнопку "Начать опрос" в главном окне.
3. Пройдите опрос, отвечая на вопросы о ваших предпочтениях и указывая важность различных аспектов.
4. Получите рекомендации: После завершения опроса приложение покажет вам список рекомендуемых языков программирования с процентом соответствия вашим предпочтениям.
5. Перезапуск опроса: Вы можете пройти опрос заново, нажав соответствующую кнопку в окне результатов.

## Поддержка и обратная связь
Если у вас возникли вопросы или вы обнаружили ошибки, пожалуйста, создайте issue в репозитории проекта или свяжитесь со мной по электронной почте: `memasik554@gmail.com`.

## Лицензия
Этот проект распространяется под лицензией MIT License. Подробнее см. в файле `LICENSE`.

## Автор
**WETQV** - [Профиль](https://github.com/WETQV)

## Дополнительная информация

### Известные проблемы
- **Производительность с большими GIF-файлами**: Использование очень больших или не оптимизированных GIF-файлов может привести к повышенному потреблению ресурсов и снижению производительности приложения.

## Благодарности
Спасибо себе за то, что сегодня поел.

