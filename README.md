# 📦 Sistema de Controle de Estoque em Python

## Sobre o projeto

Projeto desenvolvido durante meus estudos em Análise e Desenvolvimento de Sistemas, com o objetivo de praticar lógica de programação e desenvolver um sistema simples de controle de estoque.

## Funcionalidades implementadas

- Salvamento automático dos produtos em arquivo CSV.
- Carregamento dos produtos salvos ao iniciar o sistema.
- Armazenamento do arquivo CSV no Google Drive para manter os dados entre sessões do Google Colab.
- Cálculo do valor total do estoque, considerando a quantidade e o preço unitário de cada produto.
- Alerta de estoque baixo para produtos com 5 unidades ou menos.
- Identificação de produtos sem estoque.
- Exclusão de produtos com confirmação.
- Atualização da quantidade de produtos cadastrados.
- Cadastro de produtos com nome, quantidade e preço.
- Consulta dos produtos cadastrados.
- Menu interativo para utilização do sistema.

## Tecnologias utilizadas

- Python
- Google Colab
- GitHub

## Como executar

1. Baixe o arquivo `.ipynb` disponível neste repositório.
2. Abra o arquivo no Google Colab.
3. Execute a célula que contém o código.
4. Utilize o menu para cadastrar e consultar produtos.

### Como executar no Google Colab

1. Abra o notebook `.ipynb` no Google Colab.
2. Execute a primeira célula para conectar sua conta do Google Drive.
3. Execute a segunda célula para criar a pasta onde o arquivo CSV será armazenado.
4. Execute a terceira célula para iniciar o sistema.
5. Utilize o menu para cadastrar, consultar, atualizar ou excluir produtos.

**Observação:** os produtos são salvos automaticamente no arquivo `estoque.csv`, dentro da pasta `controle-estoque-python` no Google Drive. O arquivo é criado na primeira operação de salvamento.

## Objetivo

Este projeto faz parte da construção do meu portfólio para demonstrar minha evolução nos estudos de programação e desenvolvimento de software.
