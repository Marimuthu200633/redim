#include<iostream>
using namespace std;
int main()
{
    int L,B;
    cin >> L >> B;
    int perimeter = 2*(L+B);
    int area=L*B;
    cout<< area << " " << perimeter <<endl;
    return 0;
}
