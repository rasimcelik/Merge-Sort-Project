# Merge-Sort-Project

[patika.dev](https://www.patika.dev)

Patika.dev > Veri Yapıları ve Algoritmalar > Merge Sort Projesi

## [16,21,11,8,12,22] -> Merge Sort -> Dizinin sort türüne göre aşamalarını yazınız.

[16,21,11,8,12,22] İşlemlere önce diziyi parçalayarak başlayalım

1-> [16,21,11] [8,12,22] => 3'erli 2 gruba ayırdık

2-> [16] [21,11] [8,12] [22] => 3'lü grupları 2'şerli gruplara ayırdık

3-> [16] [21] [11] [8] [12] [22] => 2'li gruplar tekli gruplara dağılır

4-> [16] [11,21] [8,12] [22] => gruplar tekrar 2'li gruplara dönüştürülür. Gruplarken küçük dizinin başına geçecek

5-> [11,16,21] [8,12,22] => 3'lü sıralı gruplar seçilir

6-> [8,11,12,16,21,22] => tüm gruplar birleşir ve sıralanırlar

## Big-O gösterimini yazınız.

O(6\*(log6))
