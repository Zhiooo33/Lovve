# Lovve
int gift
#include <iostream>
using namespace std;

int main() {
    // Kode warna ANSI untuk merah dan reset
    const char* red = "\033[31m";
    const char* reset = "\033[0m";

    // Pola love sederhana menggunakan karakter '*' dengan warna merah
    cout << red << "  ***     ***  " << reset << endl;
    cout << red << " *****   ***** " << reset << endl;
    cout << red << "******* *******" << reset << endl;
    cout << red << " ************* " << reset << endl;
    cout << red << "  ***********  " << reset << endl;
    cout << red << "   *********   " << reset << endl;
    cout << red << "    *******    " << reset << endl;
    cout << red << "     *****     " << reset << endl;
    cout << red << "      ***      " << reset << endl;
    cout << red << "       *       " << reset << endl;
    cout << endl;
    // Teks di bawah love tanpa warna agar jelas terbaca
    cout << "aku akan selalu bersama" << endl;
    return 0;
}
