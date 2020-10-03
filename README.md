# Lista-1-Exercicio-2

import java.util.Scanner;

public class EX_2{
    public static void main(String[]args){
        Scanner in = new Scanner(System.in);
        double Soma,numero=0;

        System.out.print("Digite um numero:");
        numero = in.nextDouble();

        Soma = numero + 0.20;

        System.out.println("O valor de um numero atualizado é="+Soma);
    }
}
