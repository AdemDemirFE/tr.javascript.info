importance: 4

---

# Fonksiyonu '?' veya '||' kullanarak tekrar yazınız.

Aşağıdaki fonksiyon 

Aşağıdaki fonksiyon eğer `yas` parametresi `18`'den büyükse `true` dönderir. 

Diğer türlü onay sorar ve sonucunu döndürür.

```js
function yasKontrolu(yas) {
  if (yas > 18) {
    return true;
  } else {
<<<<<<< HEAD:1-js/02-first-steps/14-function-basics/2-rewrite-function-question-or/task.md
    return confirm('Ebeveynlerin izin verdi mi?');
=======
    return confirm('Did parents allow you?');
>>>>>>> 246c600f11b4e6c52b4ae14f83e65319671f998f:1-js/02-first-steps/15-function-basics/2-rewrite-function-question-or/task.md
  }
}
```

`if` yazmadan aynı işlemi tek satırda yapan kodu yazınız.

`yasKontrolu` fonksiyonunun iki türlü versiyonunu yazınız.

1. `'?'` operatörünü kullanarak.
2. veya kullanarak `||`. 
