# Criando minha primeira aplicação de Machine Learning

Neste conteúdo, foi colocado em prática o trajeto para criar um modelo de Aprendizado de Máquina no Microsoft Azure, partindo da criação da conta até retirando os dados previstos para o projeto realizado.

[Documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#deploy-and-test-the-model)

## 1. Passo - Criação de Recurso

Através da tela inicial da Microsoft Azure, selecionar a opção "Create Resource": 

Você será direcionado para a Azure Marketplace, e irá pesquisar por Azure Machine Learning e realizará a instalação.

Selecione o nome que deseja, assim como mais algumas informações.

## 2. Passo - Lançamento de Estúdio

Na tela inicial do workspace da Machine Learning, clique em "Launch Studio", onde irá te encaminhar para o Machine Learning Studio, selecione o menu e escolha Automated ML.

Selecione "+ New Automated ML job" e siga as informações conforme na documentação. 

De forma resumida, foi colocada as configurações do serviço, como banco de dados previamente liberado na documentação linkada no inicio do arquivo.

Foi colocado também o tipo de treino, que no caso foi o treino de regressão para prever o valor de aluguel de uma bicicleta em um determinado dia, além de parâmetro para a realização do treino do modelo, como tempo máximo de teste.

## 3. Passo - Lançamento de teste

Após tudo ser configurado, o inicio do teste será feito automaticamente, no meu caso, levou cerca de 5 horas para ser iniciado, e o treino durou uma quantia de 3 horas e 40 minutos.

## 4. Passo - Lançamento de modelo

A conclusão do treino gera um melhor modelo, que deve ser lançado e verificado os pontos de saída para o teste, dentre o resultados, estavam dados como comparativo de valores reais e dados previstos pela máquina, commo também um comparativo da diferença entre a média dos valores. Em geral, nos termos da própria documentação, o teste ocorreu de maneira correta. Para informações do parametro do teste, acessar o arquivo JSON.
