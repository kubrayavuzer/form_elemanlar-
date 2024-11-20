# HTML Formu - Kullanıcı Bilgileri

Bu proje, kullanıcıların kişisel bilgilerini toplamak için kullanılan bir HTML formunu içermektedir. Formda, kullanıcıların adını, soyadını, e-posta adresini, parolasını, cinsiyetini, favori meyvesini ve bir mesaj yazmalarını sağlayan çeşitli form elemanları bulunmaktadır.

## Gereksinimler

1. **Ad ve Soyad**: Kullanıcının adını ve soyadını girebileceği iki metin kutusu.
2. **E-posta Adresi**: Kullanıcının e-posta adresini girebileceği bir e-posta giriş alanı.
3. **Parola**: Kullanıcının parolasını girebileceği bir parola giriş alanı.
4. **Cinsiyet**: Kullanıcının cinsiyetini seçebileceği iki radyo düğmesi (Erkek ve Kadın).
5. **Favori Meyve**: Kullanıcının favori meyvesini seçebileceği bir açılır liste (örneğin, Elma, Muz, Çilek).
6. **Mesaj**: Kullanıcının yazabileceği bir metin alanı.
7. **Gönder Butonu**: Kullanıcı bilgilerini göndermek için bir "Gönder" düğmesi.

## Kullanılan HTML Form Elemanları

- **Metin Kutuları**: `<input type="text">` etiketi ile kullanıcı adı ve soyadını almak için kullanıldı.
- **E-posta Girişi**: `<input type="email">` etiketi ile kullanıcıdan geçerli bir e-posta adresi alındı.
- **Parola Girişi**: `<input type="password">` etiketi kullanılarak şifre gizlendi.
- **Radyo Düğmeleri**: `<input type="radio">` etiketi ile cinsiyet seçimi yapıldı.
- **Açılır Liste**: `<select>` ve `<option>` etiketleri ile kullanıcıya meyve seçenekleri sunuldu.
- **Metin Alanı**: `<textarea>` etiketi ile kullanıcıya mesaj yazması için alan sağlandı.
- **Gönder Butonu**: `<button type="submit">` etiketi ile form gönderme işlemi sağlandı.
