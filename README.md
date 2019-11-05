# KanBagisTakibi

Proje : Kan Bağış Takibi

Sınıflar : 

    1. KanBagisTakip (Test Sınıfı)
    2. KanGrupStok
    3. Hastalar
    4. AcilHasta

KanBagisTakip

İçerisinde ArrayList kullanabilmek için ‘java.util.ArrayList’ kütüphanesi; veri girişi için java.util.Scanner kütüphanesi; uygulamayı bekletmek için java.util.concurrent.TimeUnit kütüphanesi kullanıldı. KanGrupStok sınıfından stokislem nesnesi oluşturuldu, Hastalar sınıfından hasta nesnesi oluşturuldu, AcilHasta sınıfından da acil nesnesi oluşturuldu. Kullanıcıdan veri almak için Scanner sınıfından input nesnesi oluşturuldu. Menü yazdırmak için MenuGetir metodu yazıldı. Menu yazarak işlerin ilgili sınıflara dağıtılması amaçlandı.

KanGrupStok

Kan gruplarını ve stok miktarlarını tutmak için iki adet array oluşturuldu. Stok durumu öğrenme, kan ekleme,  kan kullanma ve kan seviyesi azalınca uyarı vermesi amacıyla uyarı metodları yazıldı.

Hasta

Hasta bilgilerini tutmaları amacıyla 4 adet ArrayList tanımlandı. Getter ve setter metodlarının kullanılması amacıyla her hasta özelliği için private değişkenler ve get,set metodları tanımlandı. İki adet birisi string diğeri integer değer alan hasta arama metodu yazılarak overloading işlemi gerçekleştirildi. Hasta ekleme,hasta silme hasta listeleme ve menu yazdırma metodları yazıldı.

Acil Hasta

Hasta sınıfından miras alındı. Overriding işlemini gerçekleştirmek için Hasta sınıfındaki ilkHasta metodu yeniden yazıldı.
