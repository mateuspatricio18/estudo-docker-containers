# Estudo Docker - Containers

## Sobre
Este repositório documenta meu aprendizado sobre Docker e containerização.

**Autor:** [SEU NOME]
**Curso:** [SEU CURSO TÉCNICO]
**Disciplina:** [NOME DA DISCIPLINA]
**Data:** [DATA]

## O que estou aprendendo
- Conceitos fundamentais do Docker
- Como criar e gerenciar containers
- Trabalhar com imagens Docker
- Configurar bancos de dados em containers
- Usar Docker Compose para aplicações multi-container

## Estrutura do Projeto
- `containers/` - Dockerfiles e configurações de containers
- `compose/` - Arquivos Docker Compose e aplicação Flask
- `scripts/` - Scripts de configuração, backup e monitoramento
- `evidencias/` - Prints das tarefas
- `README.md` - Documentação principal

## Status do Estudo
- [ ] Tarefa 1 - Primeiro container
- [ ] Tarefa 2 - Container personalizado
- [ ] Tarefa 3 - Banco de dados
- [ ] Tarefa 4 - Docker Compose

## Reflexão Final

### 1. Qual a principal vantagem de usar containers com Docker em vez de instalar um banco de dados e um servidor web diretamente na sua máquina?
A principal vantagem é o isolamento e a praticidade. O Docker permite executar o banco de dados e o servidor web em ambientes separados, sem instalar e configurar tudo diretamente no sistema operacional. Isso também facilita reproduzir o mesmo ambiente em outros computadores.

### 2. Explique com suas palavras o propósito de um Dockerfile. Por que ele é tão importante para a reprodutibilidade de ambientes?
O Dockerfile é um arquivo que descreve os passos necessários para construir uma imagem Docker. Ele é importante porque permite repetir a mesma configuração sempre que a imagem for construída, tornando o ambiente mais padronizado e reproduzível.

### 3. Em que cenário o Docker Compose se torna essencial? Por que não usar apenas múltiplos comandos docker run?
O Docker Compose é especialmente útil quando uma aplicação depende de vários serviços, como uma aplicação web e um banco de dados. Em vez de executar e configurar vários comandos separadamente, os serviços ficam definidos em um único arquivo e podem ser iniciados juntos.

### 4. Qual a importância dos volumes do Docker? O que aconteceria com os dados se não usássemos um volume?
Os volumes permitem manter os dados mesmo quando o container é removido e recriado. Sem um volume, os dados armazenados dentro do sistema de arquivos do container poderiam ser perdidos quando o container fosse removido.

### 5. Como o uso de containers pode facilitar o trabalho em equipe?
Containers ajudam a padronizar o ambiente de desenvolvimento. Assim, diferentes integrantes podem usar a mesma configuração e reduzir problemas causados por diferenças entre computadores.
