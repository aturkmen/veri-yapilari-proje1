
# Selection Sort

## [22, 27, 16, 2, 18, 6] dizisini selection sort algoritmasına göre sıralayınız:
- En küçük eleamını bul: 2
- Dizinin ilk elemanını en küçük elemanla değiştir: [2, 27, 16, 22, 18, 6]
- Sonraki en küçük elemanı bul: 6
- Dizinin ikinci elemanını en küçük elemanla değiştir: [2, 6, 16, 22, 18, 27]
- Sonraki en küçük elemanı bul: 16
- Dizinin üçüncü elemanını en küçük elemanla değiştir: [2, 6, 16, 22, 18, 27]
- Sonraki en küçük elemanı bul: 18
- Dizinin sonraki elemanını en küçük elemanla değiştir: [2, 6, 16, 18, 22, 27]
- Sonraki en küçük elemanı bul: 22
- Dizinin sonraki elemanını en küçük elemanla değiştir: [2, 6, 16, 18, 22, 27]
- Tek eleman kaldı, dizi sıralandı.

## Selection sort algoritmasının Big-O gösterimini yazınız:
- O (n^2)

## Dizi sıralandıktan sonra 18 sayısı hangi durum kapsamına girer. (Average, Worst, Best case):
- 18 sayısı dizinin başında ya da sonunda olmadığı için **Average case** kapsamındadır.

## [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
- En küçük eleamını bul: 2
- Dizinin ilk elemanını en küçük elemanla değiştir: [2, 3, 5, 8, 7, 9, 4, 15, 6]
- Sonraki en küçük eleamını bul: 3
- Dizinin ikinci elemanını en küçük elemanla değiştir: [2, 3, 5, 8, 7, 9, 4, 15, 6]
- Sonraki en küçük eleamını bul: 4
- Dizinin üçüncü elemanını en küçük elemanla değiştir: [2, 3, 4, 8, 7, 9, 5, 15, 6]
- Sonraki en küçük eleamını bul: 5
- Dizinin sonraki elemanını en küçük elemanla değiştir: [2, 3, 4, 5, 7, 9, 8, 15, 6]
- Sıralama son elemana kadar bu şekilde devam eder.
