# TypeScript 基础类型

1. any 任意类型

2. string 字符串类型


3. boolean bool类型


4. 数组类型
   1. 元素类型后面加[] let arr:number[] = [1,2]
   2. 数组泛型 let arr: Array<number> = [1,2]


5. 元祖 用来表示已知数量和类型的数组，各元素的类型不必相同，对应位置的类型需要相同


```js
let x: [string, number];
x = ['leo', 1];
```

6. enum 枚举类型

```js
enum Color {Red, Green, Blue};
let c: Color = Color.Blue;
console.log(c);    // 输出 2
```

7. void 标识为空的返回值类型

```js
function hello(): void {
    alert("Hello Runoob");
}
```

8. null

9. undefined

10. nerver 其他类型（包括 null 和 undefined）的子类型，代表从不会出现的类型，通常表现为抛出异常或无法执行到终止点（例如无限循环）


# TypeScript 变量声明

var[变量名] : [类型] = value;


# 接口

接口不能转换为 JavaScript。 它只是 TypeScript 的一部分。

# 命名空间
