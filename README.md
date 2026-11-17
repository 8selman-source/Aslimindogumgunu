# ASLI — The Birthday Experience (yenilenmiş)

## Kurulum
`npm install` ve `npm start`. Render Web Service: Build `npm install`, Start `npm start`.

## Güncellemeler
- Yedi fotoğrafın tamamı Hatıra Ekspresi vagonlarında.
- Her vagonda tarih, başlık, günün önemi ve açıklama.
- Fotoğrafa dokununca büyütme.
- Trenin altında **Anı yazılarını düzenle**: içerik değiştirme ve tam `content.json` indirme.
- Mevcut 3×3 oyun ve diğer bölümler korunmuştur.

## Kalıcı düzenleme
Editörün indirdiği `content.json` dosyasını GitHub deposundaki aynı dosyayla değiştirip commit edin. Render yeniden deploy edince değişiklikler herkes için kalıcıdır. **Bu paket veritabanı veya şifre korumalı yönetici paneli içermez.** Editörde yapılan değişiklikler, GitHub'a yüklenene kadar yalnızca hazırlanan JSON içindedir.

## Güvenlik
Mevcut siteyi herkese açık yayımlamadan önce kişisel fotoğraf ve metinleri paylaşma iznini doğrulayın.


## Samimi tasarım güncellemesi
- Makara ayrı bölümden kaldırıldı; photo-7.jpg trende 7. vagon olarak duruyor.
- Gazete içerik değerleri değiştirilmedi; yalnızca gazete sayfa düzeni değiştirildi.
- Vagon fotoğrafları `object-fit:contain` ile kırpılmadan görüntüleniyor.
- Anı editörü content.json dışa aktarımını korur; GitHub’a yeniden yükleme kalıcılık için gereklidir.
