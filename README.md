# Manutenção Preditiva SP

## Descrição do Projeto
Este projeto visa desenvolver um sistema de manutenção preditiva para uma indústria de grande porte em São Paulo, utilizando técnicas avançadas de aprendizado de máquina. O objetivo é analisar dados coletados de sensores em máquinas e equipamentos para identificar padrões que possam prever falhas e garantir operações mais eficientes.

## Acesso ao Projeto
O projeto está disponível para execução e revisão no Google Colab através do seguinte link: [Manutenção Preditiva SP](https://colab.research.google.com/drive/12lJStyRKGnek61UaBCsd73qCxNtkBXi6?usp=sharing).

## Pré-requisitos
- Acesso ao Google Colab.
- Conexão com a internet para acessar o notebook e os dados hospedados.
- Conta Google para salvar cópias do notebook, se desejado.

## Execução do Projeto
Para executar o projeto, siga estes passos:
1. Abra o link do projeto no Google Colab.
2. No menu superior, selecione `Ambiente de execução > Executar tudo` para rodar o notebook inteiro ou execute célula por célula manualmente.
3. Opcionalmente, ajuste os parâmetros dos modelos ou etapas de pré-processamento conforme desejado.

## Estrutura do Projeto
O notebook inclui as seguintes etapas principais:
- Carregamento e visualização dos dados dos sensores.
- Análise exploratória de dados para entender as características e distribuição das classes.
- Pré-processamento dos dados, incluindo imputação de valores faltantes e padronização.
- Aplicação do SMOTE para balanceamento das classes.
- Treinamento e avaliação de modelos de aprendizado de máquina, incluindo RandomForest e XGBoost.
- Visualização dos resultados e comparação das acurácias dos modelos.

## Resultados
Este projeto aplicou algoritmos de RandomForest e XGBoost para abordar a manutenção preditiva em máquinas industriais, com foco especial na correção do desbalanceamento de classes utilizando a técnica SMOTE. A acurácia alcançada revela insights valiosos sobre o comportamento dos modelos em um contexto altamente variável e desafiador. Apesar das limitações, como a simplicidade dos modelos frente à complexidade dos padrões nos dados, os resultados são encorajadores e abrem caminho para investigações mais profundas.

![image](https://github.com/gultes2023/Manutencao-Preditiva-SP-0-77/assets/131166618/ee027c7c-4cda-45bc-92fb-0caf44cfc500)

![image](https://github.com/gultes2023/Manutencao-Preditiva-SP-0-77/assets/131166618/f61769bb-a88d-4aca-889e-a70079745676)

## Discussão e Melhorias Futuras
A jornada para desenvolver uma solução de manutenção preditiva eficaz revelou desafios intrínsecos, como o desbalanceamento de classes e a complexidade na seleção e otimização dos modelos. A técnica SMOTE provou ser uma estratégia eficaz para mitigar o desbalanceamento, enquanto o uso dos algoritmos RandomForest e XGBoost foi justificado pela sua capacidade de processamento de dados de alta dimensionalidade e resistência a outliers.

Reflexões para o aprimoramento futuro incluem:

Exploração de Modelos Avançados: A implementação de redes neurais, como CNNs e RNNs, poderia oferecer uma compreensão mais profunda dos padrões temporais nos dados dos sensores.
Engenharia de Características: Métodos avançados de seleção de características poderiam revelar os sinais mais impactantes para a previsão de falhas.
Otimização de Hiperparâmetros: Estratégias como Grid Search e otimização Bayesiana podem refinar a configuração dos modelos para maximizar o desempenho.
Validação Cruzada Estratificada: Essencial para assegurar a representatividade das classes em conjuntos de treino e teste, fortalecendo a capacidade de generalização dos modelos.
Métricas Diversificadas: Adotar métricas como Precision-Recall AUC e F2-score, dando ênfase ao recall para minimizar o custo de previsões incorretas.

## Conclusão
A implementação da manutenção preditiva é vital para a indústria moderna, fornecendo uma estratégia proativa para a gestão de ativos. Este projeto demonstrou como técnicas de aprendizado de máquina podem ser empregadas para prever falhas em equipamentos industriais, contribuindo para a redução de paradas não planejadas e a otimização da manutenção. Apesar dos desafios, as perspectivas futuras são promissoras, sugerindo que, com contínuas melhorias e investigações, as soluções de manutenção preditiva se tornarão cada vez mais precisas e confiáveis.

## Referências
- Dataset Utilizado: Dados de Sensores para Manutenção Preditiva
- pandas: https://pandas.pydata.org/
- NumPy: https://numpy.org/
- scikit-learn: https://scikit-learn.org/stable/
- XGBoost: https://xgboost.readthedocs.io/
- imblearn (SMOTE): https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.SMOTE.html
- matplotlib: https://matplotlib.org/
- seaborn: https://seaborn.pydata.org/

