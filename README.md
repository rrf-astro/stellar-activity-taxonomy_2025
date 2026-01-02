# Stellar Activity Taxonomy

Este repositório contém os dados e o código-fonte (pipeline de análise) utilizados no estudo sobre a taxonomia da atividade estelar. O objetivo principal deste projeto é analisar e classificar diferentes tipos de atividades estelares com base em índices e parâmetros físicos.

## 📂 Estrutura do Repositório

O repositório está organizado da seguinte forma:

* **`principal.ipynb`**: O notebook principal contendo todo o fluxo de análise de dados. Ele inclui:
    * Carregamento e tratamento dos dados.
    * Cálculo de estatísticas e correlações.
    * Geração dos gráficos e visualizações apresentados no estudo.
* **`table2.csv`, `table3.csv`, `table4.csv`**: Arquivos de dados em formato CSV contendo os parâmetros estelares e índices de atividade. Estes arquivos correspondem às tabelas apresentadas na publicação/trabalho original.
* **`figures/`**: Diretório destinado ao armazenamento das figuras geradas pelo notebook.

## 🚀 Como Utilizar

Para reproduzir a análise ou explorar os dados, siga os passos abaixo:

### Pré-requisitos

Você precisará de **Python 3** e do **Jupyter Notebook** instalados. As principais bibliotecas utilizadas na análise (baseado em análises típicas de astrofísica) provavelmente incluem:

* `numpy`
* `pandas`
* `matplotlib`
* `scipy`
* `seaborn` (se aplicável para visualização)

### Instalação e Execução

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/rrf-astro/stellar-activity-taxonomy_2025.git](https://github.com/rrf-astro/stellar-activity-taxonomy_2025.git)
    cd stellar-activity-taxonomy
    ```

2.  Instale as dependências (caso tenha um arquivo requirements, senão instale manualmente):
    ```bash
    pip install notebook pandas matplotlib numpy scipy
    ```

3.  Execute o Jupyter Notebook:
    ```bash
    jupyter notebook principal.ipynb
    ```

4.  Execute as células sequencialmente para reproduzir a análise.

## 📊 Sobre os Dados

As tabelas fornecidas (`tableX.csv`) contêm dados processados essenciais para a taxonomia proposta. Certifique-se de que elas estejam no mesmo diretório do notebook para garantir o carregamento correto.

## 📝 Citação

Se você utilizar estes dados ou código em sua pesquisa, por favor, cite o trabalho original:

> *[Insira aqui a referência do seu artigo ou tese quando estiver disponível]*
> *Exemplo: Silva, R. R. et al. (2025). Stellar Activity Taxonomy...*

## 📧 Contato

Para dúvidas ou colaborações, entre em contato através do perfil no GitHub ou pelo e-mail institucional.

---
**Desenvolvido por [rrf-astro](https://github.com/rrf-astro)**
