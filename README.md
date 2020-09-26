
# Sprint 0

# BRIEFING 
### CLIENTE
Nome da empresa: Iacit (filiais)

Produto: Entregas

Responsável da empresa: Thomas Godoy

Data: 20/09/2020

### DADOS DA EMPRESA

Core Business: Fábrica de software.

Outros produtos: CNS / ATM, Telemetria, Meteorologia, Defesa e segurança pública.
Pontos positivos da empresa: Versatilidade dos produtos, incentiva a inovação e procura o desenvolvimento tecnológico.

O que diferencia esta empresa da concorrência?

A busca pela inovação e qualificação de novos profissionais para o mercado de trabalho.

### PÚBLICO-ALVO
Idade: -

Sexo: Masculino e feminino

Tipo: Empresas

Região: São Paulo, Brasil.

### OBJETIVOS DO PROJETO
Criação de um sistema de gerenciamento de entregas, onde será possível que as filiais tenham controle de que seus funcionários estão cumprindo todas as regras e normas imposta sobre eles, assim como melhorar possíveis adversidades que possam estar ocorrendo com as entregas.

### PRAZOS PARA A REALIZAÇÃO DO TRABALHO
O trabalho foi dividido em três sprints de três semanas, assim tendo uma
duração de 3 meses e prazo máximo definido para o dia 29 de novembro.
### Outras informações
A empresa oferece diversos produtos, porém o projeto trabalha em cima da
fábrica de software, assim desenvolvendo um software para as filiais da
empresa, em busca de solucionar o problema nas entregas feitas por
caminhões das filiais.


# DER

![Story User](https://cdn.discordapp.com/attachments/255045329081073684/759419030456500244/56.jpg?raw=true)


# Protótipo -> Figma:

## https://www.figma.com/proto/UVYWQDmu3b7KXbuY3Fjq3I/Untitled?node-id=0%3A1&scaling=min-zoom


## Backlog


### US01: Como Administrador quero ser capaz de cadastrar os motoristas da minha empresa então poderei gerencia-los

 - Criar tela para o cadastro de um novo motorista.
 - Criar uma tela mostrando todos os motoristas cadastrados.
 
Critério 1: Adicionar um motorista. Ao adicionar um motorita conferir se o mesmo esta presente no Banco de Dados.

Critério 2: Mostras todos os motoristas em uma tabela com Scroll.

### US02: Como Administrador quero ser capaz de buscar por um motorista especifico da minha empresa então poderei gerencia-los.
- Na tela mostrando todos os motoristas cadastrados criar método de pesquisa por nome, CPF e/ou ID.
Dependencias: US01-> - Criar uma tela mostrando todos os motoristas cadastrados.

Critério 1: Perquisar por nome, CPF e/ou ID.Conferir se o resultado esta correto(quando pesquisado CPF ou ID mostrar somente um resultado).
 
### US03: Como Administrador quero ser capaz de cadastrar os caminhões da minha empresa então poderei gerencia-los

 - Criar tela para o cadastro de um novo caminhão.
 - Criar uma tela mostrando todos os caminhões cadastrados.
 
 Critério 1: Adicionar um caminhão. Ao adicionar um caminhão conferir se o mesmo esta presente no Banco de Dados.
 
Critério 2: Mostras todos os caminhões em uma tabela com Scroll.

### US04: Como Administrador quero ser capaz de buscar por um caminhão especifico da minha empresa então poderei gerencia-los

 - Na tela mostrando todos os caminhões cadastrados criar método de pesquisa por Placa, Modelo e/ou ID.
 
Dependencias: US03-> - Criar uma tela mostrando todos os motoristas cadastrados.

Critério 1: Perquisar por Placa, Modelo e/ou ID.Conferir se o resultado esta correto(quando pesquisado Placa ou ID mostrar somente um resultado).


### US05: Como Administrador quero ser capaz de ver todas as informações de um motorista da minha empresa então poderei gerencia-lo.

 -  Criar Tela do Motorista com suas informações e entregas.
 
   Critério 1: Mostras todas as informações do motorista.
   
### US06: Como Administrador quero ser capaz de ver todas as informações de um caminhão da minha empresa então poderei gerencia-lo.

 -  Criar Tela do Caminhão com suas informações e entregas.
 
   Critério 1: Mostras todas as informações do Caminhão.
   
   
### US07: Como Administrador quero ser capaz de criar uma entrega relacionando um motorista e um caminhão então poderei gerencia-los.

 -  Criar Tela de Cadastro de entregas.
 
   Critério 1: adicionar um nova entrega no sistema. Conferir se no banco de dados as informações estão corretas.
   

### US08: Como Adminstrador quero ser capaz de reconfigurar a escala do motorista(turno, carga horária diária, dias de trabalho e folga) então posso deixa-lo da melhor forma possivel no momento atual

 - Na tela do motorista(US05) desenvolver metodo de alterar  a escala do motorista.
 
 Dependencias: US05-> - Criar Tela do Motorista com suas informações e entregas.

Critério 1: Poder salvar e alterar a escala de trabalho do motorista. Atualizar a pagina para ver se a tal mudança foi feita.

### US09: Como Adminstrador quero ser capaz de verificar os problemas nas entregas então estarei ciente do que aconteceu na entrega

 - Criar tela listando as entregas com problemas

Critério 1: listar as entregas com problemas.
Observações: Utilizar icones intuitivos.

### US10: Como Adminstrador quero ser capaz de verificar a localização do motorista então estarei sabendo o progresso da entrega.

- Na tela do motorista(US05) mostrar ultima localização do motorista.

Dependencias: US05-> - Criar Tela do Motorista com suas informações e entregas.

Critério 1: Mostrar ultima localização do motorista. Conferir se os dados estão corretos.










