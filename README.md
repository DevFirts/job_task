# Job list (Список вакансий)
Нужно отобразить список вакансий полученный с https://jobs.github.com/positions.json. Для каждой вакансии нужно показать иконку компании (если она есть), название компании, описание (первые 5 строк из поля description).
Реализовать поиск по вакансиям - пример https://jobs.github.com/positions.json?search=android.
Нужно учитывать, что при поиске может вернуться пустой результат, в это случае нужно показать заглушку (Empty list state). Также нужно учесть, что с сревера придет ошибка, в таком случае нужно показать пользователю состояние ошибки, и дать возможность загрузить данные заново, кнопка "retry". Реализовать возможность фильтрации. 

# Favorite jobs
Экран со списком избранных вакансий.

# Job card (Карточка вакансии)
Пример запроса: https://jobs.github.com/positions/7d7484e0-09f5-4168-b167-55da7d9c2ac2.json
Тут нужно показать детальную информацию о вакансии. Реализовать возможность добавления вакансии в избранные.
При назатии на apply нужно открыть ссылку (из поля "how_to_apply") в браузере.

# -/-
Обязательно нужно обрабатывать состояния ошибок, загрузки и т.д. Приложение должно быть отзывчивым. 
