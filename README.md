🧮 Calculadora de Soma em Java

Um projeto simples desenvolvido em Java que permite ao usuário informar dois números e calcular a soma entre eles.

📋 Sobre o projeto

A aplicação utiliza a classe Scanner para receber dois valores digitados pelo usuário, realizar a soma e exibir o resultado no terminal.

Este projeto é indicado para quem está começando a estudar Java, especialmente conceitos como:

Entrada de dados pelo usuário

Variáveis

Operadores matemáticos

Tipos de dados

Estrutura básica de um programa Java

🚀 Tecnologias utilizadas

Java

java.util.Scanner

📂 Estrutura do projeto
calculadora-soma/
└── CalculadoraSoma.java

💻 Código
import java.util.Scanner;

public class CalculadoraSoma {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Digite o primeiro número: ");
        double numero1 = scanner.nextDouble();

        System.out.print("Digite o segundo número: ");
        double numero2 = scanner.nextDouble();

        double resultado = numero1 + numero2;

        System.out.println("Resultado: " + resultado);

        scanner.close();
    }
}

▶️ Como executar
1. Verifique se o Java está instalado

Abra o terminal e execute:

java -version


Se o Java estiver instalado corretamente, a versão instalada será exibida.

2. Clone o repositório
git clone https://github.com/seu-usuario/calculadora-soma.git


Entre na pasta do projeto:

cd calculadora-soma

3. Compile o programa
javac CalculadoraSoma.java

4. Execute o programa
java CalculadoraSoma

🖥️ Exemplo de execução
Digite o primeiro número: 10
Digite o segundo número: 25
Resultado: 35.0

📚 Como funciona

O programa executa as seguintes etapas:

Importa a classe Scanner.

Cria um objeto Scanner para receber dados do teclado.

Solicita o primeiro número ao usuário.

Solicita o segundo número.

Soma os dois valores.

Armazena o resultado na variável resultado.

Exibe o resultado no terminal.

Fecha o objeto Scanner.

🎯 Objetivo

O objetivo deste projeto é praticar os conceitos básicos da linguagem Java por meio da criação de uma aplicação simples de entrada, processamento e saída de dados.

📝 Licença

Este projeto foi desenvolvido para fins educacionais e pode ser utilizado livremente para estudos e aprendizado.
