---

    Public class CallByValue
    Public static void main(string[]args){
      int a = 10 b= 15;
      System.out.println("前\t"+a+"\t"+b)
      ByVal(a,b)
      System.out.println("後\t"+a+"\t"+b)
      }

     static void ByVal(int x, int y){
     int t ;
     t = x;
     x = y;
     y = t;
     System.out.println("中\t"+x+"\t"+y)

---
![fibint](https://user-images.githubusercontent.com/71476321/116518145-7a311d80-a902-11eb-9e2d-d8bf5821e671.PNG)

