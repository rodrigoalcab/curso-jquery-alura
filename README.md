# Estudo de jQuery

## Descrição do projeto
- Trata-se de um jogo de digitação onde o usuário tem um tempo limitado para digitar o máximo de palavras possíveis conforme a frase disponibilizada.
- Projeto desenvolvido nos cursos: [jQuery: Domine a biblioteca mais popular do mercado](https://cursos.alura.com.br/course/jquery-a-biblioteca-do-mercado) e [jQuery: Avance na biblioteca mais popular do mercado](https://cursos.alura.com.br/course/jquery-a-biblioteca-do-mercado-parte-2)

## Tecnologias utilizadas
- JavaScript
- jQuery
- HTML5
- CSS3

## Plugins utilizados
- [Selectize](http://selectize.github.io/selectize.js)
- [Tooltipster](http://iamceege.github.io/tooltipster)

## Requisitos
- Ter o Node.js instalado na máquina
- Acessar a pasta servidor e rodar o comando npm start
- Acessar a aplicação pelo endereço http://localhost:3000/principal.html

## Funcionalidades
- Contador de palavras conforme o tamanho da frase disponibilizada
- Cronômetro automático que inicia a partir do inicio da digitação da frase
- Alteração da cor da borda do campo de digitação conforme digitação correta (verde) ou errada (vermelha)
- Travamento automático do campo de digitação quando o cronômetro chega a zero
- Placar que registra os dados do jogador
- Botão reiniciar que reseta todos os dados para um novo jogo
- Botão que esconde ou mostra o placar
- Botão que troca a frase de forma aleatória
- Botão que troca a frase conforme o ID informado
- Botão para remover registros dos jogadores
- Ajax para efetuar GET e extrair as frases e o placar do banco de dados
- Ajax para efetuar POST para enviar o placar atualizado

