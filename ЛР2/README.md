# Лабораторная 2. Формирование отчётов в Apache Spark

## Задание

Сформировать отчёт с информацией о 10 наиболее популярных языках программирования по итогам года за период с 2010 по 2020 годы. Отчёт будет отражать динамику изменения популярности языков программирования и представлять собой набор таблиц "топ-10" для каждого года.

Получившийся отчёт сохранить в формате Apache Parquet.

Для выполнения задания вы можете использовать любую комбинацию Spark API: **RDD API**, **Dataset API**, **SQL API**. 

## Набор данных

Архивы сайтов **Stack Exchange** доступны по адресу https://archive.org/details/stackexchange.

В папке [data](../data) данного репозитория вам доступны:
- выборка данных `posts_sample.xml` (из stackoverflow.com-Posts.7z),
- файл со списком языков `programming-languages.csv`, собранных с вики-страницы https://en.wikipedia.org/wiki/List_of_programming_languages.

Рекомендуется отлаживать решение на небольшой выборке данных `posts_sample.xml`. 

## Ссылки на источники
  1. https://spark.apache.org/docs/latest/sql-programming-guide.html
  2. http://timepasstechies.com/spark-dataset-api-examples-tutorial-20/
  3. https://jaceklaskowski.gitbooks.io/mastering-spark-sql/
  4. https://en.wikipedia.org/wiki/OLAP_cube
  5. http://homepage.cs.latrobe.edu.au/zhe/ZhenHeSparkRDDAPIExamples.html
  6. https://sparkbyexamples.com/

## Как запустить
  1. Скачать, настроить, запустить Hadoop. Это можно сделать по [этой](https://pro-prof.com/forums/topic/%D1%83%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-hadoop-%D0%BD%D0%B0-windows) инструкции.
  2. Скачать winutils для Hadoop можно [здесь](https://github.com/kontext-tech/winutils/tree/master).
  3. Если Hadoop ругается на `JAVA_HOME`, можно посмотреть эти ссылки: [первая](https://stackoverflow.com/questions/31621032/hadoop-on-windows-error-java-home-is-incorrectly-set), [вторая](https://stackoverflow.com/questions/32159750/getting-java-home-is-incorrectly-set-with-hadoop).
