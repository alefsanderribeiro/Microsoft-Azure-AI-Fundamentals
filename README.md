# Trabalhando com Machine Learning na Prática no Azure ML

Este repositório contém um guia prático para criar, treinar e testar modelos de aprendizado de máquina usando o Azure Machine Learning. Vamos focar na tarefa de prever aluguéis de bicicletas.

## Passo 1: Criando o Recurso do Azure Machine Learning

1. Acesse o portal do Azure.
2. Clique em "Criar um recurso" e pesquise por "Azure Machine Learning" no marketplace.
3. Crie o recurso, fornecendo os detalhes necessários, como assinatura, grupo de recursos e detalhes da área de trabalho.

## Passo 2: Configurando o Recurso do Azure Machine Learning

1. Na página do recurso criado, clique em "Iniciar o estúdio" para acessar o Azure Machine Learning Studio.
2. No estúdio, crie um novo trabalho de ML automatizado:
    - Preencha os campos básicos, como nome do trabalho e descrição.
    - Escolha o tipo de tarefa (regressão, no nosso caso).
    - Selecione os dados de treinamento (você pode usar o conjunto de dados de aluguéis de bicicletas).
    - Configure as opções de fonte de dados e esquema.
    - Crie o trabalho de treinamento.

## Passo 3: Criando o Modelo

1. Após o treinamento, acesse a página do trabalho realizado.
2. Clique em "Modelo de registro" para criar o modelo.
3. Escolha a coluna de destino (no nosso caso, a coluna "rentals").
4. Configure os limites e a validação.
5. Envie o trabalho de treinamento.

## Passo 4: Implantação e Uso

1. Crie um ponto de extremidade online para implantar o modelo treinado.
2. Use o ponto de extremidade para fazer previsões de aluguéis de bicicletas.

Lembre-se de adaptar essas etapas ao seu projeto específico e documentar qualquer configuração adicional necessária.

---

Este guia foi baseado em um projeto da Digital Innovation One. Você pode encontrar o código completo aqui: https://github.com/asilv232/Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML
