import java.util.Scanner;
/*
 * Mostrar todos los divisores del numero y decir si es primo o no.
 */
public class EjercicioAvanzado1 {

	public static void main(String[] args) {
		Scanner entrada=new Scanner(System.in);
		System.out.print("Ingrese un numero:");
		int numero=entrada.nextInt();
		int contador=1,divisores=0;
		while(numero>=contador) {
			if(numero%contador==0) {
				System.out.println(contador);
				divisores++;
			}	
			contador++;
		}
		if(divisores>2)
			System.out.print("no es primo");
		else
			System.out.print("es primo");
	}
}
