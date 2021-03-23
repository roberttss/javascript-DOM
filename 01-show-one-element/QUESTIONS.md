# DOM Atomic 01: Show One Element

## Questions

---

> If you click the link to reveal more text and then refresh the page, does the text remain revealed, or is it hidden again? Why?

Ja refresho lapu tad teksts kurš pirms tam bija atklāts uzspeiežot pogu more pasūd.

---

> Remove `window.addEventListener("load", function(){` (and the closing `})`) from **global.js**. Does the link still reveal the text? What is the purpose of this code that you've removed?

load event tiek aktivizēta, kad ir ielādēta visa lapa, ieskaitot visus atkarīgos resursus, piemēram, stilu lapas un attēlus. Tas ir pretstatā DOMContentLoaded, kas tiek aktivizēts, tiklīdz DOM lapa ir ielādēta, negaidot, kamēr resursi tiks pabeigti.

---

> Describe the the `addEventListener` method. (Remember that there is a specific, technical, methodical way to describe methods. Your reply should match that format.)

Nezināju īsti kā tulkot tapēc rakstiju angļu valoda
The addEventListener() method attaches an event handler to an element without overwriting existing event handlers. ... You can add event listeners to any DOM object not only HTML elements. i.e the window object. The addEventListener() method makes it easier to control how the event reacts to bubbling.
