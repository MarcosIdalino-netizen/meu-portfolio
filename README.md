# 🚀 Meus Estudos de Java - IFPI

Bem-vindo ao meu portfólio de estudos da faculdade! Aqui estou documentando minha jornada de transição para a programação orientada a objetos e desenvolvendo meus primeiros códigos em Java.

## 📚 Tópicos e Projetos

* **Algoritmos Iniciais:** Estruturas de repetição (`for`), testes condicionais (`if/else`) e tratamento de entrada com `Scanner`.
* **Lógica Aplicada:** Resolução de problemas práticos, como contagem de pares/ímpares e descobrimento de maior/menor número.

---

### 💻 Exemplos de Código

#### 1. Verificador de Maior e Menor Número
```java
Scanner scanner = new Scanner(System.in);

System.out.print("Digite o número 1: ");
int num = scanner.nextInt();

int maior = num; 
int menor = num;

for (int i = 2; i <= 5; i++) {
    System.out.printf("Digite o número %d: ", i);
    num = scanner.nextInt();

    if (num > maior) {
        maior = num;
    }
    if (num < menor) {
        menor = num;
    }
}

System.out.printf("Maior número = %d%n", maior);
System.out.printf("Menor número = %d%n", menor);
