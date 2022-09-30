# Program-C-_TLS22
Fatimah Nadia Eka Putri_Tesla
#include <iostream>

using namespace std;

int main()
{
    cout<<"BMI Calculator\n";
    float massa, height, BMI;
    
    cout<<"\nMasukkan berat badan Anda dalam kilogram (kg) = ";
    cin>>massa;
    cout<<"\nMasukkan tinggi badan Anda dalam sentimeter (cm) = ";
    cin>>height;
    
    
    height=height/100;
    BMI=massa/(height*height);
    cout<<"\nBMI anda adalah= "<<BMI<<endl;
    cout<<"\nKeterangan: ";
    
    if (BMI<18.5)
    {
        cout<<"\nBerat badan Anda kurang proporsional"<<endl;
    }
    else if (BMI>=18.5 && BMI<=22.9)
    {
        cout<<"\nBerat badan Anda normal"<<endl;
    }
    else if (BMI>=23 && BMI<=29.9)
    {
        cout<<"\nAnda memiliki berat badan berlebih dan berpotensi mengalami obesitas"<<endl;
    }
    else if (BMI>=30)
    {
        cout<<"\nAnda mengalami obesitas"<<endl;
    }

    return 0;
}
