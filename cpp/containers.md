## C++ Container Cheat Sheet

### Vector
##### Initialization
* `vector<int> v; v.push_back(1); v.push_back(3); v.push_back(44);`
* `// C++11 `
* `auto va = vector<int>(); // empty vector`
* `auto vb = vector<int>(10); // capacity = 10, elements were set to defualt value of int (0)`
* `vector<string> vs = {"This", "is", "a", "string"};`

#### Access
* random access
```C++
auto va = vector<int>{1,2,3,4,5};
cout<<va[4]<<va<<[0]<<va[2]<<va[1]<<va[3]<<endl; // 51324
```
* sequencial access
```C++
vector<int> a = {1,2,3,4,5};
for(vector<int>::iterator it = a.begin(); it != a.end(); ++it)
  cout<<*it<<endl;
// C++ 11 feature
for(auto v : a)
  cout<<v<<endl;
// both output
// 1
// 2
// 3
// 4
// 5
```

* insertion
```C++
vector<int> a = {1,3,5};
// add back
a.push_back(7); // a = {1,3,5,7}
```

