# Hava Durumu Uygulaması

Bu proje, kullanıcıların kayıt olabileceği, giriş yapabileceği ve hava durumu bilgilerini görüntüleyebileceği bir web uygulamasıdır. Kullanıcılar ayrıca diğer kullanıcıları görüntüleyebilir, silebilir veya güncelleyebilirler.

## Özellikler 
- **Giriş ve Kayit**: kullanıcılar kayıt olabilir ve giriş yapabilirler. 
- **Hava Durumu**: Giris yaptiktan sonra, anlık hava durumu ve önümüzdeki 4 günün hava tahmini gösterilir. 
- **Kullanma Yönetimi**: Kullanıcı listesine erişim, kullanıcı bilgilerini silme ve düzenleme imkani. 
- **Veri Saklama**: Kullanıcı bilgileri json dosyasında saklanır.


## Teknolojiler 

**HTML**: Yapisal içerik icin. 
**CSS**: Stil ve düzenleme için. 
**JavaScript**: Dinamik içerik ve etkileşimler için. 
**Node.js**: Backend sunucu işlemleri ve veri yönetimi için.

## Kurulum 
1.**Depoyu Klonlayın:** 
  ``` bash 
  git clone <crepo-url>
   ```

3. **Gerekli Node.js Puketlerini Yukleyin:** 

   ```bash 
  npm install  
  ``` 
4. **Sunucuyu Baslatin:** 
``` bash 
npa start
``` 

5. **Tarayicinaz açın ve` http://localhost:3000` adresine gidin.**

## kullanım

1. **Kayıt**: Ana sayfada kayat fornunu doldurarak kullanıcı olabilirsiniz. İsim, sifre ve sehir bilgilerini girin. Sistem otomatik olarak bir ID atar.
2. **Giris**: Kayıt olduktan sonra giriş yaparak hava durumu sayfasına yönlendirilirsiniz. 
3. **Hava Durumu**: hava durumu sayfasında, seçtiğiniz şehir için mevcut hava durumu ve önümüzdeki 4 günün tahminini görebilirsiniz.
4. **Kullanach Listesi**: Sol istteki tablardan kullanaca listesine erişin, Burada kullanıcılar silebilir veya duzenleyebilirsiniz. 
5. **Silme**: Bir kullanıcıyı silmek için ilgili satindakı "delete" düğmesine basin. kullanıcı bilgileri Json dosyasından kaldırılır.
6. **Güncelleme**: Bir kullanıcıyı güncellemek için ilgili satıraki "edit" düğmesine basın. Kullanıcı bilgileri Json dosyasında güncellenir.


## Proje Yapısı

- **spotify.html**: Kullanıcıların giriş yapabileceği arayüz.
- **sıngup.html**: Kullanıcıların kayıt olabileceği arayüz.
- **havaDurumu.html**: Hava durumu bilgilerini ve kullanıcı listesini görüntüleyen arayüz.
- **havaDurumu.js**: Hava durumu API'si ile etkileşimde bulunan JavaScript dosyası.
- **script.js**: Genel uygulama mantığını yöneten JavaScript dosyası.
- **app.js**: Sunucu tarafında çalışan JavaScript dosyası.
- **spotifyUsers.json**: Kullanıcı bilgilerini saklayan JSON dosyası.

## Özellikler

- Kullanıcı kayıt ve giriş işlemleri.
- Hava durumu bilgilerini görüntüleme.
- Şehir bazında hava durumu arama.
- Kullanıcı listesini görüntüleme, silme ve güncelleme.
- Kullanıcının konumuna göre hava durumu bilgisi alma.

