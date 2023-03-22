```
#include<iostream>
#include <numeric>
#include<string>

using namespace std;

int main()
{
    int i, num;
    long long count;
    cin >> count;
     int arr[count]
    for (i = 0; i < count; i++) {
        cin >> arr[i];
    }
    cin >> num;


    for (i = 0; i < count; i++) {
        if (arr[i] == num) {
            cout << i;
            return 0;
        }
    }
    
    cout << -1 << endl;
    return 0;
}
```
