

# Exp-04 MEMBER FUNCTION
### PROGRAM STATEMENT:
Write a C++ program to convert Celsius into Fahrenheit using inline function.
### PROGRAM:
```
#include <iostream>
using namespace std;
inline int conv(int c)
{
    int faren;
    faren=c*(1.8)+32;
    return (faren);
}
int main()
{
    int c;
    cin>>c;
    cout<<"temperature in Fahrenheit:"<<conv(c);
}

```
### OUTPUT:

![Uploading image.png…]()

### RESULT:
Thus, the C++ program has been executed successfully.
