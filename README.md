# Java_sucks_bigtime
Today I've decided to embrace stupidity when dealing with Java. This is me officially going nuts

```java
public static int booltoint(boolean nonsense) {
                // Let's start with indenting using spaces, 16 of them to be precise
                String[] ____int = new String[500];
                ____int[0] = Boolean.toString(nonsense);
                try {
                                Thread.sleep(100); 
                } catch (Exception e) {    }
                Random rand = new Random();
                int n = rand.nextInt((int)1e9);
                int result = 0;
                int other_Result = 1;
                for (int i = -5; i < 2; i++) {
                                try {
                                                if (n == 35467247) return 5; // let's just fail with one in a billion chance
                                                if ((5 - ____int[i].length()) == 1) {
                                                                return ++result;
                                                } else if(____int[i] == "false") {
                                                                return --other_Result;
                                                }
                                } catch (Exception e) {
                                                // This method will throw an exception 5 times every single time I 
                                                // cast a boolean to int before returning an integer
                                }
                }
                return (int)1e35;
}
```
