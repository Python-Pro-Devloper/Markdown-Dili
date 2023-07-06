
# Markdown Dili

## İçindekiler
1. Başlık Türleri
2. Yazı Tipleri
3. Liste Tipleri
4. Linkler ve Görseller
5. Tablolar
6. Kod Gösterimi

# Giriş
Markdown, metin tabanlı belgelerin biçimlendirilmesini sağlayan bir işaretleme dilidir.

# 1. Başlık Türleri

# Ana Başlık
Ana başlık --> #
## İkinci Başlık
İkinci başlık --> ##
### Üçüncü Başlık
Üçüncü başlık --> ###
#### Dördüncü Başlık
Dördüncü başlık --> ####

# 2. Yazı Tipleri

**kalın**  --> **

*İtalik*   --> *

_Vurgulanmış_ --> _

# 3. Liste Tipleri

## 3.1 Sıralı Liste
1. Liste öğesi 1 --> 1.
2. Liste öğesi 2 --> 2.
3. Liste öğesi 3 --> 3.

## 3.2 Sırasız Liste

 Sırasız listelerde "-", "+", veya "*" işaretlerini kullanarak maddeleri gösterebilirsiniz. 

- Liste elemanı --> -
+ Liste elemanı --> -
* Liste elemanı --> *

# 4. Linkler ve Görseller

## 4.1 Linkler
[google](https://www.google.com) 

Yukarıdaki gibi bir link oluşturmak için öncelikle köişeli parantezler içerisine linkin metnini yazıyoruz, ardından normal parantez içerisine linki yerleştiriyoruz. 

## 4.2 Görseller
![Resim Açıklaması](resim.png)     

Yukarıdaki gibi bir görsel oluşturmak için, 
- ! işaretinden sonra köşeli parantezler içerisine görselin metnini yazıyoruz, ardından normal parantezler içerisine uzantısıyla birlikte dosya ismini yazıyoruz.

- Örn: (resim.png) 

# 5. Tablolar

| Ürün      | Fiyat     | Miktar |
| --------- | --------- | ------ |
| Elma      | 2 TL      | 10     |
| Portakal  | 3 TL      | 5      |
| Muz       | 4 TL      | 8      |
| Çilek     | 5 TL      | 12     |

Markdown diliyle yukarıdaki gibi bir tablo oluşturmak için aşağıdaki adımları izleyebilirsiniz:

- Tablonun her satırını | karakteriyle başlatın ve bu karakter ile bitirin.
- Bu şekilde satırlarda yer alan sütun başlıklarını ve tablo elemanlarını birbirinden ayırıyoruz.

Buraya kadar tablo içerisindeki satırları birbirinden ayırmayı öğrendik. Peki tablonun sütunlarını nasıl birbirinden ayırabiliriz? 

- Tablonun, sütun başlıklarını düzenlediğimiz ilk satırının altındaki "|" karakterlerinin arasını "-" karakterleriyle doldurun.

**Örnek**: | ------ | ------ | ------ |

- Bu işlemi yalnızca ikinci satırda yaptığımıza dikkat edelim.

- Diğer satırlarda ise "|" karakterlerinin arasına tablonun elemanlarını ekleyin.

**Örnek**: | Elma | Armut | Portakal |

**Not:** Markdown diliyle tablo hazırlarken | karakterlerinin alt alta gelmesine özen göstermelisiniz.

# 6. Kod Gösterimi

```python
# Markdown'da kod bloğu açmak ve kapatmak için
# "Alt Gr + Virgül" tuş kombinasyonunu kullanıyoruz.

# Örnek:

# ```python
# Kodlar
# ```
```
```python
ornek = 'Örnek'
print(ornek)

list = [1, 2, 3]
for i in list:
    print(i)
```
 
    

