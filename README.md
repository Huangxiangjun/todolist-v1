# todo-list

> todolist初级版本，采用vue单页面应用 + localStorage本地存储


## 功能：
>
>   1. 基础的 `添加`、`删除`、`选择`、`编辑` 功能
>   
>   2. 顶部显示 `全选` 或 `取消全选` 按钮，取决于list中事项的选中状态，双向作用
>
>   3. 事项被选择后意为完成该事项，此时不可进行编辑，显示完成样式
>
>   4. 自动生成添加事项的时间
>
>   5. `编辑` 或 `添加` 之后，事项内容若为空，则不计入
> 
>   6. 任一状态改变都会记录到一个 `todoList` 数组中，和 `localStorage` 本地存储完成信息存、取
> 
>   7. 首屏渲染会从本地存储中读取数据，首次打开不存在本地存储的时候，显示提示信息

## Project setup

### Download dependent packages
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### After Compiled
```
  App running at:
  - Local:   http://localhost:8080/
  - Network: http://10.133.171.125:8080/
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
