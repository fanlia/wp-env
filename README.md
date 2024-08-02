# wp-env

wordpress development environment

## Usage

```sh
cp .env.example .env
vim .env

./download-wordpress

# create the_theme directroy to develpe a new theme
mkdir the_theme

sudo docker compose up -d

# config permalinks to Post name, if not the wp-json api will not enabled
# http://localhost:8080/wp-admin/options-permalink.php

# wordpress http://localhost:8080
# adminer http://localhost:8081
```
