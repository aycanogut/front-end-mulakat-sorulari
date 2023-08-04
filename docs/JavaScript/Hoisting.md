Hoisting, JavaScript'in çalışma zamanındaki değişken ve fonksiyon tanımlamalarının, kodun en üstüne taşındığı davranışıdır. Bu, JavaScript motorunun kodu çalıştırmadan önce, değişkenleri ve fonksiyonları önceden bildiği anlamına gelir. Hoisting yapısı `var` ve `function` anahtar kelimeleri ile tanımlandığında etkilerini gösterir.

Ancak `let` veya `const` anahtar kelimeleriyle tanımlanan değişkenlerde hoisting etkisi yoktur ve bu değişkenler tanımlandıkları satırda değer alır.

Fonksiyonlar da hoisting etkisine sahiptir. Fonksiyonlar, fonksiyonun tanımlandığı kod bloğunun başına taşınır ve bu nedenle tanımlandan önce kullanılabilirler:

```js
sayHello(); // "Hello"

function sayHello() {
  console.log("Hello");
}
```
