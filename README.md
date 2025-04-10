# 🏦 Sistema de Atendimento Bancário

Este projeto é uma simulação de um sistema de atendimento para um banco, que organiza clientes em duas filas: **normal** e **preferencial**. O objetivo é atender os clientes seguindo regras de prioridade, mantendo um histórico de atendimentos e permitindo a visualização das filas.

---

## 📌 Descrição do Problema

Um banco deseja implementar um sistema de atendimento para seus clientes, organizando-os em duas filas:

- **Fila Normal**: para clientes comuns.
- **Fila Preferencial**: para idosos, gestantes e pessoas com deficiência.

A regra de atendimento é:

- A cada dois clientes da **fila normal**, um da **fila preferencial** deve ser atendido (se houver).
- Se a fila preferencial estiver vazia, os atendimentos continuam normalmente com a fila comum.
- Se a fila normal estiver vazia, o atendimento será feito apenas com clientes preferenciais.

---

## 🎯 Objetivo

Criar um programa em **Python** que simule esse sistema de atendimento, utilizando listas para representar as filas e comandos básicos de manipulação de dados.

---

## ✅ Requisitos

1. Permitir a entrada de novos clientes, perguntando se são preferenciais ou não.
2. Manter a ordem de atendimento, garantindo a prioridade da fila preferencial.
3. Exibir as filas atualizadas após cada atendimento.
4. Manter um histórico dos clientes atendidos.
5. Seguir a lógica de alternância entre fila comum e fila preferencial.

---

## 🔧 Tecnologias Utilizadas

- Python 3.x

---

## 🧭 Passos para Implementação

1. Criar duas listas vazias para representar as filas:
   - `filaNormal`
   - `filaPreferencial`

2. Criar um menu interativo com as seguintes opções:
   - Adicionar um cliente à fila.
   - Atender um cliente, respeitando a regra de prioridade.
   - Exibir as filas atuais.
   - Mostrar o histórico de atendimentos.
   - Sair do programa.

3. Implementar a lógica de alternância de atendimento.
4. Exibir mensagens informativas para facilitar a interação do usuário.

---

## 🖥️ Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/lucasmvaladao/projeto-fila-de-atendimento.git
