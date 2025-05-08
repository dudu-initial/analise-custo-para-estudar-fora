# analise-custo-para-estudar-fora

# Análise dos custos para estudar fora

O objetivo deste projeto é realizar uma análise exploratória e comparativa dos custos envolvidos na educação internacional, utilizando o dataset Cost of International Education. Através dessa análise, busca-se identificar padrões, tendências e variações nos custos de mensalidade, moradia, visto, seguro e despesas gerais em diferentes países, cidades e instituições de ensino ao redor do mundo.
<br>
A proposta é gerar insights úteis para estudantes internacionais, consultores educacionais e pesquisadores, com foco em comparar acessibilidade, custo-benefício e fatores financeiros determinantes na escolha de destinos de estudo. Ao final, serão apresentadas visualizações e recomendações baseadas em dados, com potencial para serem incorporadas em dashboards ou relatórios interativos.

- Perguntas que tentaremos responder com a análise:

1. Quais cidades têm um alto custo de vida, mas surpreendem com programas mais baratos?

2. Quais cidades oferecem programas mais caros mesmo com um custo de vida relativamente baixo?

3. Há um padrão claro entre custo de vida e o custo total do programa?

4. Algum país concentra cidades com custo-benefício mais vantajoso?

## Estrutura do Projeto

- `analise_custos_para_estudar_fora.ipynb`: notebook principal com toda a análise e visualizações.
- `International_Education_Cost.csv`: arquivo com os dados dos filmes.
- `README.md`: documentação do projeto.

## Tecnologias Utilizadas

- Python 3.7
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## ▶️ Como Executar

1. Clone o repositório:
   git clone https://github.com/dudu-initial/analise-custo-para-estudar-fora.git

2. Instale as dependências (de preferência num ambiente virtual):
  pip install -r requirements.txt

Ou manualmente:
  pip install pandas numpy matplotlib seaborn

3. Abra o Jupyter Notebook:
  jupyter notebook analise_custos_para_estudar_fora.ipynb

# Exemplos de Visualizações:

- Análise Exploratória (EDA - Exploratory Data Analysis):

  

1. Quais cidades têm um alto custo de vida, mas surpreendem com programas mais baratos? <br>![image](https://github.com/user-attachments/assets/0475cf2a-05cf-4279-91c3-b98d6b5bf871)

2. Quais cidades oferecem programas mais caros mesmo com um custo de vida relativamente baixo?<br> ![image](https://github.com/user-attachments/assets/fba45754-dec3-4b77-b154-04a634e801e2)

3. Há um padrão claro entre custo de vida e o custo total do programa?<br> ![image](https://github.com/user-attachments/assets/8efa8dda-2a64-48a8-86b8-5eefc98ab9c0)

4. Algum país concentra cidades com custo-benefício mais vantajoso?<br> ![image](https://github.com/user-attachments/assets/44c2b932-3af5-4f14-92df-ea6e7da08ed0)


# Conclusões: 

<b>- Existem cidades com custo de vida elevado, mas programas acessíveis.</b>
<br>
Apesar de parecerem caras para viver, algumas cidades surpreendem ao oferecer cursos completos por valores abaixo de US$30.000, mostrando que o custo de vida não é um indicador absoluto do valor total da graduação.

<b>- Também há cidades baratas com programas extremamente caros.</b>
<br>
Algumas cidades com índice de custo de vida abaixo de 70 possuem programas educacionais que ultrapassam os US$50.000, alertando que economia no dia a dia pode ser anulada por mensalidades ou taxas altas.

<b>- O custo de vida não tem correlação forte com o custo total do programa. </b>
<br>
Ao analisar graficamente os dois indicadores, nota-se que não há um padrão fixo. Existe uma grande variação entre cidades e países, o que reforça a importância de analisar ambos separadamente.

<b>- Alguns países concentram cidades com ótimo custo-benefício. </b>
<br>
Países como Bulgaria, Iran, Morocco e India se destacam por reunirem várias cidades onde o custo de vida e o valor total do curso são equilibrados, oferecendo uma excelente oportunidade para estudantes internacionais.

<b> - Cidades alternativas devem ser consideradas na escolha de onde estudar. </b>
<br>
Cidades menos óbvias podem oferecer a mesma qualidade de ensino com custos totais muito mais baixos. Essas descobertas ajudam estudantes a tomarem decisões mais econômicas e estratégicas.

<b> - A Segurança deve ser priorizada na sua escolha, não adianta o programa completo ter um ótimo custo-benefício e ser um péssimo lugar para estudantes de diferentes culturas. </b>
