# Aprendizado de máquina aplicado à biologia

Notebook do workshop de aprendizado de máquina aplicado à biologia, com exemplos de regressão, classificação e métodos não supervisionados em dados biológicos.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lucasofalonso/workshop-ml-biologia/blob/main/workshop_ml_biologia.ipynb)

## Conteúdo

| Parte | Tema | *Dataset* | Pergunta central |
|---|---|---|---|
| 1 | Regressão linear | *Diabetes* (442 pacientes) | É possível prever a progressão do diabetes um ano após a avaliação inicial? |
| 2 | Classificação | *Breast Cancer Wisconsin* (569 nódulos) | As medidas dos núcleos celulares distinguem nódulos benignos de malignos? |
| 3 | Métodos não supervisionados | *Breast Cancer Wisconsin* (569 nódulos, sem o diagnóstico) | Sem usar o diagnóstico, a estrutura das 30 medidas revela grupos de nódulos? |

## Como usar no Google Colab

1. Clique no botão **Open in Colab** acima (é preciso ter uma conta Google).
2. Vá em **Arquivo → Salvar uma cópia no Drive** para guardar suas alterações.
3. Execute as células de cima para baixo, ou use **Ambiente de execução → Executar tudo**.

Se o Colab desconectar por inatividade, basta executar tudo novamente.

## Como usar localmente

O ambiente é gerenciado com o [uv](https://docs.astral.sh/uv/):

```bash
git clone git@github.com:lucasofalonso/workshop-ml-biologia.git
cd workshop-ml-biologia
uv sync
```

Depois, abra `workshop_ml_biologia.ipynb` no VS Code ou no Jupyter, com o ambiente `.venv` como *kernel*.

## Dados

- **Partes 1 e 2:** *datasets* incluídos no Scikit-Learn (`load_diabetes` e `load_breast_cancer`).
- **Parte 3:** métodos não supervisionados com o *Breast Cancer Wisconsin*, o mesmo *dataset* da Parte 2.