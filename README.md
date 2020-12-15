# (2020.12.07-14-15) T316-JQuery

## -------INFO
```
1. Icons (https://iconify.design/icon-sets/)
2. JQuery (https://jquery.com/)
```

jQuery is a lightweight, "write less, do more", JavaScript library.

The purpose of jQuery is to make it much easier to use JavaScript on your website.

The jQuery library contains the following features:

- HTML/DOM manipulation
- CSS manipulation
- HTML event methods
- Effects and animations
- AJAX
- Utilities

Tip: In addition, jQuery has plugins for almost any task out there.

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
T31601 - Przygotuj odpowiedniki funkcji (fadeToggle, slideUp, toggleClass) pochodzące z JQuery w Vanilla Javascript.

T31602 - Przygotuj uproszczoną alternatywę dla JQuery udostępniającą uniwersalny selektor "$" 
         pozwalający na wykonanie nastepującej sekwencji (bez dołączania jquery).

    $('#test').style.color = 'red';
    
T31603 - Przygotuj w Vanilla Javascript odpowiednik Accordion z JqueryUI albo z Bootstrapa 

          https://jqueryui.com/accordion/

          https://getbootstrap.com/docs/5.0/components/accordion/

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
