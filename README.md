## https://sbermegamarket.ru/catalog/details/smartfon-apple-iphone-14-pro-max-256gb-deep-purple-100039500627/#?details_block=prices


### Селекторы:

```css
.tab-links-component .router-link-active.active + a
.pdp-header__title
.pdp-sales-block__price-final
.product-offers .product-offer:first-child .product-offer-price__amount
.product-offers .product-offer:nth-of-type(2) .product-offer-price__amount
.product-offers .product-offer:last-child .product-offer-price__amount
```

```javascript
// Первая цена на товар в списке продавцов
let firstPrice = document.querySelector('.product-offers .product-offer .product-offer-price__amount');
console.log('Первая цена:', firstPrice.textContent);

// Вторая цена в списке продавцов
let secondPrice = document.querySelector('.product-offers .product-offer:nth-of-type(2) .product-offer-price__amount');
console.log('Вторая цена:', secondPrice.textContent);

// Последняя цена в списке продавцов
let lastPrice = document.querySelector('.product-offers .product-offer:last-child .product-offer-price__amount');
console.log('Последняя цена:', lastPrice.textContent);

// Вкладка, соседняя справа от активной ("Характеристики")
let tabLink = document.querySelector('.tab-links-component .router-link-active.active + a');
console.log('Вкладка, справа от активной:', tabLink.textContent);

// Заголовок ("Смартфон Apple iPhone 14 Pro Max 256Gb Deep Purple")
let pdpTitle = document.querySelector('.pdp-header__title');
console.log('Заголовок:', pdpTitle.textContent.trim());

// Основная цена на товар ("113 050 ₽")
let pdpPrice = document.querySelector('.pdp-sales-block__price-final');
console.log('Основная цена на товар:', pdpPrice.textContent.trim());
```

![image](https://github.com/aleksa-mnk/test-task/assets/61269026/24618c67-66e9-4cf9-a003-1082de0e8f26)


## https://price.ru/noutbuki/apple-macbook-air-mgn63/

### Селекторы:

```css
.offer-list .p-c-price:first-child .p-c-price__price__link .main-price
.offer-list .p-c-price:nth-child(2) .p-c-price__price__link .main-price
.l-more-tablet
.popular-model .price .currency
и 2 js
```

```javascript
// Первая цена на товар в списке продавцов
let firstPriceElement = document.querySelector('.offer-list .p-c-price:first-child .p-c-price__price__link .main-price');
let firstPrice = firstPriceElement.textContent.trim();
console.log('Первая цена:', firstPrice);

// Вторая цена в списке продавцов
let secondPriceElement = document.querySelector('.offer-list .p-c-price:nth-child(2) .p-c-price__price__link .main-price');
let secondPrice = secondPriceElement.textContent.trim();
console.log('Вторая цена:', secondPrice);

// Последняя цена в списке продавцов
let priceElements = document.querySelectorAll('.offer-list .p-c-price__price');
let lastPriceElement = priceElements[priceElements.length - 1];
let lastPrice = lastPriceElement.querySelector('.main-price').textContent.trim();
console.log('Последняя цена:', lastPrice);

// Вкладка, соседняя справа от активной ("Цены")
let activeTab = document.querySelector('.r-text.base.active');
let nextTab = activeTab.parentElement.nextElementSibling.querySelector('.r-text').textContent.trim();
console.log('Вкладка, справа от активной:', nextTab);

// Заголовок ("Ноутбук Apple MacBook Air MGN63")
let pdpTitle = document.querySelector('.l-more-tablet').textContent.trim();
console.log('Заголовок:', pdpTitle);

// Основная цена на товар ("85 980 ₽")
let pdpPrice = document.querySelector('.popular-model .price .currency').textContent.trim();
console.log('Основная цена на товар:', pdpPrice);
```

![image](https://github.com/aleksa-mnk/test-task/assets/61269026/021b20a9-9b74-4c0d-bbfc-3feb777a51d2)

## https://ek.ua/prices/apple-ipad-2021-64gb/

### Селекторы:

```css
.where-buy-price a
.desc-big-price
.page-title
```

Тут пришлось поиграться с js, так как не ко всем элементам можно получить путь через селектор css...

```javascript
// Первая цена на товар в списке продавцов
let firstPriceElement = document.querySelector('.where-buy-price a');
let firstPrice = firstPriceElement.innerText.trim();
console.log('Первая цена:', firstPrice);

// Вторая цена в списке продавцов
let secondPriceElement = document.querySelectorAll('.where-buy-price a')[1];
let secondPrice = secondPriceElement.innerText.trim();
console.log('Вторая цена:', secondPrice);

// Последняя цена в списке продавцов
let prices = document.querySelectorAll('.where-buy-price a');
let lastPriceElement = prices[prices.length - 2];
let lastPrice = lastPriceElement.innerText.trim();
console.log('Последняя цена:', lastPrice);

// Вкладка, соседняя справа от активной
let activeTab = document.querySelector('a.ib.active');
let nextTab = activeTab.nextElementSibling;
console.log('Вкладка, справа от активной:', nextTab.textContent);

// Заголовок
let pdpTitleElement = document.querySelector('.page-title');
let pdpTitle = pdpTitleElement.textContent.trim();
console.log('Заголовок:', pdpTitle);

// Основная цена на товар
let pdpPriceElement = document.querySelector('.desc-big-price');
let pdpPrice = pdpPriceElement.textContent.trim();
console.log('Основная цена на товар:', pdpPrice);
```

![image](https://github.com/aleksa-mnk/test-task/assets/61269026/008b6cb3-5ae6-43a7-8e74-f5a535eb6bbe)


