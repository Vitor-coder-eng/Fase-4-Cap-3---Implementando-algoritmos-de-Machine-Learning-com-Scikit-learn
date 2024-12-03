
<img src="../assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=30% height=30%>

# Classificação de Grãos de Trigo com Aprendizado de Máquina

## Nome do Aluno

#### Vitor Ribeiro Silva



## Sumário

[1. Introdução](#c1)

[2. Visão Geral do Projeto](#c2)

[3. Desenvolvimento do Projeto](#c3)

[4. Resultados e Avaliações](#c4)

[5. Conclusões e Trabalhos Futuros](#c5)

[6. Referências](#c6)

[Anexos](#c7)

<br>

# 1. Introdução <a name="c1"></a>

## 1.1. Escopo do Projeto

### 1.1.1. Contexto da Inteligência Artificial
A inteligência artificial (IA) tem se consolidado como uma das tecnologias mais disruptivas, impactando diversos setores como saúde, agronegócio, transporte e finanças. Neste projeto, o foco está na aplicação da IA no setor do agronegócio, com ênfase na classificação de grãos de trigo. Esta solução almeja melhorar a eficiência e a precisão no controle de qualidade.

### 1.1.2. Descrição da Solução Desenvolvida
A solução desenvolvida utiliza aprendizado de máquina para classificar amostras de grãos de trigo em três variedades distintas: Kama, Rosa e Canadian. O projeto inclui desde o pré-processamento de dados até a implementação e otimização de modelos de IA, com o objetivo de atender às necessidades específicas do agronegócio, fornecendo insights valiosos para tomada de decisão.

# <a name="c2"></a>2. Visão Geral do Projeto

## 2.1. Objetivos do Projeto
O principal objetivo é criar uma solução eficiente para classificar grãos de trigo, reduzindo o tempo e os custos associados a métodos tradicionais. Além disso, busca-se otimizar os modelos de aprendizado de máquina para garantir alta acurácia e uma aplicação prática para os produtores.

## 2.2. Público-Alvo
O público-alvo são produtores rurais, cooperativas agrícolas e empresas de tecnologia focadas em soluções para o agronegócio. A ferramenta também pode ser útil para pesquisadores acadêmicos interessados em explorar aplicações de IA no setor agrícola.

## 2.3. Metodologia
O desenvolvimento do projeto seguiu as seguintes etapas:
1. **Análise e pré-processamento dos dados**
2. **Implementação e comparação de diferentes algoritmos de classificação**
3. **Otimização dos modelos para melhor desempenho**
4. **Concusão e insights extraidos**

# <a name="c3"></a>3. Desenvolvimento do Projeto

## 3.1. Tecnologias Utilizadas
- **Linguagem de Programação:** Python
- **Bibliotecas:** Pandas, NumPy, Matplotlib, Scikit-learn, Seaborn
- **Ambiente de Desenvolvimento:** Google Colab
- **Ferramentas de Versionamento:** Git

## 3.2. Modelagem e Algoritmos
Os modelos utilizados foram:
- **K-Nearest Neighbors (KNN):** Simplicidade e eficiência para dados pequenos.
- **Support Vector Machine (SVM):** Capacidade de separação linear e não-linear.
- **Random Forest:** Robustez e boa generalização em problemas com dados complexos.

Esses algoritmos foram escolhidos por suas características complementares e sua aplicabilidade ao problema de classificação.

## 3.3. Treinamento e Teste
- **Conjunto de Dados:** Seeds Dataset, contendo 210 amostras de grãos de trigo.
- **Divisão dos Dados:** 70% para treinamento e 30% para teste.
- **Métricas Avaliadas:** Acurácia, precisão, recall, F1-score e matriz de confusão.
- **Resultados:** O modelo SVM destacou-se como o mais eficiente, com acurácia de 90% após otimização.

# <a name="c4"></a>4. Resultados e Avaliações

## 4.1. Análise dos Resultados
Os modelos apresentaram um bom desempenho geral, sendo o SVM o mais equilibrado entre precisão e recall. A análise revelou que as características como área e perímetro foram determinantes na classificação, destacando a importância de um pré-processamento cuidadoso.

# <a name="c5"></a>5. Conclusões e Trabalhos Futuros
O projeto atingiu seus objetivos iniciais, demonstrando o potencial da IA na classificação de grãos. No futuro, recomenda-se:
- Explorar outros modelos como Redes Neurais.
- Aumentar a base de dados para maior generalização.
- Integrar a solução em plataformas de análise agrícola.

# <a name="c6"></a>6. Referências
- Scikit-learn Documentation: [https://scikit-learn.org](https://scikit-learn.org)
- UC Irvine Machine Learning Repository: [https://archive.ics.uci.edu/ml/datasets/seeds](https://archive.ics.uci.edu/ml/datasets/seeds)

# <a name="c7"></a>7. Anexos
## 7.1. Gráficos
- **Histogramas**
- **Bloxplots**
- **Dispersão**
