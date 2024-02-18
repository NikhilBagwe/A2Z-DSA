## Started on : 18/02/2024

## Basic skeleton :

```cpp
#include <iostream>

using namespace std;

int main()
{
    cout<<"Hello World!"<<endl;
    cout<<"DSA!"<<"\n";
    cout<<"Practice";
    
    return 0;
}
```

## Basic Input / Output :

```cpp
#include <iostream>

using namespace std;

int main()
{
    int x, y;
    cin >> x >> y;
    cout << "x + y : " << x + y;
    
    return 0;
}
```

## Data types :

1. int
2. long
3. long long
4. float
5. double
6. string
7. char - can store all 256 characters present in English dictionary

## Taking a String input using getline() :

```cpp
#include <bits/stdc++.h>

using namespace std;

int main()
{
    string s;
    // getline - takes the entire string as a whole sentence as input.
    getline(cin, s);
    
    cout<<s;
    
    return 0;
}
```

## Switch statement :

```cpp
int main()
{
    int day;
    cin >> day;
    
    switch(day){
        case 1:
            cout<<"Monday";
            break;
        case 2:
            cout<<"Tuesday";
            break;
        case 3:
            cout<<"Wednesday";
            break;
        case 4:
            cout<<"Thursday";
            break;
        default :
            cout<<"Invalid number";
            break; // If this break is not written, below o/p statement is also executed.
            
        cout<<"Check";
    }
    
    return 0;
}
```

## Arrays :

- In CPU memory, the contents of array are stored consecutively next to each other starting from arr[0].

```cpp
int main()
{
    int arr[5];
    cin >> arr[0] >> arr[1] >> arr[2] >> arr[3] >> arr[4];
    
    cout << arr[2];
    
    // 2D array
    int arrr[3][5]  // arr[row][column]
    
    return 0;
}
```
