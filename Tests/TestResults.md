# Результаты тестирования

| № | Назначение/название | Сценарий | Ожидаемый результат | Фактический результат | Оценка |
|:---:|:---:|:---|:---|:---|:---|
| 1 | Перемещение карты | 1. Запустите приложение.<br> 2. Переместите карту.<br> | Перемещение карты в выбранном направлении. | Перемещение карты в выбранном направлении. | Тест пройден. |
| 2 | Увеличение размера карты | 1. Запустите приложение.<br> 2. Нажмите кнопку "+".<br> | Увеличение размера карты. | Увеличение размера карты. | Тест пройден. |
| 3 | Уменьшение размера карты | 1. Запустите приложение.<br> 2. Нажмите кнопку "-".<br> | Уменьшение размера карты. | Уменьшение размера карты. | Тест пройден. |
| 4 | Добавление новой точки маршрута | 1. Запустите приложение.<br> 2. Нажмите кнопку "Построить маршрут".<br> 3. Нажмите кнопку "Добавить точку маршрута".<br>| Добавление текстового поля для ввода новой точки маршрута. | Добавление текстового поля для ввода новой точки маршрута. | Тест пройден. |
| 5 | Удаление точки маршрута | 1. Запустите приложение.<br> 2. Нажмите кнопку "Построить маршрут".<br>3. Нажмите кнопку "Добавить точку маршрута". 4. Нажмите кнопку "Удалить последнюю точку".<br>| Отображение единственного поля для ввода точки маршрута. | Отображение единственного поля для ввода точки маршрута. | Тест пройден. |
| 6 | Построение маршрута по определенной точке | 1. Запустите приложение.<br> 2. Нажмите кнопку "Построить маршрут".<br> 3. Нажмите в поле ввода точки маршрута и введите его.<br> 4. Нажмите кнопку "Создать маршрут". <br>| Отображение карты с построенным маршрутом. | Отображение карты с построенным маршрутом. | Тест пройден. |
| 7 | Построение маршрута по определенным точкам | 1. Запустите приложение.<br> 2. Нажмите кнопку "Построить маршрут".<br> 3. Нажмите в поле ввода точки маршрута и введите его.<br> 4. Нажмите кнопку "Добавить точку маршрута". <br> 5. Нажмите в появившееся поле ввода точки маршрута и введите его.<br> 6. Нажмите кнопку "Создать маршрут". | Отображение карты с построенным маршрутом. | Отображение карты с построенным маршрутом. | Тест пройден. |
| 8 | Построение маршрута по определенным точкам с некорректными данными | 1. Запустите приложение.<br> 2. Нажмите кнопку "Построить маршрут". 3. Нажмите в поле ввода точки маршрута и введите его. 4. Нажмите кнопку "Добавить точку маршрута". <br> 5. Нажмите в появившееся поле ввода точки маршрута и введите его.<br> 6. Нажмите кнопку "Создать маршрут".| Уведомление пользователя о невозможности построения маршрута по заданным точкам. | Приложение закрылось. | Тест не пройден. |
| 9 | Построение маршрута без ввода определенных точек | 1. Запустите приложение.<br> 2. Нажмите кнопку "Построить маршрут".<br> 3. Нажмите кнопку "Добавить точку маршрута". <br> 5. Нажмите кнопку "Создать маршрут". | Уведомление пользователя о том, что точки маршрута не введены. | Игнорирование нажатии кнопки "Создать маршрут". | Тест не пройден. |
| 10 | Выбор определенного способа передвижения | 1. Запустите приложение.<br> 2. Нажмите кнопку "Построить маршрут".<br> 3. Нажмите в поле ввода точки маршрута и введите его.<br> 4. Нажмите на виджет выбора определенного способа передвижения. <br> 5. Нажмите на определенный способ передвижения из списка.<br> 6. Нажмите кнопку "Создать маршрут". | Отображение карты с построенным маршрутом, учитывая определенный способ передвижения. | Отображение карты с построенным маршрутом, учитывая определенный способ передвижения. | Тест пройден. |
| 11 | Определение текущего местоположения на карте| 1. Запустите приложение.<br> 2. Нажмите кнопку "Определения местоположения".<br> | Появление метки текущего местоположения на карте. | Появление метки текущего местоположения на карте.| Тест пройден. |
| 12 | Очистка карты от маршрута| 1. Запустите приложение.<br> 2. Нажмите кнопку "Построить маршрут".<br> 3. Нажмите в поле ввода точки маршрута и введите его.<br> 4. Нажмите кнопку "Создать маршрут".<br> 5. Нажмите кнопку "Очистки карты".<br>| Отображение карты без маршрута. | Отображение карты без маршрута. | Тест пройден. |
| 13 | Настройка цвета маршрута | 1. Запустите приложение.<br> 2. Нажмите кнопку "Настройки".<br> 3. Нажмите на виджет "Цвет маршрута".<br> 4. Нажмите на определенный цвет маршрута из списка.<br> 5. Нажмите на кнопку "Сохранить настройки".<br>6. Нажмите кнопку "Построить маршрут".<br> 7. Нажмите в поле ввода точки маршрута и введите его.<br> 8. Нажмите кнопку "Создать маршрут".<br>  | Отображение карты с построенным маршрутом, учитывая изменения в настройках. | Отображение карты с построенным маршрутом, учитывая изменения в настройках. | Тест пройден. |
| 14 | Настройка цвета маркеров точек маршрута | 1. Запустите приложение.<br> 2. Нажмите кнопку "Настройки".<br> 3. Нажмите на виджет "Цвет точек маршрута".<br> 4. Нажмите на определенный цвет точек маршрута из списка.<br> 5. Нажмите на кнопку "Сохранить настройки".<br>6. Нажмите кнопку "Построить маршрут".<br> 7. Нажмите в поле ввода точки маршрута и введите его.<br> 8. Нажмите кнопку "Создать маршрут".<br> | Отображение карты с построенным маршрутом, учитывая изменения в настройках. | Отображение карты с построенным маршрутом, учитывая изменения в настройках. | Тест пройден. |
|  |  |  |  |  |  |