#include <iostream>

using namespace std;

int main()
{


    int dimension;
    cout << "INGRESE LA DIMENSION DEL ARREGLO"<<endl;
    cin>>dimension;

    //ARREGLO
    float notasp1[dimension];
    for (int i=0;i<dimension;i++){
    cout << "ingrese la nota  - "<<"["<<i<<"]"<<endl;
    cin>>notasp1[i];
    }
    for(int i=0; i<dimension;i++){
    cout<<"LA NOTA "<<"["<<i<<"]-"<<"ES: "<<notasp1[i]<<endl;
    }
    cout<< " "<<endl;
    cout<<"SU PRIMERA NOTA: "<<notasp1[0]<<endl;

    int promedio;

    promedio = ((notasp1[0])+(notasp1[1])+(notasp1[2])+(notasp1[3])+(notasp1[4])+(notasp1[5]))/dimension;
    cout<< "SU VALOR DEL PROMEDIO ES: "<<promedio<<endl;
    return 0;
}

