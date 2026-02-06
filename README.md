# EcoFuel — Estudo de Caso em Business Intelligence

## Visão Geral

O **EcoFuel** é um projeto de *Business Intelligence* desenvolvido como **estudo de caso para análise de preços de combustíveis no Brasil**, com foco em **modelagem de dados analíticos, definição de KPIs e geração de insights voltados à tomada de decisão**.

O projeto simula um cenário real de análise governamental e corporativa, utilizando dados nacionais de preços coletados em milhares de postos de combustíveis.

---

## Objetivo do Projeto

Gerar **insights estratégicos** para o setor público e privado a partir de uma base nacional de preços de combustíveis, respondendo a perguntas de negócio como:

### Combustíveis (Visão Geral)
- Qual bandeira apresenta o **menor preço médio** por tipo de combustível?
- Como os preços se comportam **ao longo do tempo**, por tipo de combustível?
- Em quais períodos do mês os preços tendem a ser **mais elevados**?
- Quantas **amostras de preços** foram coletadas no período analisado?

### Gasolina
- Qual foi o **preço médio da gasolina comum por estado** no último mês da base?
- Quantas revendas praticam preços **acima da média nacional**?
- Qual estado apresenta o **maior preço médio** da gasolina comum?

### Diesel
- Qual a **diferença percentual** entre o maior e o menor preço praticado de diesel em cada estado?

---

## Estrutura do Projeto

```
EcoFuelLog/
├── Dados brutos/
│   └── Preços semestrais - AUTOMOTIVOS_2024.02.xlsx
├── PowerBI/
│   └── (arquivos do relatório e modelo)
├── Utils/
│   └── bg-powerbi.png
└── README.md
```

---

## KPIs e Indicadores Analisados

- Preço **mínimo**, **médio** e **máximo**
- Diferença percentual de preços
- Volume de amostragem
- Análises por Unidade Federativa (UF), período temporal e bandeira

---

## Metodologia

- Modelagem dimensional (tabelas fato e dimensões)
- Processo de ETL estruturado
- Separação clara entre dados brutos e tratados
- Cálculo padronizado e consistente de métricas
- Organização voltada à escalabilidade e reuso

---

## Principais Conclusões

### Combustíveis (Visão Geral)

- Base do **2º semestre de 2024** com **421.000 registros**, abrangendo todos os estados, seis combustíveis, 45 bandeiras e 7.454 revendas.

- Menores preços médios:
  - Geral: **WATT** (R$ 4,95)
  - Diesel / Diesel S10: **PELIKANO** (R$ 5,59 / R$ 5,71)
  - Etanol, Gasolina e Gasolina Aditivada: **ROYAL FIC**
  - GNV: **LARCO** (R$ 4,23)

- Todos os combustíveis apresentaram **alta média de 1,51%** no período.

| Combustível | Julho | Dezembro | Variação |
|------------|-------|----------|----------|
| Diesel | R$ 5,99 | R$ 6,08 | 1,50% |
| Diesel S10 | R$ 6,05 | R$ 6,14 | 1,48% |
| Etanol | R$ 4,22 | R$ 4,27 | 1,18% |
| Gasolina | R$ 6,04 | R$ 6,14 | 1,66% |
| Gasolina Aditivada | R$ 6,23 | R$ 6,34 | 1,77% |
| GNV | R$ 4,72 | R$ 4,79 | 1,48% |

---

## Autor

**Albert Richard M. Lopes**  
Engenheiro de Computação | Desenvolvedor Android | Analista de Dados em transição

---
