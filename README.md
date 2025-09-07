Яндекс Практикум

Курс "Автоматизатор тестирования на Python"

4 спринт

Финальный проект

Файлы:
conftest.py - (фикстура)
main.py - класс BooksCollector
test_main.py - тестовый класс TestBooksCollector``

Тестовые методы класса TestBooksCollector:

test_add_new_book_add_two_books_success: добавление двух книг в коллекцию. Успех

test_add_new_book_add_incorrect_name_failed: добавление некорректных наименований. Неудача

test_set_book_genre_incorrect_genre_failed: установка некорректного жанра для книги. Неудача

test_get_book_genre_success: получение жанра книги. Успех

test_get_books_with_specific_genre_add_dict_success: получение книг по жанру. Успех

test_get_books_with_specific_genre_wrong_genre_failed: получение книг по некорреткному жанру. Неудача

test_get_books_genre_success: получение всей коллекции книг с жанрами. Успех

test_get_books_for_children_success: получение детских книг. Успех

test_add_book_in_favorites_correct_name_success: добавление книг в избранное. Успех

test_add_book_in_favorites_incorrect_failed: добавление книг в избранное. Неудача

test_delete_book_from_favorites_one_book_success: удаление книги из избранного. Успех

test_delete_book_from_favorites_wrong_book_failed: Удаление книги из узбранного. Неудача

test_get_list_of_favorites_books_success: получение списка избранных книг. Успех

Запуск тестов
pytest -v

Оценка покрытия
pytest --cov=main

Подробная оценка покрытия с учетом ветвления
pytest --cov=main --cov-branch --cov-report=html
