### Hexlet tests and linter status:
[![Actions Status](https://github.com/iliatur/python-project-83/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/iliatur/python-project-83/actions)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=iliatur_python-project-83&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=iliatur_python-project-83)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=iliatur_python-project-83&metric=bugs)](https://sonarcloud.io/summary/new_code?id=iliatur_python-project-83)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=iliatur_python-project-83&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=iliatur_python-project-83)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=iliatur_python-project-83&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=iliatur_python-project-83)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=iliatur_python-project-83&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=iliatur_python-project-83)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=iliatur_python-project-83&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=iliatur_python-project-83)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=iliatur_python-project-83&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=iliatur_python-project-83)


# Page Analyzer

Веб-приложение на Python с использованием Flask для анализа веб-страниц.

Проект позволяет:

- добавлять сайты по URL
- запускать проверки
- получать информацию о странице:
  - HTTP-статус
  - заголовок `<h1>`
  - тег `<title>`
  - описание `<meta name="description">`
- хранить данные в базе PostgreSQL

Проект выполнен в рамках обучения на Hexlet.

---

## 🚀 Демо

Приложение доступно по адресу:

👉 https://python-project-83-xp9e.onrender.com

---

## 📦 Технологии

- Python 3
- Flask
- PostgreSQL
- Gunicorn
- Requests
- BeautifulSoup
- Bootstrap 5
- Jinja2
- Render.com

---

## ⚙️ Установка и запуск локально

### 1. Клонировать репозиторий

```bash
git clone https://github.com/iliatur/python-project-83.git
cd python-project-83
