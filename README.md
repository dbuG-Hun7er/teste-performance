# ⚡ Performance Testing — Apache JMeter

**Projeto prático de testes de performance utilizando Apache JMeter, simulação de usuários virtuais e massa de dados externa.**

## 📌 Sobre o projeto

Este repositório reúne um exercício prático de Teste de Performance desenvolvido durante o curso de Engenharia da Qualidade de Software da EBAC.

O objetivo é utilizar o Apache JMeter para simular acessos simultâneos a um endpoint, aplicar uma configuração de carga e registrar os resultados obtidos durante a execução.

O exercício também contempla a utilização de massa de dados em arquivo CSV e o armazenamento dos arquivos relacionados aos testes e suas evidências.

## 🎯 Objetivos

- Compreender os fundamentos de Performance Testing.
- Criar planos de teste utilizando Apache JMeter.
- Simular múltiplos usuários virtuais.
- Configurar parâmetros de carga e tempo de execução.
- Utilizar arquivos CSV como fonte de dados.
- Executar testes de performance.
- Salvar resultados e registrar evidências.

## 🛠️ Tecnologias e ferramentas

| Tecnologia | Aplicação |
|---|---|
| Apache JMeter | Execução de testes de performance |
| CSV | Armazenamento de massa de dados |
| Performance Testing | Avaliação do comportamento sob carga |

## ⚙️ Configuração do teste

Parâmetros definidos no exercício:

| Parâmetro | Configuração |
|---|---|
| Usuários virtuais | 20 |
| Ramp-up Period | 60 segundos |
| Duração | 3 minutos |
| Massa de dados | Arquivo CSV com 10 palavras |
| Ferramenta | Apache JMeter |

## 📂 Estrutura do repositório

```text
teste-performance/
│
├── massa_dados/
│   └── Arquivos de massa de dados
│
├── tests/
│   └── Arquivos relacionados aos testes
│
├── .gitattributes
└── README.md
```

## 🔍 Conceitos trabalhados

- Performance Testing
- Load Testing
- Virtual Users
- Ramp-up Period
- Test Data Management
- CSV Data Set
- Test Execution
- Result Analysis

## 📊 Resultados e evidências

O exercício tem como proposta executar os testes de performance, salvar os resultados e registrar evidências das execuções.

A análise dos resultados permite estudar o comportamento da aplicação durante a simulação de acessos simultâneos.

## 🚀 Objetivo de aprendizado

Este projeto faz parte da minha evolução profissional em Quality Assurance, ampliando meus conhecimentos para além dos testes funcionais e da automação tradicional.

A prática com Apache JMeter contribui para desenvolver competências em testes de carga, simulação de usuários e análise de comportamento de aplicações sob diferentes condições de utilização.

---

**Autor:** Lucas Ferreira de Lima

**Formação:** Engenharia da Qualidade de Software — EBAC

**Área:** Quality Assurance | Performance Testing | Apache JMeter

*Measure performance. Identify bottlenecks. Improve quality.*
