# Шаг 3. Опубликуем сокращатель через API Gateway

Перейдите в каталог и выберете сервис API Gateway.
Нажмите кнопку `Создать API-шлюз` с именем `for-serverless-shortener`.
Вставьте спецификацию из файла `for-serverless-shortener.yml`.
Обязательно замените `<bucket_name>` на имя вашего Object Storage, `<html_file>` на имя размещенного файла, 
`<service_account_id>` на id вашего сервисного аккаунта, созданного ранее.

После опубликования API-шлюза в спецификации появится секция `servers` с адресом `url`. 
Через этот `url` вы сможете обратиться к ранее опубликованному в Object Storage файлу `index.html`.
 
## Видео

https://youtu.be/nZIxjWiYrEY