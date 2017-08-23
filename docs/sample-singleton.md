```java
public class ClassicSingleton {
    private static ClassicSingleton instance = null;
        
    public static ClassicSingleton getInstance() {
        if(instance == null) {
            instance = new ClassicSingleton();
        }
        return instance;
    }
}
```
