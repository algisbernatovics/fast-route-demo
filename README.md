# FastRoute Demo

A compact PHP routing demo built around `nikic/fast-route` and controller classes.

## Learning Goal

Practice framework-light routing and front-controller flow before using a larger framework such as Laravel.

## Features

- Defines HTTP routes through FastRoute.
- Uses controller classes for request handling.
- Keeps routing, controller code, and the entry point easy to inspect.

## Tech Stack

- PHP
- Composer
- nikic/fast-route

## Run

```bash
cd router
composer install
php -S localhost:8000 index.php
```

Open `http://localhost:8000` in the browser.

## Project Structure

- `router/index.php` - front controller and router setup
- `router/app/Controller/` - controller classes
- `router/preview.png` - visual preview from the original exercise

## License

MIT License. See [LICENSE](./LICENSE).
