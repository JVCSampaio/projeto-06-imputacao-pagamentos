# Projeto 6 — Imputação de Valores Ausentes (PAY_1)

Comparação de estratégias de imputação para PAY_1 ausente (média, aleatória e random forest) com validação cruzada e varredura de threshold de classificação. Melhor: imputação pela média, AUC 0.7729.

**Livro:** *Projetos de Ciência de Dados com Python* — Stephen Klosterman (Novatec Editora, 2020)

## Conteúdo

- `projeto.ipynb` — notebook completo, já executado (com todas as saídas e gráficos)
- `Data/` — datasets usados (UCI Credit Card: 5.333 registros, 23 variáveis)

## Como executar

```bash
pip install pandas scikit-learn numpy matplotlib seaborn xlrd
jupyter notebook projeto.ipynb
```

Para as visualizações de árvores (Projeto 5), instale o binário Graphviz (`dot`).
