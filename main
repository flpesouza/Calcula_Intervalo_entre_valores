import java.util.*; 

public class main { 
  public static int calculaIntervalo(int m, int n){ 
    if(m==n){
      return m; 
    }
    return calculaIntervalo(m+1,n)+m;
  } 

  public static void main(String[] args){ 
    Scanner sc = new Scanner(System.in);
    System.out.print("Digite o valor de m: ");
    int m = sc.nextInt();
    System.out.print("Digite o valor de n: ");
    int n = sc.nextInt(); 
    System.out.print("Resultado: "+calculaIntervalo(m, n));
    sc.close(); 
  } 
}
