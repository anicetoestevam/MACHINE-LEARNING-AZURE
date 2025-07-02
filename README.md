---

# 🧠 Machine Learning Fundamentals - Bike Rental Prediction

Este repositório contém materiais e instruções práticas relacionadas ao laboratório **"Explore Automated Machine Learning in Azure Machine Learning"**, onde treinamos um modelo de machine learning para prever o número de aluguéis de bicicletas com base em dados históricos sazonais e meteorológicos.

## 📌 Sobre o Projeto

Neste projeto, exploramos o uso do **Azure Machine Learning Studio** para realizar treinamento automatizado de modelos de aprendizado de máquina (*AutoML*). Usando dados históricos de aluguel de bicicletas da Capital Bikeshare, criamos, avaliamos e implantamos um modelo capaz de prever o número de aluguéis esperados em um determinado dia com base em variáveis como clima, estação do ano e condições meteorológicas.

## 🔗 Fonte Original

O conteúdo deste repositório foi baseado no laboratório disponível em:  
[Explore Automated Machine Learning in Azure Machine Learning](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)

## 🛠️ Tecnologias Utilizadas

- **Azure Machine Learning Studio**
- **Automated Machine Learning (AutoML)**

```

## 🚀 Etapas Realizadas

1. **Criação do Workspace do Azure Machine Learning**
2. **Preparação dos dados**
   - Carregamento do dataset histórico de aluguéis de bicicletas.
3. **Treinamento Automatizado (AutoML)**
   - Definição da tarefa como **Regressão**
   - Uso de dois algoritmos (`RandomForest`, `LightGBM`)
   - Configuração de métricas, validação e limites de execução
4. **Avaliação do Modelo**
   - Análise de métricas e gráficos 



```


## 💰 Custo e Limpeza

> ⚠️ Após concluir os testes, exclua o endpoint para evitar cobranças adicionais na sua assinatura do Azure.

Se não for utilizar mais o workspace:

1. Acesse o grupo de recursos no Azure Portal.
2. Exclua o grupo inteiro ou apenas os recursos individuais (como o workspace e endpoints).

## 📚 Referências

- [Microsoft Learn - AI Fundamentals](https://learn.microsoft.com/training/paths/ai-fundamentals/)
- [Azure Machine Learning Documentation](https://learn.microsoft.com/en-us/azure/machine-learning/)

---

