#include <iostream>
#include <vector>
using namespace std;

int main()
{
    int n = 6;
    vector<int> myvec = { 1, 3, 4, 5, 33, 55, 66, 0 };

    for (vector<int>::iterator it = myvec.begin(); it != myvec.end(); )
    {
        if (*it < n)
        {
            it = myvec.erase(it); 
        }
        else
        {
            cout << *it << " ";
            ++it;
        }
    }
}
