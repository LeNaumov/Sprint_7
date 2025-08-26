# Sprint_7
create_courier_and_delete() - Фикстура создаёт курьера и удаляет его после действий теста
create_courier_data_and_delete() - Генерирует данные курьера и удаляет курьера после действий теста

test_courier.py:
  - test_courier_create_success - Проверка успешного создания курьера при заполнении всех полей
  - test_courier_create_without_name_success - Проверка успешного создания курьера без необязательного поля Имя
  - test_courier_creation_dublicate_failed - Проверка ошибки создания курьера, если курьер уже существует 
  - test_courier_creation_without_login_password_failed Проверка ошибки при создании курьера, с отсутствующим логином или паролем
  - test_courier_login_success - Проверка успешного входа в систему, при заполнении всех полей
  - test_courier_login_courier_not_exist_failed - Проверка ошибки при входе в систему с несуществующим пользователем
  - test_courier_login_invalid_cases_failed - Проверка ошибки при входе в систему с отсутствующим или неправильным логином / паролем

test_order.py:
  - test_create_order_random_data_success - Проверка успешного создания заказа с случайно сгенерированными данными заказа
  - test_get_order_list_success - Проверка успешного поулчения списка заказов