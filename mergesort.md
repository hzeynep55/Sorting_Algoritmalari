# [16,21,11,8,12,22] Dizisi Merge Sort Adımları

Yapmamız gereken diziyi tek parça kalacak şekilde elemanlarını ayırmak gerekmektedir. Böldükten sonra sıralı bir şekilde diziyi tekrar oluşturur.  

[16,21,11] ve [8,12,22] olarak iki parçaya ayırdım ve ayırmaya devam ediyorum:  
[16] [21,11]     [8] [12,22]  
[16] [21] [11]    [8] [12] [22]->Tek parça kalıncaya kadar böldüm. Şimidi sıralama işlemi yapılacak:  
[11,16,21]        [8,12,22]  
        [8,11,12,21,22] -> Ve sıralama işlemimiz tamamlanmış oldu.  


Big O: O(nlogn)
