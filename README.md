# HTML ve CSS Notları

## Etiketler
HTML, görsel ve metinsel içerikleri tanımlayan etiketleri kullanır. Her etiket, bir başlangıç ve bitiş etiketi içerir(bazıları hariç) ve bazıları iç içe kullanılabilir.

- `<html>`: Tüm HTML içeriğini sarmalar.
- `<title>`: Sayfanın sekme başlığını belirtir.
- `<body>`: Sayfanın görüntülenen içeriğini barındırır.
- Başlık etiketleri: `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>` - Metin başlıkları için kullanılır ve önem sıralarını belirtir.
- `<p>`: Paragraf etiketi, metinleri düzenler ve satır başı ekler.
- Biçimlendirme etiketleri:
  - `<b>`: Kalın yazı tipini uygular.
  - `<strong>`: Metnin önemli olduğunu belirtir.
  - `<i>`: İtalik yazı tipini uygular.
- `<hr>`: Yatay çizgi ekler.

## Listeler
HTML'de sırasız ve sıralı listeler kullanılabilir:<br>
**Sırasız Liste:**
```
<ul>
    <li>Öğe 1</li>
    <li>Öğe 2</li>
</ul>
```

**Sıralı Liste:**
```
<ol>
    <li>Öğe 1</li>
    <li>Öğe 2</li>
</ol>
```
<br>
- Start attribute ile listenin kaçla başlayacağını belirledik.<br>
- Type attribute ile listenin ne ile sıralanacağını belirledik.

```
<ol start="2" type="a">
    <li>Lorem, ipsum dolor.</li>
    <li>Lorem, ipsum dolor.</li>
   </ol>
```
   
-Listeyi hızlıca oluşturmak için kısayol:ol>li*5<br>

**img ekleme:**
``` <img src="dizin ismi/dosya adı" alt="fotograf yüklenemezse gösterilecek" width="500" height="200">```<br>
- Height kullanmak fotografın orantısı bozabilir.
