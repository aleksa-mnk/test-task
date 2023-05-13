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

![image](https://github.com/aleksa-mnk/test-task/assets/61269026/f651001d-45bf-40fd-a8ac-352c7ae41182)


