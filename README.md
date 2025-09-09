Desafio de Ciência de Dados - Indicium Lighthouse 🚀

LH_CD_VANESSAFERMINODOSSANTOSCAVALCANTE(CIENCIA DE DADOS)

Solução do desafio de ciência de dados do programa Lighthouse da Indicium.

🎯 Objetivo do Projeto
Através da utilização de ferramentas de ciência de dados e machine learning é possível analisar quais são as principais características que determinam o sucesso de um filme e auxiliam na previsão de como serão os retornos com base nas características selecionadas. Dessa forma, a empresa PProductions poderá escolher quais filmes deveram ser lançados para que se obtenha uma maior margem de lucro e a possibilidade de obter boas notas das críticas e do IMDb.

Ambiente: Jupyter Notebook / Google Colab

🚀 Como Executar o Projeto
Siga os passos abaixo para configurar e executar a análise em seu ambiente local.

1. Clonar o Repositório

git clone [https://github.com/vanessafermino/LH_CD_VANESSAFERMINODOSSANTOSCAVALCANTE.git](https://github.com/vanessafermino/LH_CD_VANESSAFERMINODOSSANTOSCAVALCANTE.git)
cd LH_CD_VANESSAFERMINODOSSANTOSCAVALCANTE

2. Criar um Ambiente Virtual
É uma boa prática isolar as dependências do projeto.

python -m venv venv

3. Ativar o Ambiente Virtual

No Windows (CMD/PowerShell):

.\venv\Scripts\activate

No Linux ou macOS:

source venv/bin/activate

4. Instalar as Dependências
Instale todas as bibliotecas necessárias listadas no arquivo requirements.txt.

pip install -r requirements.txt

(Nota: Se o arquivo requirements.txt não existir, você pode instalar as bibliotecas principais manualmente: pip install pandas scikit-learn matplotlib wordcloud jupyter)

5. Executar o Jupyter Notebook
Abra o ambiente Jupyter para interagir com o notebook da análise.

jupyter notebook

Após executar o comando, uma aba será aberta em seu navegador. Navegue até a pasta NOTEBOOK COLAB e abra o arquivo DesafioIndicium.ipynb.

📊 Análises Realizadas
Análise Exploratória de Dados (EDA): Limpeza, tratamento de valores nulos e entendimento geral do dataset.

Análise de Fatores de Faturamento: Investigação sobre quais variáveis (gênero, popularidade, duração) mais impactam a receita de um filme.

Processamento de Linguagem Natural (PLN):

Extração de temas das sinopses (Overview) com a criação de uma Nuvem de Palavras.

Construção de um modelo para prever o gênero do filme a partir da sinopse.

Modelagem Preditiva:

Desenvolvimento de um modelo de Regressão (RandomForestRegressor) para prever a nota do IMDB com base nas características do filme.

👩‍💻 Autora
Vanessa Fermino dos Santos Cavalcante

GitHub
