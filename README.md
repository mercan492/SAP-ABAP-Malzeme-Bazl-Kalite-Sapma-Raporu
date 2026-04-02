# SAP-ABAP-Malzeme-Bazl-Kalite-Sapma-Raporu
SAP ABAP ile geliştirilmiş, malzeme bazlı kalite sapmalarını analiz eden ve kritik hata oranlarını tespit eden ALV raporu.

🚗 SAP ABAP – Malzeme Bazlı Kalite Sapma Raporu
📌 Proje Hakkında
Bu proje, üretim süreçlerinde kalite performansını analiz etmek amacıyla geliştirilmiş bir SAP ABAP raporudur.
Her bir malzeme için:
•	Muayene sayısı 
•	Hatalı ürün sayısı 
•	Hata oranı (%) 
hesaplanarak, belirlenen eşik değere göre kritik sapmalar otomatik olarak tespit edilir.
👉 Amaç:
Veri odaklı karar alma süreçlerini desteklemek ve kalite problemlerini erken aşamada görünür kılmak.
________________________________________
🎯 Özellikler
•	✔️ Malzeme bazlı kalite analizi 
•	✔️ Dinamik hata oranı hesaplama 
•	✔️ Parametrik eşik değeri (threshold) 
•	✔️ Kritik / Normal sınıflandırma 
•	✔️ ALV (CL_SALV_TABLE) ile modern raporlama 
•	✔️ Hata yönetimi (TRY-CATCH) 
•	✔️ Demo veri ile çalışabilir yapı 
________________________________________
🧠 İş Mantığı
Hata oranı aşağıdaki formülle hesaplanır:
Hata Oranı (%) = (Hatalı Ürün Sayısı / Toplam Muayene Sayısı) * 100
•	Eğer hata oranı > eşik değer → Kritik 
•	Aksi durumda → Normal 
________________________________________
🛠️ Kullanılan Teknolojiler
•	SAP ABAP 
•	ALV (CL_SALV_TABLE) 
•	Internal Tables 
•	Modular Programming (FORM yapısı) 
________________________________________
📊 Örnek Çıktı
Malzeme	Açıklama	Kontrol	Ret	Ret %	Durum
MTR1001	Motor Bloku	1200	55	4.58	Normal
MTR1004	Direksiyon Bağlantısı	650	40	6.15	Kritik
________________________________________
⚙️ Parametreler
Parametre	Açıklama
p_thres	Hata oranı için eşik değer (%)
Varsayılan: 5.00%
![Material Based Quality Deviation Report 6](https://github.com/user-attachments/assets/90a72acf-d4d8-414f-a92a-83767db61614)
![Material Based Quality Deviation Report7](https://github.com/user-attachments/assets/74827e33-01cf-49bc-b042-bc00e10c2602)




