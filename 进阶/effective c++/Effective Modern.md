# auto

```c++
int main()
{
    int x = 0;
    std::cout << &x << std::endl;
    auto y = x;
    std::cout << &y << std::endl;
    auto* z = &x;
    std::cout << z << std::endl;
    auto& w = x;
    std::cout << &w << std::endl;

}
/*输出结果
0x61ff04
0x61ff00
0x61ff04
0x61ff04
*/
```

原则：只有明确需要 copy 才使用 auto，其它需要 auto 的情况用 auto*, auto&







大括号初始化

可以避免 解析语法



并发API

基于线程的方式

基于任务的方式























