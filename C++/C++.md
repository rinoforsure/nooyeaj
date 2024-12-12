	CPP를 배워보자
	그냥 이 시간을 날리는 것보다는 좋을꺼야  

# base form
``` C++
/*hell yeah*/
include <iostream>

int main ()
{
	std::cout << "Hello World"; //"<<" is intertion operater
}
```

[[cout]]
[[std]]
```C++
//we can comment even like this!
include <iostream>
using namespacd std;

int main ()
{
	cout << "Hello World";
}
```

# Variables and Types
## Variables
[[alignas]], [[alignof]], [[and]], [[and_eq]], [[asm]], [[auto]], [[bitand]], [[bitor]], [[bool]], [[break]], [[case]], [[catch]], [[char]], [[char16_t]], [[char32_t]], [[class]], [[compl]], [[const]], [[constexpr]], [[const_cast]], [[continue]], [[decltype]], [[default]], [[delete]], [[do]], [[double]], [[dynamic_cast]], [[else]], [[enum]], [[explicit]], [[export]], [[extern]], [[false]], [[float]], [[for]], [[friend]], [[goto]], [[if]], [[inline]], [[int]], [[long]], [[mutable]], [[namespace]], [[new]], [[noexcept]], [[not]], [[not_eq]], [[nullptr]], [[operator]], [[or]], [[or_eq]], [[private]], [[protected]], [[public]], [[register]], [[reinterpret_cast]], [[return]], [[short]], [[signed]], [[sizeof]], [[static]], [[static_assert]], [[static_cast]], [[struct]], [[switch]], [[template]], [[this]], [[thread_local]], [[throw]], [[true]], [[try]], [[typedef]], [[typeid]], [[typename]], [[union]], [[unsigned]], [[using]], [[virtual]], [[void]], [[volatile]], [[wchar_t]], [[while]], [[xor]], [[xor_eq]]

## Types
[[character type]]: char, char_16t, char_32t, wchar_t
[[integer type(signed)]]: signed char, signed short int, signed int, signed long int, signed long long int
[[integer type(unsigned)]]: [[unsigned]] "
[[floating point type]]: float double long double
[[boolean type]]: bool
[[void type]]: void
[[null pointer]]: decltype(nullptr)

8-bit = 256 = 2⁸
16-bit = 65536 = 2¹⁶
32-bit = 4294967296 = 2³²
64-bit = 18446744073709551616 = 2⁶⁴


```C++
// operating with variables

#include <iostream>
using namespace std;

int main ()
{
  // declaring variables:
  int a, b;
  int result;

  // process:
  a = 5;
  b = 2;
  a = a + 1; //기존의 a값에 1을 더함
  result = a - b;

  // print out the result:
  cout << result;

  // terminate the program:
  return 0;
}
```

참고로 이런거 가능

```C++
int x = 0;
int y (0);
int z {0};
```

