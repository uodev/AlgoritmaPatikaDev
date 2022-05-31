# Binary Search Tree Projesi

## Binary Search Tree'ye göre adımları;
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 

- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] root elemanı 7 sayısı olsun,

- 5, 7'den küçük olduğu için root elemanının sol tarafına yazılır.
  ```
    7
  /     
5          
  ```

- 1 sayısı root elemanından ve 5 sayısından küçük olduğu için sol tarafa yazılır

  ```
            7
          /      
        5 
    /
  1 
  ```

- 8 sayısı root elemanından büyük olduğu için root elemanının sağ tarafına yazılır

  ```
                  7
              /       \
          5               8
      /
  1
  ```

- 3 sayısı root elemanından küçük olduğu için sola gidilir. 5'ten de küçük olduğu için sola bakılır. 1'den büyük olduğu için sağa yazılır.

  ```
                  7
              /       \
          5               8
      /                       
  1                               
     \
       3
  ```

- 6 sayısı root elemanından küçük olduğu için sol tarafa fakat 5'den de büyük olduğu için sağ tarafa yazılır..

  ```
                  7
              /       \
          5               8
      /      \                  
  1            6                   
      \
          3
  ```

- 0 sayısı roottan küçük,5'ten küçük,1'ten küçük olduğu için en sol alta yazdık.

  ```
               7
           /       \
          5          8
       /     \                 
    1           6                     
  /     \                               
 0          3                               
  ```

- 9 sayısı root elemanından büyük olduğu için sağ tarafa yazılır fakat orada 8 olduğu için ve 9 8'den de büyük olduğu için yine sağa yazılır

  ```
                  7
              /       \
           5             8
       /     \            \     
    1           6           9           
  /     \                               
 0          3          
  ```

- 2 değeri 7'den ve 5'den küçüktür, 1'den büyük ama 3'den küçüktür, bu yüzden 3'ün soluna yazılır.
  ```
                  7
              /       \
          5               8
      /     \                 \
  1           6                   9
 /     \                            
0        3                             
      /       \
  2              4
  ```
