import java.util.*;
class Healthcare
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the name of Patient");
        String name=sc.nextLine();
        System.out.println("Name of Patient is" +name);
        System.out.println("Enter the location of patient\nChoice Nagpur,Bhandara,Bhopal,Gondiya,");
        String city=sc.nextLine();
        switch(city)
       {
           case "Nagpur":
               System.out.println("She is from Nagpur");
               break;
           case "Bhandara":
               System.out.println("She is from Bhandara");
               break;
            case "Bhopal":
                System.out.println("She is from Bhopal");
                break;
            case "Gondiya":
                System.out.println("She is from Gondiya");
                break;
                default:
            System.out.println("She is from mumbai");
    }   
        System.out.println("Enter the location of Hospital\nChoice Mumbai,Delhi,Chennai,Hydrabad");
        String hospital=sc.nextLine();
        switch(hospital)
       {
           case "Mumbai":
               System.out.println("hospital is in Mumbai");
               break;
           case "Delhi":
               System.out.println("hospital is in Delhi");
               break;
            case "Chennai":
                System.out.println("hospital is in Chennai");
                break;
            case "Hydrabad":
                System.out.println("Hospital is in Hydrabad");
                break;
                default:
            System.out.println("Hospital is in Nagpur");
       }
       System.out.println("Enter the name of hospital\nNagpur,Bhandara,Bhopal,Gondiya");
       String nhp=sc.nextLine();
       switch(nhp)
       {
           case "Nagpur":
               System.out.println("Meyo Hospital");
               break;
           case "Bhandara":
               System.out.println("Kukde Hospital");
               break;
            case "Bhopal":
                System.out.println("Neuron Hospital");
                break;
            case "Gondiya":
                System.out.println("Medical Hospital");
                break;
    }   
     System.out.println("Enter the Patient mobile number");
        String pphn=sc.nextLine();
    System.out.println("The mobile number of patient is  "+pphn );
        System.out.println("Enter the Hospitalphone no");
        String phn=sc.nextLine();
        switch(phn)
       {
           case "Nagpur":
               System.out.println("Phone no is 86554285");
               break;
           case "Bhandara":
               System.out.println("Phone no is 865542834");
               break;
            case "Bhopal":
                System.out.println("Phone no is 8655423434");
                break;
            case "Gondiya":
                System.out.println("Phone no is 865542675");
                break;
                default:
            System.out.println("Phone no is 865542443");
    }
    
        System.out.println("enter the age of patient");
    int age=sc.nextInt();
    if(age>=65)
    {
        System.out.println("U can use this medicine");
    }
    else
{
    System.out.println("u can't use this medicine");
    }
System.out.println("Enter the gender of patients\nChoice Male,Female");
      String gender=sc.nextLine();
        switch(gender)
        {
            case "Male":
           System.out.println("Gender is Male");
           break;
           case "Female":
               System.out.println("Gender is Female");
               break;
               default:
               System.out.println("Transgender");
        }
        
        System.out.println("Enter the name of disease\nChoice heart,brain,BP,general");
        String wdisease=sc.nextLine();
       switch(wdisease)
       {
           case "heart":
               System.out.println("U refer Aspirin medicine");
               break;
           case "brain":
               System.out.println("U  refer 1mg multivitaamin supreme medicine");
               break;
            case "BP":
                System.out.println("U refer Avapro medicine");
                break;
            case "general":
            System.out.println("u refer paracetimol medicine for fever");
                break;
                default:
            System.out.println("No medicine are avail");
    }   
   }
}
