# ProjetoRotaIntelingenteIA
Trabalho: Rota Inteligente: Otimização de Entregas com Algoritmos de IA


# 🚚 Rota Inteligente: Otimização de Entregas com Algoritmos de IA

## 📖 Descrição do Projeto
Este projeto propõe uma solução inteligente para otimização de rotas de entrega da empresa **Sabor Express**, que atua no delivery de alimentos na região central da cidade.  
O objetivo é reduzir atrasos, custos de combustível e aumentar a eficiência operacional, especialmente em horários de pico, utilizando algoritmos de Inteligência Artificial.

---

## 🎯 Objetivos

### Objetivo Geral
Desenvolver uma solução baseada em IA para otimização de rotas de entrega utilizando grafos e algoritmos de busca.

### Objetivos Específicos
- Modelar a cidade como um grafo ponderado;
- Aplicar algoritmos de busca para encontrar o menor caminho;
- Utilizar técnicas de clustering para agrupar entregas próximas;
- Comparar a solução proposta com o método tradicional.

---

## 🧠 Conceitos e Algoritmos Utilizados

- **Grafos Ponderados** (representação urbana)
- **Algoritmo A\*** (busca heurística de menor caminho)
- **Busca em Largura (BFS)** e **Busca em Profundidade (DFS)** *(conceitual)*
- **K-Means** (aprendizado não supervisionado para clustering)
- Heurísticas de otimização de rotas

---

## 🏙️ Modelagem do Problema
- **Nós:** restaurantes, bairros e clientes  
- **Arestas:** ruas  
- **Pesos:** distância ou tempo estimado  

A cidade é representada como um grafo ponderado, permitindo a aplicação de algoritmos de busca para otimização das rotas.

---

## ⚙️ Metodologia
1. Agrupamento dos pedidos em zonas de entrega utilizando **K-Means**;
2. Aplicação do algoritmo **A\*** para encontrar a melhor rota dentro de cada grupo;
3. Comparação com rotas definidas manualmente.

---

## 🧪 Simulação
Foi utilizado um cenário hipotético representando a região central da cidade, com múltiplos pedidos simultâneos.  
A solução baseada em IA foi comparada com o método tradicional utilizado pela empresa.

---

## 📊 Resultados Esperados
- Redução da distância total percorrida;
- Diminuição do tempo médio de entrega;
- Melhor aproveitamento dos entregadores;
- Aumento da satisfação dos clientes.

---

## 🔍 Discussão
Os resultados indicam que a utilização de IA na otimização de rotas é altamente eficaz, principalmente em cenários de alta demanda, proporcionando redução de custos e melhoria na eficiência logística.

---

## 📚 Referências
- UPS – ORION (Otimização de Rotas Logísticas)
- Medium – *Optimizing Logistics: Clustering e MILP*
- ResearchGate – *AI-Powered Route Optimization*
- Kardinal.ai – *Fresh Product Delivery Case Study*

---

## 👨‍💻 Autor
**Edison Felipe Neves Moreira**  
Estudante de Engenharia da Computação


## ▶️ Como executar o projeto

### 1. Criar ambiente virtual (opcional)
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

### 2. Instalar dependências
pip install -r requirements.txt

### 3. Executar o projeto
python src/main.py

### 4. Ver resultados
- Terminal: melhor rota e custo
- Pasta /outputs: gráfico dos clusters
