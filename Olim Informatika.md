Gadischa Yasmin El Faiza

## 1A - Program pertamaku

Diselesaikan oleh Yasmin

```cpp
#include <iostream>

int main() {
    std::cout << "Halo, dunia!" << std::endl;
}
```

## 1B - Mencetak dengan std::cout

Diselesaikan oleh Yasmin

```cpp
#include <iostream>

int main() {
    std::cout << "Halo, dunia!" << std::endl;
    std::cout << "Aku semangat belajar C++!" << std::endl;
}
```

## 1C - Mencetak Bilangan

Diselesaikan oleh Yasmin

```cpp
#include <iostream>

int main() {
    std::cout << "Pak Dengklek memiliki " << 75 << " ekor bebek." << std::endl;
}
```

## 1D - Menjumlahkan Bilangan

Diselesaikan oleh Yasmin

```cpp
#include <iostream>

int main() {
    std::cout << "Pak Dengklek memiliki " << 738 + 519 << " ekor bebek." << std::endl;
}
```

## 1E - String atau Bilangan

Diselesaikan oleh Yasmin

```cpp
Pada soal no. 1, perhatikan bahwa "9 * 9" adalah string, sehingga akan dicetak apa adanya.

Hanya ada satu baris yang tercetak, karena hanya ada satu `std::endl`.

---

Pada soal no. 2, nilai 4242 (bilangan) dan "42" (string) akan sama-sama tercetak sebagai `42`, begitu pula ekspresi 40+11/(5−1)40+11/(5−1) (yang menghasilkan nilai 40+11/4=40+2=4240+11/4=40+2=42).
```

## 1F - Mengukur kandang

```cpp
#include <iostream>

int main() {
    // cetak luas kandang
    std::cout << 364 * 79 << std::endl;

    // cetak keliling kandang
    std::cout << 2 * (364 + 79) << std::endl;
}
```

## 2A - #include dan std::

Diselesaikan oleh Yasmin

```cpp
Hanya program nomor II yang tidak sesuai sintaks bahasa C++. Program tersebut menggunakan `cout` dan `endl`, tanpa diawali dengan `std::` atau dilengkapi dengan perintah `using namespace std;`.
```

## 2B - Perkenalan Variabel

Diselesaikan oleh Yasmin

```cpp
#include <iostream>
using namespace std;

int main() {
    int panjang = 364;
    int lebar = 79;

    // cetak luas kandang
    cout << panjang * lebar << endl;

    // cetak keliling kandang
    cout << 2 * (panjang + lebar) << endl;
}
```

## 2C - Memperbarui nilai variabel

Diselesaikan oleh Yasmin

```cpp
#include <iostream>
using namespace std;

int main() {
    // kata sandi bulan pertama
    int sandi = 174;
    cout << sandi << endl;

    // kata sandi bulan kedua
    sandi = sandi * 23;
    cout << sandi << endl;

    // kata sandi bulan ketiga
    sandi = sandi * 23;
    cout << sandi << endl;
}
```

## 2D - Kuis Perubahan Nilai Variabel

Diselesaikan oleh Yasmin

```cpp
Pada soal no. 1, berikut adalah "perjalanan" perubahan nilai dari variabel `x`:

|Perintah|Nilai x setelah  <br>perintah dijalankan|
|---|---|
|```<br>int x = 3;<br>```|3|
|```<br>x = x + 1;<br>```|4|

---

Pada soal no. 2, berikut adalah "perjalanan" perubahan nilai dari variabel `x`:

|Perintah|Nilai x setelah  <br>perintah dijalankan|
|---|---|
|```<br>int x = 3;<br>```|3|
|```<br>x = x + x;<br>```|6|

---

Pada soal no. 3, berikut adalah "perjalanan" perubahan nilai dari variabel `x` dan `y`:

|Perintah|Nilai x setelah  <br>perintah dijalankan|Nilai y setelah  <br>perintah dijalankan|
|---|---|---|
|```<br>int x = 3;<br>```|3|(tidak ada)|
|```<br>int y = 4;<br>```|3|4|
|```<br>x = y;<br>```|4|4|
|```<br>y = x;<br>```|4|4|

Perhatikan bahwa program tersebut TIDAK menukar isi dari variabel `x` dan `y`.
```

## 2E - Perkenalan Tipe Data String

Diselesaikan oleh Yasmin

```cpp
#include <iostream> // untuk menggunakan cout dan endl
#include <string>   // untuk menggunakan string
using namespace std;

int main() {
    int tanggal = 15;
    int tahun = 2023;

    // jangan lupa bahwa string perlu diapit dengan kutip dua
    string bulan = "Februari"; 

    // cetak kata sandi
    cout << tahun + 10 << "-" << bulan << "-" << tanggal + 7 << endl;
}
```

## 2F - Aturan Variabel

Diselesaikan oleh Yasmin

```cpp
Pada soal no. 2, yang tidak sesuai sintaks adalah potongan program a. Kita tidak bisa mengisi variabel bertipe `int` dengan nilai dari variabel lain yang bertipe `std::string`.
```

## 2G - Jual Beli Bebek

Diselesaikan oleh Yasmin

```cpp
#include <iostream>
using namespace std;

int main() {
	int jantan, betina;
 
    // banyaknya bebek saat ini
	jantan = 63;
	betina = 192;
 
    // setelah bulan pertama
	betina = betina + jantan;
	jantan = jantan - (jantan / 3);
 
    // setelah bulan kedua
	jantan = jantan + betina;
	betina = betina - 10;
	
    // cetak total bebek
	cout << jantan + betina << endl;
}
```

## 2H - Rangkuman: Variabel dan Tipe Data

Diselesaikan oleh Yasmin

```cpp
Perubahan dari variabel `y` tidak berpengaruh terhadap variabel `x`.
```

## 3A - Variasi Operasi Assignment

Diselesaikan oleh Yasmin

```cpp
Pada soal no. 1, berikut adalah "perjalanan" perubahan nilai dari variabel `x` dan `y`:

|Perintah|Nilai x setelah  <br>perintah dijalankan|Nilai y setelah  <br>perintah dijalankan|
|---|---|---|
|```<br>int x = 3, y = 4;<br>```|3|4|
|```<br>x -= 1;<br>```|2|4|
|```<br>y += x * 5;<br>```|2|14|

---

Pada soal no. 2, semua operasi (kecuali no. c) melipatgandakan nilai variabel `x`.
```

## 3B - Membeli Kandang

Diselesaikan oleh Yasmin

```cpp
#include <iostream>
using namespace std;

int main() {
    int luas_kandang = 12;

    // bulan pertama
    luas_kandang += 7;
    cout << luas_kandang << endl;

    // bulan kedua
    luas_kandang += 7;
    cout << luas_kandang << endl;

    // bulan ketiga
    luas_kandang += 7;
    cout << luas_kandang << endl;
}
```

## 3C - Perkenalan While

Diselesaikan oleh Yasmin

```cpp
#include <iostream>
using namespace std;

int main() {
    int luas_kandang = 12;

    while (luas_kandang < 33) {
        luas_kandang += 7;
        cout << luas_kandang << endl;


    }
}
```

## 3D - Pendalaman While

Diselesaikan oleh Yasmin


1. Berapa kalikah `C++` akan tercetak?
```cpp

int counter = 0;
while (counter < 4) {
    cout << "C++" << endl;
    counter += 1;
}
```

b. 4

2. Berapa kalikah `C++` akan tercetak?

```cpp
```int counter = 1;
while (counter < 4) {
    cout << "C++" << endl;
    counter += 1;
}
```

a. 3

3. Berapa kalikah `C++` akan tercetak?

```cpp
int counter = 1;
while (counter <= 4) {
    cout << "C++" << endl;
    counter += 1;
}
```

b. 4

4. Berapa kalikah `C++` akan tercetak?

```cpp
int counter = 1;
while (counter <= 6) {
    cout << "C++" << endl;
    counter += 2;
}
```

a. 3

## 3E - Membeli Kandang II

Diselesaikan oleh Yasmin

```cpp
#include <iostream>
using namespace std;

int main() {
    int luas_kandang = 12;
    int nomor_baris = 1;

    while (nomor_baris < 4) {
        luas_kandang += 7;
        cout << nomor_baris << ": " << luas_kandang << endl;

        nomor_baris += 1;
    }
}
```

## 3F - Membeli Kandang III

Diselesaikan oleh Yasmin

```cpp
#include <iostream>
using namespace std;

int main() {
    int luas_kandang = 12;
    
    // Menyatakan sudah berapa bulan (berapa kali) Pak Dengklek
    // membeli kandang baru.
    int total_bulan = 0;

    // Menyatakan total luas kandang yang dimiliki Pak Dengklek.
    // Pada mulanya, totalnya adalah luas kandang lama Pak Dengklek.
    int total_luas_kandang = luas_kandang;

    while (total_bulan < 10) {
        luas_kandang += 7;
        total_luas_kandang += luas_kandang;

        total_bulan += 1;
    }

    cout << total_luas_kandang << endl;
}
```

## 3G - Membeli Kandang IV

Diselesaikan oleh Yasmin

```cpp
#include <iostream>
using namespace std;

int main() {
    // Menyatakan total banyaknya kandang yang dimiliki Pak Dengklek.
    // Pada mulanya, Pak Dengklek memiliki 1 kandang seluas 12 meter persegi.
    int total_kandang = 1;
    int luas_kandang = 12;

    int total_luas_kandang = luas_kandang;

    while (total_luas_kandang <= 800) {
        luas_kandang += 7;
        total_luas_kandang += luas_kandang;

        total_kandang += 1;
    }

    cout << total_kandang << endl;
}
```

## 3H - Jual-Beli Bebek II

Diselesaikan oleh Yasmin

```cpp
#include <iostream>
using namespace std;

int main() {
    int jantan = 0, betina = 0;
    int tanggal = 1;

    while (betina <= 10 * jantan) {
        betina += tanggal;
        tanggal += 1;
        jantan += 1;
    }

    cout << tanggal << endl;
}
```

## 3I - Rangkuman : Perulangan

Diselesaikan oleh Yasmin

1. Berapa kalikah tanda bintang tercetak pada potongan program berikut?

```cpp
int total = 0;
while (total < 2) {
    cout << "*" << endl;
}
```

e. tercetak terus-menerus tanpa henti

Perhatikan bahwa karena variabel `total` tidak pernah berubah, kondisinya tidak pernah berubah, yakni selalu benar. Oleh karena itu, perulangan `while` tersebut tidak pernah berhenti. Hati-hati! Ini merupakan kesalahan yang cukup umum.

(Sebaliknya, jika kondisinya adalah salah sedari awal, perulangan `while` tidak akan pernah dijalankan.)