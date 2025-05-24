Uçuş Rezervasyon Sistemi – Kendi Geliştirdiğim Projenin Özeti
	•	Java dilinde geliştirdiğim basit bir uçuş rezervasyon sistemi yaptım.
	•	Konsol üzerinden çalışıyor; kullanıcı arayüzü sade ve etkileşimli.
	•	İlk olarak bir uçak ve kalkış lokasyonu tanımladım.
	•	Bu bilgilerle örnek bir uçuş oluşturdum ve kullanıcıya seçim sunuyorum.
	•	Kullanıcıdan ad, soyad ve yaş bilgisi alınıyor.
	•	Uçakta boş koltuk var mı diye kontrol ediyorum.
	•	Eğer koltuklar doluysa kullanıcıya bilgi verip rezervasyonu engelliyorum.
	•	Boş yer varsa rezervasyon oluşturuluyor.
	•	Rezervasyonlar JSON formatında kaydediliyor, böylece kalıcı oluyor.
	•	Eski rezervasyonları da dosyadan okuyarak sistemin devamlılığını sağlıyorum.
	•	Tüm dosya okuma/yazma işlemleri için ayrı bir sınıf (JsonFileManager) kullandım.
	•	Sınıfları modüler ve okunabilir şekilde yazmaya özen gösterdim.
	•	Kod yapısı genişletilebilir; örneğin çoklu uçuş, koltuk numarası, rezervasyon iptali gibi geliştirmeler kolayca eklenebilir.
