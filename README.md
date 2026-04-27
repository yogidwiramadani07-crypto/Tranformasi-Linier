# Tranformasi-Linier
## Rumus Vektor (V) dan Mencari daerah asal (W)
```
R2 = Dimensi 2
T=(v1,v2) = (v1-v2, v1+2v2)
W=(v1,v2) = (-1,11), Lakukan subtitusi persamaan linier
contoh = v1 - v2 = -1
         v1 + 2v2 = 11
         -------------  -
```
## Penjumlahan Vektor
```
T=(v1,v2) = (v1-v2, v1+2v2)
u + v = (u1,u2)+(v1,v2)=(u1+v1,u2+v2)
```

## Perkalian Vektor
```
T=(v1,v2) = (v1-v2, v1+2v2)
cu = c(u1,u2) = (cu1,cu2)
```
## Contoh Fungsi yang bukan transformasi Linier
```
f(x)=x2
f(x1,x2)=(x1+x2)2 = x1*2 + x2*2
        =x1*2 + 2x1.x2 + x2*2 = x1*2 + x2*2
```

## Tranformasi nol
```
T = V > W
T(U) = 0
T(5+5) = 0
```
## Transformasi identitas
```
T = V > V
T(V) = V
T(4) = 4
```
## Sifat Transformasi Linier
```
T = V > W
T(u-v) = T(u+(-v))
       = T(u) + T(v)
       = T(u) - T(v)
```
## Transformasi Linier dan basis
```
Let T:R3 > R3
Jika T(2,3,-2)
Maka :
T((2,0,0) + (0,3,0) + (0,0,-2)) = T((2,3,-2))
```
## Transformasi Linier didefinisikan ke matrik
```
T:R2 > R3
v=(v1,v2)
T(V) = (3v1, 2v1+v2, -v1-2v2)
T(v1,v2) = (3v1, 2v1+v2, -v1-2v2)
R2 > R3
Implementasinya ke matrik yaitu :
| 3  0 |
| 2  1 | = |u1|
|-1 -2 |   |u2|
```
## Transformasi dari M(mxn) ke M(nxm)
```
T(A) = A*t (T :  M(mxn) ke M(nxm))
T(A+B+C) = (A+B+C)*T
T(AB) = (AB)*T
      = B*T A*T
      = T(B) T(A) = T(A) T(B)
```
## Matriks standar
```
T1(x,y,z)=(2x+y,0,x+z)
Matriksnya :
A1 = |2 1 0|
     |0 0 0| (matrik standar T1)
     |1 0 1|
```
## Gabungan Matrik standar
```
matrik standar T = T2 o T1
A = A1.A2
matrik standar T' = T2 o T1
A' = A1.A2
```
## Tugas
```
T1 =
T2 =
```
