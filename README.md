# Listas.cpp

#include  iostream>
using namespace std;

int a, b;

int main(){

cout <<"Hello mellow, I´am super roboto 3000, can you give me a number  "<<endl;

cin>> a;

cout<<"Mellow hello, and I´am robotó, the french cousin of roboto 3000, can you give me a number too ?  "<<endl;

cin>>b;


cout<<"My number added to my cousin´s number is:  " <<a+b<<endl;


if (a+b==0){

  cout <<"Your number is neutral and you have to feel bad"<<endl;
}

if (a+b>0){

  cout <<"The number is positive"<<endl;
  
  if (a+b==10){
  
    cout<<"¡¡You discover a secret number, yeah !!"<<endl;
  }
}
if (a+b<=-10){

    cout<<"You discovered another secret number, have a cookie "<<endl;
  }
if (a+b<0){

  cout<<"Negative"<<endl;
  
}
return 0;
}
