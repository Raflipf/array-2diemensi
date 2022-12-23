
# Ujian Akhir Semester 
<br>Mata Kuliah 	: Dasar Pemograman Dasar
<br> Nama		:Rafli Pratama Ferdian 
<br>NIM		:	1227050111
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
Tentang Array 2 Dimensi
## Source Code

#include <iostream>
#include <iomanip>
 
using namespace std;
 
int main()
{
  cout << "Nama : Rafli Pratama Ferdian \nNIM : 1227050111" << endl;
  cout << "==========================================" << endl;
  cout << endl;
 
  int matriks[100][100];
  int jumlah_baris, jumlah_kolom, i, j,a ;
 
  cout << "Input jumlah baris matriks: ";
  cin >> jumlah_baris;
 
  cout << "Input jumlah kolom matriks: ";
  cin >> jumlah_kolom;
  cout << endl;
 

  for(i = 0; i < jumlah_baris ; i++){
    for(j = 0; j < jumlah_kolom; j++){
      cout << "Baris " <<i+1<<", kolom "<<j+1<< " = ";
      cin >> matriks[i][j];
    }
    cout << endl;
  }
   cout << "Hasil matriks: " << endl;
 
 
  for(i = 0; i < jumlah_kolom ; i++){
    for(j = 0; j < jumlah_baris; j++){
    	if(matriks[j][i]%3==0 && matriks[j][i]%5==0 && matriks[j][i]%7==0){
      		cout << matriks[j][i] << " ";
    }
	}
    cout << endl<<endl;
  }

   for(a=1;a<=100;a++){
 
 }
 }
 
 


## Output
