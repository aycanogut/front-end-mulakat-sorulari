`Promise`, bir kaynaktan veri çekmek amacıyla kullanılan ve asenkron olarak çalışan bir JavaScript özelliğidir. ES6 ile birlikte JavaScript'e dahil olmuştur.

Pending (beklenen), Resolved (çözümlenen) ve Rejected (reddedilen) olmak üzere 3 farklı durum ile yönetilir.

`.then()` fonksiyonu ve `callback`'leri kullanarak API sorgusu yaptığımız kaynaktan gelen verileri yönetebilir, `.catch()` yapısı ile başarsız olan sorgunun hata yönetimini gerçekleştirebiliriz.
Sorgu attığımız kaynaktan gelecek olan verilerin yapısına göre `.then()` fonksiyonunu zincirleme olarak kullanabiliriz. Bu zincirleme yapı kodun okunabilirliğini kötü etkileyeceği için `async-await` özelliğini kullanarak daha okunabilir bir `Promise` yapısı oluşturabiliriz.