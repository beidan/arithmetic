# arithmetic
## **JavaScript算法题目总结**

> **给定字符串 str，检查其是否符合如下格式 1、XXX-XXX-XXXX 2、其中 X 为 Number 类型**

```
function matchesPattern(str) {
    var reg = /^\d{3}[-]\d{3}[-]\d{4}$/;
    return reg.test(str);
}
matchesPattern('800-555-1202');
```
