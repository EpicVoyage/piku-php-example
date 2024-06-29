# piku-php-example
Bare-bones PHP app for Piku

Demonstrates how to run a PHP app (piku/piku#369).

Set the domain in `ENV`:

```
NGINX_SERVER_NAME=my-domain.com www.my-domain.com
```

```shell
git remote add piku piku@my-server.net:my-php-app
git push piku
```

Replace `my-domain.com` with your own values.

Replace `my-server.net` with your Piku instance, and `my-php-app` with
your custom app name, if desired.
