//4.3 khndri hamar
#include <iostream>
using namespace std;
int main ()
{
int arr=20;
char name[arr];
char surname[arr];
cout<<"enter your name" <<endl;
cin.getline(name,arr);
cout<<"enter your last name" <<endl;
cin.getline(surname,arr);
cout<<"your name and surname is: " <<surname <<" " <<name;
}
