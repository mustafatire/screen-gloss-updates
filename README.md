<p align="center">
  <img src="docs/logo.png" width="88" alt="Ekran Çevir simgesi">
</p>

<h1 align="center">Ekran Çevir</h1>

<p align="center">
  <strong>Ekrandaki yazıları tek tuşla okuyup Türkçeye çeviren Windows aracı.</strong><br>
  Çeviri, orijinal metnin üzerinde kartlar hâlinde görünür; kapattığınızda ekran eski hâline döner.
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/mustafatire/ekran-cevir-updates?label=s%C3%BCr%C3%BCm&color=2563eb" alt="Sürüm">
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white" alt="Windows 10 / 11">
</p>

<p align="center">
  <a href="https://github.com/mustafatire/ekran-cevir-updates/releases/latest/download/EkranCevir.exe"><strong>⬇️ EkranCevir.exe'yi indir</strong></a>
  &nbsp;•&nbsp;
  <a href="https://github.com/mustafatire/ekran-cevir-updates/releases">Tüm sürümler</a>
</p>

![Ekran Çevir çeviri kartları](docs/onizleme.png)

<p align="center"><sub>Örnek bir sayfa üzerinde uygulamanın gerçek çeviri kartları. Orijinal metin, kartların arkasında soluk görünür.</sub></p>

## Nedir?

**Ekran Çevir**, Windows'un yerleşik OCR motoruyla ekrandaki metni okur ve seçtiğiniz dile
çevirir. Sonucu ayrı bir pencereye taşımak yerine, metnin tam üzerine yerleştirilen
kartlarda gösterir. Böylece video, oyun, PDF veya web sayfasındaki yabancı metni ekrandan
ayrılmadan takip edebilirsiniz.

Kurulum gerektirmez: tek bir `.exe` dosyasıdır ve sistem tepsisinde sessizce çalışır.

## Öne çıkanlar

- **Tek tuşla tam ekran çeviri** — `Ctrl + Alt + T`
- **Bölge seçerek çeviri** — `Ctrl + Alt + R`; fareyle istediğiniz alanı seçin
- **Panodan çeviri** — `Ctrl + Alt + C`; kopyaladığınız metni ayrı pencerede çevirin
- **16 hedef dil** — Türkçe varsayılan; İngilizce, Almanca, Rusça, Arapça, Japonca ve daha fazlası
- **Yerinde çeviri kartları** — metinlerin üzerine yerleşir; `Space` ile orijinali görün, `Esc` ile kapatın
- **Yazı boyutu kaydırıcısı** — sürüklerken ekran üzerinde canlı önizleme
- **Sistem tepsisi** — arka planda sessiz çalışır, Windows ile başlatılabilir
- **Otomatik güncelleme** — yeni sürüm çıkınca bildirim gelir; tek tıkla güncellenir
- **Kısayolları duraklat** — oyun veya başka bir programla çakışırsa geçici olarak kapatın

## Hızlı başlangıç

1. **İndirin:** [EkranCevir.exe](https://github.com/mustafatire/ekran-cevir-updates/releases/latest/download/EkranCevir.exe) dosyasına tıklayın.
2. **Çalıştırın:** İndirilen dosyaya çift tıklayın. Kurulum yoktur; uygulama sistem tepsisinde açılır.
3. **Çevirin:** Çevirmek istediğiniz metni ekrana getirip `Ctrl + Alt + T` tuşlarına basın.
4. **Kapatın:** `Esc` veya farenin sol tuşu.

> Windows "Bilinmeyen yayıncı" uyarısı gösterirse **Ek bilgi > Yine de çalıştır** seçeneğini
> kullanın. Dosya imzasızdır; yalnızca güvendiğiniz kaynaktan indirin.

İlk açılışta kısa bir tanıtım kartı görünür. Tepsi menüsündeki **Kısayolları göster** ile
bu kartı daha sonra yeniden açabilirsiniz.

## Kısayollar

| Kısayol | İşlev |
|---|---|
| `Ctrl + Alt + T` | Tüm ekranı çevir |
| `Ctrl + Alt + R` | Fareyle seçilen bölgeyi çevir |
| `Ctrl + Alt + C` | Panodaki metni çevir |
| `Ctrl + Alt + Shift + Q` | Uygulamadan çık |

> `Ctrl + Alt + T` ve `Ctrl + Alt + R`, Türkçe klavyede sırasıyla `₺` ve `®` üretmek için de
> kullanılır. Bu tuşları sık kullanıyorsanız ya da başka bir program aynı kısayolu kullanıyorsa
> Ayarlar'dan farklı bir birleşim seçin.

### Sonuç ekranı

Çeviri kartları göründüğünde:

- `Space` veya `O` — orijinal ekran ile çeviri arasında geçiş yapın.
- `Esc` veya farenin sol tuşu — çeviriyi kapatın.
- `Ctrl + C` — tüm çevrilmiş metni panoya kopyalayın ve kapatın.

Ekranın altındaki ipucu çubuğu kullanılabilecek tuşları hatırlatır.

## Ayarlar

Tepsi simgesine sağ tıklayıp **Ayarlar…** bölümünü açın.

- **Kısayollar:** Kutudaki metni silip istediğiniz tuş birleşimini basın. Ctrl, Alt veya Win
  ile birlikte bir tuş ya da tek başına **F1–F24** kullanılabilir. Tek başına harf atanamaz
  (o harf tüm programlarda yazmayı engellerdi). Aynı birleşim iki işleve atanamaz.
- **Hedef dil:** Varsayılan Türkçe. 16 dil arasından seçilebilir; tepsi menüsünden de hızlıca
  değiştirilebilir.
- **Yazı boyutu:** %80–%150 arası kaydırıcı. Sürüklerken çeviri kartlarının boyutu ekran
  üzerinde canlı olarak önizlenir.
- **Arka plan karartma:** Çeviri kartlarının okunurluğunu artırmak için ekranın ne kadar
  karartılacağını belirler.
- **OCR metin dili:** Normalde **Otomatik** bırakın. Seçeneğin yanındaki **?** simgesine
  fareyle gelince ayrıntılı açıklama görünür.
- **Ayarları sıfırla:** Kısayollar, hedef dil, yazı boyutu, karartma ve OCR dilini varsayılan
  değerlere döndürür. Uygulamak için **Kaydet**'e basın.

<p align="center">
  <img src="docs/ayarlar.png" alt="Ekran Çevir ayarlar penceresi">
</p>

Tepsi menüsünde ayrıca **Kısayolları duraklat**, **Windows ile başlat**, **Günlük dosyasını aç**,
**Güncellemeler** ve **Hakkında** seçenekleri bulunur.

## Desteklenen diller

Çeviri hedefi olarak 16 dil: **Türkçe**, İngilizce, Almanca, Fransızca, İspanyolca, İtalyanca,
Rusça, Arapça, Hollandaca, Portekizce, Lehçe, Ukraynaca, Azerice, Japonca, Korece,
Çince (Basitleştirilmiş).

> Kaynak metin Latin alfabesi dışındaysa (Rusça, Arapça, Çince vb.) Windows Ayarları >
> **Zaman ve dil** bölümünden ilgili dilin OCR paketini eklemeniz gerekir.

## Gereksinimler

- **Windows 10 veya 11 (64 bit)**
- **İnternet bağlantısı** (çeviri için)
- Python veya ek kurulum gerekmez; tek EXE yeterlidir

## Gizlilik ve notlar

- Çevrilecek metinler Google'ın çeviri servisine gönderilir. Google yanıt vermezse MyMemory
  servisi denenir. Gizli veya hassas metinlerde bunu göz önünde bulundurun.
- Uygulama hesap açmanızı istemez, reklam göstermez. Ayarlar, önbellek ve günlük dosyaları
  `%LOCALAPPDATA%\EkranCevir` klasöründe tutulur.
- DRM korumalı video içerikleri (Netflix, Disney+ vb.) ve bazı tam ekran oyunlar siyah görüntü
  verebilir; bu Windows'un ekran yakalama kısıtlamasıdır. Oyunu "pencereli / borderless" moda alın.
- Çok küçük, bulanık veya düşük kontrastlı yazılar OCR tarafından okunamayabilir. Bölge
  seçimiyle yakınlaştırmak çoğu zaman yardımcı olur.
- Çeviriler makine çevirisidir; teknik terimlerde, deyimlerde ve kısaltmalarda hata olabilir.

## Güncellemeler

- Uygulama açılışta ve günde birkaç kez yeni sürüm kontrolü yapar; güncelleme varsa bildirim
  ve bir pencere gösterir.
- **Şimdi güncelle** ile yeni EXE indirilir, SHA-256 özeti doğrulanır ve uygulama kendini
  değiştirip yeniden başlatır. Ayarlarınız ve önbellek korunur.
- Güncelleme kontrolünü tepsi menüsündeki **Güncellemeler > Şimdi kontrol et** ile hemen
  yapabilir, otomatik kontrolü aynı menüden kapatabilirsiniz.
- Güncelleme dosyaları bu depodaki [Releases](https://github.com/mustafatire/ekran-cevir-updates/releases)
  bölümünden yayınlanır. **Eski sürümler silinmez**; her sürüm kendi etiketiyle arşivde kalır.

## Bu depo hakkında

Bu depo, Ekran Çevir'in otomatik güncelleme dosyalarını (`EkranCevir.exe`, `latest.json`) ve
bu tanıtım sayfasını barındırır. Kaynak kod bu depoda yayınlanmaz.

- Son sürümü indir: [EkranCevir.exe](https://github.com/mustafatire/ekran-cevir-updates/releases/latest/download/EkranCevir.exe)
- Sürüm arşivi: [Releases](https://github.com/mustafatire/ekran-cevir-updates/releases)

## Geri bildirim

Hata bildirimi, öneri veya soru için [Issues](https://github.com/mustafatire/ekran-cevir-updates/issues)
bölümünü kullanabilirsiniz.

---

<p align="center"><sub>Ekran Çevir • Windows için ekran çevirmeni</sub></p>
