# Настройка целей для сайтов на платформе Tilda

1. Цель на отправку всех форм обратной связи с сайта

Тип условия: Посещение страницы (Тильда создает виртуальную страницу при успешной отправке формы)
Условие (url: регулярное выражение): ```.*tilda\/form[^/]+\/submitted\/```

![Goal-1](https://github.com/belousovD/goals-on-tilda_ctx/blob/main/files/goal-1.png)


2. Цель на отправку уникальной формы обратной связи с сайта

Находим уникальный идентификатор формы на странице сайта

![Goal-2.1](https://github.com/belousovD/goals-on-tilda_ctx/blob/main/files/goal-2.1.png)


Тип условия: Посещение страницы (Тильда создает виртуальную страницу при успешной отправке формы)
Условие (url: содержит): ```.*tilda\/form[^/]+\/submitted\/```

![Goal-2.2](https://github.com/belousovD/goals-on-tilda_ctx/blob/main/files/goal-2.2.png)


3. Просмотр попапа

Находим уникальный идентификатор блока на странице сайта

![Goal-3.1](https://github.com/belousovD/goals-on-tilda_ctx/blob/main/files/goal-3.1.png)



