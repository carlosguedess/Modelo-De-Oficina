# Modelo-De-Oficina
Diagrama de uma ordem de serviço de uma oficiina
Sistema de Oficina Mecânica – Modelo Conceitual
Descrição

Este projeto apresenta o modelo conceitual (Esquema Entidade-Relacionamento) de um sistema de controle e gerenciamento de ordens de serviço para uma oficina mecânica.

O sistema tem como objetivo organizar informações sobre clientes, veículos, equipes de mecânicos, serviços executados, peças utilizadas e valores envolvidos em cada ordem de serviço.

Objetivo

Modelar, de forma conceitual, o funcionamento de uma oficina mecânica, permitindo:

Controle das ordens de serviço (OS)

Registro de clientes e veículos

Associação de equipes e mecânicos

Cálculo de valores de serviços e peças

Acompanhamento do status e prazos de execução

Entidades Principais

Cliente

Veículo

Ordem de Serviço (OS)

Equipe

Mecânico

Serviço

Peça

Mão de Obra

Principais Relacionamentos

Um cliente pode possuir vários veículos

Um veículo pode gerar várias ordens de serviço

Uma equipe é responsável por atender veículos

Uma equipe é composta por vários mecânicos

Uma ordem de serviço pode conter vários serviços e utilizar várias peças

Cada serviço consulta uma tabela de referência de mão de obra

Informações da Ordem de Serviço

Cada ordem de serviço possui:

Número da OS

Data de emissão

Data de conclusão

Status

Valor total


O diagrama ER foi construído com base em uma narrativa fornecida.
