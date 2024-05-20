# OOP Boy Band
## Program 
``` +cpp
#include <iostream>
using namespace std;

// Deklarasi kelas
class Boyband {
public:
    string nama;
    int members;
    string genre;
    string debutyear;

    // Metode untuk menampilkan informasi
    void informasi() {
        cout << "Nama" << nama << endl;
        cout << "Members" << members << endl;
        cout << "Genre" << genre << endl;
        cout << "Debut year" << debutyear << endl;
    }
};

int main() {
    // Membuat objek dari kelas boyband
Boyband P1;


    // Memberi nilai atribut objek
    P1.nama = "John";
    P1.members = 30;
    P1.genre = "istj";
    P1.debutyear = "istj";

    // Memanggil metode untuk menampilkan informasi
    P1.informasi();

    return 0;
}
```
#capture Hasil Running
![Screenshot 2024-05-20 094433](https://github.com/euisjulianingsih/OOP/assets/156889234/b437a4b6-a2fb-424a-91bc-9a3d25d559f0)
