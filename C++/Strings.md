[[C++]]
```cpp
#include <iostream>
#include <string>
using namespace std;

int main ()
{
   string mystring;
   mystring = "This is a string";
   cout << mystring;
   return 0;
}
```

이런 식으로 문자열을 출력

```cpp
string mystring;
mystring = "This is the initial string content";
cout << mystring << endl;
mystring = "This is a different string content";
cout << mystring << endl;
```

inserting the `endl` manipulator **end**s the **l**ine (printing a newline character and flushing the stream).

## [[char]] 과의 차이점
