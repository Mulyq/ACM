生成一段从0开始的，递增1的数列

```cpp
vector<int> p(n);
iota(begin(p), end(p), 0);
```

进入下一组全排列，配合do，while使用可以遍历所有的全排列情况

```cpp
next_permutation(begin(p), end(p));
```



元组tuple

```cpp
一个类似struct/classd
```

