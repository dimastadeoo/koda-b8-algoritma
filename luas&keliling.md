# Algoritma
## Hitung Luas dan Keliling Lingkaran Deskriptif

Algoritma ini digunakan untuk menghitung luas dan keliling lingkaran

1. Mulai
2. masukkan nilai Jari - jari lingkaran
3. kita tampung nilai n sebagai hasil dari nilai jari jari di modulus 7
4. jika nilai n hasilnya 0 maka nilai phi sebagai 22 dibagi 7
5. Jika tidak maka nilai phi sebagai 3.14
6. Hitung luas dengan rumus phi dikalikan Jari jari kuadrat
7. Hitung Keliling dengan rumus: 2 dikalikan phi dikalikan jari jari
8. selesai

## Hitung Luas dan Keliling Lingkaran Flowchart

Algoritma ini untuk menentukan bLuas dan Keliling Lingkaran menggunakan flowchart

```mermaid
flowchart TD
    A@{ shape: circle, label: "Start" }
    
    B@{ shape: lean-r, label: "Jari" }
    G@{ shape: rect, label: "n = Jari % 7" }

    C@{ shape: diamond, label: "n==0" }

    D@{ shape: rect, label: "phi = 3.14" }
    E@{ shape: rect, label: "phi = 22/7" }

    F@{ shape: rect, label: "Luas = phi *Jari * Jari" }
    H@{ shape: rect, label: "Kel = 2* phi *Jari" }

    I@{ shape: lean-r, label: "&quot;Luas Lingkaran {Luas}&quot;" }
    J@{ shape: lean-r, label: "&quot;Keliling Lingkaran {Kel}&quot;" }    

    K@{ shape: dbl-circ, label: "Stop" }

    A --> B --> G --> C-. Ya .-> E --> F
    C-. Tidak .-> D --> F --> H --> I-->J-->K


```
## Hitung Luas dan Keliling Lingkaran Pseudo-Code

``` pseudo
DECLARE Jari: INTEGER
DECLARE n: INTEGER
DECLARE Luas: DOUBLE
DECLARE Keliling: DOUBLE

INPUT Jari
n <- Jari % 7

IF n==0 THEN
    CONSTANT phi = 22/7
ELSE 
    CONSTANT phi = 3.14
Luas <- phi * Jari * Jari
Keliling <- 2 * phi * Jari

OUTPUT "Luas Lingkaran", Luas
OUTPUT "Keliling Lingkaran", Keliling

```
