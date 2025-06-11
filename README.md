# Análise de Dados de Instalações Solares da empresa Fake Solar

## ☀️ Visão Geral do Projeto
Este projeto tem como objetivo principal analisar um conjunto de dados de instalações de energia solar fotovoltaica no Brasil da empresa Fake Solar. Através de etapas de limpeza, tratamento e análise exploratória de dados (EDA), buscamos identificar padrões, tendências e insights valiosos que possam auxiliar na tomada de decisões estratégicas para empresas do setor de energia solar.

**Problema Abordado:** A falta de compreensão clara sobre o desempenho das instalações, a satisfação do cliente, a eficácia dos canais de aquisição e os fatores que influenciam o valor do serviço dificulta a otimização de operações e o planejamento de crescimento.

**Objetivo:** Gerar insights acionáveis, focando em:

* Identificação de mercados geográficos chave.
* Avaliação da satisfação do cliente por tipo de instalação e origem.
* Análise da rentabilidade e escala dos projetos.
* Detecção de pontos de melhoria com base em avaliações baixas.
* Monitoramento do desempenho ao longo do tempo e da equipe de vendas.

## ⚙️ Como Rodar o Projeto
Para executar este projeto, você precisará ter **Python** instalado, juntamente com algumas bibliotecas comuns de ciência de dados.

**Pré-requisitos**
Certifique-se de ter as seguintes bibliotecas Python instaladas:

`pandas`
`matplotlib`
`seaborn`
`numpy`
Você pode instalá-las usando `pip`:

```
pip install pandas matplotlib seaborn numpy
```

**Estrutura do Projeto**
O projeto é tipicamente executado em um notebook Jupyter (`.ipynb`) e utiliza um arquivo CSV como fonte de dados.

1. Clone o repositório:
       
```
git clone https://github.com/Raybarreto/Analise_EnergiaSolar_BR.git
cd Energia_Solar_BR
```

2. Abra o Notebook Jupyter:

```
jupyter notebook
```

Isso abrirá seu navegador web com o ambiente Jupyter.

3. **Navegue e Abra o Notebook:** Encontre e clique no arquivo .ipynb do seu projeto.
4. **Execute as Células:** Execute as células do notebook sequencialmente. O notebook contém todos os passos, desde a importação e limpeza dos dados até a geração dos gráficos e o relatório final.

## 🌐 Fonte de Dados
Os dados utilizados são carregados diretamente de um arquivo CSV hospedado no GitHub:

```
https://raw.githubusercontent.com/Raybarreto/Analise_EnergiaSolar_BR/refs/heads/main/dados_instalacoes_solares%20_2000.csv
```

## 📊 Análises e Resultados Principais
As análises exploratórias de dados revelaram insights importantes:

* **Mercados Geográficos:** Identificação **das cidades e estados com maior concentração de instalações**, indicando os principais mercados de atuação e potenciais áreas para expansão.
* **Satisfação do Cliente:** Avaliação da satisfação média por tipo de instalação (Residencial, Comercial, Industrial) e por origem do cliente (Boca a Boca, Marketing Digital, Indicação, etc.), revelando quais segmentos ou canais geram maior satisfação.
* **Performance Financeira e de Sistema:** Comparação do valor médio do serviço, **tamanho médio do sistema (kWp) e custo por kWp** para cada tipo de instalação, fornecendo insights sobre a rentabilidade e eficiência dos projetos.
* **Pontos de Melhoria:** Análise dos **tipos de pagamento associados a avaliações de clientes baixas** (1 ou 2 estrelas), o que pode indicar áreas para revisão de processos ou comunicação.
* **Tendências Temporais:** Visualização do **número de instalações ao longo do tempo**, permitindo identificar sazonalidade e tendências de crescimento no mercado.
* **Desempenho da Equipe:** Destaque dos **vendedores com o maior número de instalações**, auxiliando na identificação de talentos e na replicação de melhores práticas.
Todos esses insights são suportados por visualizações gráficas claras e detalhadas ao longo do notebook.


## ✨ Conclusões e Recomendações
O relatório final, presente no próprio notebook, detalha as conclusões extraídas das análises e oferece recomendações estratégicas para a empresa, tais como:

* Otimização de estratégias de marketing e vendas focadas em regiões e canais de alta performance.
* Melhoria contínua da satisfação do cliente, com foco em tipos de instalação e canais que mostram avaliações mais baixas.
* Revisão de processos financeiros e de comunicação para tipos de pagamento problemáticos.
* Programas de treinamento e incentivo para a equipe de vendas.

## 🧠 Requisitos para Uso e Expansão
* Python básico/intermediário
* Conhecimentos de EDA
* Familiaridade com bibliotecas: `pandas, numpy, seaborn, matplotlib`

## 📬 Contato
Para dúvidas ou sugestões:

- Raylaine Barreto
- E-mail: raylainebarreto@outlook.com
- [LinkedIn](https://www.linkedin.com/in/raylaine-barreto)
