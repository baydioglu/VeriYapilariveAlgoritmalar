# Proje 2

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree  Projesi için hazırlanmıştır. 

1. Yukarıdaki dizinin Binary-Search-Tree aşamalarını yazınız


**Çözüm:**

Dizinin ilk elemanı 7 root olarak seçilir. Dizinin sonraki elemanı 5 root değerinden küçük olduğu için sola yazılır. Bu şekilde küçük olanlar sola, büyük olanlar sağa gelecek şekilde ağaç tamamlanır. 

                          (7)
                         /   \
                       (5)    (8)
                      /   \      \
                    (1)    (6)    (9)
                   /   \
                 (0)    (3)
                       /   \
                     (2)    (4)
