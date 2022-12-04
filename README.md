# RPC-
import java.util.Scanner;

public class RPC {

    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        String input =scanner.nextLine();

        while (true){

            if ("Scissors".equals(input)){


                input = scanner.nextLine();


                if ("Scissors".equals(input)){
                    System.out.println("Draw");
                    break;
                }


                if ("Paper".equals(input)){
                    System.out.println("You win!");
                    break;
                }else if ("Rock".equals(input)){
                    System.out.println("You lost!");
                    break;
                }else {
                    System.out.println("Type Rock , Paper or Scissors");
                   break;
                }

            }

            if ("Paper".equals(input)){


                input =scanner.nextLine();

                if ("Paper".equals(input)){
                    System.out.println("Draw");
                    break;
                }

                if ("Scissors".equals(input)){
                    System.out.println("You lost!");
                    break;
                }else if ("Rock".equals(input)){
                    System.out.println("You won!");
                    break;
                }else {
                    System.out.println("Type Rock , Paper or Scissors");
                    break;
                }
            }
            if ("Rock".equals(input)){

                input = scanner.nextLine();
                if ("Rock".equals(input)){
                    System.out.println("Draw");
                    break;
                }

                if ("Scissors".equals(input)){
                    System.out.println("You won!");
                    break;
                } else if ("Paper".equals(input)) {
                    System.out.println("You lost!");
                }else {
                    System.out.println("Type Rock , Paper or Scissors");
                    break;
                }
            }

            if (!"Scissors".equals(input) || !"Paper".equals(input) || !"Rock".equals(input)){
                System.out.println("Type Rock , Paper or Scissors");
                input = scanner.nextLine();
                continue;
            }
            }

        }
    }

