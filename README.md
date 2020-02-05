# Number-Multiplier
import java.lang.Math;

public class Multiplier 
{
  public static void main(String[] args)
  {
    System.out.println("Numbers: Multiples of 2");
    int[] nums = new int[30];
    int base = -1;
    
    for (int i = 0; i< nums.length; i= i + 1)
    { 
     
      base++;
      nums[i] = i * 2;   
      System.out.println(base + ":" + nums[i] + "\n");     
    }
   
  }
}
