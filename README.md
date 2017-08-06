# FastPojo
A java class to help to populate and initialize list from JSON or DataBase without the need of declaring Pojo modle, Because actually this is a pojo modle ready to use on the fly.


## Explanation
usually you make a modle class like this
```java 
public class Msg {
    private int id;
    private String name;
    private Double doub;
    private Boolean bool;

    public Msg(String id,.....,.........) {
        this.id = id;
        ........
    }

    public String getId() {
        return id;
    }
    ........

    public void setId(String id) {
        this.id = id;
    }
    ........

}
```
for each variable you define its type and make setter and getter voids and pass it in a Routine process and then you use it like this usually
```java 
//set
msg.setId(id);
msg.setName(name);
........
//get
msg.getId();
.........
```

BUT with FastPojo you dont need custom modle because it is a "WORCKAROUND?" that can define objects type and then set and get them appropriately you just set and get directly>
so:
## Usage
```java 
//set first vaariable
msg.set1(id);
msg.set2(name);
msg.set3(1.55);
msg.set4(true);
//get first variable where s is the type you should remember it s for string, i for int, d for double and b for boolean.
msg.get1i();//get id int
msg.get2s();//get string name
msg.get3d();//get double 1.55
msg.get4b();//get boolean true 
```
