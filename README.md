### Projeto Final Nível 2: Análise de Padrões de Reservas de Hotéis

#### **Visão Geral**

Este projeto consiste em uma análise detalhada dos dados de reservas de hotéis para identificar os principais fatores que influenciam cancelamentos, a demanda por tipo de hotel e as preferências dos clientes. O objetivo é extrair insights acionáveis que possam ajudar na tomada de decisões estratégicas para hotéis.

#### **Fonte dos Dados**

O conjunto de dados "Hotel Booking Demand Dataset" foi obtido no Kaggle e contém informações detalhadas sobre reservas em hotéis.

#### **Metodologia (Abordagem com Google Sheets)**

A análise seguiu a metodologia proposta no roadmap, utilizando uma abordagem de manipulação de dados e criação de visualizações similar à que seria feita no Google Sheets, para demonstrar o conhecimento de ferramentas e conceitos. As etapas foram:

1.  **Limpeza de Dados:** Tratei valores ausentes, removi duplicatas e formatei as colunas de data para garantir a consistência do dataset.
2.  **Análise Exploratória (EDA):** Calculei estatísticas descritivas e utilizei agregações para entender a distribuição de reservas, a taxa de cancelamento e a duração da estadia.
3.  **Visualização:** Criei diversos gráficos para ilustrar os resultados, seguindo a paleta de cores solicitada para o dashboard.

#### **Resultados e Insights Principais**

* **Meses com maior demanda e cancelamentos:** Os meses de verão (Julho e Agosto) apresentam a maior taxa de reservas e também de cancelamentos.
* **Tipos de hotéis mais demandados:** O "City Hotel" tem uma demanda significativamente maior do que o "Resort Hotel".
* **Impacto da duração da estadia:** A duração média da estadia é maior em "Resort Hotels", e a taxa de cancelamento é menor nesses hotéis, sugerindo uma correlação.

#### **Arquivos no Repositório**

Você pode adicionar os seguintes arquivos ao seu repositório do GitHub:

* hotel_bookings.csv: O dataset original.
* hotel_bookings_cleaned.csv: O arquivo com os dados limpos e prontos para análise.
* total_reservas_por_hotel.csv: Tabela de resumo do total de reservas por tipo de hotel.
* taxa_cancelamento_por_mes_hotel.csv: Tabela com a taxa de cancelamento por mês e tipo de hotel.
* tendencia_reservas_cancelamentos.png: Gráfico de linhas da tendência de reservas e cancelamentos.
* taxa_cancelamento_por_hotel.png: Gráfico de barras da taxa de cancelamento por tipo de hotel.
* duracao_media_estadia.png: Gráfico de barras da duração média da estadia por tipo de hotel.
