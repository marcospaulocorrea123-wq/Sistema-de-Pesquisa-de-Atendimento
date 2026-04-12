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
<img width="424" height="171" alt="Ex01" src="https://github.com/user-attachments/assets/bfef197b-565d-48c3-8d31-36ec6464bc2f" />

## 💡 Exemplo de uso 02
<img width="495" height="249" alt="Ex02" src="https://github.com/user-attachments/assets/b1022150-a119-4221-ace4-3259a63761f3" />

## 💡 Exemplo de uso 03
<img width="551" height="510" alt="Ex03" src="https://github.com/user-attachments/assets/c079fa1e-dd4f-4c3d-9b8d-77ede3f2aa4a" />
<img width="451" height="303" alt="Ex04" src="https://github.com/user-attachments/assets/1304e77f-788d-4bd1-a61b-583113fa9695" />
<img width="440" height="500" alt="Ex05" src="https://github.com/user-attachments/assets/ebb2fe4c-6c9b-4e70-a76c-7f698bfb1834" />
<img width="723" height="591" alt="Ex06" src="https://github.com/user-attachments/assets/7ebf3d41-2a9b-413e-abf1-957c0a484b2b" />



