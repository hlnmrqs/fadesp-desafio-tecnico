# 📊 Desafio Técnico – Power BI, Python e SQL

## 🧾 Introdução

Este repositório apresenta a minha solução para o Desafio Técnico de Analista de BI proposto pela FADESP, abrangendo as tarefas das Etapas 1, 2 e 3. O desafio original propunha duas trilhas (Análise e Visualização, Engenharia de Dados) com três etapas. 

O desafio original visava avaliar habilidades em Power BI, Python e SQL através de três etapas distintas. As Etapas 1 e 2 focavam em análise e visualização com Power BI, enquanto a Etapa 3 envolvia análise exploratória programática com Python e SQL. Minha submissão inclui a resolução das tarefas propostas nas três etapas.

As instruções e requisitos completos do desafio original serviram como base para esta implementação.


## 📁 Estrutura do Repositório

O repositório está organizado para refletir as etapas do desafio, contendo os dados originais e os arquivos de solução correspondentes:

`etapa_1/`: Contém os dados originais (data/) e o arquivo da solução para a Etapa 1 (Dashboard Power BI).

`etapa_2/`: Contém os dados originais (data/) e o arquivo da solução para a Etapa 2 (Modelo e Tabela Power BI).

`etapa_3/`: Contém os dados originais (data/) e o arquivo da solução para a Etapa 3 (Notebook Python e banco SQLite).
.gitignore: Arquivo que especifica padrões de arquivos/diretórios a serem ignorados pelo Git.
.gitattributes: Arquivo de configuração para o Git LFS, utilizado para gerenciar arquivos grandes como .pbix e .db.

### ✅ Etapas Concluídas

Concluí as tarefas propostas nas Etapas 1, 2 e 3, demonstrando habilidades em análise, visualização, modelagem de dados e análise programática.

**✅ Etapa 1:** 

– Desenvolvimento de Dashboard em Power BI

**Objetivo:** 
Desenvolver um dashboard funcional e informativo a partir de dados de vendas, com foco em análise e visualização.

**Implementação:**
Nesta etapa, realizei a carga dos dados fornecidos em *etapa_1/data/*, apliquei transformações necessárias no Power Query para garantir a qualidade e estrutura adequadas dos dados. No Power BI Desktop, construí um dashboard interativo que aborda as análises solicitadas: Visão Geral de Vendas, Análise Temporal, Análise Geográfica e uma Tabela detalhada por Produto. A construção do dashboard priorizou a clareza das informações e a eficácia das visualizações para extrair insights relevantes.

- Arquivo da Solução: `etapa_1/fadesp_desafio_etapa1.pbix`

**✅ Etapa 2:** 

- Aplicação da Camada Semântica em Dados Quebrados:

Um cliente solicitou a criação de um painel com as seguintes análises:

**Objetivo**: Estruturar e modelar dados com inconsistências para criar uma base confiável para análise, culminando em uma visualização de tabela.

**Implementação**:

A partir dos arquivos .csv em *etapa_2/data/*, foquei no tratamento e limpeza dos dados para corrigir inconsistências e garantir sua integridade. Realizei a modelagem dos dados no Power BI, estabelecendo relacionamentos e criando uma camada semântica robusta. Com os dados estruturados, desenvolvi a visualização em formato de tabela solicitada, incorporando filtros relevantes para permitir a exploração detalhada das informações.

- Arquivo da Solução: `etapa_2/fadesp_desafio_etapa2.pbix`

**✅ Etapa 3 – Análise Exploratória com Python + SQL**

**Objetivo**: Avaliar familiaridade com ferramentas de análise programática e manipulação de dados utilizando Python e SQL.

**Implementação**:

Nesta etapa, utilizei Python para carregar os dados de *etapa_3/data/* e armazená-los em um banco de dados SQLite (fadesp_desafio.db). Realizei consultas SQL diretamente no banco para extrair e agregar informações. A análise exploratória foi conduzida utilizando a biblioteca pandas para manipulação dos dados e bibliotecas de visualização (como matplotlib/seaborn/plotly - mencione as que você usou) para exibir indicadores e padrões. O código está documentado para facilitar o entendimento do processo.

- Arquivo da Solução: `etapa_3/fadesp_desafio_etapa3.ipynb`

- Banco de Dados: `etapa_3/fadesp_desafio.db`

**▶️ Como Visualizar a Solução:**

Para explorar os arquivos da solução:

1. Clone ou faça download deste repositório para o seu ambiente local.
2. Certifique-se de ter o Git LFS instalado e configurado para baixar os arquivos grandes (.pbix, .db).
3. **Para Etapas 1 e 2 (Power BI):**
- É necessário ter o Microsoft Power BI Desktop instalado.
- Navegue até os diretórios *etapa_1/* ou *etapa_2/*.
- Abra os arquivos .pbix correspondentes *(fadesp_desafio_etapa1.pbix* e *fadesp_desafio_etapa2.pbix)* utilizando o Power BI Desktop.
4. **Para Etapa 3 (Python/SQL/Jupyter):**
É necessário ter Python instalado (versão 3.6+ recomendada).
Recomenda-se criar e ativar um ambiente virtual (ex: python -m venv .venv e .venv/bin/activate no Linux/macOS ou .venv\Scripts\activate no Windows).
Instale as dependências Python listadas no arquivo requirements.txt. Navegue até a raiz do repositório no terminal (com o ambiente virtual ativado) e execute:
~~~ bash
pip install -r requirements.txt
~~~

*   Abra o diretório do repositório no **VS Code**. Com as extensões Python e Jupyter instaladas no VS Code, você poderá abrir e executar o arquivo `etapa_3/fadesp_desafio_etapa3.ipynb` diretamente.
*   Alternativamente, você pode navegar até o diretório `etapa_3/` no terminal (com o ambiente virtual ativado) e iniciar o Jupyter Notebook ou JupyterLab: `jupyter notebook` ou `jupyter lab`. No navegador, abra o arquivo `fadesp_desafio_etapa3.ipynb` e execute as células.

**🛠 Tecnologias e Ferramentas Utilizadas**

- Power BI Desktop: Utilizado para carga, transformação, modelagem e visualização de dados nas Etapas 1 e 2.
- Python: Linguagem de programação utilizada na Etapa 3.
- Pandas: Biblioteca Python para manipulação e análise de dados (Etapa 3).
- SQLite: Banco de dados leve utilizado para armazenamento e consulta na Etapa 3.
- SQL: Linguagem de consulta utilizada na Etapa 3.
- Jupyter Notebook: Ambiente interativo para executar o código Python da Etapa 3.
- Git LFS (Large File Storage): Empregado para gerenciar eficientemente arquivos grandes como .pbix e .db.

**Considerações Finais**

Este projeto demonstra a minha capacidade de trabalhar com dados em diversas frentes, desde a ingestão, tratamento e modelagem até a análise exploratória programática e a criação de visualizações e dashboards interativos. Agradeço a oportunidade de participar deste processo seletivo e estou à disposição para fornecer quaisquer esclarecimentos adicionais sobre a solução apresentada.


Helen Carneiro | Analista de Dados