# Ujian Akhir Semester 
<br>Mata Kuliah 	: Dasar pemrograman
<br> Nama		: Aghiz Ghifari
<br>NIM		:	1227050008
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
Matriks adalah suatu susunan bilangan real atau bilangan kompleks (atau elemen-elemen) yang disusun dalam baris dan kolom sehingga membentuk jajaran persegi panjang. Suatu matriks diberi nama dengan menggunakan huruf kapital seperti A, B, C, dan seterusnya, sedangkan anggotanya dinyatakan dengan huruf kecil.

## Source Code
#include<iostream>
using namespace std;


	int main()
	{
	int m, n;

	cout << "UJIAN AKHIR SEMESTER DASAR PEMROGRAMAN"<<endl;
	cout << "---------------------------------------"<<endl<<endl;
	cout << "Nama : Aghiz Ghifari "<<endl;
	cout << "NIM  : 1227050008 "<<endl;
	cout << "Kelas: Teknik informatika - A"<<endl<<endl;
	cout << "-------------------------------"<<endl<<endl;
	cout << "NO.1"<<endl<<endl;
	cout << "Mengubah baris menjadi kolom dan kolom menjadi baris " <<endl<<endl;
	cout << "-------------------------------------------------------"<<endl<<endl;
	cout << "Masukkan jumlah baris matriks: ";
	cin >> m;
	cout << "Masukkan jumlah kolom matriks: ";
	cin >> n;

	int matriks[m][n], transpose[n][m];

	cout << "Masukkan Nilai-Nilai Matriks\n";
	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < n; j++)
		{
			cout <<"Baris ke "<<i+1<<", Kolom ke "<<j+1<<" : ";
			cin  >> matriks[i][j];
		}
	}

	cout << "Hasil dari matriks yang diinputkan :\n";
	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < n; j++)
		{
			cout << matriks[i][j] << "\t";
		}
		cout << endl;
	}
	cout << endl;

	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < n; j++)
		{
			transpose[j][i] = matriks[i][j];
		}
	}

	cout << "Hasil Transpose Matriks: \n";
	for (int i = 0; i < n; i++)
	{
		for (int j = 0; j < m; j++)
		{
			cout << transpose[i][j] << "\t";
		}
		cout << endl;
	}
}
	

#include <iostream>
using namespace std;  
int main(){
int  m,n,matriks[100][100];
    cout <<"NO.2"<<endl;
	cout << "Menampilkan bilangan yang habis dibagi 3, 5 dan 7" << endl;
	cout << "---------------------------------------------------"<<endl;
	cout << "Masukkan jumlah baris matriks: ";
	cin >> m;
	cout << "Masukkan jumlah kolom matriks: ";
	cin >> n;

	cout << "Masukkan Nilai-Nilai\n";
	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < n; j++)
		{
			cout <<"("<<i+1<<","<<j+1<<") : ";
			cin  >> matriks[i][j];
		}
	}
	cout << endl;

	bool cek = true;
	cout << "Nilai yang tidak bisa dibagi 3, 5, 7 yaitu :";
	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < n; j++)
		{
			if (matriks[i][j]%3!=0 && matriks[i][j]%5!=0 && matriks[i][j]%7!=0)
			{
				cout << " " << matriks[i][j];
				cek = false;
			}
		}
	}
	if (cek)
	{
		cout << " Nilai yang anda input bisa dibagi 3, 5 dan 7" <<endl;
	}
	return 0;

	}

# Ujian Akhir Semester 
<br>Mata Kuliah 	: Dasar pemrograman
<br> Nama		: Aghiz Ghifari
<br>NIM		:	1227050008
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
Matriks adalah suatu susunan bilangan real atau bilangan kompleks (atau elemen-elemen) yang disusun dalam baris dan kolom sehingga membentuk jajaran persegi panjang. Suatu matriks diberi nama dengan menggunakan huruf kapital seperti A, B, C, dan seterusnya, sedangkan anggotanya dinyatakan dengan huruf kecil.

## Source Code
#include<iostream>
using namespace std;


	int main()
	{
	int m, n;

	cout << "UJIAN AKHIR SEMESTER DASAR PEMROGRAMAN"<<endl;
	cout << "---------------------------------------"<<endl<<endl;
	cout << "Nama : Aghiz Ghifari "<<endl;
	cout << "NIM  : 1227050008 "<<endl;
	cout << "Kelas: Teknik informatika - A"<<endl<<endl;
	cout << "-------------------------------"<<endl<<endl;
	cout << "NO.1"<<endl<<endl;
	cout << "Mengubah baris menjadi kolom dan kolom menjadi baris " <<endl<<endl;
	cout << "-------------------------------------------------------"<<endl<<endl;
	cout << "Masukkan jumlah baris matriks: ";
	cin >> m;
	cout << "Masukkan jumlah kolom matriks: ";
	cin >> n;

	int matriks[m][n], transpose[n][m];

	cout << "Masukkan Nilai-Nilai Matriks\n";
	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < n; j++)
		{
			cout <<"Baris ke "<<i+1<<", Kolom ke "<<j+1<<" : ";
			cin  >> matriks[i][j];
		}
	}

	cout << "Hasil dari matriks yang diinputkan :\n";
	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < n; j++)
		{
			cout << matriks[i][j] << "\t";
		}
		cout << endl;
	}
	cout << endl;

	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < n; j++)
		{
			transpose[j][i] = matriks[i][j];
		}
	}

	cout << "Hasil Transpose Matriks: \n";
	for (int i = 0; i < n; i++)
	{
		for (int j = 0; j < m; j++)
		{
			cout << transpose[i][j] << "\t";
		}
		cout << endl;
	}
}
	

#include <iostream>
using namespace std;  
int main(){
int  m,n,matriks[100][100];
    cout <<"NO.2"<<endl;
	cout << "Menampilkan bilangan yang habis dibagi 3, 5 dan 7" << endl;
	cout << "---------------------------------------------------"<<endl;
	cout << "Masukkan jumlah baris matriks: ";
	cin >> m;
	cout << "Masukkan jumlah kolom matriks: ";
	cin >> n;

	cout << "Masukkan Nilai-Nilai\n";
	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < n; j++)
		{
			cout <<"("<<i+1<<","<<j+1<<") : ";
			cin  >> matriks[i][j];
		}
	}
	cout << endl;

	bool cek = true;
	cout << "Nilai yang tidak bisa dibagi 3, 5, 7 yaitu :";
	for (int i = 0; i < m; i++)
	{
		for (int j = 0; j < n; j++)
		{
			if (matriks[i][j]%3!=0 && matriks[i][j]%5!=0 && matriks[i][j]%7!=0)
			{
				cout << " " << matriks[i][j];
				cek = false;
			}
		}
	}
	if (cek)
	{
		cout << " Nilai yang anda input bisa dibagi 3, 5 dan 7" <<endl;
	}
	return 0;

	}
  
  ##output
  UJIAN AKHIR SEMESTER DASAR PEMROGRAMAN
---------------------------------------

Nama : Aghiz Ghifari
NIM  : 1227050008
Kelas: Teknik informatika - A

-------------------------------

NO.1

Mengubah baris menjadi kolom dan kolom menjadi baris

-------------------------------------------------------

Masukkan jumlah baris matriks: 2
Masukkan jumlah kolom matriks: 2
Masukkan Nilai-Nilai Matriks
Baris ke 1, Kolom ke 1 : 4
Baris ke 1, Kolom ke 2 : 3
Baris ke 2, Kolom ke 1 : 2
Baris ke 2, Kolom ke 2 : 1
Hasil dari matriks yang diinputkan :
4       3
2       1

Hasil Transpose Matriks:
4       2
3       1

--------------------------------
Process exited after 5.91 seconds with return value 0
Press any key to continue . . .
  
  NO.2
Menampilkan bilangan yang habis dibagi 3, 5 dan 7
---------------------------------------------------
Masukkan jumlah baris matriks: 2
Masukkan jumlah kolom matriks: 2
Masukkan Nilai-Nilai
(1,1) : 4
(1,2) : 3
(2,1) : 2
(2,2) : 1

Nilai yang tidak bisa dibagi 3, 5, 7 yaitu : 4 2 1
--------------------------------
Process exited after 8.169 seconds with return value 0
Press any key to continue . . .


