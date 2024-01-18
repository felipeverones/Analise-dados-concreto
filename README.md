
# Análise da Resistência à Compressão de Concreto

## Visão Geral do Projeto
Este projeto visa analisar e prever a resistência à compressão do concreto utilizando técnicas de Data Science. O estudo combina análise exploratória de dados, pré-processamento, visualização e modelagem preditiva usando machine learning.


## Dados
O conjunto de dados contém 1030 registros com 9 atributos, que incluem a composição do concreto e sua resistência à compressão após diferentes períodos de cura. Os atributos são:
1. Cimento (componente 1) - Quantidade em kg/m^3
2. Escória de Alto Forno (componente 2) - Quantidade em kg/m^3
3. Cinzas Volantes (componente 3) - Quantidade em kg/m^3
4. Água (componente 4) - Quantidade em kg/m^3
5. Superplastificante (componente 5) - Quantidade em kg/m^3
6. Agregado Grosso (componente 6) - Quantidade em kg/m^3
7. Agregado Fino (componente 7) - Quantidade em kg/m^3
8. Idade (dias) - Período de cura do concreto
9. Resistência à Compressão (MPa) - Medida de força do concreto

## Metodologia
### Pré-processamento
- Limpeza de dados, incluindo a remoção de duplicatas.
- Aplicação de normas para a idade máxima do concreto (28 dias).
- Cálculo da relação água/cimento e normalização utilizando Z-Score.

### Visualização de Dados
- Uso de bibliotecas como Matplotlib e Seaborn para visualizar a distribuição dos dados e suas correlações.

### Modelagem
- Aplicação de técnicas de machine learning, incluindo Regressão Linear, Ridge e Regressor de Árvore de Decisão, com ajustes de hiperparâmetros para otimizar o desempenho.
- Uso de R², MSE (Erro Quadrático Médio) e outras métricas para avaliar e comparar a eficácia dos modelos.

## Bibliotecas Utilizadas
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Como Executar
Para executar este projeto:
1. Clone o repositório.
2. Instale as dependências listadas.
3. Execute sequencialmente o Jupyter Notebook `final.ipynb`.

## Dúvidas
Para mais informações, consultar apresentação em PDF.
