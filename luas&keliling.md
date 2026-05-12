# Algoritma
## Hitung Luas dan Keliling Lingkaran Deskriptif

Algoritma ini digunakan untuk menghitung luas dan keliling lingkaran

1. Mulai
2. masukkan nilai Jari - jari lingkaran
3. gunakan nilai phi jika jari jari nilainya ketika dibagi 7 sisa pembagian adalah 0 gunakan nilai phi sebagai 22 dibagi 7
4. selain itu gunakan nilai phi sebagai 3.14
5. Hitung luas dengan rumus: phi dikalikan Jari jari kuadrat
6. Hitung Keliling dengan rumus: 2 dikalikan phi dikalikan jari jari
7. selesai

## Hitung Luas dan Keliling Lingkaran Flowchart

Algoritma ini untuk menentukan bLuas dan Keliling Lingkaran menggunakan flowchart

```mermaid
flowchart TD
    A@{ shape: circle, label: "Start" }
    
    B@{ shape: lean-r, label: "Jari" }
    G@{ shape: rect, label: "n = Jari % 7" }

    C@{ shape: diamond, label: "n==0" }

    D@{ shape: lean-r, label: "phi = 3.14" }
    E@{ shape: lean-r, label: "phi = 22/7" }

    F@{ shape: rect, label: "Luas = phi *Jari * Jari" }
    H@{ shape: rect, label: "Kel = 2* phi *Jari" }

    I@{ shape: lean-r, label: "&quot;Luas Lingkaran {Luas}&quot;" }
    J@{ shape: lean-r, label: "&quot;Keliling Lingkaran {Kel}&quot;" }    

    K@{ shape: dbl-circ, label: "Stop" }

    A --> B --> G --> C-. Ya .-> E --> F
    C-. Tidak .-> D --> F --> H --> I-->J-->K


```
