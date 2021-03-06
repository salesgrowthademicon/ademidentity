# Ademidentity

 Padrão de estilos Ademicon

## Ademidentity com CDN

+ Estilos css
  
  👉 [https://cdn.jsdelivr.net/gh/salesgrowthademicon/ademidentity@latest/css/theme.css](https://cdn.jsdelivr.net/gh/salesgrowthademicon/ademidentity@latest/css/theme.css)

+ JavaScript necessário para alguns recursos
  
  👉 [https://cdn.jsdelivr.net/gh/salesgrowthademicon/ademidentity@latest/js/scripts.js](https://cdn.jsdelivr.net/gh/salesgrowthademicon/ademidentity@latest/js/scripts.js)

+ JavaScript necessário para carousel
  
  👉 [https://cdn.jsdelivr.net/gh/salesgrowthademicon/ademidentity@latest/js/plugin-scroll.js](https://cdn.jsdelivr.net/gh/salesgrowthademicon/ademidentity@latest/js/plugin-scroll.js)
  
+ JQuery 3.5.1 compilado e minimizado necessário para alguns recursos
  
  👉 [https://cdn.jsdelivr.net/gh/salesgrowthademicon/ademidentity@latest/js/library.js](https://cdn.jsdelivr.net/gh/salesgrowthademicon/ademidentity@latest/js/library.js)

Para usar basta colar os links no `head` de sua `index`. Na raiz do projeto há um exemplo demostrativo.

  ```html
    <!-- Estilos css -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/salesgrowthademicon/ademidentity@latest/css/theme.css" />
    
    <!-- JavaScript necessário para alguns recursos -->
    <script src="https://cdn.jsdelivr.net/gh/salesgrowthademicon/ademidentity@latest/js/scripts.js" type="text/javascript"></script>

    <!-- JavaScript necessário para carousel -->
    <script src="https://cdn.jsdelivr.net/gh/salesgrowthademicon/ademidentity@latest/js/plugin-scroll.js" type="text/javascript"></script>
    
    <!-- JQuery 3.5.1 compilado e minimizado necessário para alguns recursos -->
    <script src="https://cdn.jsdelivr.net/gh/salesgrowthademicon/ademidentity@latest/js/library.js" type="text/javascript"></script>
    
    <!-- Font Awesome necessário para alguns recursos -->
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous"/>
  ```

## Ademidentity via gerenciadores de pacotes

Para aplicações em node use nossa lib com [npm](https://www.npmjs.com/package/ademidentity@latest) ou [yarn](https://yarnpkg.com/package/ademidentity)

+ npm

  ```bash
    npm install ademidentity
  ```

+ yarn

  ```bash
    yarn add ademidentity
  ```

## Ademidentity via composer

Para aplicações em php use nossa lib com [composer](https://packagist.org/packages/mktademicon/ademidentity)

**Nota**: necessário "minimum-stability": "dev"

+ composer

  ```bash
    composer require mktademicon/ademidentity
  ```

## Estrutura de arquivos e pastas

```bash
ademidentity/
├── css/
│   ├── globals.css
│   ├── globals.css.map
│   ├── theme.css
│   └── theme.css.map
├── js/
│   ├── library.js
│   ├── plugin-scroll.js
│   └── script.js
├── scss/
│   ├── _animate.scss
│   ├── _buttons.scss
│   ├── _columns.scss
│   ├── _carousel.scss
│   ├── _flex.scss
│   ├── _form.scss
│   ├── _mobile.scss
│   ├── _spacing.scss
│   ├── globals.scss
│   └── theme.scss
├── index.php
└── READEME.md
```
