# Button 按钮
常用操作按钮

## 基础用法

基础的函数用法

:::demo 使用`size`、`color`、`pain`、`round`属性来定义 Button 的样式。

```vue
<template>
 <p>这是一个自动变更测试</p>
 <div style="margin-bottom:20px;">
  <XButton color="blue">主要按钮</XButton>
  <XButton color="green">绿色按钮</XButton>
  <XButton color="gray">灰色按钮</XButton>
  <XButton color="yellow">黄色按钮</XButton>
  <XButton color="red">红色按钮</XButton>
 </div>
 <div style="margin-bottom:20px;"
 >
  <XButton color="blue" plain>朴素按钮</XButton>
  <XButton color="green" plain>绿色按钮</XButton>
  <XButton color="gray" plain>灰色按钮</XButton>
  <XButton color="yellow" plain>黄色按钮</XButton>
  <XButton color="red" plain>红色按钮</XButton>
 </div>
 <div style="margin-bottom:20px;">
  <XButton size="small" plain>小按钮</XButton>
  <XButton size="medium" plain>中按钮</XButton>
  <XButton size="large" plain>大按钮</XButton>
 </div>
 <div style="margin-bottom:20px;">
  <XButton color="blue" round plain icon="search">搜索按钮</XButton>
  <XButton color="green" round plain icon="edit">编辑按钮</XButton>
  <XButton color="gray" round plain icon="check">成功按钮</XButton>
  <XButton color="yellow" round plain icon="message">提示按钮</XButton>
  <XButton color="red" round plain icon="delete">删除按钮</XButton>
 </div>
 <div style="margin-bottom:20px;">
  <XButton color="blue" round plain icon="search"></XButton>
  <XButton color="green" round plain icon="edit"></XButton>
  <XButton color="gray" round plain icon="check"></XButton>
  <XButton color="yellow" round plain icon="message"></XButton>
  <XButton color="red" round plain icon="delete"></XButton>
 </div>
</template>
```
:::

## 图标按钮

带图标的按钮可增强辨识度（有文字）或节省空间（无文字）。

:::demo 设置 icon 属性即可，icon 的列表可以参考 Element 的 icon 组件，也可以设置在文字右边的 icon ，只要使用 i 标签即可，可以使用自定义图标。

```vue
<template>
 <div class="flex flex-row">
  <XButton icon="edit" plain></XButton>
  <XButton icon="delete" plain></XButton>
  <XButton icon="share" plain></XButton>
  <XButton round plain icon="search">搜索</XButton>
 </div>
</template>
```
