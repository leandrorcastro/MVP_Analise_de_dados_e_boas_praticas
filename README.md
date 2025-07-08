# MVP_Analise_de_dados_e_boas_praticas

### Introdução

O presente trabalho é um pré-requisito da disciplina Análise de Dados e Boas Práticas da pós graduação em Ciência de Dados e Analytics da PUC-Rio.

Nele é feita a análise do dataset Predictive Maintenance Dataset - Air Compressor e são aplicados os conceitos aprendidos nas disciplinas do curso.

### Estrutura do trabalho

O trabalho está dividido em tópicos, conforme a seguir:

1. Definição do problema: Este tópico apresenta o escopo do projeto, abordando o uso do dataset Predictive Maintenance Dataset - Air Compressor. O objetivo é analisar e prever falhas/condições anormais em compressores, identificando padrões que sinalizem a ocorrência de falhas/condições anormais por meio de variáveis contínuas e categóricas.

2. Coleta dos Dados: Detalha o processo de aquisição e carregamento do dataset, utilizando o Google Colab e Python. As bibliotecas principais empregadas são Pandas, NumPy, Matplotlib, Seaborn e scikit-learn.

3. Análise de Dados: Nessa etapa é feita a Análise Exploratória (EDA) do dataset. Visa compreender a distribuição, relações e características das variáveis, utilizando estatísticas descritivas e diversas visualizações gráficas (gráficos de barras, boxplots, histogramas, mapas de calor e etc) para verificar hipóteses e obter insights iniciais.

4. Pré Processamento de Dados: Descreve as etapas essenciais para preparar os dados para a modelagem. Inclui técnicas como normalização, padronização, seleção de características (via Random Forest), redução de dimensionalidade (PCA) e criação de novas características (Feature Engineering), garantindo a otimização para algoritmos de aprendizado de máquina.

5. Conclusão: Apresenta as principais descobertas da análise e pré-processamento. Destaca a importância de compreender a estrutura dos dados, a natureza desbalanceada do dataset, as correlações identificadas e a eficácia das visualizações. Reafirma a relevância das técnicas de normalização e padronização para o aprendizado de máquina, e valida as hipóteses levantadas com base nas análises gráficas.

### Hipóteses de Estudo

Foram levantadas as seguintes hipóteses que espera-se sejam provadas com a análise dos dados:

1. Compressor com vibração elevada (gacc/hacc) está associado a rolamentos desgastados. → Espera-se que vibrações sejam indicativos de problemas mecânicos como rolamentos desgastados.

2. Ruído (noise_db) elevado está associado a rolamentos desgastados. → Equipamentos ruidosos podem sinalizar atrito excessivo e/ou desgaste de componentes.

3. Altas temperaturas na saída ou no sistema de água tem relação com a condição do sistema de refrigeração. → A elevação da temperatura pode preceder falhas térmicas e pode ser indicativo de falta de manutenção no sistema de arrefecimento.

4. Pressão de saída fora da faixa operacional indica válvula de escape ou obstrução. → Pressões anormais podem apontar falhas e/ou bloqueio na válvula de escape.

5. Pressão na bomba do sistema de água tem relação com a condição do sistema de refrigeração. → A elevação da pressão na bomba da água de arrefecimento pode preceder falhas térmicas e pode ser indicativo de falta de manutenção no sistema de arrefecimento.

### Dados Complementares

Uma cópia do notebook do Google Colab e do dataset (Predictive Maintenance Dataset - Air Compressor), em formato csv, encontram-se anexados a este repositório.

Link para o dataset utilizado: https://www.kaggle.com/datasets/afumetto/predictive-maintenance-dataset-air-compressor

Link para o notebook no Google Colab: https://colab.research.google.com/drive/1hyTA-WzEMMbISWDW2SwIMDsvSDyRiUEi#scrollTo=Gm6mOo5PBYwr
