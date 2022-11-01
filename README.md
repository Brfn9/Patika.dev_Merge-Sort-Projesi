# Patika.dev_Merge-Sort-Projesi
Proje 2
[16,21,11,8,12,22] -> Merge Sort
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
 [16,21,11]     [8,12,22]  --> First Step
 [16] [21,11]  [8] [12,22] -->Second step
 [16] [21] [11] [8] [12] [22] -->Third step
 [16,21] [11]   [8,12] [22] --> Fourth step
 [11,16,21]    [8,12,22] --> Fifth step
 [8,11,12,16,21,22] -->Sixth step
  Big-O gösterimini yazınız. 
 eleman sayısı n olan bir dizide, her bir satırda n kere işlem yapıyoruz.Parçalara ayırarak ilerledigimiz için 
 2^x =n ;  x=logn tane satırımız var.Dolayısıyla  Big-O notationımız;
  O(nlogn ) oluyor.
