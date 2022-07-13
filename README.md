<!-- START -->
```java
    public class Main {
        public static void main(String[] args){
            printf("Hello %s", getName());
        }
        
        public static void printf(String s, Object... o) {
            System.out.printf(s, o);
        }
    
        public static String getName() {
            return "Ahmad";
        }
    }
```        
<!-- END -->
