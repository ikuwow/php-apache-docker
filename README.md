# php-apache-docker

## What is it?

## How to work

### php Built-in server

```
php -S localhost:8383
```

### Docker

build:


```
docker build -t pad .
```

And run:

```
docker run --rm -p 8383:80 pad
```
