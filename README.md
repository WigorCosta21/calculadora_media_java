# Calculadora de Média

Este repositório contém um programa simples desenvolvido em Java para calcular a média de quatro notas inseridas pelo usuário e determinar o status do aluno com base na média final. O programa utiliza a biblioteca `JOptionPane` para a entrada e saída de dados em uma interface gráfica simples.

## Funcionalidade

O programa pede ao usuário para inserir quatro notas. Após a inserção, ele calcula a média aritmética dessas notas e classifica o aluno da seguinte forma:
- **Aprovado**: Se a média for 70 ou mais.
- **Em Recuperação**: Se a média estiver entre 50 e 69.
- **Reprovado**: Se a média for menor que 50.

## Como Usar

1. Clone este repositório para sua máquina local:
    ```bash
    git clone https://github.com/seu-usuario/calculadora_media.git
    ```

2. Compile o código Java:
    ```bash
    javac calculadora_media.java
    ```

3. Execute o programa:
    ```bash
    java calculadora_media
    ```

4. O programa solicitará a inserção das quatro notas. Após inserir todas, ele exibirá uma mensagem com o status do aluno baseado na média calculada.

## Exemplo de Execução

- Se o usuário inserir as notas 60, 70, 80, e 90, o programa calculará a média como `(60 + 70 + 80 + 90) / 4 = 75`. Nesse caso, a saída será:
Aluno está aprovado com média de: 75.0

---

- Se a média for 45, a saída será:
Aluno está reprovado com média de: 45.0


