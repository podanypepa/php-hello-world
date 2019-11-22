# php-hello-world
Simple PHP App

## PHP App

The PHP Hello, World! application is in `src/index.php`.

My example code:

```php
phpinfo();
```

## Runtime
Fully functionally config is in dir ./config. You don't need modify any file.

## Run & Use

1. Build Docker image

	```bash
	cd php-hello-world
	docker build -t phpserver .
	```

2. Run Docker container

	```bash
	docker run phpserver -p 8080:8080
	```

3. Consume content

	```bash
	curl http://127.0.0.1:8080
	```
