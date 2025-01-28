# Öğrenci Sınıf Tablosu Projesi

Bu proje, öğrenci bilgilerini düzenli bir şekilde görüntülemek, aramak ve sıralamak için geliştirilmiş interaktif bir web tablosudur.

## 🚀 Özellikler

- **Anlık Arama:** Tablodaki herhangi bir bilgiye göre filtreleme
- **Gelişmiş Sıralama:** Tüm sütunlarda çift yönlü sıralama
- **Responsive Tasarım:** Mobil cihazlara uyumlu görünüm
- **Not Renklendirme:** Yüksek ve düşük notların renkli gösterimi
- **Hover Efektleri:** Kullanıcı dostu görsel geri bildirimler

## 💻 Kullanılan Teknolojiler

- HTML5
- CSS3
- JavaScript (Vanilla)

## 🛠️ Kurulum

1. Projeyi klonlayın:
   ```bash
   git clone https://github.com/KULLANICI_ADINIZ/sinif-tablosu.git
   ```

2. Proje klasörüne gidin:
   ```bash
   cd sinif-tablosu
   ```

3. `sinif_tablosu.html` dosyasını bir web tarayıcısında açın.

## 📱 Kullanım

### Arama Yapma
- Üst kısımdaki arama kutusuna herhangi bir kelime yazarak tablo içeriğinde arama yapabilirsiniz
- Arama öğrenci numarası, isim, soyisim, not veya bölüm bilgilerine göre yapılabilir

### Sıralama
- Herhangi bir sütun başlığına tıklayarak o sütuna göre sıralama yapabilirsiniz
- Tekrar tıklayarak sıralama yönünü değiştirebilirsiniz
- Not sütunu sayısal olarak, diğer sütunlar alfabetik olarak sıralanır

### Not Renklendirmeleri
- 90 ve üzeri notlar yeşil renkte gösterilir
- 70 altı notlar kırmızı renkte gösterilir

## 🔧 Özelleştirme

### Yeni Öğrenci Ekleme
```html
<tr>
    <td>20240999</td>
    <td>Yeni</td>
    <td>Öğrenci</td>
    <td class="not-yuksek">95</td>
    <td>01.01.2003</td>
    <td>Yeni Bölüm</td>
</tr>
```

### Renk Şemasını Değiştirme
CSS içindeki renk kodlarını değiştirerek tasarımı özelleştirebilirsiniz:
```css
:root {
    --yuksek-not: #27ae60;
    --dusuk-not: #c0392b;
    --header-bg: #3498db;
}
```

## 📊 Ekran Görüntüleri
![1](https://github.com/user-attachments/assets/398b1480-f4b3-439c-8948-20ed39a0be1f)



## 📝 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylı bilgi için `LICENSE` dosyasını inceleyebilirsiniz.

## 📞 İletişim

ADINIZ SOYADINIZ - [@github_begumdoganay](https://github.com/github_begumdoganay)

Proje Linki: [https://github.com/begumdoganay/sinif-tablosu](https://github.com/begumdoganay/sinif-tablosu)
