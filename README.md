# 📊 Análise de Vendas para E-Commerce com Python

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge)

---

## 📌 Sobre o Projeto

Este projeto consiste em uma análise exploratória e diagnóstica de dados de vendas de uma operação de **E-commerce**, desenvolvida em **Python** com foco na tomada de decisões estratégicas orientadas por dados (*Data-Driven Decision Making*).

A partir de registros transacionais de pedidos, o projeto estrutura e responde a **quatro perguntas fundamentais de negócio**, eliminando decisões baseadas em intuição e fornecendo direcionamentos claros para as áreas de Gestão de Produtos, Marketing, Finanças e Logística.

---

## 🎯 Perguntas de Negócio & Objetivos

| Pergunta | Objetivo Estratégico | Métrica Analisada |
| :--- | :--- | :--- |
| **1. O que vender?** | Identificar produtos campeões e itens de baixa saída para otimizar o estoque e evitar ruptura ou custos de armazenagem. | Volume total de unidades vendidas por produto. |
| **2. Onde focar?** | Compreender a representatividade de cada categoria na receita global para guiar campanhas e parcerias. | Faturamento total e participação percentual (%) por categoria. |
| **3. Quando agir?** | Mapear o comportamento temporal das vendas para antecipar picos de demanda e planejar ações promocionais em períodos de baixa. | Curva de faturamento mensal e análise de sazonalidade. |
| **4. Para onde expandir?** | Mapear a concentração geográfica dos clientes para priorizar investimentos logísticos e centros de distribuição. | Receita total e volume de pedidos por Estado (UF). |

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **Linguagem:** [Python 3.x](https://www.python.org/)
* **Ambiente de Desenvolvimento:** [Jupyter Notebook](https://jupyter.org/) via [Anaconda Distribution](https://www.anaconda.com/)
* **Manipulação e Análise de Dados:** [Pandas](https://pandas.pydata.org/) e [NumPy](https://numpy.org/)
* **Visualização de Dados:** [Matplotlib](https://matplotlib.org/)

---

## 📂 Estrutura do Repositório

```text
├── mini_projeto_1_vendas.ipynb   # Jupyter Notebook com a análise completa e gráficos
├── README.md                      # Documentação detalhada do projeto
└── .gitignore                     # Arquivos e diretórios ignorados pelo Git
```

---

## 📈 Resumo dos Resultados e Insights Obtidos

1. **Gestão de Estoque:** Produtos com maior volume de saída exigem políticas de reposição contínua com estoque de segurança reforçado, enquanto itens na cauda inferior devem passar por ações promocionais de desova para liberação de capital de giro.
2. **Mix de Categorias:** As categorias de maior valor agregado concentram a maior parte da receita bruta, justificando a alocação prioritária do orçamento de marketing digital e aquisição de clientes (CAC).
3. **Planejamento Sazonal:** A distribuição temporal das vendas permite planejar estoques com antecedência para meses de pico e estruturar promoções táticas para amortecer períodos de desaceleração.
4. **Estratégia Regional:** A concentração de faturamento em polos específicos orienta negociações de fretes corporativos e parcerias logísticas para redução de prazos de entrega (*lead time*).

---

## 🚀 Como Executar o Projeto Localmente

### Pré-requisitos

* Ter o **Python 3.x** e o **Anaconda** instalados (compatível com Windows 11, macOS e Linux).
* Git instalado em sua máquina.

### Passo a Passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/analise-vendas-ecommerce-python.git
   ```

2. **Acesse o diretório do projeto:**
   ```bash
   cd analise-vendas-ecommerce-python
   ```

3. **Inicie o Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Abra o arquivo:**
   No navegador que abrir automaticamente, clique em `mini_projeto_1_vendas.ipynb` e execute as células sequencialmente (`Shift + Enter` ou vá em **Kernel > Restart & Run All**).

---

## 📝 Licença

Este projeto é disponibilizado para fins educacionais e de estudo. Sinta-se à vontade para utilizá-lo como base para suas próprias análises de dados.
