# Mac OS için Türkçe F Klavye Düzeni

# Nedir?

Yaygın olarak kullanılan F klavye düzeni ile Mac işletim sistemleriyle birlikte gelen F klavye düzeni arasındaki uyumsuzlukları gideren, Windows'taki F klavye dizilimini esas alan bir klavye düzenidir.

## Nasıl yüklenir?

1. Bağlantıda yer alan [TurkceF.bundle](/TurkceF.bundle) dosyasını indirip bilgisayarınızın kullanıcı dizininde bulunan `~/Library/Keyboard Layouts` klasörüne kopyalayın. Klavye düzeninin bilgisayarınızda tanımlı tüm kullanıcılar tarafından kullanılabilmesini istiyorsanız `/Library/Keyboard Layouts` klasörünü tercih edin.

2. _Sistem tercihleri_'nden _Klavye_ ayarlarına gidip _Giriş Kaynakları_ sekmesini açın.

3. Listededen _Türkçe F_ isimli kaynağı aktif hale getirin.

  Birden fazla klavye düzeni kullanıyorsanız _Klavye ve Karakter görüntüleyiciyi menü çubuğunda göster_ seçeneğini aktif hale getirin.

4. Aktif durumdaki klavye düzenini değiştirmek için ekranın sağ üst kısmında, saatin yanındaki klavye sembolüne tıklayın, gelen listeden _Türkçe F_ yi seçin. Menü çubuğunda yer alan _Türkçe F_ yazısını gizlemek isterseniz klavye sembolü üzerine tıklayıp _Giriş kaynağı adını gizle_ tercihini seçin.

5. Bilgisayarınızı yeniden başlatın. (Yeniden başlatmadan bazı programlar yeni klavye düzenini tanımıyorlar.)


## Tuş dizilimi

![F Klavye Tuş Dizilimi](/src/layout.png?raw=true "Tuş Dizilimi")

### Control

![Control](/src/control.png?raw=true "control pressed")

### Alt

![Alt](/src/alt.png?raw=true "alt pressed")

### Cmd + alt

![Cmd + alt](/src/alt_cmd.png?raw=true "cmd + alt pressed")

### Shift + alt

![Shift + alt](/src/alt_shift.png?raw=true "shift + alt presssed")

### Capslock + alt

![Capslock + alt](/src/capslock_alt.png?raw=true "capslock + alt pressed")


## Notlar

â, á, ñ gibi özel işaretler (accent ya da diacritic de deniyor) içeren harfleri doğrudan yazmak mümkün değil. Bunları yazarken önce işareti ardından işaretin kullanılacağı harfi tuşlamamız gerekir. 

![^ ölü tuşu](/src/circumflex.png?raw=true "shift + 3 pressed")

Örneğin, â yazabilmek için önce `Shift + ^` birleşimi ardından a harfini tuşlanmalı. ``^,`´¨~`` gibi doğrudan yazılamayan bu düzenleyici tuşlara [ölü tuşlar](https://en.wikipedia.org/wiki/Dead_key, "Dead key - wikipedia") denir. 

`` ^ ``: `Shift + 3`
`` ` ``: `Alt + x`
`` ´ ``: `Alt + y`
`` ~ ``: `Alt + w`
`` ¨ ``: `Alt + q`

![tilde](/src/glyph_tilde.png?raw=true "tilde kullanan ölü tuşlar")
![acute](/src/glyph_acute.png?raw=true "acute kullanan ölü tuşlar")
![grave](/src/glyph_grave.png?raw=true "grave kullanan ölü tuşlar")
![circumflex](/src/circumflex.png?raw=true "circumflex kullanan ölü tuşlar")
![dieresis](/src/glyph_dieresis.png?raw=true "dieresis kullanan ölü tuşlar")