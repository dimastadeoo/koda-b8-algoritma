# Algoritma
## Menentukan Ganjil Genap Deskriptif

Algoritma ini untuk menentukan bilangan ganjil dan genap secara Deskriptif

1. Mulai
2. siapkan deretan angka yang ingin ditentukan bilangan ganjil / genap
3. menentukan bilang genap: jika bilangan bisa habis dibagi 2, Kelompokkan di bilangan genap
4. lalu sisanya kelompokkan di bilangan ganjil
5. selesai

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
CONSTANT n = Bilangan % 2

INPUT Bilangan

IF n==0 THEN
    OUTPUT "Bilangan Genap"
ELSE
    OUTPUT "Bilangan Ganjil"
ENDIF



```