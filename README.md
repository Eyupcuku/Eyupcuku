#include <iostream>

  using namespace std;

int main() {
    
    cout<< "ŞiMdİ SiZe SıNıFı GeÇtİnİzMi KaLdINıZmI sÖyLeYeCeĞiM!!!!!😁" <<endl;
    
    
    cout << "1.yazılı puanınızı girin😑: ";
    double yzl1;
    cin >> yzl1;

    cout << "2.yazılı puanınızı giriniz😑: ";
    double yzl2;
    cin >> yzl2;

    double ort = (yzl1 + yzl2) / 2.0;


    if (ort > 50) {
        cout << "Hadi yine sınıfta kalmaktan yırttın haa!🤩" << endl;
        
    } else {
        cout << "zorrt Sınıfta kaldın?!!?😞" << endl;
    }

    return 0;
}
