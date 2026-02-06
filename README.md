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
- Análises por: 
    - Unidade Federativa (UF)
    - Período temporal
    - Bandeira dos postos

---

## Metodologia

O projeto segue práticas consolidadas de Business Intelligence e análise de dados:
- Modelagem dimensional (tabelas fato e dimensões)
- Processo de ETL estruturado
- Separação clara entre dados brutos e tratados
- Cálculo padronizado e consistente de métricas
- Organização voltada à escalabilidade e reuso

---

## Principais Conclusões

### Combustíveis (Visão Geral)

- Os dados analisados correspondem ao **segundo semestre de 2024**, totalizando **421.000 registros**, abrangendo:
    - Todos os estados brasileiros
    - Seis tipos de combustíveis
    - 45 bandeiras de postos
    - 7.454 revendas
- Considerando **todos os combustíveis**, a bandeira **WATT** apresentou o **menor preço médio de venda** (R$ 4,95).
    - **Diesel e Diesel S10**: menor média pela bandeira **PELIKANO** (R$ 5,59 e R$ 5,71).
    - **Etanol, Gasolina e Gasolina Aditivada**: menores médias registradas pela bandeira **ROYAL FIC** (R$ 3,65; R$ 5,67; R$ 5,67).
    - **GNV**: menor média registrada pela bandeira **LARCO** (R$ 4,23).
- Na análise mensal do semestre, **todos os combustíveis apresentaram aumento médio de 1,51%**. Apesar do GNV também registrar alta no período, observou-se recuo nos preços a partir de agosto, mês marcado por uma elevação expressiva.
| Combustível | Julho | Dezembro | Variação |
|------------|-------|----------|----------|
| Diesel | R$ 5,99 | R$ 6,08 | 1,50% |
| Diesel S10 | R$ 6,05 | R$ 6,14 | 1,48% |
| Etanol | R$ 4,22 | R$ 4,27 | 1,18% |
| Gasolina | R$ 6,04 | R$ 6,14 | 1,66% |
| Gasolina Aditivada | R$ 6,23 | R$ 6,34 | 1,77% |
| GNV | R$ 4,72 | R$ 4,79 | 1,48% |
- Ao dividir o mês em duas partes iguais, observou-se que **os preços tendem a subir com maior frequência no final do mês**.

### Gasolina

- Em dezembro (último mês da base), o **maior preço médio da gasolina foi registrado no estado do Acre (AC)**, que manteve essa posição ao longo de todo o semestre.
- O **Amapá (AP)** apresentou o menor preço médio, alternando com **São Paulo (SP)** ao longo dos meses.
- No período analisado, **4.178 revendas praticaram preços acima da média nacional**.

### Diesel

- **São Paulo (SP)** registrou a **maior diferença percentual de preços**, tanto na análise semestral (49,15%) quanto mensal, com pico em julho (47,83%).
- Com exceção do mês de outubro, **Roraima (RR)** apresentou a **menor variação percentual**, tanto semestral (10,52%) quanto mensal, com menor diferença entre julho e setembro (1,88%).
---

## Contexto Acadêmico

Este projeto foi desenvolvido no contexto do curso **Power BI: analisando dados de forma inteligente**, oferecido pela Alura, com foco em problemas reais de negócio e aplicação prática de ferramentas amplamente utilizadas no mercado.

🔗 Certificação:[Power BI: analisando dados de forma inteligente](https://cursos.alura.com.br/formalCertificate/10f0032a-a76d-4449-9159-da67356e3bd7)

---

## Contexto Acadêmico

- Abordagem orientada a problemas reais de negócio
- Ênfase em modelagem de dados e métricas, não apenas visualização
- Organização clara e escalável
- Documentação focada em raciocínio analítico

---

## Autor

**Albert Richard M. Lopes**  
Engenheiro de Computação | Desenvolvedor Android | Analista de Dados em transição
[Linkedin](https://linkedin.com/in/albert-richard-73983723)

---


