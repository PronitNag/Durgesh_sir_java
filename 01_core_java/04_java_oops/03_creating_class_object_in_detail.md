# class and Object

- class banaya jata haii **class** keyword se
- Object banaya jata haii **new** se

This is the main class

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello, World!");

        Pen p1 = new Pen();
        Pen p2 = new Pen();

        p1.model="Liko fiko";
        p2.model= "Renolds";

        p1.color = "black";
        p2.color = "blue";

        System.out.println(p1.model);
        System.out.println(p2.model);

        System.out.println(p1.color);
        System.out.println(p2.color);

        p1.write();
        p2.write();
    }
}
```

From this pen class we jika object bayana haii

```
class Pen{
    //properties/variable/[instance]/data members
    String color;
    double price;
    String model;



    //behaviour/methods/member methods
    public void write(){
        System.out.println(model + "  is writing in " + color +" Color  ");
    }
}
```

- Notice humlog main me Pen ka Object banaya haii **new Pen()** fir usko store kiya hai,Jab humne wo kiya to object bane heap me  
- fir refernce variable **p1,p2** se us heap object ko point kiya(ye refrence variable store hua stack me)
- fir humlogo me **.(dot operater)** ke through usme value dala,aur use ke through write method ko call kiyaa
- 
- 



