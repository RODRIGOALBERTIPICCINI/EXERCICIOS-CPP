# EXERCICIOS-CPP
//Escreva um programa que solicita inserir dois numeros, imprime a soma, produto, diferenÃ§a e diviÃ§Ã£o:

#include <iostream>
# include <iomanip>

using namespace std;

int main()
{
    float n,m,r,s,d,b;
    cout << "Digite dois numeros quaisquer: \n";
    cin >> n;
    cin >> m;
    s=n+m;
    d=n-m;
    r=n*m;
    b=n/m;
    
    cout << "O resultado da soma eh: \n " << n << endl;
    cout << "O resultado da diferenca eh: \n " << d << endl;
    cout << "O resultado da multiplicaC'C#o eh: \n " << r << endl;
    cout << "O resultado da divisC#o eh: \n " << b << endl;
    
    cout << endl;

    return 0;
}
