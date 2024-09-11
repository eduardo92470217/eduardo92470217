import java.util.Scanner; 

class Main {
  public static void main(String[] args) {
  /*  
  
    int numeroX;
    int numeroY;
    int resultado;
    
    Scanner entrada = new Scanner (System.in);
   System.out.println("qual o valor numero X");
    numeroX=entrada.nextInt();
    System.out.println("qual valor numero Y");
    numeroY=entrada.nextInt();
    
    resultado = numeroX % numeroY ;
   System.out.println("resto divisao e :" + resultado); 
    
    
     }
}
*/
/*
Scanner entrada = new Scanner (System.in);
    
    double real;
    double dolar;
    
    System.out.println("digite o valor em dolares: ");
    dolar = entrada.nextDouble();
    
    System.out.println("o valor em real e :" + dolar*4.95);
    
    
  }
}
*/
/*
 Scanner entrada = new Scanner (System.in);
    
    double raio ;
    double area;
    
    System.out.println("digite o raio: ");
    raio= entrada.nextDouble();
    
    area = 3.14 * raio;
     System.out.println("o valor da area do circulo e :" + area);
    
  }
}
*/
/*
   
    Scanner entrada = new Scanner (System.in);
    
    
    Double Nota1;
     Double Nota2;
     Double Nota3;
    
    System.out.println("digite a nota " );
    Nota1=entrada.nextDouble();
     System.out.println("digite a nota " );
    Nota2=entrada.nextDouble();
     System.out.println("digite a nota " );
      Nota3=entrada.nextDouble(); 
        System.out.println("o valor medio das notas informadas e"+ Nota1 +Nota2 +Nota3 );
       
       
       
  }
}
*/
/*

   
    // exercicio 5 inss fabricio 
    Scanner entrada = new Scanner(System.in);

    System.out.print("qual o valor da hora de trabalho: R$ ");
    double valorHora = entrada.nextDouble();

    System.out.print("qual o número de horas trabalhadas no mês: ");
    int horasTrabalhadas = entrada.nextInt();

    System.out.print("qual o percentual de desconto do INSS (em %): ");
    double descontoINSS = entrada.nextDouble();
    double salarioBruto = valorHora * horasTrabalhadas;
    double descontoINSSReal = salarioBruto * (descontoINSS / 100);
    double salarioLiquido = salarioBruto - descontoINSSReal;
    
   System.out.println("\nSalário Bruto: R$ " + salarioBruto);
    System.out.println("Desconto do INSS: R$ " + descontoINSSReal);
    System.out.println("Salário Líquido: R$ " + salarioLiquido);
     
    // porcetagem do inss e 7.5% e se coloca ponto nao virgula se digitar virgula vai dar erro //   
  }
}
*/
/*
Scanner scanner = new Scanner(System.in);
        System.out.print("Digite o valor de A: ");
        int a = scanner.nextInt();
        System.out.print("Digite o valor de B: ");
        int b = scanner.nextInt();
        // Troca os valores de A e B
        int temp = a;
        a = b;
        b = temp;
        System.out.println("Após a troca:");
        System.out.println("A: " + a);
        System.out.println("B: " + b);
         
      //exercicio 6 professor fabricio 
    // edu
    
    }
}
*/
/*
 public static void main(String[] args) {
        System.out.println("Número | Quadrado | Cubo");
        System.out.println("-------|----------|------");
        for (int i = 0; i <= 10; i++) {
            int quadrado = (int) Math.pow(i, 2);
            int cubo = (int) Math.pow(i, 3);
          System.out.printf("%-7d|%-10d|%-6d\n", i, quadrado, cubo);
     
          
          //nao sei se esta certo
        
        
        }
      
      
    }
}
*/
/*
 Scanner scanner = new Scanner(System.in);

        System.out.print("Digite a temperatura em Fahrenheit: ");
        double fahrenheit = scanner.nextDouble();

        double celsius = (fahrenheit - 32) * 5 / 9;

        System.out.println("A temperatura em Celsius é: " + celsius);
    
    //bingo ~~~~~~~8/10 pronto 
    
    
    }
}
*/
/*
 Scanner scanner = new Scanner(System.in);
        System.out.print("Digite o numero de canetas: ");
        int n = scanner.nextInt();
        System.out.print("qual o valor da nota: ");
        int z = scanner.nextInt();
        System.out.print("qual o valor do troco: ");
        int y = scanner.nextInt();
        // Calcula o valor pago pelas canetas
        int valorTotal = z - y;
        // Calcula o preco de cada caneta
        int preco = valorTotal / n;
  System.out.println(" o preco de cada caneta é: " + preco);
  
    
    //bingo~~~~~~~9/20
    
    }
}
*/
/*
Scanner scanner = new Scanner(System.in);
        System.out.print("Digite a hora (HH:MM): ");
        String hora = scanner.nextLine();
        // Separa a hora e os minutos
        String[] partes = hora.split(":");
        int horas = Integer.parseInt(partes[0]);
        int minutos = Integer.parseInt(partes[1]);
        // Calcula os minutos desde o início do dia
        int minutosTotais = (horas * 60) + minutos;
        System.out.println("Minutos desde o início do dia: " + minutosTotais);
    
      
      //acho que fiz certo mais deu trabalho tive que pesquisar no yutube 
    
    
    }
}
*/
/*
 Scanner scanner = new Scanner(System.in);
        System.out.print("Digite o preço da gasolina: R$ ");
        double precoGasolina = scanner.nextDouble();
        System.out.print("Digite o preço do etanol: R$ ");
        double precoEtanol = scanner.nextDouble();
        double relacao = precoEtanol / precoGasolina;
        if (relacao < 0.7) {
            System.out.println("Abasteça com etanol! É mais vantajoso.");
        } else {
            System.out.println("Abasteça com gasolina! É mais vantajoso.");
        
        //digite usando ponto e nao virgula se nao ira funcionar
        
        
        
        
        
        }
    }
}
*/
/*
  Scanner scanner = new Scanner(System.in);

        // medidas da área a ser revestida
        System.out.print("qual a largura da área ( metros): ");
        double larguraArea = scanner.nextDouble();
        System.out.print("qual o comprimento da área ( metros): ");
        double comprimentoArea = scanner.nextDouble();

        System.out.print("qual largura da cerâmica ( centímetros): ");
        double larguraCeramica = scanner.nextDouble();
        System.out.print("qual o comprimento da cerâmica ( centímetros): ");
        double comprimentoCeramica = scanner.nextDouble();
        larguraCeramica /= 100;
        comprimentoCeramica /= 100;
        double areaArea = larguraArea * comprimentoArea;
        double areaCeramica = larguraCeramica * comprimentoCeramica;
        double quantidadeCeramica = Math.ceil(areaArea / areaCeramica);
       
      
      // 10% para acabamento
        quantidadeCeramica *= 1.1;

        System.out.println("vai precisar de : " + quantidadeCeramica + " peças");
    }
}
*/
/*
 Scanner scanner = new Scanner(System.in);

        // medidas da área a ser revestida
        System.out.print("Digite a largura da área (em metros): ");
        double larguraArea = scanner.nextDouble();
        System.out.print("Digite o comprimento da área (em metros): ");
        double comprimentoArea = scanner.nextDouble();
        // medidas da cerâmica
        System.out.print("Digite a largura da cerâmica (em centímetros): ");
        double larguraCeramica = scanner.nextDouble();
        System.out.print("Digite o comprimento da cerâmica (em centímetros): ");
        double comprimentoCeramica = scanner.nextDouble();
        System.out.print("Digite o preço do metro quadrado da cerâmica: R$ ");
        double precoMetroQuadrado = scanner.nextDouble();
        larguraCeramica /= 100;
        comprimentoCeramica /= 100;
        double areaArea = larguraArea * comprimentoArea;
        double areaCeramica = larguraCeramica * comprimentoCeramica;
        double quantidadeCeramica = Math.ceil(areaArea / areaCeramica);
        quantidadeCeramica *= 1.1;
        double valorTotal = quantidadeCeramica * areaCeramica * precoMetroQuadrado;
        System.out.println("Quantidade de cerâmica necessária: " + quantidadeCeramica + " peças");
        System.out.println("Valor total a ser pago: R$ " + valorTotal);
    }
}
*/
/*
        Scanner scanner = new Scanner(System.in);
        System.out.print("Digite o seu peso (em kg): ");
        double peso = scanner.nextDouble();
        // Cálculo da quantidade de água recomendada (em ml)
        double aguaRecomendadaMl = peso * 35;
        // Conversão de ml para litros
        double aguaRecomendadaLitros = aguaRecomendadaMl / 1000;
        // Saída da quantidade de água recomendada em litros
        System.out.println("A quantidade de água recomendada para você é: " + aguaRecomendadaLitros + " litros.");
    }
}
*/
/*
 Scanner scanner = new Scanner(System.in);
        // Entrada das coordenadas do ponto P1
        System.out.print("Digite a coordenada x do ponto P1: ");
        double x1 = scanner.nextDouble();
        System.out.print("Digite a coordenada y do ponto P1: ");
        double y1 = scanner.nextDouble();
        // Entrada das coordenadas do ponto P2
        System.out.print("Digite a coordenada x do ponto P2: ");
        double x2 = scanner.nextDouble();
        System.out.print("Digite a coordenada y do ponto P2: ");
        double y2 = scanner.nextDouble();
        // Cálculo da distância entre os pontos
        double distancia = Math.sqrt(Math.pow(x1 - x2, 2) + Math.pow(y1 - y2, 2));
        // Saída da distância
        System.out.println("A distância entre os pontos P1 e P2 é: " + distancia);
    }
} 
*/
/*
  Scanner scanner = new Scanner(System.in);
        // Leitura das notas
        System.out.print("Digite a nota da primeira avaliação: ");
        double nota1 = scanner.nextDouble();
        System.out.print("Digite a nota da segunda avaliação: ");
        double nota2 = scanner.nextDouble();
        System.out.print("Digite a nota da terceira avaliação: ");
        double nota3 = scanner.nextDouble();
        // Cálculo da média
        double media = (nota1 + nota2 + nota3) / 3;
        // Verificação da aprovação
        if (media >= 7) {
            System.out.println("Aluno aprovado! Média: " + media);
        } else {
            System.out.println("Aluno reprovado. Média: " + media);
        }
    }
}
*/
/*
 Scanner scanner = new Scanner(System.in);

        // Leitura dos votos
        System.out.print("Digite o número de votos brancos: ");
        int votosBrancos = scanner.nextInt();
        System.out.print("Digite o número de votos nulos: ");
        int votosNulos = scanner.nextInt();
        System.out.print("Digite o número de votos válidos: ");
        int votosValidos = scanner.nextInt();

        // Cálculo do total de votos
        int totalVotos = votosBrancos + votosNulos + votosValidos;

        // Cálculo dos percentuais
        double percentualBrancos = (double) votosBrancos / totalVotos * 100;
        double percentualNulos = (double) votosNulos / totalVotos * 100;
        double percentualValidos = (double) votosValidos / totalVotos * 100;

        // Saída dos percentuais
        System.out.println("Percentual de votos brancos: " + String.format("%.2f", percentualBrancos) + "%");
        System.out.println("Percentual de votos nulos: " + String.format("%.2f", percentualNulos) + "%");
        System.out.println("Percentual de votos válidos: " + String.format("%.2f", percentualValidos) + "%");
    }
}
*/
/*
Scanner scanner = new Scanner(System.in);

        System.out.print("QUAL A IDADE DA PESSOA?: ");
        int idade = scanner.nextInt();

        if (idade < 16) {
            System.out.println("NÃO ELEITOR");
        } else if (idade >= 16 && idade < 18 || idade >= 70) {
            System.out.println("ELEITOR FACULTATIVO");
        } else {
            System.out.println("ELEITOR OBRIGATÓRIO");
        }
    }
}
*/
/*
 Scanner scanner = new Scanner(System.in);

        int opcao;

        do {
           
            System.out.println(" Menu do Caixa Eletrônico ");
            System.out.println("1. Exibir Saldo");
            System.out.println("2. Exibir Extrato");
            System.out.println("3. Realizar Depósito");
            System.out.println("4. Realizar Saque");
            System.out.println("5. Sair");
            System.out.print("Digite a opção desejada: ");

            
            opcao = scanner.nextInt();

            switch (opcao) {
                case 1:
                    System.out.println("Exibindo Saldo...");
                   
                    break;
                case 2:
                    System.out.println("Exibindo Extrato...");
                   
                    break;
                case 3:
                    System.out.println("Realizando Depósito...");
                   
                    break;
                case 4:
                    System.out.println("Realizando Saque...");
                 
                    break;
                case 5:
                    System.out.println("Saindo do Caixa Eletrônico...");
                    break;
                default:
                    System.out.println("Opção inválida. Saindo do programa.");
                    break;
            }
        } while (opcao != 5);
    }
}
 */
 /*
   Scanner scanner = new Scanner(System.in);

      
        System.out.print("Digite a descrição do produto: ");
        String descricao = scanner.nextLine();
        System.out.print("Digite a quantidade adquirida: ");
        int quantidade = scanner.nextInt();
        System.out.print("Digite o preço unitário: ");
        double precoUnitario = scanner.nextDouble();

      
        double total = quantidade * precoUnitario;

        
        double desconto = 0;
        if (quantidade <= 5) {
            desconto = 0.02; // 2%
        } else if (quantidade > 5 && quantidade <= 10) {
            desconto = 0.03; // 3%
        } else if (quantidade > 10 && quantidade < 30) {
            desconto = 0.05; // 5%
        } else if (quantidade >= 30) {
            desconto = 0.1; // 10%
        }
        desconto *= total; // Aplica o desconto ao total

       
        double totalAPagar = total - desconto;

        
        System.out.println("Descrição do Produto: " + descricao);
        System.out.println("Quantidade: " + quantidade);
        System.out.println("Preço Unitário: R$ " + precoUnitario);
        System.out.println("Total: R$ " + total);
        System.out.println("Desconto: R$ " + desconto);
        System.out.println("Total a Pagar: R$ " + totalAPagar);
    }
}
*/
/*


