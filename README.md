#include <iostream>
using namespace std;
int main()
{
    float kilometers;
    cout << "Enter the number of kilometers traveled: " ;
    cin >> kilometers ;

    if (kilometers <= 3.5)

        {
        cout << "The charge for your fare is GHc 15.00 \n";
        cout << "Thank You \n";
        }

else if (kilometers > 3.5)

        {
        float Kilometers;
        Kilometers = ((kilometers - 3.5) * 4.5) + 15;
        cout << "The charge for your fare is GHc " << Kilometers ;
        }

    return 0;
}


