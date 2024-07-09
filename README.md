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

# open http://localhost:8080
```
