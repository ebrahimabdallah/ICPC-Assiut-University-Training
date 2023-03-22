```
#include<iostream>
#include <numeric>
#include<string>

using namespace std;

int main()
{
    int count;
    int min, i;
    cin >> count;
    int arr[count];

    for (int i = 0; i < count; i++) {
        cin >> arr[i];
    }
    
    for (int i = count-1 ;i >= 0; i--)
    {

        cout << arr[i] <<" ";
        
    }
}
```
