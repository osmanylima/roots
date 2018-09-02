1 - git clone git@github.com:osmanylima/roots.git

*Navegue até a pasta (cd web/wp/wp-content/themes/)

2 - composer create-project roots/sage studio084

*Navegue até a pasta src e execute o comando composer install*

3 - Crie uma cópia do .env.example com o nome .env

*Navegue até a pasta web/wp/wp-content/themes/*

4 - Execute os comandos yarn install e composer install

5 - Certifique-se de aumentar as seguites variáveis do php:

- define('WP_MEMORY_LIMIT', '64M');

- define('POST_MAX_SIZE', '15M');

- define('UPLOAD_MAX_FILESIZE', '15M');

*Configurar o plugin WP-SMTP para disparar os emails dos formulários:*

6 - ADMIN > Configurações -> WP SMTP

*Build commands*

- yarn start — Compile assets when file changes are made, start Browsersync session

- yarn build — Compile and optimize the files in your assets directory

- yarn build:production — Compile assets for production
