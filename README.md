#include <iostream>
#include <stdio.h>
#include <conio.h>
using namespace std;

int main()
{
    int gaji;
    int jam;
    char nama;
    cout << "Program input Gaji Karyawan\n"<< endl;
    cout<< "Gaji karyawan Rp.5000 perjam dalam 1 hari kerja 8 jam"<<endl;
    cout<< "Masukkan nama karyawan =";
    cin>> nama;
    cout<< "-------------------------------"<<endl;
    cout<<endl<<endl;
    if (jam>=8)
        gaji= 8*5000;
    cout<< "Total gaji anda =";
    cout<< "Rp."<<gaji<<endl;
    cout<< "---------Terima kasih----------"<<endl;

}
