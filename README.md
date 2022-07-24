# Patika.dev-Binary-Search-Tree-Projesi
**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

## Binary Search Tree Aşamaları

> Root 7'dir. Dizinin solundan başlarız ve sağa doğru ilerleyerek Binary Search Tree'yi oluştururuz.

    7

> 5, 7'den daha küçük olduğu için 7'nin solunda bulunur.

                      7
                     /
                    5

> 1, 7 ve 5'ten küçük olduğu için 5'in solunda bulunur.
					
                  7
                 /
                5
               /
              1

> 8, 7'den büyük olduğu için sağında bulunur.

                  7
                 / \
                5   8
               /
              1

> 3, 7 ve 5'ten küçük fakat 1'den büyük olduğu için 1'in sağında
> bulunur.

                  7
                 / \
                5   8
               /
              1
               \
                3

> 6, 7'den küçük 5'ten büyüktür ve 5'in sağında bulunur.

                  7
                 / \
                5   8
               / \
              1   6
               \
                3

> 0, 7'den, 5'ten ve 1'den küçük olduğu için 1'in solundadır.

                  7
                 / \
                5   8
               / \
              1   6
             / \
            0   3

> 9, 7'den ve 8'den büyük olduğu için 8'in sağında bulunur.

                  7
                 / \
                5   8
               / \   \
              1   6   9
             / \
            0   3

> 4, 7'den ve 5'ten küçüktür fakat 1 ve 3'ten büyük olduğu için 3'ün
> sağında bulunur.

                  7
                 / \
                5   8
               / \   \
              1   6   9
             / \
            0   3
                 \
                  4

> 2, 7'den ve 5'ten küçük, 1'den büyük, 3'ten küçük olduğu için 3'ün
> solundadır.

                  7
                 / \
                5   8
               / \   \
              1   6   9
             / \
            0   3
               / \
              2   4
www.patika.dev
