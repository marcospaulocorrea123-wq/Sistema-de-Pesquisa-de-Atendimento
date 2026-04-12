# ⚡ SISTEMA PESQUISA DE OPINIÃO SOBRE ATENDIMENTO

![Status](https://img.shields.io/badge/Status-Concluído-green?style=for-the-badge)

## 📌 SOBRE O PROJETO

Este sistema foi desenvolvido para gerenciar pesquisas de satisfação de atendimento ao cliente. Ele permite o cadastro de até 50 entrevistados, validação de dados em tempo real e geração de relatórios estratégicos e analíticos. O projeto foca na aplicação prática de Estruturas de Repetição (FOR/WHILE) e manipulação de coleções de dados em Python.

## ▶️ COMO EXECUTAR

1. Instale o Python
2. Copie o codigo e cole no python app.py
3. Execute o programa 

## 🧠 FUNCIONALIDADES

 ## Estrutura de Repetição "FOR" .

- Este projeto dá ênfase ao uso da estrutura de repetição "FOR" aplicando a Coleta por um limitador de dados de "i in range (len(dados) + 1, 51)", afim de garantir que o limite de 50 entrevistas seja respeitado, automatizando a numeração dos IDs.Esse range pode ser editado como por exemplo para 500 entrevistados e para um PC moderno, podemos usar um "FOR" para coletar milhões de entrevistas antes de esgotar a memória, já que cada linha de texto ocupa poucos bytes.
- O programa possui um "checkpoint" que a cada 10 entrevistados aciona o operador matemático de módulo (total % 10 == 0) que pausa a coleta e pergunta ao usuário se ele deseja continuar ou voltar ao menu. Isso evita que o usuário fique "preso" em um loop longo sem poder visualizar os resultados parciais.

## Resumo do Fluxo Lógico.

- Entrada: Usuário digita os dados.

- Processamento: O sistema valida, classifica a opinião e guarda na lista.

- Saída: O sistema lê a lista e formata os dados visualmente para o usuário.
  
- O diagrama abaixo detalha a lógica de decisão e os loops de repetição implementados:

<img width="1408" height="768" alt="Fluxograma" src="https://github.com/user-attachments/assets/6a7b26e3-05d1-41ec-bc9a-37bbe9a591cc" />

## Regras e Restrições:
- Para garantir a integridade dos dados coletados, foram  implementadas as seguintes restrições em caso de Erro:
- Nome	Deve conter apenas letras e espaços, ou aparecerá uma mensagem de erro e repetição da pergunta.
- Opção de retorno ao menu por meio da primeira pergunta, digite seu "Nome" ou "Esc" para voltar ao menu principal imediatamente e acessar os dados armazenados.
- Idade	Deve ser um número inteiro entre 3 e 100, ou caso contrário surgirá uma mensagem de erro e repetição da pergunta.
Opinião	Deve ser obrigatoriamente 1 (Excelente), 2 (Bom) ou 3 (Ruim) ou ocorrerá uma mensagem de erro e repetição da pergunta.

 
## 💡 EXEMPLOS DE UTILIZAÇÃO

## Exemplo de utilização 01 "Inicio do programa com Menu principal"
<img width="424" height="171" alt="Ex01" src="https://github.com/user-attachments/assets/a97a5ebf-a878-4ccb-863f-f0c7328b0c70" />

## Exemplo de utilização 02 "Entrada de Dados para cada entrevistado o programa solicita:

- Nome ou voltar para menu 
- Idade 
- Opinião
- Atualiza os contadores
  
<img width="495" height="249" alt="Ex02" src="https://github.com/user-attachments/assets/97d4cf8f-d70e-469c-b739-5d55eee20b19" />

## Exemplo de utilização  03 "Demonstração de entrada de dados com erro"
<img width="551" height="510" alt="Ex03" src="https://github.com/user-attachments/assets/84bc52f4-6021-408a-b8fc-cbf3fc47386b" />

 ## Exemplo de utilização 04 "Relatório principal"
 - O sistema percorre os dados e realiza um filtro nas categorias"Excelente ou Ruim". Isso é útil para diagnósticos rápidos para solução de problemas e visuão de metas.
<img width="437" height="563" alt="Ex04" src="https://github.com/user-attachments/assets/f3b35e67-ff96-4920-8170-5d11f25765f4" />

 ## Exemplo de utilização 05 "Relatório principal"
- O sistema usa o For novamente para percorrer toda a lista de cadastrados e imprimir na tela de forma organizada, alinhando colunas como se fosse uma tabela de parâmetros técnicos.Para a exibição da "planilha", o programa utiliza f-strings com especificadores de formato {variavel:<20} que alinha o conteúdo à esquerda preenchendo o espaço restante com caracteres vazios até completar 20 bytes de largura.
Isso cria uma interface tabular estática no terminal, simulando uma estrutura de colunas de banco de dados SQL.

<img width="720" height="828" alt="Ex05" src="https://github.com/user-attachments/assets/09c69e5d-3d8e-43a1-a10c-45bde92b1953" />

## 🚀 TECNOLOGIAS APLICADAS

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="70"/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="70"/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="70"/>
</p>

<p align="center">
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
</p>
<p align="center">
![Autor](https://img.shields.io/badge/Autor-Marcos%20Correa-000000?style=for-the-badge&logo=github&logoColor=white)
</p>

