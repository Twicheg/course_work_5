# Курсовая работа №5


 Класс DBManager

Создайте класс `DBManager`, который будет подключаться к БД Postgres и иметь следующие методы:

- `get_companies_and_vacancies_count()`: получает список всех компаний и количество вакансий у каждой компании.
- `get_all_vacancies()`: получает список всех вакансий с указанием названия компании, названия вакансии и зарплаты и ссылки на вакансию.
- `get_avg_salary()`: получает среднюю зарплату по вакансиям.
- `get_vacancies_with_higher_salary()`: получает список всех вакансий, у которых зарплата выше средней по всем вакансиям.
- `get_vacancies_with_keyword()`: получает список всех вакансий, в названии которых содержатся переданные в метод слова, например “python”.

Класс `DBManager` должен использовать библиотеку `psycopg2` для работы с БД.