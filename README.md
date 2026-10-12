# ogrenci_bilgi_sistemi
ogrenci_yasi=18
notlar=[60,70,80]
basarili_mi=True

#1.Yaşı metin türüne dönüştür
ogrenci_yasi=20
print(type(ogrenci_yasi))

#2.Tekrar tam sayıya dönüştür
ogrenci_yasi=int(ogrenci_yasi)
print(type(ogrenci_yasi))

#3.Not listesine 100 ekle
notlar.append(100)
print(notlar)

#4.Ortalama 50'nin altındaysa başarısız olsun
ortalama=sum(notlar)/len(notlar)
