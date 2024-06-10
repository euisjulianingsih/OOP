## Inhertiance
```

#include <iostream>
#include <string>
using namespace std;

class Hewan{
    public:
        void predator(){
        cout<<"Ini adalah hewan predator"<<endl;}
        void taring(){
        cout<<"Hewan ini memiliki taring"<<endl;}
        void cakar(){
        cout<<"Hewan ini memiliki cakar"<<endl;}
};
class Harimau:public Hewan {
    public:
        void Harimauinfo(){
        cout<<"Hewan ini adalah Harimau"<<endl;}
};
class Singa:public Hewan {
    public:
        void Singainfo(){
        cout<<"Hewan ini adalah singa"<<endl;}
};
class Macan:public Hewan {
    public:
        void Macaninfo(){
        cout<<"Hewan ini adalah macan"<<endl;}
};
int main () {
    Harimau harimau;
    harimau.Harimauinfo();
    harimau.predator();
    // harimau predator();
    harimau.taring();
    harimau.cakar();
cout << endl;

    Singa singa;
    singa.Singainfo();
    singa.predator();
    //singa.predator();
    singa.taring();
    singa.cakar();

cout << endl;

    Macan macan;
    macan.Macaninfo();
    macan.predator();
    // macan predator();
    macan.taring();
    macan.cakar();

    return 0;
}
## hasilruning
```
![Screenshot (29)](https://github.com/euisjulianingsih/OOP/assets/156889234/09f6b9ba-9a0b-40fa-be81-964107a29d6f)




## inhertiance
```

#include <iostream>
#include <string>
using namespace std;

class Hewan{
    public:
        void predator(){
        cout<<"Ini adalah hewan predator"<<endl;}
        void taring(){
        cout<<"Hewan ini memiliki taring"<<endl;}
        void cakar(){
        cout<<"Hewan ini memiliki cakar"<<endl;}
};
class Harimau:public Hewan {
    public:
        void predator(){
        cout<<"Hewan ini adalah Harimau"<<endl;}
};
class Singa:public Hewan {
    public:
        void predator(){
        cout<<"Hewan ini adalah singa"<<endl;}
};
class Macan:public Hewan {
    public:
        void predator(){
        cout<<"Hewan ini adalah macan"<<endl;}
};
int main () {
    Harimau harimau;
    harimau.predator();
    //harimau.predator();
    harimau.taring();
    harimau.cakar();
cout << endl;

    Singa singa;
    singa.predator();
    //singa.predator();
    singa.taring();
    singa.cakar();

cout << endl;

    Macan macan;
    macan.predator();
    //macan.predator();
    macan.taring();
    macan.cakar();

    return 0;
}
## Hasilruning
```
![Screenshot (31)](https://github.com/euisjulianingsih/OOP/assets/156889234/f6cc0e4d-c013-4c32-8939-6bbc14fc213f)

Pada koding pertama, saat memanggil fungsi predator() dari objek-objek kelas turunan, yang dipanggil adalah fungsi predator() dari kelas dasar Hewan. Oleh karena itu, hasil outputnya adalah "Ini adalah hewan predator" untuk setiap objek, tanpa memperhatikan jenis spesifik dari hewan tersebut.Sedangkan pada koding kedua, pemanggilan fungsi predator() dari objek-objek kelas turunan memanggil fungsi predator() yang sudah di-override pada masing-masing kelas turunan. Oleh karena itu, hasil outputnya mencerminkan deskripsi spesifik dari masing-masing hewan, yaitu "Hewan ini adalah Harimau" untuk objek Harimau, "Hewan ini adalah Singa" untuk objek Singa, dan "Hewan ini adalah Macan" untuk objek Macan.Dengan kata lain, perbedaan utama terletak pada penggunaan fungsi override di kelas turunan pada koding kedua, yang memungkinkan output lebih spesifik sesuai jenis hewan.
