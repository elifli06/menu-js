# menu-js

Projede HTML ,CSS BOOTSTRAP  VE JS KULLANILMIŞTIR.

Bootstrap cdn: "https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.2/css/bootstrap.min.css" />

Proje gif:menü.gif

JAVASCRIPT
-Data.js'den gelen menü dizisini array metodu olarak dönme işlemi yapıldı.
-Diziden dönen her bir veri için ekrana bir eleman bastırma işlemi yapıldı.
-Sayfa yüklendiinde fonksiyonları çalıştırma işlemi yapıldı.
-forEach ile filtreleme işlemi yapan butonlara dönme işelmi yapıldı.
(forEach kullanma nedenimiz map metodunun,sadece dizilerde kullanılabilmesinden kaynaklanıyor.)
-Her bir butona bir olay dinleyicisi eklendi.
-Filtreleme işlemi yapacak olan fonksiyona o an tıklanılan butonun category bilgisini parametre olarak gönderme işelemi yapıldı.
    
  NOT:  Filter metodu tüm menuyü döner ve verilen parametre doğrultusunda  yeni diziyi geri döndürür.

  Menumüzden dönen elemanların category bilgisi parametre olarak gelen "categoryInfo " eşit ise bu elamanı ekleyerek yeni dizi oluşturma işlemi yapıldı.  

Tıklanılan buton "all ise tüm menuyü gösterme, 
Tıklanılan button "all" değilse eğer;
Tıklanılan  butondan da dönen diziyi gösterme işlemleri yapıldı.

