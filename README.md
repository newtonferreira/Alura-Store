# Alura-Store
📌 Sobre
Este projeto foi desenvolvido como parte do programa ONE (Oracle Next Education) — uma iniciativa da Oracle em parceria com a plataforma Alura, para formação de profissionais em tecnologia.

O desafio consiste em auxiliar o Sr. João, proprietário de quatro lojas da AluraStore, a tomar uma decisão estratégica: vender uma das lojas para investir em um novo negócio. Para isso, realizei uma análise baseada em cinco métricas principais, com apoio de gráficos e indicadores.

⚙️ Tecnologias e Bibliotecas Utilizadas
Python 3.11
Pandas - Manipulação de dados
Matplotlib - Visualização gráfica
Seaborn - Gráficos estatísticos avançados
Folium - Geração de mapas interativos
Plotly - Gráficos dinâmicos

📊 Etapas da Análise
1. 📦 Faturamento Total por Loja
Soma dos valores da coluna Preço para estimar o desempenho financeiro.
Gráfico de barras estilizado para facilitar a comparação.
2. 🧮 Categorias Mais Vendidas
Agrupamento por Categoria do Produto.
Visualização por loja para entender preferências de consumo.
3. ⭐ Avaliações Médias
Análise da coluna Avaliação da compra.
Gráfico de pontos para representar visualmente.
4. 🔝 Produtos Mais e Menos Vendidos
Contagem de frequência dos produtos por loja.
Gráfico de violino para representar a variação.
5. 🚚 Frete Médio
Cálculo da média da coluna Frete por loja.
Representação com linhas.

💡 Como Executar o Projeto
Clone este repositório:
git clone https://github.com/seu-usuario/projeto-analise-lojas.git
Instale os pacotes necessários:
pip install -r requirements.txt
Execute o notebook:
jupyter notebook analise_lojas.ipynb

❗ Possíveis Problemas
Certifique-se de estar usando a versão correta do Python (3.11 ou superior).
Os dados são carregados diretamente de URLs, então uma conexão com a internet é necessária.
Algumas bibliotecas como folium podem não funcionar corretamente em ambientes offline.
