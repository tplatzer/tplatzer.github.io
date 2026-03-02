# This is a Contact Site

```Java
import java.util.Random;

public class ZufallsGenerator {
    public static void main(String[] args) {
        Random random = new Random();

        // Zufallszahl zwischen 0 (inklusive) und 100 (exklusive)
        int zufallsZahl = random.nextInt(100);
        
        // Zufälliger Boolean (true oder false)
        boolean zufallsBool = random.nextBoolean();

        System.out.println("Zufällige Zahl: " + zufallsZahl);
        System.out.println("Zufälliger Boolean: " + zufallsBool);
    }
}
```
