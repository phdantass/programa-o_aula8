# 🏥 Sistema Simples de Gestão de Consultas (Python)

## 📌 Descrição do Projeto

Este projeto reúne scripts em Python que simulam funcionalidades básicas de um sistema de gestão de pacientes e consultas médicas.

Cada arquivo representa uma “pílula” de lógica, abordando problemas reais como:

* Priorização de atendimento
* Controle de fila
* Histórico de pacientes
* Análise de consultas

O foco do projeto é o aprendizado de lógica de programação utilizando:

* Listas e dicionários
* Estruturas condicionais
* Laços de repetição
* Algoritmos de ordenação (Bubble Sort)

---

## 📂 Estrutura do Projeto

```
📁 projeto-consultas
│── pilula1.py  # Ranking de prioridade de pacientes
│── pilula2.py  # Especialidade mais frequente
│── pilula3.py  # Fila de atendimento
│── pilula4.py  # Histórico de pacientes
│── pilula5.py  # Processamento de consultas
```

---

## ⚙️ Funcionalidades

### 🔹 pilula1.py — Ranking de Prioridade

Calcula a prioridade dos pacientes com base em:

* Gravidade do caso
* Idade

**Regras:**

* Gravidade ≥ 4 → +3 pontos
* Gravidade ≥ 2 → +2 pontos
* Idade ≥ 60 → +2 pontos

---

### 🔹 pilula2.py — Especialidade mais frequente

Identifica qual especialidade médica aparece mais vezes em uma lista de consultas.

---

### 🔹 pilula3.py — Fila de atendimento

Simula uma fila (FIFO), atendendo o primeiro paciente e atualizando a lista.

---

### 🔹 pilula4.py — Histórico de pacientes

Atualiza o histórico removendo duplicatas e mantendo o paciente mais recente no final da lista.

---

### 🔹 pilula5.py — Processamento de consultas

Calcula:

* Tempo total de atendimento
* Quantidade de consultas
* Classificação do paciente (leve, moderado, crítico)

---

## 🚀 Como Executar

### ✅ Pré-requisitos

* Python 3 instalado

### ▶️ Execução

```bash
python pilula1.py
python pilula2.py
python pilula3.py
python pilula4.py
python pilula5.py
```

---

## 💡 Exemplos de Saída

### pilula1.py

```
Ana
1 - Carlos,3
2 - Beatriz,4
3 - Ana,4
4 - João,0
```

---

### pilula2.py

```
Especialidade mais frequente: Cardiologia
```

---

### pilula3.py

```
Fila inicial ['Gabriel', 'Beatriz', 'Carlos', 'Ana', 'Alcides']
Atendendo: Gabriel
Fila atualizada ['Beatriz', 'Carlos', 'Ana', 'Alcides']
```

---

### pilula4.py

```
['Ana', 'Guilherme', 'Denilson']
Paciente retornando: Guilherme
Histórico atualizado: ['Ana', 'Denilson', 'Guilherme']
```

---

### pilula5.py

```
Paciente: Ana, Tempo total 3, Qtd de consultas 2, Status: moderado
Paciente: Carlos, Tempo total 4, Qtd de consultas 1, Status: moderado
```

---

## 🎯 Objetivo Educacional

Projeto voltado para prática de lógica de programação em Python, simulando cenários reais da área da saúde.

---

## 📌 Melhorias Futuras

* Substituir Bubble Sort por métodos mais eficientes (`sorted()`)
* Criar sistema integrado
* Adicionar entrada de dados do usuário
* Implementar banco de dados (SQLite)
* Criar interface web (Flask/Django)

---
