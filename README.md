#include<iostream>
#include <string>

using namespace std;

struct mahasiswa
{
    string nim;
    string nama;
    string alamat;
    float ipk;
};  

int main() {
    mahasiswa doni;

    doni.nim = "c03240001";
    doni.nama = "Budyy";
    doni.alamat = "Jl.Berkah No.15";
    doni.ipk = 3.7;

    cout << doni.nim << "\n";
    cout << doni.nama << "\n";
    cout << doni.alamat << "\n";
    cout << doni.ipk << "\n";
    return 0;
}
