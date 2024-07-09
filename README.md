# wp-env

wordpress development environment

## Usage

```sh
cp .env.example .env
vim .env

./download-wordpress

# to install plugins
# add to wp-config.php
# define("FS_METHOD", "direct");

sudo docker compose up -d

# wordpress http://localhost:8080
# adminer http://localhost:8081
```
