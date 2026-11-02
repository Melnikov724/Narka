# Narka Book Reader

Word (.docx) dosyasını tarayıcıda baştan sona sesli okuyan, kaldığın yeri ve kırmızı kurdeleni hatırlayan tek sayfalık okuyucu.

- Metin olduğu gibi okunur; araya ekleme, çıkarma ya da yapay zekâ yorumu girmez.
- Dosya hiçbir sunucuya yüklenmez. Kaldığın yer, kurdele ve kitaplık tarayıcının kendi hafızasında durur.
- Ses, tarayıcının sesleridir. Edge'de "Natural" yazan Türkçe sesler en iyisidir.

## Kullanım

1. `index.html` dosyasını Edge ya da Chrome'da aç.
2. Word dosyasını seç ya da sayfaya sürükle.
3. Oku düğmesine bas. İstediğin paragrafa tıklayıp oradan başlatabilirsin.
4. Kurdele koy düğmesi o paragrafı işaretler. Kurdeleye git ile döner.

Boşluk tuşu okuyu başlatır ve durdurur, sağ/sol ok tuşları paragraf atlar.

## GitHub Pages ile yayınlama

1. GitHub'da yeni bir depo (repository) oluştur. Örneğin `narka-book-reader`.
2. `index.html` ve `README.md` dosyalarını depoya yükle (Add file, Upload files).
3. Depoda Settings, Pages bölümüne gir. "Deploy from a branch" seç, branch olarak `main` ve klasör olarak `/ (root)` seç, Save de.
4. Bir iki dakika sonra sayfan `https://KULLANICI-ADIN.github.io/narka-book-reader/` adresinde açılır.

Kitaplar ve kurdeleler her kişinin kendi tarayıcısında saklanır; sayfayı paylaştığında kimse senin kitaplarını görmez.
