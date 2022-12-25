# Modelleme Nedir ?
Gerçek hayattaki problemleri bilgisayarın sanal ortamında çözebilmek için, her şeyden önce problemin uygun şekilde bilgisayar ortamına aktarılması gerekmektedir. Bu işlem `“soyutlama (abstraction)”` ya da `“modelleme (modeling)”` olarak anılır.

Modelleme, insanın problem çözmek üzere eskiden beri kullandığı bir yöntemdir. Büyükçe bir problemin tamamını zihinde canlandırıp çözmeye çalışmak yerine, oluşturulacak model ya da modeller üzerinde hedef sistemin görünüşü, davranışı ya da bazı durumlarda verdiği tepkiler gözlemlenebilir.

# UML (Unified Modeling Language) Nedir ?
UML’ in Türkçe deki karşılığı “Birleşik Modelleme Dili” olsa da aslında bir programlama dili değil yazılım mühendisliğinde nesne tabanlı modellemede kullanılan standart olmuş görsel modelleme dilidir. Bir yazılımın hayata geçirilmesinde farklı görev tanımlamaları bulunmaktadır (Tasarımcılar, programcılar, analistler, testçiler, kalite sorumluları, kullanıcılar) gibi. Bir yazılım için her kişinin farklı bakış açısı vardır. Müşteri açısından projeye baktığımızda müşteriyi işlerin sıralandırılması, sisteme artıları ve eksileri , işler arasındaki ilişkiler ilgilendirirken bir fonksiyonun detayları ilgilendirmemektedir. Analist açısından baktığımızda nesne özellikleri, fonksiyonlar ve alacakları parametreler yeterli iken tasarımcı açısından parametrelerin veri tipleri, fonksiyonun performansı, yaşam süresi gibi bilgiler de önemli olmaktadır.

Bu nedenle UML bu ekip için gerekli farklı diyagramlar içermektedir. Yazılım geliştirme işinde yer alacak farklı ekiplerin farklı bakış açılarına uygun farklı UML diyagramları bulunmaktadır.

# Peki Neden UML ?
```
1- Hataların kolaylıkla fark edilip en düşük seviyeye indirgenmesi.(Risk, zaman, maliyet)
2- Kodlama kolaylığı sağlar.
3- Kullanılan tekrar kod sayısı ayırt edilebilir bu sayede verim sağlanır.
4- Mantıksal hataların minimum seviyeye düşürülmesini sağlar.
5- Geliştirme maliyetinin düşmesini sağlar.
6- Resmin tamamının görülmesini sağlar.
7- UML diyagramları ile yazılım tamamını görebileceğimiz için verimli bellek kullanımı sağlanabilir.
8- Karmaşık sistemlerde değişiklik yapmayı kolaylaştırır.
9- UML ile dokümanlandırılmış kodları düzenlemek daha az zaman alacaktır.
10- UML diyagramlarını kullanan yazılımcılar aynı dili konuşacaklarından kolay iletişim sağlanır.
```

# Sınıf Diyagramları (Class Diagram)
Nesne yönelimli programlamada her bir nesnenin konseptini belirten yapılara sınıf (class) adı verilmektedir. Sınıflar çok farklı yapılarda ve işlevlerde olabilirler. Bununla birlikte, genellikle programlamada bütün iş tek bir sınıfın üzerine yüklenmez. Kuracağınız sistem ile ilgili önce temel sınıflar belirlenip daha sonra bunlar arasındaki bağlantıların açıklanması gerekir. Bunu bir yazılım geliştirme sürecinin tasarım aşamasında yaparız. Burada sınıfların modellemesi için UML kullanırız ve Sınıf Diyagramları adı veririz.

Programlamada sınıfların niteliklerini "değişkenler" , davranışlarını da "metotlar" tanımlar.

# Sınıf Tanımlama

![alt text](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/oop/uml-class-diagram/figures/c1.jpg)

Şekilde görüldüğü üzere bir dikdörtgen 3 parçaya bölünerek, ilk parçasına "Sınıf Adını", ikinci parçaya "Sınıfın Değişkenleri" , son parçaya da "Sınıf Metotları" yazılır.

