# 📦 MisterFabLearn — Controle de Ferramentas e Agendamento do Laboratório

Sistema desenvolvido em **Portugol Studio** para gerenciar estoque de ferramentas e agendamentos do espaço FabLearn por turmas.


## 🚀 Funcionalidades

### 🔧 Gestão de Ferramentas
- Visualizar estoque disponível
- Retirar itens (com alerta de estoque baixo)
- Devolver itens
- Bloqueia retirada quando o item está zerado
- Alerta quando estoque está acabando (≤ 2 unidades)

### 📝 Histórico de Movimentações
- Registra:
  - RA do aluno
  - Nome do item
  - Tipo de movimento (Retirada ou Devolução)
- Exibe todo histórico armazenado

### 📅 Agendamento do Espaço
- Agenda semanal com 15 períodos:
  - Segunda a Sexta (Manhã, Tarde, Integral)
- Permite agendar apenas períodos livres
- Associa cada agendamento a uma turma
- Exibe a agenda com status (LIVRE ou OCUPADO)


## 🧠 Habilidades e Conceitos Utilizados
- Vetores
- Estruturas de repetição
- Condicionais e validações
- Menu interativo com escolha/caso


## 📌 Regras do Sistema
✔ Impede retirada de itens sem estoque  
✔ Alerta quando o item precisa ser reposto  
✔ Não permite agendar períodos já ocupados  
✔ Registra todas as movimentações realizadas  


## 📂 Estrutura do Menu

| Opção | Função |
|------|--------|
| 1 | Visualizar Estoque |
| 2 | Retirar Item |
| 3 | Devolver Item |
| 4 | Histórico de Movimentações |
| 5 | Visualizar Agenda |
| 6 | Agendar Período |
| 0 | Sair do sistema |


## 🗃 Dados Armazenados

### 🔩 Ferramentas (11 itens)
Ex:
- Alicate
- Trena
- Ferro de Solda
- Chave de Fenda
- Lixadeira
- etc

### 📆 Agenda (15 períodos)
Ex:
- Segunda Inteira
- Terça de Manhã
- Quinta de Tarde

### 👥 Turmas (12 cadastradas)
Ex:
- 1º Ano — Alan Turing
- 2º Ano — Nísia Floresta
- 3º Ano — Mary Jackson


## 🛠 Tecnologias Utilizadas
- **Portugol Studio**
- Lógica de Programação Estruturada



## 💡 Objetivo do Projeto
Automatizar o controle de ferramentas e horários de uso do laboratório escolar de forma simples, prática e sem banco de dados.


## 📌 Observações
- O armazenamento é feito em vetores (os dados não são salvos após o programa fechar)
- Ideal para prática de lógica e sistemas educacionais
- Fácil de expandir com novas funções


## 👨‍💻 Desenvolvido por
**Alunos do Ensino Medio da Escola SESI Jose Pedro Fernando Piovan** ✨  
Projeto educacional, uso livre para estudos.

Quer que eu personalize com seu nome ou escola? 😎
