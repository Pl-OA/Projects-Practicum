# Описание проекта
Данные предоставлены стартапом по продажам продуктов питания.

Необходимо разобраться как ведут себя пользователи мобильного приложения магазина.

Задача проекта:  

 1.изучить воронку продаж (как пользователи доходят до покупки, сколько пользователей застревает, на каких "шагах" застревает пользователь)  

 2.исследовать результаты А/А/В - теста. В группу В попали пользователия, которые видят новый шифр в приложении. Выяснить, повлияло ли изменение шифра на поведение пользователей.  
 
# Вывод
Для аналитики был предоставлен файл с логами покупателей  

в файле содержится 4 колонки и 244 тыс.строчек.  

Была проведена предобработка данных, изменен тип данных в столбце даты, заменили названия столбцов,

проверили и удалили дубликаты.  

В логе представлено пять вариантов событий:  

MainScreenAppear - главный экран 117328 событий  

OffersScreenAppear - экран с продуктами 46333 событий  

CartScreenAppear - экран с корзиной 42303 событий  

PaymentScreenSuccessful - экран с подтверждением оплаты 33918 событий  

Tutorial - экран с обучением 1005 событий  

Была проведена очистка данных. Убраны строки с данными о просмотре страницы с обучением.

Проведена корректировка данных по времени. Для дальнейшего анализа приняты данные за период с 01 августа по 07 августа 2019 года  

Изучив воронку событий получены следующие данные:  

Посетителей на главной странице: (100.0%)  

Посмотрели экран с продуктами в % от предыдущего шага: (61.9%)  

Посмотрели экран с корзиной в % от предыдущего шага: (81.3%)  

Оплатили в % от предыдущего шага: (94.8%)  

Доля пользователей от посещения главной страницы к оплате : (47.7%)  

Проверены статистические различия между контрольными группами 246 и 247. По результату группы идентичны.  

Проверены статистические различия между контрольными группами и проверяемой.  

Исследование показало, что группа с измененным шрифтом не отличается от контрольных групп.
