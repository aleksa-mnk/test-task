## https://sbermegamarket.ru/catalog/details/smartfon-apple-iphone-14-pro-max-256gb-deep-purple-100039500627/#?details_block=prices

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
var firstPrice = document.querySelector('.product-offers .product-offer .product-offer-price__amount');
console.log('Первая цена:', firstPrice.textContent);

// Вторая цена в списке продавцов
var secondPrice = document.querySelector('.product-offers .product-offer:nth-of-type(2) .product-offer-price__amount');
console.log('Вторая цена:', secondPrice.textContent);

// Последняя цена в списке продавцов
var lastPrice = document.querySelector('.product-offers .product-offer:last-child .product-offer-price__amount');
console.log('Последняя цена:', lastPrice.textContent);

// Вкладка, соседняя справа от активной ("Характеристики")
var tabLink = document.querySelector('.tab-links-component .router-link-active.active + a');
console.log('Вкладка, справа от активной:', tabLink.textContent);

// Заголовок ("Смартфон Apple iPhone 14 Pro Max 256Gb Deep Purple")
var pdpTitle = document.querySelector('.pdp-header__title');
console.log('Заголовок:', pdpTitle.textContent.trim());

// Основная цена на товар ("113 050 ₽")
var pdpPrice = document.querySelector('.pdp-sales-block__price-final');
console.log('Основная цена на товар:', pdpPrice.textContent.trim());
```

![image](https://github.com/aleksa-mnk/test-task/assets/61269026/24618c67-66e9-4cf9-a003-1082de0e8f26)


## https://price.ru/noutbuki/apple-macbook-air-mgn63/

```css
.offer-list .p-c-price:first-child .p-c-price__price__link .main-price
.offer-list .p-c-price:nth-child(2) .p-c-price__price__link .main-price
.l-more-tablet
.popular-model .price .currency
и 2 js
```

```javascript
// Первая цена на товар в списке продавцов
var firstPrice = document.querySelector('.offer-list .p-c-price:first-child .p-c-price__price__link .main-price');
console.log('Первая цена:', firstPrice.textContent);

// Вторая цена в списке продавцов
var secondPrice = document.querySelector('.offer-list .p-c-price:nth-child(2) .p-c-price__price__link .main-price');
console.log('Вторая цена:', secondPrice.textContent);

// Последняя цена в списке продавцов
var priceElements = document.querySelectorAll('.offer-list .p-c-price__price');
var lastPriceElement = priceElements[priceElements.length - 1];
var lastPrice = lastPriceElement.querySelector('.main-price');
console.log('Последняя цена:', lastPrice.textContent.trim());

// Вкладка, соседняя справа от активной ("Цены")
var activeTab = document.querySelector('.r-text.base.active');
var nextTab = activeTab.parentElement.nextElementSibling.querySelector('.r-text');
console.log('Вкладка, справа от активной:', nextTab.textContent.trim());

// Заголовок ("Ноутбук Apple MacBook Air MGN63")
var pdpTitle = document.querySelector('.l-more-tablet');
console.log('Заголовок:', pdpTitle.textContent.trim());

// Основная цена на товар ("85 980 ₽")
var pdpPrice = document.querySelector('.popular-model .price .currency');
console.log('Основная цена на товар:', pdpPrice.textContent.trim());
```

![image](https://github.com/aleksa-mnk/test-task/assets/61269026/021b20a9-9b74-4c0d-bbfc-3feb777a51d2)


