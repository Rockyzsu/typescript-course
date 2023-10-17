# typescript 基础



## 介绍

javascript的超集, Javascript支持的, typescript也支持

无法直接在浏览器运行, 需要编译成Javascript



## 安装

```javascript
npm install -g typescript
```



测试

```
tsc -v
```



编译

define.ts 文件

```typescript
let number:number = 10;
console.log(number);
```

编译命令:

```
tsc define.ts
```

生成一个define.js 文件

可以直接用node.js运行

node define.js



#### 配置环境

tsc –init

自动生成 tsconfig

