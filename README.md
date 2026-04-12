# ⚡ SISTEMA PESQUISA DE OPINIÃO SOBRE ATENDIMENTO
![Status](https://img.shields.io/badge/Status-Concluído-green?style=for-the-badge)

## 📌 SOBRE O PROJETO
Este sistema foi desenvolvido para gerenciar pesquisas de satisfação de atendimento ao cliente. Ele permite o cadastro de até 50 entrevistados, validação de dados em tempo real e geração de relatórios estratégicos e analíticos. O projeto foca na aplicação prática de Estruturas de Repetição (FOR/WHILE) e manipulação de coleções de dados em Python.

## ▶️ COMO EXECUTAR
1. Instale o Python
2. Copie o codigo e cole no python app.py
3. Execute o programa 

## 🧠 FUNCIONALIDADES
 ## 1. Estrutura de Repetição FOR
O projeto dá ênfase ao uso do FOR em dois momentos críticos:
1.	Coleta Limitada: O for i in range(len(dados) + 1, 51) garante que o teto de 50 entrevistas seja respeitado, automatizando a numeração dos IDs.
2.	Processamento de Planilha: O for p in dados_entrevistados percorre a lista de objetos para renderizar a tabela global com alinhamento preciso de colunas.
   
## 2. O programa inicia com contadores zerados, entra em um laço de repetição (até 50 pessoas) e opera em um loop contínuo, apresentando quatro opções principais:
- Cadastrar entrevistado: Inicia o fluxo de coleta de dados.
- Relatório Principal: Exibe a contagem atual detalhada
- Relatório Global: (Atalho para o relatório) Exibe a visão geral dos dados.
- Sair: Finaliza a execução do script.

## 3. PARA CADA ENTREVISTADO O PROGRAMA SOLICITA:
- Nome ou voltar para menu 
- Idade 
- Opinião 
- Atualiza os contadores 

## 4.	REGRAS E RESTRIÇÕES
- Para garantir a integridade dos dados coletados, foram  implementadas as seguintes restrições em caso de Erro:
- Nome	Deve conter apenas letras e espaços, ou aparecerá uma mensagem de erro e repetição da pergunta.
- Opção de retorno ao menu por meio da primeira pergunta, digite seu "Nome" ou "Esc" para voltar ao menu principal imediatamente e acessar os dados armazenados.
- Idade	Deve ser um número inteiro entre 3 e 100, ou caso contrário surgirá uma mensagem de erro e repetição da pergunta.
Opinião	Deve ser obrigatoriamente 1 (Excelente), 2 (Bom) ou 3 (Ruim) ou ocorrerá uma mensagem de erro e repetição da pergunta.
- O programa possui um "checkpoint" que a cada 10 entrevistados aciona o operador matemático de módulo (total % 10 == 0) que pausa a coleta e pergunta ao usuário se ele deseja continuar ou voltar ao menu. Isso evita que o usuário fique "preso" em um loop longo sem poder visualizar os resultados parciais.
- O Limitador do processo será aplicado para encerrar automaticamente quando atingir 50 cadastros.
 
## 💡 EXEMPLOS DE UTILIZAÇÃO
## 💡 Exemplo de uso 01
<img width="424" height="171" alt="Ex01" src="https://github.com/user-attachments/assets/bfef197b-565d-48c3-8d31-36ec6464bc2f" />

## 💡 Exemplo de uso 02
<img width="495" height="249" alt="Ex02" src="https://github.com/user-attachments/assets/b1022150-a119-4221-ace4-3259a63761f3" />

## 💡 Exemplo de uso 03
<img width="551" height="510" alt="Ex03" src="https://github.com/user-attachments/assets/c079fa1e-dd4f-4c3d-9b8d-77ede3f2aa4a" />
<img width="451" height="303" alt="Ex04" src="https://github.com/user-attachments/assets/1304e77f-788d-4bd1-a61b-583113fa9695" />
<img width="440" height="500" alt="Ex05" src="https://github.com/user-attachments/assets/ebb2fe4c-6c9b-4e70-a76c-7f698bfb1834" />
<img width="723" height="591" alt="Ex06" src="https://github.com/user-attachments/assets/7ebf3d41-2a9b-413e-abf1-957c0a484b2b" />

## 🚀 TECNOLOGIAS APLICADAS
<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="70"/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="70"/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="70"/>
</p>




