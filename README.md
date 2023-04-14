# Apache-Airflow


## Descrição:

Desenvolvendo projeto no curso de Airflow da Alura, onde construi um pipeline de dados que extrai a previsão do tempo da semana atual para que a empresa de turismo consiga organizar os passeios de acordo com as condições climáticas.
Mas, precisamos automatizar esse processo de forma que nosso data pipeline seja executado automaticamente toda segunda-feira. E a ferramenta que vai nos possibilitar a realizar esta automação é o Apache Airflow. 
Fonte: www.alura.com.br

## O que é o Apache Airflow:

O Apache Airflow é uma plataforma de gerenciamento de fluxo de trabalho de código aberto para pipelines de engenharia de dados. Começou no Airbnb em outubro de 2014 como uma solução para gerenciar os fluxos de trabalho cada vez mais complexos da empresa. 
Fonte: Wikipedia 

## O que são as triggers:

As triggers no Airflow são implementadas como gatilhos (triggers) que são associados a tarefas individuais ou a DAGs (Directed Acyclic Graphs), que são os fluxos de trabalho definidos no Airflow. Quando uma trigger é ativada, ela inicia a execução do fluxo de trabalho associado. As triggers podem ser ativadas de várias maneiras, como por exemplo:

1. Agendamento de tempo: É possível definir triggers baseadas em cronogramas específicos, como executar uma tarefa ou fluxo de trabalho a cada hora, diariamente, semanalmente, mensalmente, etc. É uma forma comum de acionar tarefas ou fluxos de trabalho em intervalos regulares.

2. Disparo externo: É possível usar gatilhos externos para iniciar a execução de fluxos de trabalho no Airflow. Por exemplo, é possível configurar uma API externa para disparar uma trigger no Airflow quando um evento específico ocorre, como a chegada de um novo arquivo em um diretório específico.

3. Triggers manuais: É possível definir triggers manuais que são acionadas manualmente pelos usuários por meio da interface do Airflow ou por meio de uma API, permitindo que os usuários iniciem a execução de fluxos de trabalho sob demanda.

As triggers no Airflow são altamente configuráveis e podem ser personalizadas de acordo com as necessidades de cada fluxo de trabalho. Elas fornecem uma maneira flexível e poderosa de controlar a execução de fluxos de trabalho com base em eventos específicos ou em cronogramas agendados.
