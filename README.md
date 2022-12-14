# **Merge Sort Project**

Bu repo [Patica.dev](https://www.patika.dev/tr) Veri Yapıları ve Algoritmalar Eğitiminde oluşturduğumuz Merge Sort Projesi reposudur. İçerisinde bir adet README dosyası barındırmaktadır.

---

## **Soru**

[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.

---

## **Cevap**

---

**_Divide bölümü_**

```
    [16,21,11]       [8,12,22]

  [16,21]  [11]     [8]  [12,22]

[16]  [21]  [11]   [8]  [12]  [22]
```

![divide](https://raw.githubusercontent.com/Overated/Merge-Sort-Projesi/main/image/a1.png)

**_Merge bölümü_**

```
[16,21]  [11]  [8]  [12,22]

 [11,16,21]      [8,12,22]

    [8,11,12,16,21,22]
```

![merge](https://raw.githubusercontent.com/Overated/Merge-Sort-Projesi/main/image/a2.png)

## **Big-O gösterimi;**

---

# Big-O = **$0(n.log(n))$**

# Contributing

Pull requestler kabul edilir. Büyük değişiklikler için, lütfen önce neyi değiştirmek istediğinizi tartışmak için bir konu açınız.

# License

[MIT](https://choosealicense.com/licenses/mit/)
