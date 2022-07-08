# Kirka.io ESP

# Tamper Monkey
Install the tamper monkey chrome extension

https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en\

Then install the ESP script

https://greasyfork.org/en/scripts/446770-kirka-wallhack

# Bookmarklet

```js
javascript:(function()%7Bfetch('https%3A%2F%2Fraw.githubusercontent.com%2Fseanv999%2FKirka.io%2Fmain%2FESP.js')%0A.then(r%20%3D%3E%20r.text())%0A.then(j%20%3D%3E%20eval(j))%7D)()%3B
```

# Console

```js
fetch('https://raw.githubusercontent.com/seanv999/Kirka.io/main/ESP.js')
.then(r => r.text())
.then(j => eval(j))
```
