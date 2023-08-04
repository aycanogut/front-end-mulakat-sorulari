`useContext`, bir bileşen içerisinde belirli bir context (kaynak) içindeki verilere erişmek için kullanılır.

React uygulamalarında prop'lar kapsayıcı bileşenden çocuk bileşenlere aktarıldığı için, çok fazla bileşenin iç içe kullanıldığı durumlarda gereksiz bir prop aktarımı gerçekleşebilir. Bu duruma `prop drilling` adı verilir. `useContext` bu probleme bir çözüm olarak getirilmiştir.

Context, React ağacı içerisindeki herhangi bir yerde bulunan bir veri deposudur. Bileşenler, bu bağlama `Provider` bileşeni ile veri ekleyebilirler ve `Consumer` bileşeni ile bu verilere erişebilirler. 