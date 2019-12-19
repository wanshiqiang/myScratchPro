# myScratchPro

- 五子棋.sb2
  - 绘制棋谱
  - 下棋
    - 纠正棋的落点
  - 判断是否满5
    - [x] 水平交叉计数判断
    - [ ] 竖直交叉计数判断
    - [ ] 左倾斜交叉计数判断
    - [ ] 右倾斜交叉计数判断 
  - 清空满5棋子



```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```