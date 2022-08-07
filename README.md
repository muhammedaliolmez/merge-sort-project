# Merge Sort Projesi

## [16,21,11,8,12,22] -> Merge Sort  
## Yukarıdaki dizinin  Merge sort türüne göre aşamalarını yazınız.  

[16,21,11] | [8,12,22]

[16] [21,11] | [8] [12,22]

[16] [21] [11] | [8] [12] [22]

[16,21] [11] | [8,12] [22]

[11,16,21] | [8,12,22]

[8,11,12,16,21,22]
  
## Big-O gösterimini yazınız.  

Dizi içerisindeki veri sayısı değişmediği için her seferinde n seferlik işlem yapılır. Toplam adım sayısı da diziyi 2'ye böldüğümüz için 2'nin katı olmalıdır. Yani 2^x=n olmalıdır. Toplam işlem sayısını bulabilmek için adım sayısı ile her adımda yapılan işlemi çarpmamız gerekir.  
Bunun neticesinde böyle bir sonuç ortaya çıkar:  

log2n=x
(log2n).(n)=  nlog2n  
O(nlogn)
