# WPZ - Wise Parking Zone
# Концепт
WPZ - Умная парковочная зона. Основная идея - это предоставлять информацию о загруженности парковочной зоны и построить кратчайший маршрут до свободного парковочного места. Данная фича позволит водителям не кружиться в поисках места, а четко следовать до ближайшего места, тем самым уменьшая выброс CO2 в атмосферу и сэкономить свое время на поиск свободного места.
Комплекс WPZ - может применяться у зданий/сооружений со своей парковочной зоной. Данный комплекс позволяет мониторить загруженность парковочной зоны, а также вести определенную статистику по загруженности в разрезе дня/часов/недели/месяца.


# MVP
Отображать информацию о загруженности парковочной зоны в режиме реального времени
Вести сбор статистики по загруженности парковочной зоны
Формировать отчеты в разрезе промежутка часов, дня, недели, месяца
Возможность добавлять и удалять парковочные места в рамках одной парковочной зоны

# План работ:
# Фронт -
Разработать дизайн парковочной зоны
Динамическое изменение статуса парковочного места на парковочной карте
Реализовать страничку для админа парковочной зоны
Реализовать страничку по отчетности
# Бэк -
Реализовать функционал обработки входящего сообщения с парковочного места
Реализовать функционал для администратора парковочной зоны
Реализовать функционал по отчетности

# БД
Спроектировать модель данных

# Псевдо датчики
Псевдо датчики - сервис по отправке сообщений от датчиков.


Тех стек: React, JavaScript, Java Spring Boot
