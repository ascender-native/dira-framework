# DIRA Framework

DIRA Framework - это мощный инструмент для реализации web приложений Python.

## Установка

Для работы с проектом убедитесь, что у вас установлен Python 3.11.

Следующие шаги помогут вам начать работу:

### Шаг 1: Клонирование Репозитория

Сначала клонируйте репозиторий на свой локальный компьютер:

```bash
pip install -e .

dira serve # --reload --port 8000

```
or 
```bash
pip install -r requirements.txt

uvicorn dira:serve --reload --port 8000
```