# Switch-de-Opc
#include <iostream>
using namespace std;
int main()
{
int opc=0; //variable para opcion elegido del menu
//creamos menu
cout<<"Menu de operaciones/n"<<endl;
cout<<"1.Suma"<<endl;
cout<<"2.Resta"<<endl;
cout<<"3.Multiplicacion"<<endl;
cout<<"4.Division"<<endl;
cout<<"Selecciona una opcion: "<<endl;
cin>>opc;//captura opcion de Menu

switch (opc)
{ //Llave de inicio
case 1:
int sn1,sn2,rs;
cout<<"Captura primer numero: ";
cin>>sn1;
cout<<"Captura segundo numero: ";
cin>>sn2;
rs=sn1+sn2;
cout<<"Resultado de la suma es: "<<rs;
break;

case 2:
int rn1,rn2,rr;
cout<<"Captura primer numero: ";
cin>>rn1;
cout<<"Captura segundo numero: ";
cin>>rn2;
rr=rn1-rn2;
cout<<"Resultado de la resta es: "<<rr;
break;

case 3:
int mn1,mn2,rm;
cout<<"Captura primer numero: ";
cin>>mn1;
cout<<"Captura segundo numero: ";
cin>>mn2;
rm=mn1*mn2;
cout<<"Resultado de la multiplicacion es: "<<rm;
break;

case 4:
int dn1,dn2,rd;
cout<<"Captura primer numero: ";
cin>>dn1;
cout<<"Captura segundo numero: ";
cin>>dn2;
rd=dn1/dn2;
cout<<"Resultado de la division es: "<<rd;
break;
default:
cout<<"Error de captura por favor seleccione una opcion del 1 al 4";
break;
}//Llave de cierre
    return 0;
}
