
# if'in içindeki fonksiyon

<<<<<<< HEAD:1-js/06-advanced-functions/03-closure/3-function-in-if/task.md
Aşağıdaki son satır çalıştığında sonuç ne olur?
=======
Look at the code. What will be the result of the call at the last line?
>>>>>>> 6989312841d843f2350803ab552d9082437be569:1-js/06-advanced-functions/03-closure/5-function-in-if/task.md

```js run
let sozcuk = "Merhaba";

if (true) {
  let kullanici = "Ahmet";

  function selamVer() {
    alert(`${sozcuk}, ${kullanici}`);
  }
}

*!*
selamVer();
*/!*
```
