# details-1

1. Получаете всю историю сообщений (записываете в переменную или localStorage)
2. Вешаете обработчик на событие скролла
3. Вызываете обработчик (когда скролл “ударяется” в верхнюю границу окна) и добавляете в чат еще 20 сообщений.
4. Когда добавлять уже нечего - выводите текст “Вся история загружена”