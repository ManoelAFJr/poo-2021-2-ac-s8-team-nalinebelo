1)Escreva um modelo para representar uma lâmpada que está à venda em
um supermercado. Que dados devem ser representados por esse modelo?

-Voltagem
-Marca
-Modelo
-Consumo
-Potência

2)Crie um modelo para representar um time de um esporte qualquer em um
campeonato desse esporte. Que dados e operações esse modelo deve ter?

-Número de jogadores
-Número de vitorias
-Número de derrotas
-Técnico
-Títulos conquistados

3)class Main mostraDados() {
  public class void mostraDados(){
      System.out.print("O nome do correntista é: ");
      System.out.print(nomeCorrentista);

      if (contaEspecial) {
        System.out.print("A conta é especial");

        if (saldo < 0) {
          System.out.print("O seu saldo é negativo!");
        } else {
          System.out.print("Seu saldo é: ");
          System.out.print(saldo);
        }

      } else {
        System.out.print("A conta é comum");
        System.out.print("O seu saldo é: ");
        System.out.print(saldo);
      }
    }
}

4)public static void main(String[] args){
private int voltagem = 110;
private int potencia = 10;
	public void mostraEstado(){
	  if(estado){
	   system.out.print("A lâmpada esta acesa.")
	  }else{
	   system.out.print("A lâmpada esta apagada.")
	  }
	}	
	public void ligar(){
	 estado = true
	}
	public void desligar(){
	 estado = false
	}
	public void mostraVoltagem(){
	 system.out.printf("A voltagem é: ")
	 system.out.printf(voltagem)
	}
	public void mostraPotencia(){
	 system.out.printf("A potencia é: ")
	 system.out.printf(potencia)
	}
}
}

5)public class time{

public static void main(String[] args){

private string[] jogadores = {"João", "Pedro", "Matheus", "Maria", "Ana"};
private string tecnico = "Edimar";
private int vitorias = 0;
private int derrotas = 0;
private int vitoriasEmSerie = 0;

public void venceu(){
 vitorias++;
 vitoriasEmSerie++;
}	
public void perdeu(){
  derrotas++;
  vitoriasEmSerie=0;
}

  }
}

6) Modifique o método “abreContaSimples” da classe “ContaBancariaSim-
plificada” de forma que o cliente só possa abrir uma conta com um valor
mínimo de R$ 100,00.

Para que a instancia seja executada basta igualar a condição, que seria:
    if (saldo >= 100){}

7) Identifique e explique o(s) erro(s) na classe abaixo:
1 class Registro De Eleitor
2 {
3 /**
4 * Declaração dos campos desta classe
5 */
6 int tituloDeEleitor; // número do título do eleitor
7 String nome; // nome do eleitor
8 short zonaEleitoral; // número da zona eleitoral
9 } // fim da classe

*ERRO= EXISTE UM ESPAÇO NO NOME DA CLASSE* 

8)Identifique e explique o(s) erro(s) na classe abaixo:
1 class Teste2
2 {
3 /**
4 * Declaração dos campos desta classe
5 */
6 int num1,num2;
7 /**
8 * Declaração dos métodos desta classe
9 */
10 int maior()
11 {
12 if (num1 > num2)
13 return true;
14 else return false;
15 }
16 void menor()
17 {
18 if (num1 < num2)
19 return num1;
20 else return num2;
21 }
22 } // fim da classe

*ERRO= EXISTE UM ERRO NOS IF/ELSE, ESTÃO SEM CHAVES* 

9)Identifique e explique o(s) erro(s) na classe abaixo.
1 class TesteImpressao
2 {
3 main(String[] args)
4 {
5 System.out.println(“7+2=”+(7+2));
6 System.out.println(“7-2=”+(7-2));
7 System.out.println(“7*2=”+(7*2));
8 System.out.println(“7/2=”+(7/2));
9 return true;
10 }
11 } // fim da classe

*ERRO= NÃO DECLAROU CORRETAMENTE A CLASSE MAIN* 

10)Identifique e explique o(s) erro(s) na classe abaixo.
1 class TesteDatas
2 {
3 public void static main(String[] args)
4 {
5 Data2 hoje = new Data2();
6 hoje.inicializaData(7,1,2001);
7 Data2 amanha;
8 amanha.inicializaData(8,1,2001);
9 System.out.println(amanha.eIgual(hoje));
10 }
11 } // fim da classe
Identifique e explique o(s) erro(s) na classe abaixo.
1 class TesteObjetos
2 {
3 public static void main(String[] args)
4 {
5 Data a;
6 Data b = new Data();
7 b = null;
8 b = a;
9 }
10 } // fim da classe

*A CLASSE MAIN ESTÁ COM A ORDEM DA DECLARAÇÃO AO CONTRÁRIO, O CORRETO É: PUBLIC STATIC VOID MAIN(*