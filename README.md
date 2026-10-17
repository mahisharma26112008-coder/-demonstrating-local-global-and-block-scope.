# -demonstrating-local-global-and-block-scope.

#include<iostream>
  using namespace std;
    int x=10;
    
    int main(){
        int y=20;
        cout<<"global variable  : "<<x<<"\n";
        cout<<"local variable   : "<<y<<"\n";
    
    
    {
        int z;
        z=30;
        cout<<"block  variable : "<<z<<"\n";
    }
    return 0;
    }
