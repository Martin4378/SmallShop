# SmallShop
import java.util.Scanner;

public class P11_SmallShop {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        String product = scanner.nextLine();
        String town = scanner.nextLine();
        double ammount = Double.parseDouble(scanner.nextLine());

        double coffeeSofia = 0.50;
        double waterSofia = 0.80;
        double beerSofia = 1.20;
        double sweetsSofia = 1.45;
        double peanutsSofia = 1.60;

        double coffeePlovdiv = 0.40;
        double waterPlovdiv = 0.70;
        double beerPlovdiv = 1.15;
        double sweetsPlovdiv = 1.30;
        double peanutsPlovdiv = 1.50;

        double coffeeVarna = 0.45;
        double waterVarna = 0.70;
        double beerVarna = 1.10;
        double sweetsVarna = 1.35;
        double peanutsVarna = 1.55;

        if (town.equalsIgnoreCase("sofia")) {
            if (product.equalsIgnoreCase("coffee")) {
                System.out.println(coffeeSofia * ammount);
            } else if (product.equalsIgnoreCase("water")) {
                System.out.println(waterSofia * ammount);
            } else if (product.equalsIgnoreCase("beer")) {
                System.out.println(beerSofia * ammount);
            } else if (product.equalsIgnoreCase("sweets")) {
                System.out.println(sweetsSofia * ammount);
            } else if (product.equalsIgnoreCase("peanuts")) {
                System.out.println(peanutsSofia * ammount);
            }
        } else if (town.equalsIgnoreCase("plovdiv")) {
            if (product.equalsIgnoreCase("coffee")) {
                System.out.println(coffeePlovdiv * ammount);
            } else if (product.equalsIgnoreCase("water")) {
                System.out.println(waterPlovdiv * ammount);
            } else if (product.equalsIgnoreCase("beer")) {
                System.out.println(beerPlovdiv * ammount);
            } else if (product.equalsIgnoreCase("sweets")) {
                System.out.println(sweetsPlovdiv * ammount);
            } else if (product.equalsIgnoreCase("peanuts")) {
                System.out.println(peanutsPlovdiv * ammount);
            }
        } else if (town.equalsIgnoreCase("varna")) {
            if (product.equalsIgnoreCase("coffee")) {
                System.out.println(coffeeVarna * ammount);
            } else if (product.equalsIgnoreCase("water")) {
                System.out.println(waterVarna * ammount);
            } else if (product.equalsIgnoreCase("beer")) {
                System.out.println(beerVarna * ammount);
            } else if (product.equalsIgnoreCase("sweets")) {
                System.out.println(sweetsVarna * ammount);
            } else if (product.equalsIgnoreCase("peanuts")) {
                System.out.println(peanutsVarna * ammount);
            }
        }

    }
}
