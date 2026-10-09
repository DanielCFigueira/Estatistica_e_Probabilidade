# Estatística e Probabilidade para IA e Dados

Meu caderno digital de estudos: cada notebook é uma **aula completa**, que parte da intuição e da teoria formal, passa pela implementação em Python e termina em aplicações reais de **Análise de Dados, Ciência de Dados, Machine Learning e Deep Learning**.

> Objetivo: mostrar que sei a teoria com profundidade **e** sei aplicá-la na prática.

## Como cada aula é construída

1. **Gancho**: um problema real que motiva o conceito
2. **Intuição**: a ideia sem fórmulas
3. **Formalização**: definição matemática (LaTeX)
4. **Implementação do zero**: NumPy puro, conferido com a biblioteca
5. **Visualização**: gráficos que mostram o comportamento do conceito
6. **Armadilhas**: quando o conceito engana
7. **Aplicação em IA e Dados**: onde ele aparece em pipelines e modelos
8. **Exercício**: para fixar

## Mapa do curso

| Módulo | Tópico | Status |
|---|---|---|
| 01 · Estatística Descritiva | Média aritmética e ponderada | 🔄 em reformulação |
| | Média truncada | 🔄 em reformulação |
| | Mediana | 🔄 em reformulação |
| | Moda | 🔄 em reformulação |
| | Variância e desvio padrão | 🔄 em reformulação |
| | Amplitude, quartis e IQR | 🔜 próximo |
| | Assimetria e curtose | 🔜 |
| 02 · Probabilidade | Fundamentos e Teorema de Bayes | 🔜 |
| | Distribuições discretas e contínuas | 🔜 |
| 03 · Estatística Inferencial | Intervalos de confiança e testes de hipótese | 🔜 |

✅ concluído · 🔄 em reformulação · 🔜 planejado

## Dataset

Todos os notebooks usam `data/dataset_estatistica.csv`, um dataset **sintético** de 200 clientes de e-commerce, gerado de forma reprodutível (`seed=42`) por `data/gerador_de_dados.ipynb`. Ele inclui assimetria, outliers e valores ausentes de propósito, para tornar as aulas realistas.

## Como rodar

```bash
git clone https://github.com/DanielCFigueira/Estatistica_e_Probabilidade.git
cd Estatistica_e_Probabilidade

python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt

jupyter lab
```

## Ferramentas

Python 3.11 · NumPy · Pandas · SciPy · Matplotlib · Seaborn · scikit-learn · Jupyter

## Autor

**Daniel Max Magnus** · Sistemas de Informação (UFPA, Campus Cametá) · Pesquisador no LASEDI
