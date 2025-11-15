import java.util.Scanner;

public class HotelBookingSystem {
  public static void main (String[] args) {
  Scanner input = new Scanner(System.in);

System.out.println ("-----------------------------------------------------------"); 
    System.out.println ("\t\t\tWelcome!"); 
    System.out.println ("\tWe offer comfortable rooms"); 
    System.out.println ("-----------------------------------------------------------"); 
    System.out.println (); 

    System.out.print("Please enter your name:"); 
    String guestName = input.nextLine(); 
    System.out.println ();  
    
    System.out.println("Hello," + guestName); 
    System.out.println("Let's begin with your booking process"); 
    System.out.println (); 
    
   
    // Room Description with prices
    System.out.println("Available Room Types"); 
    System.out.println(); 
    System.out.println("1 - Single room (P10,200/night)\n Ideal for 1 person"); 
    System.out.println("2 - Double room (P15,550/night)\n Ideal for 2 persons, 1 queen bed"); 
    System.out.println("3 - Twin room (P15,550/night)\n Ideal for 2 persons, 2 single bed"); 
    System.out.println("4 - Quad room (P18,300/night)\n For 4 guests, 2 queen bed"); 
    System.out.println("5 - Family room (P22,400/night)\n For 3-5 guests, 2 king bed"); 
    System.out.println("6 - Suite room (P33,600/night)\n For 4-6 guests, luxury amenities"); 

    System.out.print("Which room would you like to avail (1-6):");
        String roomChoice = input.nextLine(); 

    System.out.print ("You have selected" + roomChoice);


        // Amenities
        System.out.println("Available Amenities");
        System.out.println("------------ Meals ------------");
        System.out.println();
        System.out.println("1 - Buffet: Charges vary.");
        System.out.println("2 - Food Court: No charges applied.");

        System.out.println();
        System.out.print("Which Dining Option are you going to avail (1 or 2): ");
        String diningChoice = input.nextLine();

        // IF user chooses Buffet
        if (diningChoice.equals("1")) {
            System.out.println();
            System.out.println("------------ Buffet ------------");
            System.out.println();
            System.out.println("1 - Standard Buffet (Breakfast, Lunch, Dinner): PHP 3000");
            System.out.println("2 - Gourmet Buffet (Breakfast, Lunch, Dinner, Snacks): PHP 5000");
            System.out.println("3 - Luxury Buffet (Unlimited Food): PHP 8000");
            System.out.println();
            System.out.print("Which Buffet Plan are you going to avail (1-3): ");
            String buffetChoice = input.nextLine();
        } 
        
        // ELSE → user chose Food Court
        else {
            System.out.println();
            System.out.println("Available Amenities");
            System.out.println();
            System.out.println("------------ Spa ------------");
            System.out.println("1 - Facial: PHP 4000");
            System.out.println("2 - Full Body Massage: PHP 5000");
            System.out.println("3 - None");
            System.out.println();
            System.out.print("Which Spa Plan are you going to avail (1-3): ");
            String spaChoice = input.nextLine();
        }

        input.close();
    }
}








