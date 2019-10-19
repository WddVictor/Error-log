# log

- ### Warning of using auto in cpp

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



- ### The wild pointer.

  When we initialize a struct, we **must** initialize all its members!!!!!!!!!!!!!!!!!!!!!



- ### [Could not resolve all dependencies for configuration ':classpath'](https://stackoverflow.com/questions/25994163/could-not-resolve-all-dependencies-for-configuration-classpath) in Android Studio

  It might because of the global gradle proxy setting. The global configuration file is in ~/.gradle/gradle.properties. 

  See more in [Global gradle proxy settings?](https://stackoverflow.com/questions/26523804/global-gradle-proxy-settings)

  

- 



