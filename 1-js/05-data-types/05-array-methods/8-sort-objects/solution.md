```js run no-beautify
<<<<<<< HEAD
function sortByName(arr) {
  arr.sort((a, b) => a.adi > b.adi);
=======
function sortByAge(arr) {
  arr.sort((a, b) => a.age - b.age);
>>>>>>> 29216730a877be28d0a75a459676db6e7f5c4834
}

let muzaffer = { adi: "Muzaffer", yas: 25 };
let mehmet = { adi: "Mehmet",yas: 30 };
let ahmet = { adi: "Ahmet", yas: 28 };

let arr = [   muzaffer , mehmet, ahmet ];

sortByName(arr);

// şimdi: [ahmet, mehmet, muzaffer]
alert(arr[1].adi) // Mehmet
```

