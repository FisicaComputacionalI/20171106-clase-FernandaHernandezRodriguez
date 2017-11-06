# 20171106-clase-FernandaHernandezRodriguez
20171106-clase-FernandaHernandezRodriguez created by GitHub Classroom



//Programa para entender uso de SWITCH
//Autor: Marìa Fernanda Hernandez Rodriguez
//Creado:Lunes 6 de noviembre de 2017

#include <iostream>
using namespace std;

int main(){
        char variable;
cout<<"Escoge una opcion entre  A,B,C,D,E"<<endl;
cin>>variable;

switch(variable){
        case 'A': cout<<"Excelente"<<endl;break;
        case 'B': cout<<"Muy bien"<<endl;break;
        case 'C': cout<<"Bien"<<endl;break;
        case 'D': cout<<"Pasaste"<<endl;break;
        case 'E': cout<<"Intentalo nuevamente"<<endl;break;

        default: cout<<"opcion no valida"<<endl;
                }
return 0;
          }
