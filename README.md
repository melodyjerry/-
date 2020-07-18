# 贪吃蛇小游戏-C语言版本

大一时学C语言，在同学的帮助下完成了C语言版的贪吃蛇。

## 方法定义
```c
void welcome();               //55开始界面
void Finish();                //291结束界面
void creatgraph();            //69围墙打印
void gotoxy(int x, int y);    //111光标跳转，横为X 0,1,2..
void gotoprint(int x, int y); //121跳转打印
void gotodelete(int x, int y);//127跳转删除
void creatfood();             //133食物产生
int ClickControl();           //157获取键盘信号
int Judge();                  //270游戏结束判断
void MovingBody(); 	    	  //172蛇的移动 
void Eating();                //223蛇吃到东西后的操作（伸长）
void ChangeBody(int a,int b); //245蛇的坐标变换,后一个复制前一个STRUCT,a,b为head之前坐标 
```
## 运行截图
![Ug1DSA.png](https://s1.ax1x.com/2020/07/18/Ug1DSA.png)
![Ug1fYQ.png](https://s1.ax1x.com/2020/07/18/Ug1fYQ.png)
