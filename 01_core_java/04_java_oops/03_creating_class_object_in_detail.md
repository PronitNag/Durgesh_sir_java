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

![object and class ](https://github.com/user-attachments/assets/79123859-431c-4520-b153-ed325052c5fa)

```text
ab in dono line ko comment out karo
tho value null ayega
kyuki string ka default value null haii
```

```java
        p1.model="Liko fiko";
        p2.model= "Renolds";
```

price ka 0.00 kyuki uska default value haii

```text
Notice variable ko directly use nai kar rahe haii
mai class ke thorugh value allocate aur
output me show bhi kar rahe haii
``` 


