# Final Kurulum Plani

Bu sistemin final amaci:

1. Urun bilgilerini `data/products.csv` dosyasina girmek
2. Urun gorsellerini Etsy mantigina gore hazirlamak
3. GitHub Actions ile Etsy listeleme dosyalarini otomatik uretmek
4. Cikan CSV/JSON dosyalarini Etsy listeleme surecinde kullanmak

## 1. GitHub reposu

Yeni repo adi onerisi:

```text
porselian-etsy-creator
```

Bu klasordeki tum dosyalar GitHub reposuna yuklenir.

## 2. Urun tablosu

Ana dosya:

```text
data/products.csv
```

Her satir bir urundur. Sarmaşik vazo ve Hermes bust icin ornek satirlar eklendi.

## 3. Otomasyon

GitHub'da `Actions` bolumunden `Generate Etsy Listings` calistirilir.

Otomasyon sunlari uretir:

- `data/etsy_listings.csv`
- `data/etsy_listings.json`

## 4. Gorsel sistemi

Her urun icin Etsy'de ideal gorsel seti:

- 1 ana/lifestyle gorsel
- 1 temiz katalog gorseli
- 1 olcu gorseli
- 1 yakin doku gorseli
- 1 kullanim gorseli
- 1 set/adet gorseli
- 1 paketleme veya hediye gorseli

## Hermes Bust Gorsel Yorumu

Gonderilen ilk Hermes gorseli Etsy ana gorseli icin uygundur:

- kitap tutucu olarak kullanim net gorunuyor
- dekorasyon sahnesi guclu
- renkli urun karakteri belli
- yasam alani hissi Etsy icin iyi

Gonderilen ikinci Hermes gorseli olcu gorseli icin uygundur:

- marka yerlesimi var
- 2'li set bilgisi var
- boy ve en bilgisi net

Eksik kalabilecek gorseller:

- beyaz/temiz fonda katalog gorseli
- yakindan doku ve renk detay gorseli
- urunu tek basina bust dekoru olarak gosteren gorsel
- paketleme veya hediye konsepti

## Sonraki adim

Her yeni urun icin once urun bilgisi tabloya girilir, sonra 2-5 adet gorsel eklenir.
Bu sekilde Etsy listelemesi hem metin hem gorsel olarak tamamlanir.

