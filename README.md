####  flex布局盒子

- flex实现骰子是一个联系flex布局的好的素材



####  第一种


```js
.second-face {
    display: flex;
    justify-content: space-between;
}
```

#### 第二种



```js
.second-face {
    display: flex;
    justify-content: space-between;
}
/*将第二个点固定到盒子的下方*/
.second-face span:nth-child(2){
    align-self: flex-end;
}
```

#### 第三种



```js
.third-face {
    display: flex;
    justify-content: space-between;
}
.third-face span:nth-child(2){
    align-self: center;
}
.third-face span:nth-child(3){
    align-self: flex-end;
}
```



####  第四种



```js
.fourth-face{
    display: flex;
    justify-content: space-between;
}
.fourth-face .column:nth-child(1){
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.fourth-face .column:nth-child(2){
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
```

#### 第五种



```js

.fifth-face {
    display: flex;
    justify-content: space-between;
}
.fifth-face .column:nth-child(1){
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.fifth-face .column:nth-child(2){
    display: flex;
    flex-direction: column;
    justify-content: center;
}
.fifth-face .column:nth-child(3){
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
```

#### 第六种



```js
.sixth-face {
    display: flex;
    justify-content: space-between;
}
.sixth-face .column:nth-child(1){
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.sixth-face .column:nth-child(2){
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
```

