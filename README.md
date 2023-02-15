# Anonymous messages in Vas3k Chats

## Fork
- install [dokku](https://dokku.com/docs/getting-started/installation/) container
- create [dokku app](https://dokku.com/docs/deployment/application-deployment/)
- install [redis plugin](https://dokku.com/docs/getting-started/install/docker/?h=redis#plugin-installation)
- link redis to the app `dokku redis:link %your_redis_base% %your_app%`
- [override variables](https://dokku.com/docs/configuration/environment-variables/): BOT_TOKEN, CHAT_ID, CHAT_NAME, BOT_NAME
- [deploy the app](https://dokku.com/docs/deployment/application-deployment/)
