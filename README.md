# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Implementando algoritmos de Machine Learning com Scikit-learn

## 👨‍🎓 Aluno:
- <a href="https://www.linkedin.com/in/vitor-ribeiro-691a3729a/">Vitor Ribeiro Silva</a>

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/in/lucas-gomes-moreira-15a8452a/">Lucas Gomes Moreira</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/in/profandregodoi/">André Godoi Chiovato</a>


## 📜 Descrição

# Classificação de Grãos de Trigo com Aprendizado de Máquina  

Este projeto busca aplicar técnicas de aprendizado de máquina para classificar amostras de grãos de trigo em três variedades: **Kama**, **Rosa** e **Canadian**, utilizando o **Seeds Dataset**, disponível no [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/236/seeds).  

O estudo é baseado na metodologia **CRISP-DM** e inclui etapas como **preparação de dados**, **análise exploratória**, **treinamento de modelos** e **avaliação de desempenho**. Foram utilizados algoritmos como **Random Forest**, **SVM** e **KNN**, com foco na otimização de modelos para melhorar a acurácia e o desempenho geral.  

## Sobre o Dataset  
O conjunto de dados contém medições de **210 amostras** de grãos de trigo, com os seguintes atributos:  
- **Área**: medida da área do grão.  
- **Perímetro**: comprimento do contorno do grão.  
- **Compacidade**: calculada como (4 × π × Área) / (Perímetro²).
- **Comprimento do Núcleo**: eixo principal da elipse equivalente ao grão.  
- **Largura do Núcleo**: eixo secundário da elipse.  
- **Coeficiente de Assimetria**: medida da assimetria do grão.  
- **Comprimento do Sulco do Núcleo**: comprimento do sulco central do grão.  
- **Classe do Grão**: Kama, Rosa, Canadian.  

O objetivo é identificar padrões nos dados e treinar modelos capazes de realizar classificações precisas, auxiliando em futuras análises e aplicações práticas no setor agrícola.  



## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- **.github**: Contém arquivos de configuração e automação específicos para o GitHub, como workflows do GitHub Actions, utilizados para automatizar processos como testes e deploy.
- **assets**: Pasta destinada ao armazenamento de arquivos estáticos, como imagens dos gráficos desenvolvidos ou outros recursos visuais usados no projeto.
- **config**: Arquivos de configuração gerais que definem parâmetros e ajustes para o funcionamento do projeto.
- **document**: Contém os documentos do projeto, como o arquivo `.ipynb` com a análise desenvolvida.
- **scripts**: Scripts auxiliares para tarefas específicas do projeto, como o arquivo `.py` com o código desenvolvido e funções que complementam a execução do projeto.


## 🔧 Como executar o código

### Pré-requisitos

Antes de executar o código, é necessário ter os seguintes pré-requisitos instalados em sua máquina:

- **IDE ou editor de código**: Pode-se usar qualquer editor de código de sua preferência, como [VS Code](https://code.visualstudio.com/), [PyCharm](https://www.jetbrains.com/pycharm/), ou até mesmo o Jupyter Notebook para a execução dos arquivos `.ipynb`.
- **Python**: Certifique-se de ter o Python instalado na versão 3.x. Você pode verificar a instalação do Python executando o comando:
  ```bash
  python --version

### Passos para executar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Vitor-coder-eng/Implementando-algoritmos-de-Machine-Learning-com-Scikit-learn

2. **Acesse o diretório do projeto**:
   ```bash
   cd Implementando-algoritmos-de-Machine-Learning-com-Scikit-learn

3. **Executar o código**:

    Para executar o arquivo .ipynb, basta abrir o arquivo no Jupyter Notebook ou Jupyter Lab.
    Para rodar o arquivo .py, execute o comando:
    ```bash
    python script.py

4. **Verificar a saída**: Verifique os resultados gerados após a execução do código, como gráficos ou saídas de análises.

5. **Observação**: Se for necessário, ajuste as configurações conforme o ambiente de execução, como versões de bibliotecas ou configurações específicas de serviço.

## 🗃 Histórico de lançamentos

* 0.5.0 - 03/12/2024
  
## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>

