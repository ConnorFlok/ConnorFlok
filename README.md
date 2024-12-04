import java.util.Scanner;

public class FavoriteFood {
    public static void main(String[] args) {
        // Create a Scanner object for user input
        Scanner scanner = new Scanner(System.in);

        System.out.println("What is your favorite food?");
       
        String favoriteFood = scanner.nextLine();
        
        if (favoriteFood.equalsIgnoreCase("tacos")) {
            System.out.println("Tacos are amazing! Great choice!");
        } else {
            System.out.println(favoriteFood + " sounds delicious too!");
        }
        
        scanner.close();
    }
}
