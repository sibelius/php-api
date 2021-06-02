# PHP API

Simple Php Api training

## Installing PHP
You must have php installed
- macos
`brew install php`
  
- arch linux with yay (for pacman just replace)
`yay -S php`
  
## Installing composer
You must have composer installed. Follow the official docs [here](https://getcomposer.org/doc/faqs/how-to-install-composer-programmatically.md)

## Installing composer dependencies
`php composer.phar install`

## Run the server

```
php -S 127.0.0.1:8000 -t public
```

```jsx
curl 'http://localhost:8000'
```