```
npx ts-node hello-b.ts
```

没有类型提示：

![hello-a](./images/hello-b.jpg)

如果参数类型错误，编译不会报错，直接传给真正的JavaScript代码。结果是运行时可能报错，可能不报（JavaScript自己成功转换了类型）。

```
Hello, typescript (from b)
```

