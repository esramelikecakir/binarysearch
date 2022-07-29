# binarysearch
1- Arrayimizin ilk elemanı 7 olduğundan root olarak seçilir.

<img width="1418" alt="Ekran Resmi 2022-07-29 23 10 13" src="https://user-images.githubusercontent.com/77747702/181836383-c8d1dcb3-61fb-4834-9613-c07f9ee0972e.png">

2- Sıradaki elemanı root'a göre sorgulama işlemi yapılır. 5, 7'den büyük müdür? Hayır. O zaman 5, ağacımızda 7'nin solunda bulunur.


3- Aynı işlem bu sefer 3. eleman için yapılır. 1, root olan 7'den küçük olduğundan 7'nin solunda yer alır. Fakat orada 5 olduğundan ona göre de bir sorgulama yapılır. 1, 5'ten de küçük olduğundan 1, 5'in solunda yer alır.


4- 8 roota göre büyük olduğundan 8, 7'nin sağında yer alır.


5- 3, 7 ve 5'ten küçük, 1'den büyüktür. Bu yüzden 1'in sağ tarafında bulunur.


6- 6, 7'den küçük 5'ten büyüktür. O vakit 5'in altında sağ tarafta bulunur.


7- 0, sırasıyla kontrol edildiğinde 7,5,1'den küçüktür. O yüzden 1'in altında sol tarafta bulunur.


8- 9, 7'den ve 8'den büyüktür. 8'in altında sağ tarafta yer alır.


9- 4, 7 ve 5'ten küçüktür. 1'den ve 3'ten büyük olduğundan 3'ün altında sağ tarafta bulunur.


10- 2, 7 ve 5'ten küçük 1'den büyüktür. 3'e göre kıyaslandığında küçük olduğundan 3'ün sağında bulunur. 

<img width="1418" alt="Ekran Resmi 2022-07-29 23 06 20" src="https://user-images.githubusercontent.com/77747702/181835832-662b8c8e-3724-46b1-bee6-a37e94a2ee83.png">
