# Ciência de Dados

Repositório individual com os exercícios e tarefas da disciplina de Ciência de Dados.

- **Aluno:** Davi Horácio de Souza
- **Matrícula:** 20250059934

## Sumário

Cada pasta de unidade é um projeto: tem o próprio `requirements.txt`, um README com as instruções dos dados e a pasta `data/`. Cada aula fica na sua pasta `Aula_XX`.

### Unidade 1 — Projeto de vendas

- **Aula 01 (24/08) — Ferramentas, Ambiente e Versionamento:** [exercicio_aula01.ipynb](Unidade_01/Aula_01/exercicio_aula01.ipynb)
- **Aula 02 (26/08) — Introdução aos Dados Tabulares:** [exercicio_aula02.ipynb](Unidade_01/Aula_02/exercicio_aula02.ipynb)
- **Aula 03 (05/10) — Análise de Vendas em Python:** [exercicio_aula03.ipynb](Unidade_01/Aula_03/exercicio_aula03.ipynb)
- **Aula 04 (12/10) — Análise de Vendas em R:** [exercicio_aula04.ipynb](Unidade_01/Aula_04/exercicio_aula04.ipynb)

### Unidade 2 — Estatística

- **Aula 05 (19/10) — Estatística Descritiva:** [exercicio_aula05.ipynb](Unidade_02/Aula_05/exercicio_aula05.ipynb)

## Como reproduzir

Escolha a unidade e recrie o ambiente dela (exemplo com a Unidade 1):

```bash
git clone https://github.com/davihoracio/ciencia-de-dados-ufrn.git
cd ciencia-de-dados-ufrn/Unidade_01
uv venv
source .venv/bin/activate
uv pip install -r requirements.txt
```

Os dados não são versionados. Para baixá-los, siga a seção **Dados** do README da unidade ([Unidade 01](Unidade_01/README.md), [Unidade 02](Unidade_02/README.md)).

A Aula 04 usa R (kernel IRkernel). Para rodá-la, instale os pacotes:

```bash
Rscript -e 'install.packages(c("tidyverse", "readxl", "IRkernel")); IRkernel::installspec()'
```
