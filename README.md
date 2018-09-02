1 - git clone git@github.com:osmanylima/roots.git

*Navegue até a pasta src e execute o comando*

- composer install

*Navegue até a pasta (cd web/wp/wp-content/themes/)

2 - composer create-project roots/sage nome-tema

3 - Entre na pasta do tema e execute:

- yarn && yarn build

4 - Certifique-se de aumentar as seguites variáveis do php em wp-config e personalizar os dados do banco de dados:

- define('WP_MEMORY_LIMIT', '64M');

- define('POST_MAX_SIZE', '15M');

- define('UPLOAD_MAX_FILESIZE', '15M');

*Configurar o plugin WP-SMTP para disparar os emails dos formulários:*

5 - ADMIN > Configurações -> WP SMTP

*Build commands*

- yarn start — Compile assets when file changes are made, start Browsersync session

- yarn build — Compile and optimize the files in your assets directory

- yarn build:production — Compile assets for production
