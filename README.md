# Structured Regression for Fetal Head Circumference Prediction

### Regressão Estruturada Para Previsão de Circunferência da Cabeça de Fetos

OBS: Caso o Github não renderize o arquivo .ipynb use os links abaixo:

- <a href="https://nbviewer.org/github/Julio-M39/09-Structured_Regression_for_Fetal_Head_Circumference_Prediction/blob/main/Regress%C3%A3o%20Estruturada%20Para%20Previs%C3%A3o%20de%20Circunfer%C3%AAncia%20da%20Cabe%C3%A7a%20de%20Fetos.ipynb">Clique aqui!</a> 

### Definição do Projeto


<div>
<img src="https://user-images.githubusercontent.com/54995990/189235506-a3d6de95-a4f9-47db-b29d-ae877912d3ad.png" width="800px" />
</div>

A medida do perímetro cefálico (PC) fetal é realizada durante toda a gestação como uma chave biométrica para monitorar o crescimento do feto. Esta medição é realizada em imagens de ultrassom, através do ajuste manual de uma elipse. A operação é dependente do operador e pode ser propensos ao erro intra e intervariabilidade. Essa abordagem é experimentada no conjunto de dados público HC18, que contém imagens de todos os trimestres da gravidez. 

Fonte de Dados:

https://hc18.grand-challenge.org/

### Etapas do Projeto

- Carga, Análise e Manipulação de Dados.
- Divisão em Treino e Teste
- Transformação das Imagens (Classe Para Formatação do Dataset)
- Dataloader
- Modelo - CNN-Based Structured Regression
- Treinamento do Modelo
- Função de Perda e Otimizador
- Avaliação
- Teste do Modelo Treinado com Novos Dados

### Resultados:

Podemos observar resultados próximos aos resultados obtidos do trabalho original. Obtemos no conjunto de teste um MAE Loss = 0.1303, Desvio Padrão de HC =  3.4988 mm, e MAE Loss de HC = 45.1474 mm. O modelo ainda pode ser otimizado com alterações nos hiperparâmetro.

**Referências:**

<a href="https://proceedings.mlr.press/v121/zhang20a.html">Direct estimation of fetal head circumference from
ultrasound images based on regression CNN</a>



