<div align="center">
    <h1>Jogo da Velha em Java</h1>

<img src="https://github.com/user-attachments/assets/e19af2a2-52d1-4b45-97e7-acaeb096be2d"  width="60%" />

  <div align="center">
      <a href="#"><img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"></a>
  </div>

<h3>Jogo da Velha Console Game</h3>

<p>Este é um projeto em Java que implementa o clássico Jogo da Velha (Tic Tac Toe), permitindo que o jogador enfrente o computador diretamente pelo console. O jogo alterna entre as jogadas do jogador e do computador, verifica automaticamente as condições de vitória ou empate e exibe o tabuleiro atualizado a cada rodada.</p>

</div>

---

## <a name="table">Súmario</a>

1. [Introdução](#introdução)
2. [Funcionamento](#funcionamento)
3. [Requisitos](#requisitos)
4. [Como Jogar](#como-jogar)
5. [Funcionalidades do Projeto](#funcionalidades-do-projeto)
6. [Limitações](#limitações)
7. [Possíveis Melhorias](#possiveis-melhorias)
8. [Desenvolvedores](#desenvolvedores)

---

## <a name="introdução">Introdução</a>

O projeto apresenta uma implementação completa do Jogo da Velha em Java, com as seguintes funcionalidades:

- Escolha do símbolo do jogador (X ou O);
- Decisão aleatória de quem começa;
- Jogadas interativas e automáticas;
- Verificação de condições de vitória, empate e jogadas válidas;
- Interface simples via console, com exibição visual do tabuleiro a cada jogada.

---

## <a name="funcionamento">Funcionamento</a>

1. O jogador utiliza o símbolo **X** e o computador utiliza o símbolo **O**.
2. Alternam-se as jogadas até que:
   - Haja um vencedor (três símbolos iguais em linha, coluna ou diagonal);
   - O tabuleiro fique completo, resultando em empate.

A cada jogada, o tabuleiro é exibido no console.

---

## <a name="requisitos">Requisitos</a>

- **Java 8** ou superior.
- Ambiente de desenvolvimento configurado (IDE ou terminal com o compilador `javac`).

---

## <a name="como-jogar">Como Jogar</a>

1. Clone o repositório ou copie o código para um arquivo chamado `Main.java`.
2. Compile o código com o comando:

   ```bash
   javac Main.java
   ```

3. Execute o programa:

   ```bash
   java Main
   ```

4. Siga as instruções exibidas no console para fazer suas jogadas e tentar vencer o computador!

---

## <a name="funcionalidades-do-projeto">Funcionalidades do Projeto</a>

- **Interatividade Simples**: O jogo é jogado no terminal, oferecendo uma experiência direta e sem complexidade.
- **Validação de Jogadas**: Garante que as jogadas sejam feitas em posições válidas.
- **Sistema de Vitória e Empate**: Detecta automaticamente quando há um vencedor ou empate.
- **Jogada Automática do Computador**: O computador realiza jogadas automáticas simples.
- **Exibir Tabuleiro**: O tabuleiro é atualizado e exibido a cada jogada.

---

## <a name="limitações">Limitações</a>

- **Jogadas do computador**: Simples, escolhendo posições livres aleatoriamente. Não utiliza lógica avançada para prever movimentos.
- **Interface limitada**: Funciona exclusivamente via console.

---

## <a name="possiveis-melhorias">Possíveis Melhorias</a>

- **Melhoria na Inteligência Artificial**: Tornar a jogada do computador mais estratégica.
- **Modo de Dois Jogadores**: Permitir que duas pessoas joguem entre si.
- **Tamanho do tabuleiro**: Permitir que o jogador escolha o tamanho do tabuleiro.

---

## <a name="desenvolvedores">Desenvolvedores</a>

Este projeto foi desenvolvido durante uma hackathon, com a colaboração da seguinte equipe:

- Thiago Vieira
- Lucas Lima
- Eduardo Lima
- Marcos Vinicius
- Maiky Caires
- Taísa Tavares
- Rennan

---

Esperamos que você aproveite o jogo! Contribuições são bem-vindas para melhorias no projeto.
