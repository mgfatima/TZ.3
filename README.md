Краткое описание системы:
	Данное мобильное приложение доставки еды предоставляет пользователям удобный способ заказывать еду из различных ресторанов. Пользователям предоставлен следующий функционал приложения: они могут просматривать меню, выбирать блюда, оформлять заказы, производить оплату через встроенную платежную систему и отслеживать статус доставки в реальном времени.
	Рестораны же могут управлять своим меню, добавляя и обновляя позиции, а также обрабатывать поступающие заказы. Курьеры могут принимать заказы на доставку, отслеживать маршруты и подтверждать выполнение заказов.
	Приложение включает модули аутентификации пользователей, позволяющие зарегистрироваться и войти в систему, модуль управления меню для ресторанов, модуль заказов, обрабатывающий все аспекты создания и выполнения заказов, модуль оплаты, обеспечивающий безопасные транзакции, и модуль доставки, координирующий работу курьеров.
	Взаимодействие между компонентами обеспечивается через API Gateway, который маршрутизирует запросы и отвечает за интеграцию всех частей системы, являясь некоторой точкой входа всех запросов на серверную часть, а также точкой, откуда клиентские приложения получают ответ на свой запрос.
	База данных хранит информацию о пользователях, меню ресторанов, заказах, оплатах и курьерах, обеспечивая целостность и доступность данных для всех участников процесса.
 ## UML Диаграммы
 ### Диаграмма использований
 ![Диаграмма вариантов использования](images/d1.png)
 ### Диаграмма последовательности
 ![Диаграмма последовательности](images/d2.png)
 ### Диаграмма состояний
 ![Диаграмма состояний](images/d3.png)
 ### Диаграмма деятельности
 ![Диаграмма деятельности](images/d4.png)
 ### Диаграмма классов
 ![Диаграмма классов](images/d5.png)
