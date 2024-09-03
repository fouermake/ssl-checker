Программа предназначена для проверки установленных SSL-сертификатов на доменах, а также даты их окончания. Результат выполнения записывается в файл. Поддерживаются форматы .xlsx / .txt. Реализована базовая валидация ввода доменов, асинхронность, а также проверки на дубли.

![image](https://github.com/user-attachments/assets/7ede17c1-947a-48e7-8fa2-acb481cd1b01)

## Требования

Для работы скрипта вам понадобятся:
- Python версии 3.12 или выше
- Установите зависимости:
  ```bash
  pip install pandas aiofiles
  ```

## Установка

1. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/fouermake/ssl-checker.git
   ```
2. Перейдите в директорию проекта:
   ```bash
   cd ssl-checker
   ```

## Использование

Запустите программу:

```bash
python ssl_checker.py
```

### Доступные команды:
1. **list (ll, ls)** - показать список добавленных доменов.
2. **add <домен1, домен2, ...>** - добавить домены в список (через запятую).
3. **remove (rm) <домен1, домен2, ...>** - удалить домены из списка (через запятую).
4. **check ssl** - проверить SSL сертификаты добавленных доменов.
5. **exit** - выход из программы.
