# Binary-Search-Tree Projesi

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

## ***7 root'tur.***

## *1.Aşama*

5, 7'den küçük olduğu için sola yazılır.

```
  7 
 /
5 
```
## *2.Aşama*

```
  7 
 / \
5   8
```
## *3.Aşama*

```
  7 
 / \
5   8
     \
      9
```
## *4.Aşama*

```
    7 
   / \
  5   8
 /     \
1       9
```
## *5.Aşama*

```
    7 
   / \
  5   8
 / \   \
1   6   9
 
```
## *6.Aşama*

```
         7 
        / \
       5   8
      / \   \
     1   6   9
    / 
   0   
```
## *7.Aşama*

```
         7 
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3
     
```
## *8.Aşama*

```
         7 
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3
      /  
     2    
```
## *9.Aşama*

```
         7 
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3
      /  \
     2    4
```