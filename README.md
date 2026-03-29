import java.io.IOException;
import java.util.Scanner;

public class Main {
public static void main(String[] args) {

    Scanner sc = new Scanner(System.in);
    while(true){//inicio do loop
     //nome das string
    System.out.println("usuario");
    String usuario = sc.nextLine();

    System.out.println("senhade");
 String senha = sc.nextLine();

 //variavel se estiver senha correta ou errada
        // loguin e senha de acesso

if(usuario.equals("admin") && senha.equals("1234")) {
    System.out.println("loguin realizado com sucesso");
    break;//sai do sistema
}else
    System.out.println("senha invalida");}
}



}
