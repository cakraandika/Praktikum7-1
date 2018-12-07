# Praktikum7
 cin >> b;
 cout << " AxB = " << kali_rekursif(a, b) << endl;
}

**Screenshoot**
![Screenshoot](https://raw.githubusercontent.com/fiqihalfiansyahzahari/Praktikum7/master/Soal2.png)

##Latihan3 : Carilah kasus lain yang bisa diselesaikan dengan cara rekursif dengan iteratif.

1.Mulai program tersebut
2.input menggunakan initruksi void dan menggunakan pointer untuk menetapakan void typedata (char *s)
3.jika nilai s!=0--> menggunakan Pointer(*) maka masukan intruksi membalik (&s[1])
4.masuan char untuk intruksi kata yang ingin kita ubah dan intruksi balik
5.cetak pemblikan kata dengan memanggil funsi rekrusif menggunkan type datany.
Pseudecoede

#include
#include
void balik(char *k){
if(*k!=”){
balik(&k[1]);
cout<
}
}main(){
char *kata=”....”;--> //untuk masukan kata
balik(kata);
cout<
return 0;
CODE PROGRAM

#include<iostream>
#include<string.h>

using namespace std;
void balik(char *s)
{ if (*s != '\0'){
balik(&s[1]);
cout << s[0];
}
}
int main()
{
      char* kata = (char*) "rehan";
    balik(kata); cout << endl;
    return 0;

}

**Screenshoot**
![Screenshoot](https://raw.githubusercontent.com/fiqihalfiansyahzahari/Praktikum7/master/Soal3.png)
