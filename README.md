# (2020.12.07-14-15) T316-JQuery

## -------INFO
```
1. Icons (https://iconify.design/icon-sets/)
2. JQuery (https://jquery.com/)
```
```javascript
function fadeIn(el) { // Vanilla JavaScript
  el.style.opacity = 0;
  var last = +new Date();
  var tick = function() {
    el.style.opacity = +el.style.opacity + (new Date() - last) / 400;
    last = +new Date();
    if (+el.style.opacity < 1) {
      (window.requestAnimationFrame && requestAnimationFrame(tick)) || setTimeout(tick, 16);
    }
  };
  tick();
}
fadeIn(el); // calling the above function



Versus the jQuery equivalent.

$(el).fadeIn();
```
### --------ZAD

```
T31501 - Przygotuj uproszczoną alternatywę dla JQuery udostępniającą uniwersalny selektor "$" pozwalający na wykonanie nastepującej sekwencji (bez dołączania jquery).

    $('#test').style.color = 'red';

```

### --------Links
https://github.com/T3iL/T316-JQuery
https://medium.com/javascript-in-plain-english/why-developers-prefer-vanilla-javascript-over-jquery-e707b249d421

GOOGLE DRIVE: 

https://www.w3.org | https://validator.w3.org | https://www.php.net/manual/en/
### --------Repositiories
https://www.w3schools.com | https://stackoverflow.com | https://css-tricks.com |
### --------On line editors
https://codepen.io/ | https://codesandbox.io/ | https://jsfiddle.net/ |
### ---------Assets
https://cdnjs.com/ | https://fontawesome.com | http://fontello.com/ | https://fonts.google.com/ |
### ---------Stock Img
https://www.pexels.com/ | https://unsplash.com | https://pixabay.com
### ---------License
[MIT](https://choosealicense.com/licenses/mit/)
