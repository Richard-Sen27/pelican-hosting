# First time setup

```sh
# create a new user for the panel
docker compose exec panel php artisan p:user:make
# in case an error is thrown that no tables exist yet
docker compose exec panel php artisan migrate --force
```