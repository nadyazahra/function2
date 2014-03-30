//function2_variable_lokal
#include <iostream>

void alpha();                  //prototipe fungsi 
int main()
{ 
    int x = 22;               //variabel lokal pada main()
    double y = 2.22;         //begitu juga variabel ini

    cout<<"Pada main () : x = " <<x
        <<" y = "<< y << endl;

    alpha(); //panggil fungsi alpha
    cout<<"Pada main () : x = " <<x
        <<" y = "<< y << endl;
} 

void alpha() 
{   
    int x = 20;              //variabel lokal pada alpha()
    double y = 3.14;        //begitu juga variabel ini

    cout<<"Pada alpha () : x = " <<x 
        <<" y = "<< y << endl;
}
