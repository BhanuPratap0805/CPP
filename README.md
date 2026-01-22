# CPP
## OUTPUT QUESTIONS 
What will be the output of these questions

1. CODE:
```cpp
int x = 5;
int *p = &x;
*p = 10;
cout << x;
```
OUTPUT:
```
10
```

2. CODE:
```cpp
int a = 1, b = 2;
int *p = &a;
p = &b;
*p = 5;
cout << a << " " << b;
```
OUTPUT:
```
1 5
```

3. CODE:
```cpp
int x = 10;
int *p = &x;
int **pp = &p;
**pp = 20;
cout << x;
```
OUTPUT:
```
20
```

4. CODE:
```cpp
int a[5] = {2,4,6,8,10};
int *p = a;
cout << *p++ << " ";
cout << *p;
```
OUTPUT:
```
2 4
```

5. CODE:
```cpp
int a[] = {1,2,3,4,5};
int *p = a;
cout << *p++ << " ";
cout << (*p)++ << " ";
cout << ++*p << " ";
cout << *p << "\n";
for(int i=0;i<5;i++) cout << a[i] << " ";
```
OUTPUT:
```
1 2 4 4
1 4 3 4 5 
```

6. CODE:
```cpp
int x=10;
int *p=&x;
cout << (*p)++ << " " << x << "\n";
cout << ++(*p) << " " << x << "\n";
cout << *p++ << " " << x << "\n";
```
OUTPUT:
```
10 11
12 12
12 12
```
7. CODE:
```cpp
int a[] = {10,20,30,40,50};
int *p = a + 1;
cout << *(p+2) << " " << *(p-1) << "\n";
```
OUTPUT:
```
40 10
```
   
