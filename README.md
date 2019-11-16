# producto#include <iostream>
#include"Producto.h"
using namespace std;

int main(void)
{
    Producto P1;
    cout<<endl<<"P1"<<endl;
    P1.muestraDatos();

    Producto P2("Teclado",1,1234.56);
    cout<<endl<<"P2"<<endl;
    P2.muestraDatos();

    P1.modificaNombre("Raton");
    P1.modificaNumero(2);
    P1.modificaPrecio(654.32);
    cout<<endl<<"P1"<<endl;
    P1.muestraDatos();

    P2.modificaDatos("Monitor",3,2345.67);
    cout<<endl<<"P2"<<endl;
    P2.muestraDatos();

    cout<<endl<<"P1"<<endl;
    P1.pideDatos();
    cout<<endl<<"P1"<<endl;
    P1.muestraDatos();

    return 0;
}
