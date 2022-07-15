# Hava-S-cakl-na-G-re-Etkinlik-nerme
## Koşullar :
* Sıcaklık 5'dan küçük ise "Kayak" yapmayı öner.
- Sıcaklık 5 ve 15 arasında ise "Sinema" etkinliğini öner.
- Sıcaklık 15 ve 25 arasında ise "Piknik" etkinliğini öner.
- Sıcaklık 25'ten büyük ise "Yüzme" etkinliğini öner.




      import java.util.Scanner;

      public class Main {

       public static void main(String[] args) {
        int heat;

        Scanner inp = new Scanner(System.in);

        System.out.print("Sıcaklık Gririniz :");
        heat = inp.nextInt();

        if (heat < 5) {
            System.out.println("Kayak Yapabilirsiniz");
        } else if (  heat <= 25) {
            if (heat<=15){
                System.out.println("Sinemaya Gidebilirsiniz.");

            } if (heat>10){
                System.out.println("Pikniğe Gidebilirsiniz");

            }
        } else if (heat>25) {
            System.out.println("Yüzmeye Gidelirsiniz.");

        }
      }
      }

![image](https://user-images.githubusercontent.com/107626332/179190078-fa71a0e8-a6c6-4150-9280-0f45088e2b88.png)
