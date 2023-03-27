#include<iostream>
#include<math.h>
using namespace std;

int main()
{
    const double pi=3.14;
    double r;
    
    cout << "Enter the radius of sphere ";
    cin >> r;
    
    double surfaceArea = 4 * pi * r * r;
    double volume = (4/3) * pi * r * r * r;
    
    cout << "surfaceArea " << surfaceArea << endl;
    cout << "volume " << volume << endl;
    
    return 0;
    
}
