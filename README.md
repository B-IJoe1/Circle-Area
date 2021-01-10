# Circle-Area

    package lab02;

    public class ExFinal {


	public static void main(String[] args) {

		Ex_Q1 A1=new Ex_Q1();
		A1.UsrInput();
	    }

    }

//////////////////////////////////////


    public static void UsrInput()
    {
	  Scanner input = new Scanner(System.in);
	  System.out.println("Enter in radius");
	  double radius = input.nextDouble();
	  final double pi= 3.145;
	
    CircleArea(radius, pi);
	
    }

    public static void CircleArea(double radius, double pi)
    {
    
	  double Area;
	  
	  Area = pi*(radius*radius);
	
	  System.out.print("This is the: " + Area);

      }
    }
