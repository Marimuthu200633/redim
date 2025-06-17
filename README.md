#include<iostream>
using namespace std;
int main()
{
    int L,B;
    cout<<"Enter the length:";
    cin >> L;
    cout<<"Enter the birth:";
    cin >> B;
    int perimeter = 2*(L+B);
    int area=L*B;
    cout<< area << " " << perimeter <<endl;
    return 0;
}
