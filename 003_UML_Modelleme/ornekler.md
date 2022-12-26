# Sipariş İşlemleri Sınıf Tasarımı

![](https://github.com/Kodluyoruz/taskforce/raw/main/oop/class-diagram-example/figures/order-processing.jpg)

```
- 0 veya 1 müşterinin (Customer) en az 1 veya daha fazla siparişi (Order) olabilir.
- Siparişin (Order) ürünü (Product) vardır.
- Stoğun (Stock) ürünü (Product) vardır.
```

---
---
---

# Banka Yönetim Sistemi Sınıf Tasarımı

![](https://github.com/Kodluyoruz/taskforce/raw/main/oop/class-diagram-example/figures/bank-management-systems.jpg)

```
1- Bankanın (Bank) ATM, Müşteri (Customer), Hesap (Account) sınıfları vardır.
2- 1 müşterinin (Customer) en az 1 en çok 2 hesabı (Account) olabilir.
3- 1 hesap (Account) 0 veya daha fazla ATM işlemi yapabilir.
4- Hesap (Account) sınıfına ait iki tane alt sınıf vardır, Ana Hesap (Main Account) ve Birikim Hesabı (Saving Account).
```

---
---
---

# Şirket Yönetim Sistemi Sınıf Tasarımı

![](https://github.com/Kodluyoruz/taskforce/raw/main/oop/class-diagram-example/figures/company-systems.jpg)

```
1- Şirketin (Company) 0 veya daha fazla departman (Department) ve ofisi (Office) vardır.
2- Şirket (Company) olmadan departman (Department) ve ofis (Office) olamaz.
3- Bir departmanın (Department) en az bir çalışanı (Employee) olmalıdır.
4- Bir departman (Department) bir çalışan (Employee) tarafından yönetilir.
5- Ofise (Office) ait bir merkez ofis (Headquarter) olabilir.
```

---
---
---

# Okul Yönetim Sistemi Sınıf Tasarımı

![](https://github.com/Kodluyoruz/taskforce/raw/main/oop/class-diagram-example/figures/school.jpg)

```
1- 1 okulun (School) en az bir veya daha fazla departmanı (Department) olabilir.
2- En az 1 veya daha fazla okulun (School) birden fazla öğrencisi (Student) olabilir.
3- 0 veya daha fazla öğrenci (Student) , en az 1 veya daha fazla ders (Subject) alabilir.
4- En az 1 veya daha fazla dersin (Subject), en az 1 veya daha fazla öğretmeni (Instructor) olabilir.
5- Bir departmanın (Department) en az 1 veya daha fazla dersi (Subject) olabilir.
6- Bir veya daha fazla departmana (Department), 1 veya daha fazla öğretmen (Instructor) atanabilir.
```

---
---
---

# Sipariş Yönetim Sistemi Sınıf Tasarımı

![](https://github.com/Kodluyoruz/taskforce/raw/main/oop/class-diagram-example/figures/order.jpg)

```
1- Bir müşterinin 0 veya daha fazla siparişi olabilir.
2- Bir siparişe ait sipariş detayı ve ürünleri olur.
3- 1 siparişin birden fazla ödemesi olabilir.
4- Nakit , Çek ve Kredi Kartı ödeme yöntemleridir.
```