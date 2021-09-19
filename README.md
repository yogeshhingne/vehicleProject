import java.util.*;
class Vehicle
{
void fun(String s)
{
if(s.equals("bike"))
{
System.out.println("Bike NoOfSeats 2  NoOfWheels 2");
}
if(s.equals("car"))
{
System.out.println("Car NoOfSeats 4  NoOfWheels 4");
}
}
}
class VehicleApp
{
public static void main(String args[])
{
System.out.println("enter the vehicle name");
Scanner sc=new Scanner(System.in);
String s1=sc.nextLine();
String s=s1.toLowerCase();
Vehicle Bike=new Vehicle();
Vehicle Car=new Vehicle();
if(s.equals("bike"))
{
Bike.fun(s);
}
if(s.equals("car"))
{
Car.fun(s);
}
}
}

