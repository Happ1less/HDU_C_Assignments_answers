# 字符串逆序

- 完成《C Primer Plus》前八章的阅读或其他方式的知识等价学习。

注：考虑空格，scanf无法读入空格，不要使用gets()!  

紫外线注：问了chatGPT为啥不能用gets()，答案如下
> `gets()` 函数也可以用于读取包含空格的整行输入，但它有一个重大缺陷：`gets()` 没有办法指定输入的最大长度，这会导致缓冲区溢出风险，使程序变得不安全。因此，`gets()` 函数在 C11 标准中被移除，不推荐使用。
>
> 如果你一定要使用 `gets()`，你需要确保输入不会超过缓冲区的大小。但为了安全，建议使用 `fgets()` 代替 `gets()`。  

不知道准不准用`fgets()`，就用了。