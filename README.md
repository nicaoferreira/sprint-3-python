# Sistema de Promoção da Fórmula E

## Descrição
Este projeto é uma simulação de um sistema interativo para promover a Fórmula E. O objetivo é oferecer um ambiente digital no qual os fãs podem se engajar com conteúdos exclusivos da Fórmula E, como quizzes e enquetes, ganhando pontos ao interagir com essas atividades. Os pontos acumulados podem ser visualizados e organizados em um ranking de fãs.

O projeto utiliza estruturas como **dataframes**, **funções**, **loops** e **condições** para armazenar e gerenciar dados dos usuários, tais como pontuações e interações com o conteúdo. O sistema permite registrar novos usuários, fazer login e visualizar o ranking de fãs.

## Funcionalidades
- **Cadastro e Login**: Os usuários podem se cadastrar no sistema e fazer login utilizando seu nome de usuário e senha.
- **Interações**: Ao fazer login, os usuários podem participar de atividades interativas (quizzes, enquetes, compartilhamentos em mídias sociais) e ganhar pontos.
- **Ranking de Fãs**: O sistema exibe um ranking dos fãs com base nas pontuações acumuladas pelas interações.
  
## Tecnologias Utilizadas
- **Pandas**: Para armazenamento e manipulação de dados dos usuários em um `DataFrame`.
- **Random**: Para gerar interações e pontos aleatórios durante a simulação.
- **Estruturas de Controle**: Uso de loops, condições e funções para controlar o fluxo do programa.
- **Entrada e Saída de Dados**: Inputs são utilizados para registrar e autenticar os usuários, e o output exibe as pontuações e o ranking.

## O que foi utilizado no código Python
- **Biblioteca `random`**: Para simular a geração de pontos e interações aleatórias.
- **Biblioteca `pandas`**: Para armazenar e organizar os dados dos usuários.
- **Classes e Métodos**: Para organizar a lógica do sistema em uma estrutura orientada a objetos.
- **Funções `input()` e `print()`**: Para receber dados do usuário e exibir as informações no terminal.
- **Estruturas de Decisão (`if`, `else`)**: Para controle do fluxo de login e registro.
- **Laços (`while`)**: Para criar menus de interação e permitir que o usuário execute ações repetidas até fazer logout.

## Requisitos
- Ter instalado um interpretador Python, como o **Python 3.x**.
- Usar um editor de texto ou IDE de preferência (recomendado: **VSCode**).

## Como Utilizar o Código
1. Execute o código Python no seu ambiente de desenvolvimento.
2. No menu inicial, escolha se deseja **registrar um novo usuário** ou **fazer login**.
3. Se optar pelo **registro**, insira um nome de usuário e senha. Se optar pelo **login**, utilize as credenciais registradas.
4. Após o login, você pode:
   - **Interagir com conteúdos da Fórmula E** para acumular pontos.
   - **Visualizar o ranking de fãs**.
   - **Fazer logout** quando terminar.

O sistema irá gerar pontos aleatórios e adicionar à sua pontuação cada vez que você participar de uma atividade.
