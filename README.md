# nominatim_api

⸻

Nominatim Türkiye API (x86_64)

Türkçe Açıklama

📌 Nominatim API Nedir?

Nominatim, OpenStreetMap (OSM) verilerini kullanarak adresleri koordinatlara (geocoding) ve koordinatları adreslere (reverse geocoding) dönüştüren açık kaynaklı bir coğrafi kodlama servisidir. Kullanıcılar, serbest metin veya yapılandırılmış sorgular aracılığıyla belirli yerleri arayabilir ve bu yerlerin coğrafi koordinatlarını elde edebilirler. Ayrıca, belirli bir koordinata karşılık gelen adres bilgilerini de sağlayabilir.  ￼

🚀 Proje Hakkında

Bu proje, Nominatim API’nin Türkiye verileriyle önceden entegre edilmiş ve x86_64 mimarisi için optimize edilmiş Docker imajını sunar. Bu imaj, Türkiye genelindeki OSM verilerini içerir ve sabit bir veri setiyle çalışır; yani, veri güncellemeleri yapılmaz.

🧩 Özellikler
	•	Türkiye genelindeki OSM verileriyle entegre
	•	Sabit veri seti (güncellenmeyen)
	•	x86_64 mimarisi için optimize edilmiş Docker imajı
	•	Kolay kurulum ve kullanım

📦 Docker İmajı

Aşağıdaki komutla Docker imajını çekebilirsiniz:
```
docker pull ghcr.io/muhammedfurkansahin/nominatim-turkey-api-x86-64:v1.0
```
⚙️ Kullanım

Docker konteynerini aşağıdaki şekilde çalıştırabilirsiniz:
```
docker run -d -p 8080:8080 ghcr.io/muhammedfurkansahin/nominatim-turkey-api-x86-64:v1.0
```
Bu komut, Nominatim API’yi 8080 portu üzerinden erişilebilir hale getirir.

🔗 API Uç Noktaları
	•	/search – İleriye dönük coğrafi kodlama (adres → koordinatlar)
	•	/reverse – Geriye dönük coğrafi kodlama (koordinatlar → adres)
	•	/lookup – Belirli OSM nesneleri için adres bilgileri
	•	/status – Sunucu durumu ￼ ￼

Daha fazla bilgi için resmi Nominatim belgelerine başvurabilirsiniz:  ￼

📄 Lisans

Bu proje, OpenStreetMap topluluğunun katkılarıyla oluşturulan verileri kullanır ve ODbL lisansı altında lisanslanmıştır. ￼

⸻

English Description

📌 What is Nominatim API?

Nominatim is an open-source geocoding service that utilizes OpenStreetMap (OSM) data to convert addresses into geographic coordinates (geocoding) and vice versa (reverse geocoding). Users can perform searches using free-form text or structured queries to find specific locations and obtain their geographic coordinates. Additionally, it provides address information corresponding to a given coordinate.  ￼ ￼

🚀 About the Project

This project offers a Docker image of the Nominatim API preloaded with Turkey’s OSM data and optimized for x86_64 architecture. The image operates with a static dataset, meaning it does not receive updates.

🧩 Features
	•	Integrated with Turkey’s OSM data
	•	Static dataset (non-updating)
	•	Docker image optimized for x86_64 architecture
	•	Easy setup and usage ￼

📦 Docker Image

Pull the Docker image using the following command:
```
docker pull ghcr.io/muhammedfurkansahin/nominatim-turkey-api-x86-64:v1.0
```
⚙️ Usage

Run the Docker container with the following command:
```
docker run -d -p 8080:8080 ghcr.io/muhammedfurkansahin/nominatim-turkey-api-x86-64:v1.0
```
This command makes the Nominatim API accessible via port 8080.

🔗 API Endpoints
	•	/search – Forward geocoding (address → coordinates)
	•	/reverse – Reverse geocoding (coordinates → address)
	•	/lookup – Address details for specific OSM objects
	•	/status – Server status ￼ ￼

For more information, refer to the official Nominatim documentation:  ￼

📄 License

This project utilizes data contributed by the OpenStreetMap community and is licensed under the ODbL license. ￼

⸻

```
 __  __     _____           _                 ____        _     _       
|  \/  |   |  ___|   _ _ __| | ____ _ _ __   / ___|  __ _| |__ (_)_ __  
| |\/| |   | |_ | | | | '__| |/ / _` | '_ \  \___ \ / _` | '_ \| | '_ \ 
| |  | |_  |  _|| |_| | |  |   < (_| | | | |  ___) | (_| | | | | | | | |
|_|  |_(_) |_|   \__,_|_|  |_|\_\__,_|_| |_| |____/ \__,_|_| |_|_|_| |_|
                                                )__)                    
```
