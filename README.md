1.Нужен ключ доступа с правами. Это json файл, дают девопсы. 
2.В енв.вар. нужно прописать путь к этому файлу по ключу GOOGLE_APPLICATION_CREDENTIALS т.к. библиотека будет пытаться установить дефолтные креды именно из этой вар.
3.Topics - в документации к задаче.
4.ProjectId можно скопировать из этого файла.
5.SubscriptionId - мы генерим сами. Вместе с ProjectId должно получиться уникальное subscriptionName. В проекте мы проверяем есть ли уже subscription в гугл консоли и если нет - создаем.
6.Дальше работаем как с эмулятором.