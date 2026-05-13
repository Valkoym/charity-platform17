# charity-platform17
Platform for charity collection contributions
# Charity Platform 17

## CI/CD Status
![CI](https://github.com/Valkoym/charity-platform17/actions/workflows/main.yml/badge.svg)

---

## Опис проєкту

Charity Platform 17 — це платформа для збору благодійних внесків та управління благодійними кампаніями.

Система дозволяє:
- створювати кампанії збору;
- робити благодійні внески;
- керувати волонтерами;
- формувати звітність;
- автоматизувати процес перевірки та збірки проєкту через CI/CD.

---

## Основні можливості

- створення благодійних кампаній;
- підтримка донатів;
- волонтерська система;
- аналітика та звітність;
- Docker-контейнеризація;
- GitHub Actions автоматизація.

---

## Технології

- GitHub
- GitHub Actions
- Docker
- YAML
- Python

---

## Запуск у Docker

```bash
docker build -t charity-platform17 .
docker run charity-platform17
```

---

## Автоматизація

Проєкт містить GitHub Actions workflow, який автоматично:

- перевіряє код на помилки;
- запускає тести;
- збирає Docker-образ;
- відображає статус CI/CD через badge.

Workflow запускається при кожному:
- push
- pull request
