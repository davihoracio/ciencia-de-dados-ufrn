# Ciência de Dados

Repositório individual com os exercícios e tarefas da disciplina de Ciência de Dados.

- **Aluno:** Davi Horácio de Souza
- **Matrícula:** 20250059934

## Sumário

### Unidade 1

A pasta [`Unidade_01`](Unidade_01) é o projeto de vendas da unidade: contém o `requirements.txt`, o README do projeto e a pasta `data/`, e cada aula fica na sua pasta `Aula_XX`.

- **Aula 01 (24/08) — Ferramentas, Ambiente e Versionamento:** [exercicio_aula01.ipynb](Unidade_01/Aula_01/exercicio_aula01.ipynb)
- **Aula 02 (26/08) — Introdução aos Dados Tabulares:** [exercicio_aula02.ipynb](Unidade_01/Aula_02/exercicio_aula02.ipynb)
- **Aula 03 (05/10) — Análise de Vendas em Python:** [exercicio_aula03.ipynb](Unidade_01/Aula_03/exercicio_aula03.ipynb)
- **Aula 04 (12/10) — Análise de Vendas em R:** [exercicio_aula04.ipynb](Unidade_01/Aula_04/exercicio_aula04.ipynb)

## Como reproduzir

```bash
git clone https://github.com/davihoracio/ciencia-de-dados-ufrn.git
cd ciencia-de-dados-ufrn/Unidade_01
uv venv
source .venv/bin/activate
uv pip install -r requirements.txt
```

A Aula 04 usa R (kernel IRkernel). Para rodá-la, instale os pacotes:

```bash
Rscript -e 'install.packages(c("tidyverse", "readxl", "IRkernel")); IRkernel::installspec()'
```

Os dados não são versionados. Para baixá-los, siga a seção **Dados** do [README da Unidade 01](Unidade_01/README.md).
