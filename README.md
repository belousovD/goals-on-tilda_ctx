# Настройка целей для сайтов на платформе Tilda

1. Цель на отправку всех форм обратной связи с сайта

Тип условия: Посещение страницы (Тильда создает виртуальную страницу при успешной отправке формы)
Условие (url: регулярное выражение): ```.*tilda\/form[^/]+\/submitted\/```

![Goal-1](https://github.com/belousovD/goals-on-tilda_ctx/blob/main/files/goal-1.png)



## 2. Цель на отправку уникальной формы обратной связи с сайта

Находим уникальный идентификатор формы на странице сайта

![Goal-2.1](https://github.com/belousovD/goals-on-tilda_ctx/blob/main/files/goal-2.1.png)


Тип условия: Посещение страницы (Тильда создает виртуальную страницу при успешной отправке формы)
Условие (url: содержит): ```/tilda/form436204329/submitted```

![Goal-2.2](https://github.com/belousovD/goals-on-tilda_ctx/blob/main/files/goal-2.2.png)



## 3. Цель на просмотр попапа

Находим уникальный идентификатор блока на странице сайта

![Goal-3.1](https://github.com/belousovD/goals-on-tilda_ctx/blob/main/files/goal-3.1.png)

Тип условия: Посещение страницы
Условие (url: содержит): ```tilda/popup/rec31654896/opened```

![Goal-3.2](https://github.com/belousovD/goals-on-tilda_ctx/blob/main/files/goal-3.2.png)



## 4. Цель на клик по кнопке

Находим уникальный идентификатор кнопки на странице сайта

![Goal-4.1](https://github.com/belousovD/goals-on-tilda_ctx/blob/main/files/goal-4.1.png)

Тип условия: Посещение страницы
Условие (url: содержит): ```/tilda/click/rec435762390/button1```

![Goal-4.2](https://github.com/belousovD/goals-on-tilda_ctx/blob/main/files/goal-4.2.png)



## 5. Цель на просмотр определенного товара

Находим уникальный идентификатор товара (product id)

![Goal-5.1](https://github.com/belousovD/goals-on-tilda_ctx/blob/main/files/goal-5.1.png)

Тип условия: Посещение страницы
Условие (url: содержит): ```tilda/product/detail/710086249671```

![Goal-5.2](https://github.com/belousovD/goals-on-tilda_ctx/blob/main/files/goal-5.2.png)
