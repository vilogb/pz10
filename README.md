# pz10

<img width="1138" height="393" alt="image" src="https://github.com/user-attachments/assets/818b5c3e-1dda-40e2-8dcf-251b85b73916" />


## Задание 1
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
    for( int i = 1; i <= N; i++ )
        cout<< i << " ";
    // Ваш код:


    return 0;
}
```

## Задание 2
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
        for( int i = N; i >= 1; i-- )
        cout<< i << " ";
    // Ваш код:


    return 0;
}
```


## Задание 3
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
    int x = 0;
      for( int i = 1; i <= N; i++ )
        x = i + x;
    // Ваш код:
    cout << x;

    return 0;
}
```


## Задание 4
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
    for( int i = 1; i <= N; i++ )
    if (i % 2 == 0)
        cout << i << " ";
    // Ваш код:


    return 0;
}
```


## Задание 5
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
    int x = 0;
    for( int i = 1; i <= N; i++ )
        if (i % 2 == 0)
            x++;
    // Ваш код:

    cout<< x;
    return 0;
}
```


## Задание 6
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
    int x = 1;
    for(int i = N; i >= 1; i--)
        x = x * i;
    // Ваш код:

    cout << x;
    return 0;
}
```


## Задание 7
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
    int x = 1;
    for(int i = 1; i<= 10; i++)
        cout << N << " * " << i << " = " << i*N << endl ;
    // Ваш код:


    return 0;
}
```


## Задание 8
```
#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
    for(int i = 0; i < N; i++) {
        for(int y = 0; y < N; y++) {
                cout << "*";
        }
        cout << endl; }
    // Ваш код:


    return 0;
}
```
