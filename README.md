import java.util.Scanner;
public class Swap1 {
public static void main(String args[]) {
System.out.println(&quot;Before swapping&quot;);
int x = 10;
int y = 20;
System.out.println(&quot;value of x:&quot; + x);
System.out.println(&quot;value of y:&quot; + y);
System.out.println(&quot;After swapping&quot;);
x = x + y;
y = x - y;
x = x - y;
System.out.println(&quot;value of x:&quot; + x);
System.out.println(&quot;value of y:&quot; + y);
}
}
