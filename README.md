TypeScript Sub Project Use Root Node Modules Demo
===========================

把所有的依赖安装于root，内部的sub project中可以直接引用到。

注意：

- `tsc`这样的命令不行

```
npm install
npm run demo
```

Note:

`esModuleInterop` is recommended to set to `true`,
since we can have consistent importing syntax with babel,
always use:

```
import some from 'some'
```

