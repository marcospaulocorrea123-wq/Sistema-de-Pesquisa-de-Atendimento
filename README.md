# ⚡ Sistema de Pesquisa de Atendimento

![Status](https://img.shields.io/badge/Status-Concluído-green?style=for-the-badge)

## 📌 Sobre o Projeto

Este sistema foi desenvolvido para gerenciar pesquisas de satisfação de atendimento ao cliente. Ele permite o cadastro de até 50 entrevistados, validação de dados em tempo real e geração de relatórios estratégicos e analíticos. O projeto foca na aplicação prática de Estruturas de Repetição (FOR/WHILE) e manipulação de coleções de dados em Python.


## 🧠 Funcionalidades

1. O programa inicia com contadores zerados, entra em um laço de repetição (até 50 pessoas) e opera em um loop contínuo, apresentando quatro opções principais:
- Cadastrar entrevistado: Inicia o fluxo de coleta de dados.
- Relatório Principal: Exibe a contagem atual detalhada
- Relatório Global: (Atalho para o relatório) Exibe a visão geral dos dados.
- Sair: Finaliza a execução do script.


2. Para cada entrevistado o programa Solicita:

- Nome ou voltar para menu 
- Idade 
- Opinião 
- Atualiza os contadores 
O programa possui um "checkpoint" a cada 10 entrevistados e utiliza o operador matemático de módulo (total % 10 == 0).Então o sistema pausa a coleta e pergunta ao usuário se ele deseja continuar ou voltar ao menu. Isso evita que o usuário fique "preso" em um loop longo sem poder visualizar os resultados parciais.

3.	Regras e Restrições
Para garantir a integridade dos dados coletados, foram  implementadas as seguintes restrições:
Campo	Regra de Validação	Ação em caso de Erro
Nome	Deve conter apenas letras e espaços.	Mensagem de erro e repetição da pergunta.
Saída (Esc)	Se digitado "Esc" no campo Nome, o cadastro é cancelado.	Retorno imediato ao Menu Principal.
Idade	Deve ser um número inteiro entre 3 e 100.	Mensagem de erro e repetição da pergunta.
Opinião	Deve ser obrigatoriamente 1 (Excelente), 2 (Bom) ou 3 (Ruim).	Bloqueio de outros números ou letras.
Limite	O ciclo encerra automaticamente ao atingir 50 cadastros.	Exibe relatório final e encerra o for.

## 💡 Exemplo de uso

## 💡 Exemplo de uso 01

=== SISTEMA DE PESQUISA DE OPINIÃO ===
1 - Cadastrar entrevistado
2 - Relatório Principal (Excelente/Ruim)
3 - Relatório Global (Planilha Completa)
4 - Sair
Escolha uma opção: 1

## 💡 Exemplo de uso 02

--- Entrevistado 1 ---
Digite seu Nome ou 'Esc' para voltar: Marcos Correa
Digite a idade (3 a 100): 42
Opinião: 1-EXCELENTE | 2-BOM | 3-RUIM
Opção: 1

--- Entrevistado 2 ---
Digite seu Nome ou 'Esc' para voltar: esc


## 💡 Exemplo de uso 03


--- Entrevistado 9 ---
Digite seu Nome ou 'Esc' para voltar: Ruth Rocha
Digite a idade (3 a 100): 50
Opinião: 1-EXCELENTE | 2-BOM | 3-RUIM
Opção: 1

--- Entrevistado 10 ---
Digite seu Nome ou 'Esc' para voltar: Leila Toraca
Digite a idade (3 a 100): 101
Erro: Idade entre 3 e 100.
Digite a idade (3 a 100): 95
Opinião: 1-EXCELENTE | 2-BOM | 3-RUIM
Opção: 4
Opção inválida!
Opção: 3

10 feitos. Continuar? (S/N): s

--- Entrevistado 11 ---
Digite seu Nome ou 'Esc' para voltar: esc

=== SISTEMA DE PESQUISA DE OPINIÃO ===
1 - Cadastrar entrevistado
2 - Relatório Principal (Excelente/Ruim)
3 - Relatório Global (Planilha Completa)
4 - Sair
Escolha uma opção: 2

===================================
        RELATÓRIO PRINCIPAL        
===================================
CATEGORIA            |      VOTOS
-----------------------------------
EXCELENTE            |          5
RUIM                 |          4
-----------------------------------
Total (Exc/Ruim): 9

Pressione Enter para voltar...

=== SISTEMA DE PESQUISA DE OPINIÃO ===
1 - Cadastrar entrevistado
2 - Relatório Principal (Excelente/Ruim)
3 - Relatório Global (Planilha Completa)
4 - Sair
Escolha uma opção: 3

=================================================================
              RELATÓRIO GLOBAL DETALHADO (PLANILHA)              
=================================================================
ID   | NOME                      | IDADE  | AVALIAÇÃO   
-----------------------------------------------------------------
1    | Marcos Correa             | 42     | EXCELENTE   
2    | Marina Dantas             | 39     | RUIM        
3    | Cloves Lourenço           | 75     | EXCELENTE   
4    | Matheus Pinho             | 25     | BOM         
5    | Amilton King              | 48     | EXCELENTE   
6    | Robson Lee                | 33     | RUIM        
7    | Macaly Kaukin             | 4      | EXCELENTE   
8    | Vera Carpa                | 60     | RUIM        
9    | Ruth Rocha                | 50     | EXCELENTE   
10   | Leila Toraca              | 95     | RUIM        
-----------------------------------------------------------------
TOTAL GERAL DE ENTREVISTADOS: 10

Pressione Enter para voltar...

