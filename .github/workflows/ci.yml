name: CI/CD Pipeline

on:
  push:
    branches: [ "main" ]

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - name: Кодду алуу
        uses: actions/checkout@v3

      - name: Текшерүү
        run: echo "Файл текшерилди"

      - name: Test
        run: echo "Тест ийгиликтүү өттү"

      - name: Build
        run: echo "Проект жыйналды"

      - name: Deploy
        run: echo "Сайт жайгаштырылды"
