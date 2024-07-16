# Sınıf Diyagram Örnekleri

## Sipariş İşlemleri Sınıf Tasarımı

![Sipariş İşlemleri Sınıf Tasarımı](images/0.jpg)

- 0 veya 1 müşterinin (Customer) en az 1 veya daha fazla siparişi (Order) olabilir.
- Siparişin (Order) ürünü (Product) vardır.
- Stoğun (Stock) ürünü (Product) vardır.

## Banka Yönetim Sistemi Sınıf Tasarımı

![Banka Yönetim Sistemi Sınıf Tasarımı](images/1.jpg)

- Bankanın (Bank) ATM, Müşteri (Customer), Hesap (Account) sınıfları vardır.
- 1 müşterinin (Customer) en az 1, en çok 2 hesabı (Account) olabilir.
- 1 hesap (Account) 0 veya daha fazla ATM işlemi yapabilir.
- Hesap (Account) sınıfına ait iki tane alt sınıf vardır: Ana Hesap (Main Account) ve Birikim Hesabı (Saving Account).

## Şirket Yönetim Sistemi Sınıf Tasarımı

![Şirket Yönetim Sistemi Sınıf Tasarımı](images/2.jpg)

- Şirketin (Company) 0 veya daha fazla departman (Department) ve ofisi (Office) vardır.
- Şirket (Company) olmadan departman (Department) ve ofis (Office) olamaz.
- Bir departmanın (Department) en az bir çalışanı (Employee) olmalıdır.
- Bir departman (Department) bir çalışan (Employee) tarafından yönetilir.
- Ofise (Office) ait bir merkez ofis (Headquarter) olabilir.

## Okul Yönetim Sistemi Sınıf Tasarımı

- 0 veya daha fazla öğrenci (Student), en az 1 veya daha fazla ders (Subject) alabilir.
- En az 1 veya daha fazla dersin (Subject), en az 1 veya daha fazla öğretmeni (Instructor) olabilir.
- Bir departmanın (Department) en az 1 veya daha fazla dersi (Subject) olabilir.
- Bir veya daha fazla departmana (Department), 1 veya daha fazla öğretmen (Instructor) atanabilir.

## Sipariş Yönetim Sistemi Sınıf Tasarımı

![Sipariş Yönetim Sistemi Sınıf Tasarımı](images/4.jpg)

- Bir müşterinin (Customer) 0 veya daha fazla siparişi (Order) olabilir.
- Bir sipariş (Order) detayları (Order Detail) ve ürünleri (Product) içerir.
- 1 sipariş (Order) birden fazla ödemeye (Payment) sahip olabilir.
- Ödeme yöntemleri: Nakit (Cash), Çek (Check) ve Kredi Kartı (Credit Card).
