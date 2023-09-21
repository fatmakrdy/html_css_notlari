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
- yerel img yükleme:
``` <img src="dizin ismi/dosya adı" alt="fotograf yüklenemezse gösterilecek" width="500" height="200">```<br>
- internetten img yükleme:
```<img src="resim bağlantısı" >```
- Height kullanmak fotografın orantısı bozabilir.

**form oluşturma**
- type ile inputun nasıl olacağını belirledik.<br>
- Name ile gruplandırma yaptık inputla gelen veriler  server a bu isimlerle yüklenirler.<br>
- Cinsiyet ksımında name vererek kullanıcının tek seçim yapmasını sağladık.Bu şekilde kullanım radio type ında oldu chechkbox da kullanıcı birden fazla seçim yapabilir.<br>
 ``` <form action="">
        <p>Ad:<input type="text" name="ad"></p>
        <p>Email: <input type="email" name="email"></p>
        <p>Şifre: <input type="password" name="sifre"></p>
        <p>Şifreyi hatırla <input type="checkbox" name="parolahatirla"></p>
        <p>Cinsiyet:
            K<input type="radio" name="cinsiyet">
            E <input type="radio" name="cinsiyet">
        </p>
    </form>```
- select ile seçim inputu ekledik.
```
<p>
            Doğum Yeri: <br>
            <select multiple="dogumyeri" >
                <option value="izmir"></option>
                <option value="ankara"></option>
                <option value="konya"></option>
            </select>
        </p>```
