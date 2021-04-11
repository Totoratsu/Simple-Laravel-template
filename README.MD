# Laravel + MySQL project template

I'll add either VueJS or ReactJS in the future.

## Build

```bash
docker-compose build
```

## Test

```bash
docker-compose up -d
```

### MySQL Configuration

```bash
sudo mysql_secure_installation

...

SET GLOBAL validate_password.length = 4;
SET GLOBAL validate_password.number_count = 0;
CREATE USER 'admin'@'localhost' IDENTIFIED BY 'admin';
GRANT ALL PRIVILEGES ON *.* TO 'amin'@'localhost';
FLUSH PRIVILEGES;
```

## Inspiration

- [aschmelyun/docker-compose-laravel](https://github.com/aschmelyun/docker-compose-laravel)
