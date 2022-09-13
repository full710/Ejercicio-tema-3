public class Main {
    public static void main(String[] args) {
        //Ejercicio utilizando if
        System.out.println("If:");
        int numero = 5;
        if (numero == 0) {
            System.out.println("El numero es 0");
        }
        if (numero > 0) {
            System.out.println("El numero es positivo");
        }
        if (numero < 0) {
            System.out.println("El numero es negativo");
        }
        //Ejercicio utilizando bucle while
        System.out.println("While:");
        int numeroWhile = 0;
        while (numeroWhile < 3) {
            System.out.println(numeroWhile);
            numeroWhile++;
        }
        //Ejercicio utilizando bucle DoWhile
        System.out.println("Do While:");
        do {
            System.out.println(numeroWhile);
        } while (numeroWhile < 3);
        System.out.println("For:");
        //Ejercicio utilizando bucle For
        for (int numeroFor = 0; numeroFor <= 3; numeroFor++){
            System.out.println(numeroFor);
        }
        //Switch
        System.out.println("Switch:");
        var estacion = "Verano";
        switch (estacion){
            case "Verano":
                System.out.println("Estamos en Verano");
                break;
            case "Invierno":
                System.out.println("Estamos en Invierno");
                break;
            case "Otoño":
                System.out.println("Estamos en Otoño");
                break;
            case "Primavera":
                System.out.println("Estamos en Primavera");
                break;
            default:
                System.out.println("El valor de la variable no corresponde a una estacion");
        }

    }
}
