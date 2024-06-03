# pratikum1
```
#include <iostream>
#include <string>

class Mahasiswa {
private:
  int nrp;
};

class Fakultas {
 public: 
  int kode;
};

int main() {
//mahasiswa mhs;
 Fakultas fkl;
 //mahasiswa nrp 
//mhs.nrp = 12345;
 fkl.kode = 22;
//cout
std ::cout << "kode" << fkl.kode<< std ::endl;

return 0;
}
```
# HasilRuningoutput
![Screenshot (27)](https://github.com/euisjulianingsih/OOP/assets/156889234/c7193d99-240a-49f0-8d61-7b96b4471d36)

# pratikum2
```
#include <iostream>
#include <string>
using namespace std;
class mahasiswa {
    private:
    int nrp;
    public:
    //setter untuk mengatur nilai nrp ( jika di perlukan
    void setNrp(int a) {
        nrp = a;
    }
    // Getter untuk mendapatkan nilai nrp
    int getNrp() {
        return nrp;
    }
};

class Fakultas {
    public:
    int kode;
    void setkode(int k) {
        kode = k;
    }
    // Getter untuk mendapatkan nilai nrp
    int getkode() {
        return kode;
    }
};

int main() {
    mahasiswa mhs;
    Fakultas fkl;

    //mengatur nilai nrp
    mhs.setNrp(12345);
    //mengatur nilai kode
    fkl.setkode(22);

    //mengakses dan mencetak nilai nrp
    cout <<"NRP:"<<mhs.getNrp()<<endl;
    cout <<"kode:"<<fkl.getkode()<<endl;

    return 0;
};
```
# hasilruning
![Screenshot (26)](https://github.com/euisjulianingsih/OOP/assets/156889234/fd40bdd8-bce5-4dbf-8eb6-aafd22144180)
