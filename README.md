# 🔄️ Vektörler
Vektörler orijin (0,0) noktasından belirtilen x, y koordinatına uzunluğa ve boyuta sahip doğrulardır. \
Koordinatları şu şekilde gösterilebilir,
```math
(x, y) = \begin{bmatrix}
x  \
y
\end{bmatrix}
```
Matris ile gösterim lineer cebir işlemlerini yaparken geometriden bağımsız işlemler yapabilmeyi sağlar, bu açıdan kullanışlıdır.

# Baz Vektörler
Normal koordinat ekseninde baz vektörler x ve y eksenini gösteren bir birimlik vektörlerdir. \
+1 birimlik x ekseni ile aynı yönde olan vektöre i baz vektörü adı verilir. \
+1 birimlik y ekseni ile aynı yönde olan vektöre j baz vektörü denir. \
Teorik olarak $\hat{\textbf{i}}$ ve $\hat{\textbf{j}}$ baz vektörlerini kullanarak bütün vektörleri ifade etmek mümkündür. \
![Geometrik gösterim](https://github.com/Eikosa/baz-vektorlerin-degisimi/assets/20538090/5c481021-19a9-496f-9c6a-a429bf89b90a) \
Ayrıca baz vektörler koordinatlarıyla birlikte şöyle gösterilebilir
```math
i = \begin{bmatrix}
1  \
0
\end{bmatrix} 
```
```math
j = \begin{bmatrix}
0 \
1
\end{bmatrix}
```
Bu iki baz vektör şu şekilde matriks ile gösterilebilir.
```math
\text{Baz vektörler} = \begin{bmatrix}
1 & 0 \
0 & 1
\end{bmatrix}
```

# Vektörlerin Baz Vektörler ile Yazılışı
Her vektör tipik olarak tanımlanmış i ve j baz vektörleri ile yazılabilir \
Örnek: \
$(4,5)$ vektörünü \
$4i+5j$ şeklinde yazmak mümkündür.

------
💡 Peki ya baz vektörleri değiştirseydik baz vektörler ile tanımladığımız vektörlerin koordinatlarına ne olurdu? \
Bu soruyu cevaplamak için önce normal baz vektörler ile 4i + 5j vektörünün koordinatlarını bulalım.\
Hatırlayacağımız üzere i = (1,0) idi ve j = (0,1) idi.\
Bu iki koordinatı matris olarak yazarak hesap yapalım
```math
4i + 5j = 4 \begin{bmatrix}1  \\ 0 \end{bmatrix} + 5*\begin{bmatrix}0  \\1\end{bmatrix} = \begin{bmatrix}4  \\0\end{bmatrix} + \begin{bmatrix}0  \\5\end{bmatrix} = \begin{bmatrix}4  \\5\end{bmatrix}
```
Bu sayede 4i+5j vektörünün 4,5 koordinatına geldiğini göstermiş olduk. 

------
Baz vektörlerimizi 90 derece sola dönecek şekilde değiştirelim. \
![image](https://github.com/Eikosa/baz-vektorlerin-degisimi/assets/20538090/e087ac93-c085-4f20-8f24-03556423c121) \
Vektörlerimiz işte böyle gözükecek. Koordinatlarını yazalım
```math
i = \begin{bmatrix}
0  \
1
\end{bmatrix} 
```
```math
j = \begin{bmatrix}
-1 \
0
\end{bmatrix}
```
Demin yaptığımız mantık ile i + j olarak yazdığımızda buna denk döşen vektörümüzü bulmuş olacağız.
```math
4i + 5j = 4 \begin{bmatrix}0  \\ 1 \end{bmatrix} + 5*\begin{bmatrix}-1  \\0\end{bmatrix} = \begin{bmatrix}0  \\4\end{bmatrix} + \begin{bmatrix}-5  \\0\end{bmatrix} = \begin{bmatrix}-5  \\4\end{bmatrix}
```
Vektörleri baz vektörler ile ifade ederek aslında ne kadar güzel bir iş yaptığımızı da böylece kanıtlamış oluyoruz çünkü vektörümüz bu sayede koordinat eksenlerinden bağımsız olmuş oluyor. \
Bu öğrendiğimiz bilgilere dayanarak ezbersiz elde edebileceğimiz bazı bilgilere göz atalım.
![image](https://github.com/Eikosa/baz-vektorlerin-degisimi/assets/20538090/69e802ab-8eb4-4b72-99cc-e83afb287828)
![image](https://github.com/Eikosa/baz-vektorlerin-degisimi/assets/20538090/a9652f12-e88e-420e-8561-33fcd14d0749)

- Teşekkür ederim.
