#include <iostream>
#include <string>


using namespace std;

void swap(string &name, string &prename){
    string aux = name;
    name = prename;
    prename = aux;
}

int main(){
    string name, prename;

    cout<<"Enter your name: ";
    cin>>name;

    cout<<"Enter your prename: ";
    cin>>prename;

    cout<<"Your first name is "<<name<<" and your second name is: "<< prename<<endl;

    swap(name, prename);

    cout<<"Your first name is "<<name<<" and your second name is: "<< prename<<endl;

    system("pause");

    return 0;
}
