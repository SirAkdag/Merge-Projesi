# Proje Ödevi - Emre Akdag  

## Proje 2 - Merge Sort
### Asagidaki dizinin sort türüne göre siralamasi su sekildedir;
```
      [16,21,11,8,12,22] 
```

```
      [16,21,11,8,12,22]
        |             |
   [16,21,11]        [8,12,22]
    |     |           |     |
  [16]  [21,11]     [8]  [12,22]
    |    |   |       |    |   |
[16] [21] [11]    [8] [12] [22]
     |      |        |      |
  [16] [11,21]    [8] [12,22]
          |             |
    [11,16,21]   [8,12,22]
            |       |
        [8,11,12,16,21,22]
```
### Yukaridaki dizinin Big-O gösterimi ise;
```
O(n*logn)
```