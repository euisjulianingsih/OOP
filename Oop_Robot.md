# OOP ROBOT
## Program
``` +cpp
#include <iostream>
using namespace std;

// Deklarasi kelas
class Robot {
public:
    string nama;
    int umur;
    string mbti;

    // Metode untuk menampilkan informasi
    void perkenalandiri() {
        cout << "Nama: " << nama << endl;
        cout << "Umur: " << umur << endl;
        cout << "mbti: " << mbti << endl;
    }
};

int main() {
    // Membuat objek dari kelas robot
    Robot r1;
    Robot r2;

    // Memberi nilai atribut objek
    r1.nama = "John";
    r1.umur = 30;
    r1.mbti = "istj";

    r2.nama = "jaehyun";
    r2.umur = 30;
    r2.mbti = "istj";

    r1.perkenalandiri();
    r2.perkenalandiri();
    

    // Memanggil metode untuk menampilkan informasi


    return 0;
}
```

#Capture Hasil Running
![Screenshot 2024-05-20 094102](https://github.com/euisjulianingsih/OOP/assets/156889234/a712131f-aa8b-4b75-967a-f88d8eb01404)
