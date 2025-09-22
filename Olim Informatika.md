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

## 4A- Perkenalan If

Diselesaikan oleh Yasmin

```cpp
Pada soal no. 1, terdapat sebuah percabangan `if`. Kondisinya bernilai benar ✅.

- Sehingga, kode di dalamnya dijalankan.

---

Pada soal no. 2, terdapat sebuah percabangan `if`. Kondisinya bernilai salah ❌.

- Sehingga, kode di dalamnya TIDAK dijalankan.

---

Pada soal no. 3, terdapat **tiga** buah percabangan `if`:

- Pada `if` pertama, kondisinya bernilai salah ❌.
    - Sehingga, kode di dalamnya TIDAK dijalankan.
- Pada `if` kedua, kondisinya bernilai benar ✅.
    - Sehingga, kode di dalamnya dijalankan.
- Pada `if` ketiga, kondisinya bernilai benar ✅.
    - Sehingga, kode di dalamnya dijalankan.

---

Selanjutnya, kita akan coba gunakan struktur percabangan `if` ini pada soal berikutnya.
```

## 4B - Menggiring Bebek

Diselesaikan oleh Yasmin

```cpp
#include <iostream>
using namespace std;

int main() {
    int jantan = 67;
    int betina = 98;

    if (jantan % 2 == 0) {
        cout << "banyaknya bebek jantan adalah bilangan genap" << endl;
    }

    if (betina % 2 == 0) {
        cout << "banyaknya bebek betina adalah bilangan genap"<< endl;
    }
}
```

## 4C - Perkenalan Else

Diselesaikan oleh Yasmin

```cpp
#include <iostream>
using namespace std;

int main() {
    int total_bebek = 67 + 98;

    if (total_bebek % 2 == 0) {
        cout << "total banyaknya bebek adalah bilangan genap" << endl;
    } (total_bebek % 2 == 0) ;{
        cout << "total banyaknya bebek adalah bilangan ganjil" << endl;
    }
}
```

## 4D - Perkenalan Else If

Diselesaikan oleh Yasmin

```cpp
#include <iostream>
using namespace std;

int main() {
    int total_bebek = 67 + 98;

    if (total_bebek % 13 == 0) {
        cout << 13 << endl;
    }
    else if (total_bebek % 11 == 0) {
        cout << 11 << endl;
    }
    else if (total_bebek % 5 == 0) {
        cout << 5 << endl;
    }
    else if (total_bebek % 3 == 0) {
        cout << 3 << endl;
    } else {
        cout << 1 << endl;
    }
}
```
## 4E - Kuis If

Diselesaikan oleh Yasmin

## 4F - Pendalaman Ekspresi Boolean

Diselesaikan oleh Yasmin

Pada soal no. 1, perhatikan bahwa kita tidak bisa menuliskan `1000 <= n < 10000`. Pada C++, kode tersebut ekuivalen dengan `(1000 <= n) < 10000`; yang tidak bermakna seperti yang kita inginkan.

---

Pada soal no. 2, perhatikan bahwa operator logika bersifat komutatif, sehingga semua ekspresi di bawah ini ekuivalen:

- `(tahun % 4 == 0 && tahun % 100 != 0) || tahun % 400 == 0`
- `tahun % 400 == 0 || (tahun % 4 == 0 && tahun % 100 != 0)`
- `tahun % 400 == 0 || (tahun % 100 != 0 && tahun % 4 == 0)`
- ... dst.

## 4G - Mengukur kandang II

Diselesaikan oleh Yasmin

```cpp
#include <iostream>
#include <string>
using namespace std;

int main() {
    int A = 364 * 79;
    int B = 243 * 99;
    int C = 189 * 155;

    string terbesar, terkecil;

    if (A > B && A > C) {
        // jika A lebih besar dari B dan C, maka A terbesar
        terbesar = "A";

        // cari yang terkecil, yakni yang lebih kecil antara B dan C
        if (B < C) {
            terkecil = "B";
        } else {
            terkecil = "C";
        }
    } else if (B > A && B > C) {
        // jika B lebih besar dari A dan C, maka B terbesar
        terbesar = "B";

        // cari yang terkecil, yakni yang lebih kecil antara A dan C
        if (A < C) {
            terkecil = "A";
        } else {
            terkecil = "C";
        }
    } else {
        // sampai sini, maka C terbesar
        terbesar = "C";

        // cari yang terkecil, yakni yang lebih kecil antara A dan B
        if (A < B) {
            terkecil = "A";
        } else {
            terkecil = "B";
        }
    }

    cout << terbesar << endl;
    cout << terkecil << endl;
}
```

## 4H - Rangkuman: Percabangan

Diselesaikan oleh Yasmin

Sebetulnya, struktur `if`-`else if` merupakan sintaks yang disediakan bahasa C++, agar kita tidak harus menuliskan perulangan `if`-`else` bersarang apabila terdapat lebih dari satu kondisi.

## 5A - Perkenalan For

Diselesaikan Oleh Yasmin

```cpp
#include <iostream>
using namespace std;

int main() {
    for (int sisi = 121; sisi <= 125; sisi += 1) {
        cout << sisi * sisi << endl;
    }
}
```

## 5B - Perkenalan Tipe Data Boolean

Diselesaikan oleh Yasmin

```cpp
#include <iostream>
using namespace std;

int main() {
    bool ada_yang_dijual = true;

    for (int sisi = 121; sisi <= 125; sisi++) {
        bool kelipatan_2 = sisi % 2 == 0;
        bool kelipatan_3 = sisi % 3 == 0;

        if (sisi % 2 == 0 && sisi != sisi % 3 == 0) {
            ada_yang_dijual = true;
        }
    }

    if (ada_yang_dijual) {
        cout << "ada" << endl;
    } else {
        cout << "tidak ada" << endl;
    }
}
```

## 5C - Perkenalan Continue dan Break

