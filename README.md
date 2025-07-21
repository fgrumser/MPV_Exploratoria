
# Análise da Qualidade do Ar

Este projeto realiza uma análise exploratória de um conjunto de dados de qualidade do ar, com medições horárias coletadas por sensores químicos e analisadores de referência entre março de 2004 e fevereiro de 2005. Os dados foram obtidos ao nível da rua, em uma área urbana altamente poluída de uma cidade italiana.

## Objetivo

O objetivo deste trabalho é entender o comportamento das variáveis atmosféricas e poluentes ao longo do tempo, buscando possíveis correlações entre elas. A análise contempla etapas de exploração estatística e visual, bem como um pré-processamento cuidadoso para garantir a consistência dos dados antes da modelagem.

## Fonte dos Dados

- **Base**: Air Quality Data Set  
- **Origem**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/360/air+quality)  
- O dataset contém 9.358 instâncias com medições horárias de sensores químicos de óxidos metálicos e analisadores certificados. Valores ausentes estão representados por -200.

## Etapas do Projeto

- Definição do problema e formulação de hipóteses
- Análise exploratória dos dados (EDA)
  - Estatísticas descritivas (média, desvio padrão)
  - Visualizações (histogramas, boxplots, matriz de correlação)
- Pré-processamento
  - Tratamento de valores nulos
  - Normalização e padronização dos dados
- Análise com base nas hipóteses levantadas
- Consolidação dos principais achados

## Hipóteses analisadas

1. **Variação dos poluentes por período do dia**: A noite apresenta as maiores medianas para a maioria dos poluentes. Pela manhã, há picos nos níveis de C6H6 e NO₂.
2. **Influência do tráfego urbano sobre o NO₂**: As maiores concentrações de NO₂ coincidem com os horários de pico, especialmente manhã e fim de tarde.
3. **Relação entre umidade relativa e CO**: A dispersão dos dados não apresentou padrão definido, não sendo possível confirmar uma correlação clara.

## Tecnologias e Bibliotecas Utilizadas

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn` (StandardScaler, MinMaxScaler)

## Como Executar

- Acesse o link do Google Colab disponível no topo da página do repositório.
- Clique em "Executar no Colab".
- Siga as células do notebook em ordem para visualizar a análise completa.

---

Este projeto foi desenvolvido como parte da formação em Data Science pela PUC-Rio, na sprint de **Análise de Dados e Boas Práticas**. A entrega foi bem avaliada e apontamentos construtivos sobre boas práticas de organização de código e consolidação de datasets finais reforçam a importância da prática contínua.  
