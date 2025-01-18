Проект для настройки и тестирования webhook jenkins deploy.
Для успешного деплоя необходимо:
- Установленный Jenkins с белым публичным IP
- Плагин Generic Webhook Trigger
- github secrets переменные:

`DEPLOY_URL: <host>/<endpoint>`

Например: http://example.com/generic-webhook-trigger/invoke

`DEPLOY_TOKEN: <token>`

Например: my_token123




