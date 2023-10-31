# 23B
# **C110118223 龔倢**
## *C110118223 龔倢*
### ~~C110118223 龔倢~~
#### C110118223 龔倢
##### C110118223 龔倢

😸💌

----
![NKUST](logo.png "NKUST")

- [ ] check list
- [x] 1st thing
- [ ] 2nd thing
- [ ] 3rd thing
- [ ] 4th thing

```python 
s = "python highlighted syntex"
print(s)
```
```js
var s = "Javascript highlights"
alert(s)
```
| Name | Height | Weight |
| :----|:------:| ------:|
|kemy  |  166   |   55   |
|Anna  |  161   |   48   |
|Ricky |  170   |   88   |
***
>SNSD
>>TAEYEON

>>SUNNY

>>TIFFANY

>>HYOYEON

>>YURI

>>SOOYOUNG

>>YOONA

>>SEOHYUN

>SHINee
>>JongHyun

>>Minho

>>Key

>>Taemin

>>Onew
***
[JS MOTOR STORE](https://www.instagram.com/js_motor_store/)

### ZUVIO HOMEWORK
## 請新增一個CShape的子類別CTriangle，其constructor 共有三個double的參數 a,b,c (為直角三角形的三個邊長)，其面積為0.5*a*b，請寫出CTriangle的類別程式與產生其物件的main 程式(顏色為紅色，a=3, b=4, c=5) 程式碼請放在個人的github 答案請列出其連結
## CShape.java        
abstract class CShape{
    protected String color;
    public void setColor(String str){
        color = str;
    }


    public abstract void show();
}
## CTriangle.java
class CTriangle extends CShape{
    double ca, cb, cc;
    public CTriangle(double a, double b, double c){
        ca=a;
        cb=b;
        cc=c;
    }
   
    public void show() {
       
        System.out.print("color="+color+"  ");
        System.out.print("area="+0.5*ca*cb);
    }
   
}
## app11.java
public class app11 {
   public static void main(String[] args) {
    CTriangle ct = new CTriangle(3, 4, 5);
    ct.setColor("red");
    ct.show();
}
}

