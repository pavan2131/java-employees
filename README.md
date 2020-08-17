# java-employees
Employees info
class Info
{
  String name;
  int year;
  String address;
}
class Main
 {
   public static void main(String args[])
   {
     Info obj1=new Info();
     obj1.name="Robert wallsStreet";
     obj1.year=1994;
     obj1.address="64C-";
     Info obj2=new Info();
     obj2.name="Sam wallsStreet";
     obj2.year=2000;
     obj2.address="68D-";
     Info obj3=new Info();
     obj3.name="John wallsStreet";
     obj3.year=1999;
     obj3.address="26B-";
     System.out.println("name                       year of joining      address ");
     System.out.println(obj1.name+"             "+obj1.year+"              "+obj1.address);
     System.out.println(obj2.name+"                "+obj2.year+"              "+obj2.address);
     System.out.println(obj3.name+"               "+obj3.year+"              "+obj3.address);
     }
   }
