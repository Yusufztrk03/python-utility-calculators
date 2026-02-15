# python-utility-calculators
print('Hesap Makinesi')
sayı1 = float(input('Birinci sayıyı giriniz:'))
sayı2 = float(input('İkinci sayıyı giriniz:'))

print('İşlemler:')
print('1. Toplama')
print('2. Çıkarma')
print('3. Çarpma')
print('4. Bölme')

seçim = input('Seçiminizi yapınız: (1/2/3/4:)')

if seçim =='1':
    print('sonuç:', sayı1 + sayı2)
elif seçim =='2':
    print('sonuç:', sayı1 - sayı2)
elif seçim =='3':
    print('sonuç:', sayı1 * sayı2)
elif seçim =='4':
    if sayı2 != 0:
        print('sonuç', sayı1 / sayı2)
    else:
        print('Hata: Sıfırla bölme yapılmaz!')
else:
    print('Geçersiz seçim!')
