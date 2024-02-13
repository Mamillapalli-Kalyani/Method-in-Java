# Method-in-Java
import java.util.*;

public class Main {
    public static void main(String[] args) {
      String c=add(19,28,89);
      System.out.println(c);
  }
  public static String add (int num1,int num2)
  {
    int Result=num1+num2;
    return("Result is:"+(num1+num2));
  }
  public static String add(int num1,int num2,int num3)
  {
    int Result=num1+num2+num3;
    return("Result is:"+(num1+num2+num3));
  }
  public static float add(float num1,float num2)
  {
    return num1+num2;
  }
}
