# Palindromos
Encontrar los palindromos en el rango de 23:59 hrs.



public class expe {

    public static void main(String[] args) {

        int hour = 0;
        int hour1 = 0;
        int min = 0;
        int min1 = 0;
        int porfavordameelnumerototaldeestoscositosllamadospalindromos = 0;

        for (hour = 0; hour <= 2; hour++) {
            for (hour1 = 0; hour1 <= 3; hour1++) {
                for (min = 0; min <= 5; min++) {
                    for (min1 = 0; min1 <= 9; min1++) {

                        if (hour == min1 && hour1 == min) {
                            System.out.println("Logre ver un palindromo: " + hour + hour1 + ":" + min + min1);
                            porfavordameelnumerototaldeestoscositosllamadospalindromos++;
                        }
                    }
                }
            }
        }
        System.out.println("En total hay : " + porfavordameelnumerototaldeestoscositosllamadospalindromos + " cositos raros llamados palindromos en 24 hrs");
    }
}
