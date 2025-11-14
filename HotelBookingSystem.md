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
    System.out.println("6 - Suite room (P33,600/night)\n For 6-10 guests, luxury amenities"); 

    System.out.print("Which room would you like to avail (1-6):");
        String roomChoice = input.nextLine(); 

    System.out.print ("You have selected" + roomChoice);










