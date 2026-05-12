# Algoritma
## Menentukan Ganjil Genap Deskriptif

Algoritma ini untuk menentukan bilangan ganjil dan genap secara Deskriptif

1. Mulai
2. Masukkan Bilangan
3. Tampung nilai n dari hasil Bilangan di Modulus 2
4. jika nilai n hasilnya 0, outputkan bilangan genap
5. jika tidak outputkan di bilangan ganjil
6. selesai

## Menentukan Ganjil Genap Flowcart

Algoritma ini untuk menentukan bilangan ganjil dan genap menggunakan flowchart

```mermaid
flowchart TD
    A@{ shape: circle, label: "Start" }
    
    B@{ shape: lean-r, label: "Bilangan" }
    G@{ shape: rect, label: "n = Bilangan % 2" }

    C@{ shape: diamond, label: "n==0" }

    D@{ shape: lean-r, label: "&quot;Bilangan Ganjil&quot;" }
    E@{ shape: lean-r, label: "&quot;Bilangan Genap&quot;" }

    F@{ shape: dbl-circ, label: "Stop" }

    A --> B --> G --> C-. Ya .-> E --> F
    C-. Tidak .-> D --> F


```
## Menentukan Ganjil Genap PSEUDO-CODE

Algoritma ini untuk menentukan bilangan ganjil dan genap menggunakan Pseude-Code

```pseudo
DECLARE Bilangan: INTEGER
DECLARE n: INTEGER


INPUT Bilangan
n <- Bilangan % 2

IF n==0 THEN
    OUTPUT "Bilangan Genap"
ELSE
    OUTPUT "Bilangan Ganjil"
ENDIF



```
