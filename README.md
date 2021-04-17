# PRAK_DKP_FANGKI-IGO-PRAMANA_KELOMPOK-43

#include <iostream>  

using namespace std;

void opening() {
    cout << "==================== Toko Buku Komik Animepedia ====================" << endl;
}
void judul_komik() {
    cout << "Daftar Komik: 1.Boku No Hero Academia (A) 2.Jujutsu Kaisen (B) 3.Doctor Stone (C) 4.Attack On Titan (D) " << endl;
}
void Volume_tersedia() {
    cout << "Volume tersedia: A.Volume 1 (1) B.Volume 2 (2) C.Episode Spesial (3-4) " << endl;
}
void Kelompok() {
    cout << "=============== Kelompok 43 ===============" << endl;
    cout << "Nama: Muhammad Farhan Ashari NIM: 21120120130072" << endl;
    cout << "Nama: Rama Pradana Putra NIM: 21120119140125" << endl;
    cout << "Nama: Fangki Igo Pramana NIM: 21120120130088" << endl;
    cout << "Nama: Bainingtyas Khalifa Nurharyanti NIM: 21120120140111" << endl;
}



int main() {

    char KodeBuku;

    string Judul_Komik, pernyataan;

    int Volume, harga, i;


   

    opening();
    printf("\n\n");

    judul_komik();
    cout << "Masukkan Kode Buku Komik : ";

    cin >> KodeBuku;

    printf("\n\n");
    Volume_tersedia();
    

    cout << "Masukkan Volume : ";

    cin >> Volume;
