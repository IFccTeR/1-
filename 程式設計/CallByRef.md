---

    Public class Obj{
      int a,b;
      Obj(){
      a=10;
      b=15;
      }
    }
    public class CallByRef{
      public static void main(string{} args){
      Obj obj = new Obj();
      System.out.println
      byRef(obj)
      }

    static void byRef(Obj p){
      int t;
      t=p.a;
      p.a=p.b;
      p.b=t;
    }
    }
    
---

![fibint](https://user-images.githubusercontent.com/71476321/116519735-6ab2d400-a904-11eb-9ead-a98e233ae8eb.PNG)



