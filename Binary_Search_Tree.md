# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] Dizisini Binary Searh Tree Aşamaları  
Dizideki 7 rakamından başlayarak  7'nin sağ tarafına 7'den büyük olanlar, sol tarafına ise 7'den küçük olanlar yazılacak.
#### Sağ taraf:8,9 
Sağ tarafa ilk 8 yazılacak. 9, 8'den büyük olduğu için 8'in sağ tarafına yazılacak.
#### Sol taraf:5,1,3,6,0,4,2  
Sol tarafta ilk 5 olduğu için 5'in sağ tarafında 6,sol tarafında ise 1,3,0,4 olacak. 5'in sağ tarafı daha devam etmeyeceği için sol tarafından devam ediyoruz:  
1 rakamının sol tarafında kalanlar:0, sağ tarafında kalanlar 3,4   
3'ün sağ tarafına 4 yazılıp binary search tree aşamamızı tamamlamış olduk.

