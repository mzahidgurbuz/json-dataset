# json-dataset
Some json dataset for use in mobile, web and other projects. 

## ilceler.json
Bu dataset türkiyedeki ilçelerin listesini içeren bir json dosyasıdır. içerisinde ilçenin içerisinde bulunduğu coğrafi bölge adı, il plaka kodu ve il adı yer almaktadır. 

içerdiği json dosya yapısı şu şekildedir. 
``` JSON
[
  {
    "bolge": "AKDENİZ",
    "id": 1,
    "il": "ADANA",
    "ilce": "ALADAĞ",
    "plaka": 1
  },
  //---
]
```
## araclar1.json, araclar2.json
Bu dataset alıştırma yapmak isteyen kullanıcılar için örnek olarak hazırlanmış bir json dosyadır. Araç kiralama projesinde kullanmak için gerçek olmayan araçlar listesini içerir.
içerdiği json dosya yapısı şu şekildedir. 
``` JSON
[
  {
    "veritipi": "0", //başlık verisi 
    "adi": "Benzinli"
  },
  {
    "veritipi": "1", //araç verisi
    "adi": "BMW SERIES 1 1.5 116D ",
    "vites": "Otomatik",
    "koltuk": "5",
    "model": "2019",
    "yakit": "Benzinli",
    "sarfiyat": "5.9",
    "kira": "2720",
    "foto": "https://images.garenta.com.tr/jato/300/2017/BMW/SERIES%201/5Hatchback315.png"
  },
  //---
]
```
