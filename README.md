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
    
    if (KodeBuku == 'A') {

        Judul_Komik = "Boku No Hero Academia";

        if (Volume == 1) {

            harga = 25000;

        }

        else if (Volume == 2) {

            harga = 27000;

        }

        else if (Volume == 3) {

            harga = 30000;

        }
        else if (Volume == 4) {
            
            harga = 33000;
        }
        else {

            harga = 0;
            cout << "Masukkan Kode Dengan Benar" << endl;
        }
    }

    else if (KodeBuku == 'B') {

        Judul_Komik = "Jujutsu Kaisen";

        if (Volume == 1) {

            harga = 28000;

        }

        else if (Volume == 2) {

            harga = 29000;

        }

        else if (Volume == 3) {

            harga = 31000;

        }
        else if (Volume == 4) {

            harga = 34000;
        }
        else {

            harga = 0;
            cout << "Masukkan Kode Dengan Benar" << endl;
        }
    }

    else if (KodeBuku == 'C') {

        Judul_Komik = "Doctor Stone";

        if (Volume == 1) {

            harga = 30000;

        }

        else if (Volume == 2) {

            harga = 32000;

        }

        else if (Volume == 3) {

            harga = 34000;

        }
        else if (Volume == 4) {

            harga = 36000;
        }
        else {

            harga = 0;
            cout << "Masukkan Kode Dengan Benar" << endl;
        }
    }

    else if (KodeBuku == 'D') {

        Judul_Komik = "Attack On Titan";

        if (Volume == 1) {

            harga = 30000;

        }

        else if (Volume == 2) {

            harga = 32000;

        }

        else if (Volume == 3) {

            harga = 35000;

        }
        else if (Volume == 4) {

            harga = 37000;
        }
        else {

            harga = 0;
            cout << "Masukkan Kode Volume Dengan Benar" << endl;
        }
    }

    

    else {

        Judul_Komik = "Error";
        harga = 0;


    }
    switch (Volume) {
    case 1:
        cout << "\n\nJudul Komik  = " << Judul_Komik;

        cout << "\nVolume = " << Volume;

        cout << "\nHarga Komik  = " << harga;
        break;

    case 2:
        cout << "\n\nJudul Komik  = " << Judul_Komik;

        cout << "\nVolume = " << Volume;

        cout << "\nHarga Komik  = " << harga;
        break;

    case 3:
        cout << "\n\nJudul Komik  = " << Judul_Komik;

        cout << "\nVolume = " << Volume;

        cout << "\nHarga Komik  = " << harga;
        break;

    case 4:
        cout << "\n\nJudul Komik  = " << Judul_Komik;

        cout << "\nVolume = " << Volume;

        cout << "\nHarga Komik  = " << harga;
        break;

    case 5:
        cout << "\n\nJudul Komik  = " << Judul_Komik;

        cout << "\nVolume = " << Volume;

        cout << "\nHarga Komik  = " << harga;
        break;
    default:
        cout << Judul_Komik << endl;
        cout << "\n== Kami tidak mempunyai komik ini ==";


    }

    printf("\n\n");
    cout << "Apakah anda ingin membeli komik lagi?: (Ya) (Tidak) ";

    cin >> pernyataan;
    printf("\n\n");

    if (pernyataan == "Ya") {
        main();
    }
    else if (pernyataan == "Tidak") {
        cout << "Masukkan Jumlah komik yang anda beli: ";
        cin >> i;
        printf("\n\n");
        while (i > 0) {
            cout << "Pembelian Komik Anda yang Ke " << i << " Berhasil Dilakukan"" \n";
            i--;
        }         

        printf("\n\n");
        cout << "Terima Kasih sudah berbelanja di toko kami" << endl;
        printf("\n\n");
        opening();
    }
    else {
        cout << "Tolong Masukkan kata yang sesuai, terima kasih" << endl;
        printf("\n\n");
        main();
    }
   
    return 0;
}
    

