<h1>字符串方法_substr()</h1>

![Alt text](image.png)

substr方法用于从原字符串取出子字符串并返回，不改变原字符串，跟substring方法的作用相同
substr方法的第一个参数时子字符串的开始位置（从0开始计算），第二个参数是子字符串的长度

![Alt text](image-1.png)

如果省略第二个参数，则表示字符串一直到原字符串的结束

![Alt text](image-2.png)

如果第一个参数是负数，表示倒数计算的字符位置。如果第二个参数是负数，将被自动转为0，因此会返回空字符串

![Alt text](image-3.png)