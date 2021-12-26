# pretty-name

Simple and consistent way how to get a type name in compile-time.

```cpp

struct Test {
	int a;
	int b;
};

std::cout << pretty_name::pretty_name<Test>() << std::endl;

```
