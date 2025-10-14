# Projeto 4  
## Ficha Técnica: Produtos e Avaliações da Amazon

### Objetivo
Automatizar o processo de **análise de crédito** no banco *Super Caja* por meio de técnicas avançadas de análise de dados, visando aumentar a eficiência, precisão e agilidade na avaliação de pedidos de empréstimo.  

A análise busca:
- Investigar relações entre preços, descontos e avaliações dos produtos vendidos
- Identificar padrões de comportamento do consumidor, correlações entre variáveis e possíveis fatores que influenciam a popularidade e a satisfação dos clientes

### Equipe
- Projeto desenvolvido por **Ana Paula de Almeida Coiado**

### Ferramentas e Tecnologias
- Linguagem de programação Python para manipulação e análise de dados
- Bibliotecas principais: Pandas, NumPy, Matplotlib/Seaborn
- Ambiente de Desenvolvimento Google Colab
- Inteligência Artificial Gemini para auxílio na execução dos códigos e análises
- Power Point para apresentação dos resultados (slides)
  
---

## Processamento e Análises
#### Importação dos Dados
- Importação dos arquivos `.csv` disponibilizados no Google Colab:
  - `amazon - amazon_product.csv`
  - `amazon - amazon_review.csv`
  
#### Tratamento de Dados
> *Todas as etapas foram realizadas com auxílio da Inteligência Artificial Gemini*
- Identificação e tratamento de dados nulos, duplicados, fora do escopo de análise, dados discrepantes em variáveis e numéricas
- Verificação e alteração do tipo de dados
- União das tabelas com base em uma chave comum

---

#### Análise Exploratória (EDA)
- Agrupamento e visualizações dos dados conforme variáveis categóricas com tabelas e gráficos
- Aplicação de medidas de tendência central: **média, mediana e moda**  
- Visualização da distribuição (tabelas, histogramas e boxplots)  
- Aplicação de medidas de dispersão: **desvio padrão, variância e intervalo interquartílico**
- Criação de **categorias com base em quartis** no Google Colab
- Cálculo de **correlação de Pearson** (`CORR`) e visualização no gráfico de dispersão  
  
---

#### Técnicas de Análise
- Aplicação de segmentação do dataset em grupos ou segmentos para análise detalhada
- Visualização dos resultados com tabels, gráficos e mapas de calor
- Validação de Hipóteses e visualizações com tabelas e gráficos
- Cálculo de Risco Relativo entre dois grupos para comparação de probabilidade

---

#### Apresentação dos Resultados
- Criação de relatório com os resultados da análise
- Apresentação de slides

---

### Resultados e Conclusões
- Correlação forte entre preço original e preço com desconto (0.96)
- Baixa relação entre descontos e números de avaliações (0.0l)
- Produtos com mais avaliações tendem a ter melhores classificações
- Pequena tendência de que maiores descontos estejam associados a mais avaliações baixas
- Esses resultados indicam que a popularidade está mais relacionada à qualidade percebida do produto do que ao valor do desconto

---

### Limitações / Próximos Passos
#### Limitações
- Base de dados limitada (≈ 1.000 registros), podendo não representar toda a Amazon
- Ausência de informações sobre tempo de publicação e contexto das avaliações
- Próximos Passos: aplicar testes estatísticos de signifiância e análise de sentimento (PNL) nos textos das avaliações para aprofundar as conclusões

---

### Links de Interesse

- [Ficha Técnica (Notion)](https://www.notion.so/Projeto-4-28b8dc77aa2d802fb9f6f38aab7577e6)
- [Apresentação (Loom)](https://www.loom.com/share/aa14361b04644b0eae6df82a2aba5657?sid=38775f96-2eea-45fa-b2db-344fbf704879)
- [Apresentação (Slides)](https://docs.google.com/presentation/d/1ZfCUU_xbx7fty8sxzTMI5r7eYuw8M88l/edit?usp=drive_link&ouid=112893683117403532765&rtpof=true&sd=true)
