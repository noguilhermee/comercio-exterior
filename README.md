# Análise de Comércio Exterior - NEPE/UFSJ

Este projeto contém ferramentas e scripts em Python voltados para o processamento, análise e visualização de dados de comércio exterior, desenvolvidos para o **Núcleo de Ensino, Pesquisa e Extensão em Economia (NEPE)** da Universidade Federal de São João del-Rei (UFSJ).

## 📌 Descritivo
O objetivo principal é automatizar a geração de indicadores de exportação (EXP) e importação (IMP), permitindo a análise temporal e geográfica dos fluxos comerciais. Os scripts processam bases de dados brutas e geram visualizações prontas para relatórios e artigos científicos.

## 📂 Estrutura do Repositório

* **`app/`**: Contém os Jupyter Notebooks (`.ipynb`) responsáveis pela lógica de análise.
    * `2022-1.ipynb`, `2022-2.ipynb`, etc.: Análises fechadas por períodos específicos.
    * `countries.ipynb`: Script para tratamento e padronização de nomes de países.
* **`data/`**: Armazenamento de bases de dados.
    * `bce.xlsx`: Base principal de comércio exterior.
    * `countries.xlsx`: Tabela de referência para padronização.
    * `old/`: Arquivos legados e versões anteriores das bases.
* **`images/`**: Gráficos e visualizações geradas automaticamente pelos scripts (formatos `.png`).
    * Exemplo: Mapas e gráficos de barras de exportação/importação de 2022.

## 🛠️ Tecnologias Utilizadas

* **Python 3.x**
* **Pandas**: Manipulação e tratamento de dados.
* **Matplotlib/Seaborn**: Geração de visualizações estáticas.
* **Jupyter Notebook**: Ambiente de desenvolvimento e documentação das análises.