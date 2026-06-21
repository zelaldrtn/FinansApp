# FinansApp - Modern .NET MAUI Mobil Finans Yönetimi

FinansApp, kullanıcıların gelir ve giderlerini minimalist, kurumsal ve modern bir arayüz üzerinden takip etmelerini sağlayan, .NET MAUI ve SQLite tabanlı bir mobil finansal yönetim uygulamasıdır. Proje geliştirilirken hem yüksek UI/UX standartlarına hem de güvenli kod yazım (Secure Coding) prensiplerine sadık kalınmıştır.

## Öne Çıkan Özellikler

* **Premium UI/UX Tasarımı:** Soft krem ve pastel tonlarında, göz yormayan modern kart (Border/Frame) yerleşimlerine sahip dashboard tasarımı.
* **Gelişmiş Finansal Raporlama:** SQLite üzerinde `GROUP BY` ve `SUM` agregasyonları kullanılarak, harcamaların kategorilerine göre otomatik analiz edilmesi ve bütçe durumunun anlık hesaplanması.
* **Siber Güvenlik Standartları (Secure Coding):** Uygulama içerisindeki tüm veri tabanı süreçleri **Parametreli Sorgular (SQLiteParameter)** ile yönetilerek, siber güvenlik dünyasındaki en kritik açıklardan biri olan **SQL Injection** riskine karşı tamamen korumalı hale getirilmiştir.
* **Asenkron Mimari:** Veri tabanı işlemleri `async/await` yapısıyla asenkron olarak yürütülür; bu sayede arayüz (UI Thread) kilitlenmeden akıcı bir performans sunulur.

## Teknolojik Altyapı

* **Framework:** .NET MAUI (C# / XAML)
* **Veri Tabanı:** SQLite (Secure & Parameterized queries)
* **Tasarım Standartları:** MVVM mimarisi ve Modern Dashboard UI
