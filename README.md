# Game.Girotto
Alunos: Diogo Pantoja Angelica e André Luís Colares Marinho

Descrição
TRI-game é um programa em C que oferece três jogos diferentes em uma única interface:

Perguntas e Respostas: Um quiz com 5 perguntas de múltipla escolha

Cobra na Caixa!: Jogo de aventura com elementos de azar

Gousmas War: Jogo estratégico de combate entre criaturas

Como Compilar e Executar
Requisitos
Compilador GCC instalado

Sistema operacional Linux/Windows/Mac

Compilação
bash
Copy
gcc tri_game.c -o tri_game
Execução
bash
Copy
./tri_game
Jogos Disponíveis
1. Perguntas e Respostas
Quiz com 5 perguntas de múltipla escolha

O jogador seleciona alternativas (a, b, c ou d)

Mostra se acertou ou errou após cada resposta

No final, exibe o número de acertos

2. Cobra na Caixa!
Jogo de aventura em uma tumba egípcia

Escolha entre 5 caixas, uma tem um botão para escapar, outra uma cobra mortal

As posições mudam aleatoriamente a cada rodada

Derrota se encontrar a cobra, vitória se encontrar o botão

3. Gousmas War
Jogo estratégico por turnos para 2 jogadores

Cada jogador controla 2 Gousmas (criaturas) com níveis de fúria

Ações disponíveis:

Atacar: transfere toda fúria de uma Gousma para uma inimiga

Dividir: redistribui fúria entre suas próprias Gousmas

Regras:

Se uma Gousma ultrapassar 5 de fúria, ela explode (volta a 0)

Perde quem ficar sem Gousmas com fúria positiva

Funcionalidades Adicionais
Sistema de "jogar novamente" após o término de cada jogo

Menu principal intuitivo

Tratamento de entradas inválidas

Observações
O jogo não usa bibliotecas complexas, apenas funcionalidades básicas de C

Para melhor experiência, execute em um terminal com bom suporte a caracteres

A Inteligência Artificial DeepSeek foi usada durante a programação deste jogo.
