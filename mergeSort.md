# MERGE SORT 

[16, 21, 11, 8, 12, 22] -> Merge Sort

1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2) Big-O gösterimini yazınız.

## 1)
[16, 21, 11, 8, 12, 22]
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

#### 1. aşama 
Sayı dizini ikiye bölünür.
[16, 21, 11] --- [8, 12, 22]

#### 2. aşama
Böldüğümüz sayı dizinindeki her bir parça tekrardan ikiye bölünür.
[16] [21, 11] --- [8, 12] [22]

#### 3. aşama
Dizinler tek elemanlı olana kadar bölme işlemi devam eder.
[16] [21] [11] --- [8] [12] [22]

### 4. aşama 
Tek elemanlı dizinler tekrardan birleştirilir. Birleştiririken kıyaslama yapılarak birleştirilir. <br>
- Soldaki grupta; <br>
[16] tek elemanlı olduğu için aynı tutulur. <br>
11<21 olduğu için [11, 21] olarak sıralanır. <br>
- Sağdaki grupta ise; <br>
8<12 olduğu için [8, 12] olarak sıralanır. <br>
[22] tek elemanlı olduğu için aynı tutulur. <br>
#### Bu aşama sonunda şöyle gruplar oluşur. <br>
[16] [11, 21] --- [8, 12] [22]

### 5. aşama
- Soldaki üçlü grupta önce 16 ile 11 kıyaslanır. 
- 16>11 olduğu için 11 en sola yazılır.
- 16 ile 21 kıyaslanır. 16<21 olduğu için sıralama şu şekilde olur. <br>
[11, 16, 21]

- Sağdaki üçlü grupta önce 8 ile 22 kıyaslanır. 8<22 olduğu için 8 olduğu yerinde kalır.
- 12 ile 22 kıyaslanır. 12<22 olduğu için bu elemanlar da olduğu yerinde kalarak birleşir. <br>
[8, 12, 22]

- Bu aşama sonunda gruplar şu şekilde olur. <br>
[11, 16, 21] --- [8, 12, 22]

## 6. aşama
##### Bu aşamada üçlü gruplar dizilerin en soldaki elemanlarından başlanarak kıyaslanır
- 11 ile 8 kıyaslanır. 11>8 olduğu için 8 en başa geçer.
- 11 ile 12 kıyaslanır. 11<12 olduğu için 8'den sonra 11 gelir.
- 16 ile 12 kıyaslanır. 16>12 olduğu için 11'den sonra 12 gelir.
- 16 ile 22 kıyaslanır. 16<22 olduğu için 12'den sonra 16 gelir.
- 21 ile 22 kıyaslanır. 21<22 olduğu için 22 son elemandır, 16'dan sonra da 21 gelir.
##### Bu aşama sonunda dizi şu hale gelir
[8, 11, 12, 16, 21, 22]

## 2
##### Big-O gösterimini yazınız.
O(nlogn)
