# Veri Yapıları ve Algoritmalar

## Merge Sort Projesi

### Proje 2
---
1. **[16,21,11,8,12,22]** -> Merge Sort
   1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
   2. Big-O gösterimini yazınız.
---
### Cevaplar
1. Cevap
   1. Merge Sort Adımları
        > ||||[16,21,11,8,12,22]||||
        > |---:|---:|---:|---|---|---|---|
        > |||[16,21,11]||[8,12,22]|||
        > |[16]||[21,11]||[8,12]||[22]|
        > |[16]|[21]|[11]||[8]|[12]|[22]|
        > |[16]||[11,21]||[8,12]||[22]|
        > |||[11,16,21]||[8,12,22]|||
        > ||||[8,11,12,16,21,22]||||
    1. Big-O-Notation
        > O(nlogn)
#   p a t i k a d e v _ m e r g e s o r t  
 