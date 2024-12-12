([[signed]])short [[int]]: -32767 to 32767
short int와 int의 메모리는 같으나, 연산이 커지면 달라진다.
```c
CPU             short   int
8 bit           16      16
16 bit          16      16
32 bit          16      32
64 bit          16      32
```
