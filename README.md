# Spelling_cheque_RUS
Базовый алгоритм автоматической корректировки орфографии текстов на русском языке

Этот проект представляет собой инструмент для автоматической коррекции орфографических и грамматических ошибок в русском тексте с использованием библиотеки language_tool_python. Также реализованы функции исправления капитализации и анализа качества исправлений на основе контрольного текста.

Функциональность

- Исправление орфографических и грамматических ошибок в тексте с помощью LanguageTool.
- Коррекция капитализации (приведение первых букв предложений к верхнему регистру).
- Обработка текстов из файлов – загрузка, исправление и сохранение результатов.
- Оценка качества исправлений: вычисление метрик Precision, Recall и F1-Score.
- Формирование отчёта об исправленных и пропущенных ошибках в формате DataFrame.

Установка

Клонируйте репозиторий:
git clone https://github.com/your-username/your-repository.git
cd your-repository


Требования

- Python 3.7+
- language_tool_python
- pandas

Авторы:
https://github.com/Kate-PSU
https://github.com/Safarbekov7717
