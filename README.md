# Installation

1. Copy repository
2. Navigate to ./battle-game/ directory and run `docker-compose up --build`
3. Execute in php container (`docker exec -it container-hash-here /bin/sh`)
4. Run `composer install` in root directory
5. **Running the App!**

This is a command-line only app - so no web server needed. Instead, run in root directory:

```
php bin/console app:game:play
```
