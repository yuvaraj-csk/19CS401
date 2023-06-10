# Exp-02 CLASS SCOPE & ACCESSING CLASS
### PROGRAM STATEMENT:
Demonstrate Reference variable( x=10 then use ref change as 20 then assign x as 30 and display the value using ref).
### PROGRAM:
```
#include<iostream>
using namespace std;
int main()
{
  int x =10;
  int& ref=x;
  ref =20;
  cout<<"x = "<<x<<endl;
  x=30;
  cout<<"ref = "<<ref;
}
```
### OUTPUT:
![image](https://github.com/yuvaraj-csk/19cs401/assets/134052574/54158a15-4980-42c2-94df-82a5178e2d29)
### RESULT:
Thus, the C++ program has been executed successfully.
