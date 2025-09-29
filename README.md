# 🤖 Estudo de IA Simbólica: Motores de Inferência com Backward Chaining

Este repositório educacional (`estudo-IA-simbolica`) é um estudo aprofundado sobre a implementação de **Motores de Inferência** que utilizam a estratégia **Backward Chaining** (Encadeamento para Trás) dentro do domínio da Inteligência Artificial Simbólica (Symbolic AI).

O foco principal é o desenvolvimento de um **sistema especialista** simples, projetado para **diagnóstico médico veterinário (pets)** baseado em regras. O projeto demonstra a evolução do design de software, apresentando duas implementações distintas do mesmo sistema de inferência.

---

## 🎯 Implementações Apresentadas

O repositório contém duas abordagens paralelas para a construção de um motor de inferência, ambas em Python, mas com arquiteturas diferentes:

| Aspecto | Implementação Simples | Implementação Avançada |
| :--- | :--- | :--- |
| **Arquivo Principal** | `IA_simbolica.ipynb` | `IA_simbolica_Backward_Chaining.ipynb` |
| **Arquitetura** | **Procedural** | **Orientada a Objetos (OO)** |
| **Lógica Suportada** | Apenas condições **AND** | Condições **AND** e **OR** |
| **Motor de Inferência** | Função `motor_de_inferencia()` | Classe `MotorDeInferencia` |
| **Gerenciamento de Fatos** | Dicionário global | Classe `BaseDeFatos` |

---

## ⚙️ Componentes Principais do Sistema

Ambas as implementações compartilham os conceitos fundamentais de um sistema de IA Simbólica:

1.  **Base de Conhecimento (Knowledge Base):** Contém os fatos conhecidos e as **regras lógicas** (o conhecimento do domínio).
2.  **Base de Fatos (Fact Base):** Armazena o conhecimento atualmente inferido ou fornecido pelo usuário (os sintomas).
3.  **Motor de Inferência (Inference Engine):** O algoritmo que aplica a lógica de *Backward Chaining* para deduzir novos fatos (diagnósticos) a partir das regras.

---

## 💻 Tecnologias e Execução

* **Linguagem:** Python
* **Ambiente:** Jupyter Notebook (`.ipynb`)

### Clonagem do Repositório

```bash
# Clone o repositório
git clone [https://github.com/EvelyParanhos/estudo-IA-simbolica.git](https://github.com/EvelyParanhos/estudo-IA-simbolica.git)

# Acesse o diretório
cd estudo-IA-simbolica
````

### Execução dos Notebooks

Para rodar o projeto, abra o ambiente **Jupyter** (Jupyter Lab ou Notebook) no diretório clonado:

```bash
jupyter notebook
# ou
jupyter lab
```

Execute os notebooks na seguinte ordem para acompanhar a evolução do design:

1.  `IA_simbolica.ipynb` (Estudo da implementação **procedural simples**)
2.  `IA_simbolica_Backward_Chaining.ipynb` (Estudo da implementação **orientada a objetos avançada**)

-----

## 📌 Valor Educacional

Este projeto serve como uma excelente demonstração da **evolução do design de software** aplicado à IA:

  * A **Implementação Simples** fornece uma introdução direta e acessível aos conceitos de *Backward Chaining*.
  * A **Implementação Avançada** ilustra como padrões de arquitetura profissional (como a Orientação a Objetos e a separação de preocupações) tornam sistemas baseados em regras mais robustos, manuteníveis e extensíveis, suportando lógicas complexas (**AND/OR**).

-----

## 🤝 Contribuições

Contribuições são bem-vindas\! Sinta-se à vontade para propor melhorias, correções ou novos exemplos abrindo uma **Issue** ou enviando um **Pull Request**.

-----

## 📄 Acesse a documentação no DeepWiki

[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/EvelyParanhos/estudo-IA-simbolica)

-----

## 📫 Como me encontrar

- **LinkedIn:** [www.linkedin.com/in/evely-paranhos-souza]
- **E-mail:** [evelyparanhos05@gmail.com]

