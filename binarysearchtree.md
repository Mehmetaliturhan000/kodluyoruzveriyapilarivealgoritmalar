# Binary Search Tree Projesi
Bu dosya patika.dev'e ait olan Mehmet Ali Turhan tarafından yapılmış "Veri Yapıları ve Algoritmalar" dersinin Binary Search Tree ödevini içermektedir.

>[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

İlk aşamada dizinin sıralanması gerekir. Verilen dizinin sıralanmış hali,

>[0,1,2,3,4,5,6,7,8,9]


Root 7'dir.

5 root'dan küçük olduğu için soluna yazılır.

1 root'dan ve 5 sayısından küçük olduğu için 5'in soluna yazılır.

8 root'dan büyük olduğu için root'un sağına yazılır.

3 root sayısından küçük olduğu için sol tarafta 1'den büyük olduğu için 1'in sağına yazılır.

6 root sayısının solunda 5 sayısının sağında yer alır.

0 root sayısının solunda 1 sayısının soluna yazılır.

9 root sayısının sağında 8 sayısınında sağında yer alır.

4 root sayısının solunda 3 sayısının sağında yer alır.

2 root sayısının solunda 3 sayısının solunda yer alır.


|   |   |   |   |   |   | 7 |   |   |   |   |

|   |   |   |   |   | / |   |  \|   |   |   |

|   |   |   |   | 5 |   |   |   | 8 |   |   |

|   |   |   | / |   | \ |   |   |   | \ |   |

|   |   | 1 |   |   |   | 6 |   |   |   | 9 |

|   |   | / | \	|   |   |   |   |   |   |   |

|   | 0 |   |   | 3 |   |   |   |   |   |   |

|   |   |   | / |   | \ |   |   |   |   |   |

|   |   |   | 2 |   |   | 4 |   |   |   |   |




--------------------------
Author: Mehmet Ali Turhan

**[Linkedin](https://www.linkedin.com/in/mehmet-ali-turhan-43669415b/g)**

**[Youtube](https://www.youtube.com/channel/UCh1HyT37pbPwN6w1wRd43Dg)**
