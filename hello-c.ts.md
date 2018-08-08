```
npx ts-node hello-c.ts
```

在编辑器中看起来一切正常，还有类型提示。

![hello-c](./images/hello-c.jpg)

但是运行时，会提示找不到`./modules/c`，因为没有提供真正运行的js文件：

```
Cannot find module './modules/c'
```

