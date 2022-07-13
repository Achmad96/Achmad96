<!-- START -->
```java
    public class Main {
        public static void main(String[] args){
            printf("Hello %s", getName());
        }
        
        public static void printf(String s, ...Object) {
            System.out.printf(s, Object);
        }
    
        public static String getName() {
            return "Ahmad";
        }
    }
```        
<!-- END -->
