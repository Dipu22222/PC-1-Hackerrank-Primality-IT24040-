# IT24040 (Dipu Mondol) 
## Java Primality Test  


![](https://raw.githubusercontent.com/Dipu22222/PC-1-Hackerrank-Primality-IT24040-/refs/heads/main/Java%20Primality%20Test/Screenshot%202026-10-31%20125708.png)  
```cpp
import java.io.*;
import java.math.BigInteger;

public class Solution {

    public static void main(String[] args) throws IOException {
        BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
        BigInteger n = new BigInteger(br.readLine().trim());

        if (n.isProbablePrime(100)) {
            System.out.println("prime");
        } else {
            System.out.println("not prime");
        }
    }
}
```
## Prime Checker  
![]()

