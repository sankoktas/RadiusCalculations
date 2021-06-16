# RadiusCalculations
This program asks for the radius value and then calculates the area and circumference of th circle. 

import java.util.Scanner;
public class KFS_RadiusCalculations_Main

{
    public static void main(String [] args)
    
    {
        Scanner in = new Scanner(System.in);
        System.out.print("Please enter the radius value: "); //user will plug in a number here
        double radius = in.nextDouble();
        
        double circumference = 2*Math.PI*radius; //user's radius will be converted to circumference
        System.out.println(circumference);
        
        double area = Math.PI*radius*radius; //user's radius will be converted to area
        System.out.println(area);
    }
    
}
