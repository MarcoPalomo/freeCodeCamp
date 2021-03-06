---
title: Object Fit
localeTitle: Объект Fit
---
# Объект Fit

Свойство `object-fit` указывает, как элемент реагирует на ширину / высоту родительского поля.

Это свойство может использоваться для изображений, видео или любых других носителей. Его также можно использовать со свойством `object-position` чтобы получить больше контроля над отображением носителя.

В основном мы используем свойство `object-fit` чтобы определить, как оно растягивается или хлюпает встроенный носитель.

## Синтаксис

```css
.element { 
    object-fit: fill || contain || cover || none || scale-down; 
 } 
```

## Значения

*   `fill` : **Это значение по умолчанию** . Измените размер содержимого в соответствии с его родительским полем независимо от соотношения сторон.
    
*   `contain` : Измените размер содержимого, чтобы заполнить его родительское поле, используя правильное соотношение сторон.
    
*   `cover` : аналогично `contain` но часто обрезать контент.
    
*   `none` : отображение изображения в исходном размере.
    
*   `scale-down` : сравнить разницу между `none` и `contain` чтобы найти наименьший размер конкретного объекта.
    

## Совместимость с браузером

`object-fit` поддерживается большинством современных браузеров, для получения самой последней информации о совместимости вы можете проверить это http://caniuse.com/#search=object-fit

Также есть полифил для браузера который не поддерживает это свойство (в основном IE). https://github.com/anselmh/object-fit

## Больше информации

https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit https://drafts.csswg.org/css-images-3/#the-object-fit
