# README - Workshop ECS

Nesse repositório você encontra alguns artefatos que serão utilizados durante o workshop sobre ECS.

Nesse workshop instanciaremos um cluster ECS atrás de um ALB e faremmos a criação de contêineres utilizados no aplicação. 
As imagens serão armazenadas no AWS ECR que alimentará o cluster ECS.
Também utilizaremos facilidades auto escaláveis e de monitoramento, assim como criaremos um pipeline CI/CD.

O material está assumindo a região us-east-1 da AWS.

Você precisa de uma conta na AWS para executar esse workshop e ele pode ter custos associados (~ US$ 5,00).

### ecs-workshop-personal.yaml
Cloudformation para instanciar a infraestrutura da VPC para executar o workshop.

## Comandos Dia 02 - ECS.txt
Comandos que serão executados durante o workshop. Para evitar erros de digitação.

## CatsDef-TaskDefinition.json e DogsDef-TaskDefinition.json
Instruções no formato JSON para criação das definições de tarefas catsdef e dogsdef utilizados durante o workshop.

# buildspec-template.txt
Template do buildspec para automação do pipeline de CI/CD no github.
