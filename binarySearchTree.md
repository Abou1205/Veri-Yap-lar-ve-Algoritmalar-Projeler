# BINARY SEARCH TREE

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. <br> <br> Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

- Root 5 olarak belirlenmiştir.
- Dizideki elemanlar 5 ile başlayarak kıyaslanılan elemandan büyük olanlar sağ tarafa, küçük olanlar sol tarafa yazılacak şekilde bir yapı oluşturulacaktır.

### Aşamalar şöyle olacaktır

- Root elemanı 5 olarak belirlenmiştir.

- 7 ile 5 kıyaslanır 7>5 olduğu için sağ tarafına yazılır.
>
                       5
                         \
                           7
- 1 ile 5 kıyaslanır. 1<5 olduğu için sol tarafına yazılır.
>
                        5
                     /    \
                    1      7
- 8 ile 5 kıyaslanır. 8>5 olduğu için sağa yazılır.
>
                        5
                     /    \
                    1      7 
                             \
                              8
- 3 ile 5 kıyaslanır. 3<5 olduğu için sol tarafa ilerlenir.
- 3 ile 1 kıyaslanır. 1<3 olduğu için sağ tarafa ilerlenir.
> 

                        5
                     /    \
                    1       7 
                     \       \
                       3       8
 - 6 ile 5 kıyaslanır. 5<6 olduğu için sağ tarafa ilerlenir.
 - 6 ile 7 kıyaslanır. 6<7 olduğu için sol tarafa ilerlenir.
>

                        5
                     /    \
                    1       7 
                     \     /  \
                      3   6    8
- 0 ile 5 kıyaslanır. 0<5 olduğu için sol tarafa ilerlenir.
- 0 ile 1 kıyaslanır. 0<1 olduğu için sol tarafa ilerlenir
>

                       5                       
                     /    \
                    1       7 
                  /  \     /  \
                 0    3   6    8
                 
- 9 ile 5 kıyaslanır. 9>5 olduğu için sağ tarafa ilerlenir.
- 9 ile 7 kıyaslanır. 9>7 olduğu için sağa ilerlenir.
- 9 ile 8 kıyaslanır. 9>8 olduğu için sağa yazılır.
>
                        5                       
                     /    \
                    1       7 
                  /  \     /  \
                 0    3   6    8
                                \
                                 9
- 4 ile 5 kıyaslanır. 4<5 olduğu için sol tarafa ilerlenir.
- 4 ile 1 kıyaslanır. 4>1 olduğu için sağ tarafa ilerlenir.
- 4 ile 3 kıyaslanır. 4>3 olduğu için sağ tarafa yazılır.
>
                         5                       
                    /        \
                    1         7 
                  /  \      /   \
                 0    3    6     8
                       \          \
                        4          9
- 2 ile 5 kıyaslanır. 2<5 olduğu için sol tarafa ilerlenir.
- 2 ile 1 kıyaslanır. 2>1 olduğu için sağ tarafa ilerlenir.
- 2 ile 3 kıyaslanır. 2<3 olduğu için sol tarafa yazılır.
>
                        5                       
                    /        \
                    1         7 
                  /  \      /   \
                 0    3    6     8
                    /  \          \
                   2     4          9
