# log

### 1. Warning of using auto in cpp

```shell
   input.cpp:69:5: warning: 'auto' type specifier is a C++11 extension
      [-Wc++11-extensions]
    auto iter = str.begin();
    ^
		1 warning generated.
```



Solution

Use `-std=c++11`.

```shell
g++ input.cpp -o input -std=c++11
```



### 2. The wild pointer.

When we initialize a struct, we **must** initialize all its members!!!!!!!!!!!!!!!!!!!!!

