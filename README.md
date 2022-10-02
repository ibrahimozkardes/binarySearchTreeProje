# Binary Search Tree Projesi

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- Root'u 7 olarak aldım.

|işlem|   |   |   |
|---|---|---|---|
|**root=7**|   | **7** |   |

- 5 sayısı, 7'den küçük olduğu için root'un soluna eklendi.

|işlem|   |   |   |
|---|---|---|---|
|   |   |   | 7 |
|   |   | / |   |
|**5 eklendi**| **5** |   |   |

- 1 sayısı, 7'den küçük ve aynı zamanda 5'ten de küçük olduğu için en sola eklendi.

|işlem|   |   |   |   |   |
|---|---|---|---|---|---|
|   |   |   |   |   | 7 |
|   |   |   |   | / |   |
|   |   |   | 5 |   |   |
|   |   | / |   |   |   |
|**1 eklendi**| **1** |   |   |   |   |

- 8 sayısı, 7'den büyük olduğu için root'un sağına eklendi.

|işlem|   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|---|
|   |   |   |   |   | 7 |   |   |
|   |   |   |   | / |   | \ |   |
|**8 eklendi**|   |   | 5 |   |   |   | **8** |
|   |   | / |   |   |   |   |   |
|   | 1 |   |   |   |   |   |   |

- 3 sayısı, 7'den ve 5'ten küçük olduğu için 5'in soluna, 1'den büyük olduğu için ise 1'in sağına eklendi.

|işlem|   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|---|
|   |   |   |   |   | 7 |   |   |
|   |   |   |   | / |   | \ |   |
|   |   |   | 5 |   |   |   | 8 |
|   |   | / |   |   |   |   |   |
|   | 1 |   |   |   |   |   |   |
|   |   | \ |   |   |   |   |   |
|**3 eklendi**|   |   | **3** |   |   |   |   |

- 6 sayısı, 7'den küçük olduğu için 7'nin soluna, 5'ten büyük olduğu için 5'in sağına eklendi.

|işlem|   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|---|
|   |   |   |   |   | 7 |   |   |
|   |   |   |   | / |   | \ |   |
|   |   |   | 5 |   |   |   | 8 |
|   |   | / |   | \ |   |   |   |
|**6 eklendi**| 1 |   |   |   | **6** |   |   |
|   |   | \ |   |   |   |   |   |
|   |   |   | 3 |   |   |   |   |

- 0 sayısı, 7'den, 5'ten ve 1'den büyük olduğu için en sola eklendi.

|işlem|   |   |   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|---|---|---|
|   |   |   |   |   |   |   | 7 |   |   |
|   |   |   |   |   |   | / |   | \ |   |
|   |   |   |   |   | 5 |   |   |   | 8 |
|   |   |   |   | / |   | \ |   |   |   |
|   |   |   | 1 |   |   |   | 6 |   |   |
|   |   | / |   | \ |   |   |   |   |   |
|**0 eklendi**| **0** |   |   |   | 3 |   |   |   |   |

- 9 sayısı, 7'den ve 8'den büyük olduğu için en sağa eklendi.

|işlem|   |   |   |   |   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|---|---|---|---|---|
|   |   |   |   |   |   |   | 7 |   |   |   |   |
|   |   |   |   |   |   | / |   | \ |   |   |   |
|   |   |   |   |   | 5 |   |   |   | 8 |   |   |
|   |   |   |   | / |   | \ |   |   |   | \ |   |
|**9 eklendi**|   |   | 1 |   |   |   | 6 |   |   |   | **9** |
|   |   | / |   | \ |   |   |   |   |   |   |   |
|   | 0 |   |   |   | 3 |   |   |   |   |   |   |

- 4 sayısı, 7'den ve 5'ten küçük olduğu için 5'in soluna, 1'den ve 3'ten büyük olduğu için 3'ün sağına eklendi.

|işlem|   |   |   |   |   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|---|---|---|---|---|
|   |   |   |   |   |   |   | 7 |   |   |   |   |
|   |   |   |   |   |   | / |   | \ |   |   |   |
|   |   |   |   |   | 5 |   |   |   | 8 |   |   |
|   |   |   |   | / |   | \ |   |   |   | \ |   |
|   |   |   | 1 |   |   |   | 6 |   |   |   | 9 |
|   |   | / |   | \ |   |   |   |   |   |   |   |
|   | 0 |   |   |   | 3 |   |   |   |   |   |   |
|   |   |   |   |   |   | \ |   |   |   |   |   |
|**4 eklendi**|   |   |   |   |   |   | **4** |   |   |   |   |

- 2 sayısı, 7'den ve 5'ten küçük olduğu için 5'in soluna, 1'den büyük olduğu için 1'in sağına ve 3'ten küçük olduğu için ise 3'ün soluna eklendi.

|işlem|   |   |   |   |   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|---|---|---|---|---|
|   |   |   |   |   |   |   | 7 |   |   |   |   |
|   |   |   |   |   |   | / |   | \ |   |   |   |
|   |   |   |   |   | 5 |   |   |   | 8 |   |   |
|   |   |   |   | / |   | \ |   |   |   | \ |   |
|   |   |   | 1 |   |   |   | 6 |   |   |   | 9 |
|   |   | / |   | \ |   |   |   |   |   |   |   |
|   | 0 |   |   |   | 3 |   |   |   |   |   |   |
|   |   |   |   | / |   | \ |   |   |   |   |   |
|**2 eklendi**|   |   | **2** |   |   |   | 4 |   |   |   |   |

## Patika.dev profilime [buradan](https://app.patika.dev/ozkardes) ulaşabilirsiniz.