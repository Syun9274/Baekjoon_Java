# Java 11 information

- 언어 번호: 93
- 컴파일: `javac -release 11 -J-Xms1024m -J-Xmx1920m -J-Xss512m -encoding UTF-8 Main.java`
- 실행: `java -Xms1024m -Xmx1920m -Xss512m -Dfile.encoding=UTF-8 -XX:+UseSerialGC -DONLINE_JUDGE=1 -DBOJ=1 Main`
-  버전: openjdk version "16.0.1" 2021-04-20
- 시간 제한: ×2+1 초
- 메모리 제한: ×2+16 MB

```java
import java.util.*;

public class Main{

    public static void main(String args[]){
    
        Scanner sc = new Scanner(System.in);
        int a, b;
        a = sc.nextInt();
        b = sc.nextInt();
        System.out.println(a + b);
    }
}