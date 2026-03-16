# 🚲 Estudo de Caso: Cyclistic Bike-Share Chicago

## 📋 Sobre o Projeto
Este projeto é o **Capstone de conclusão do Certificado Profissional de Análise de Dados do Google**. O desafio consiste em analisar os dados de uma empresa fictícia de compartilhamento de bicicletas em Chicago para entender como **Membros Anuais** e **Ciclistas Casuais** utilizam o serviço de forma diferente.

O objetivo final é desenhar estratégias de marketing baseadas em dados para converter usuários casuais em membros anuais, aumentando a rentabilidade da empresa.

---

## 🚀 Links Rápidos
* 📺 [Apresentação Completa no YouTube](https://www.youtube.com/watch?v=ggVvfY0VTXY)
* 📊 [Dashboard Interativo no Tableau](https://public.tableau.com/app/profile/shaini.dittberner/viz/GoogleDataAnalyticsCapstoneProject-CyclisticBike-Share_17597593701720/Mapaeestaes)
* 📄 [Relatório Técnico (HTML)](https://shaiditt.github.io/cyclistic-bike-share-analysis/)

---

## 🛠️ Tecnologias e Metodologia
A análise seguiu as fases de: **Pergunta, Preparação, Processamento, Análise, Compartilhamento e Ação.**

* **R (RStudio):** Utilizado para limpeza de dados (limpeza de 24 NAs e remoção de *outliers*), unificação de datasets de 2019 e 2020 e análise estatística.
* **Tableau:** Criação de visualizações de geolocalização e dashboards de tendências.
* **PowerPoint:** Estruturação das recomendações de negócio.

### 📂 Base de Dados
Os dados brutos foram extraídos dos repositórios públicos da empresa. Você pode acessar as planilhas utilizadas nos links abaixo:
* 📥 [Divvy_Trips_2019_Q1 - Google Sheets](https://docs.google.com/spreadsheets/d/1uCTsHlZLm4L7-ueaSLwDg0ut3BP_V4mKDo2IMpaXrk4/template/preview?resourcekey=0-dQAUjAu2UUCsLEQQt20PDA#gid=1797029090)
* 📥 [Divvy_Trips_2020_Q1 - Google Sheets](https://docs.google.com/spreadsheets/d/179QVLO_yu5BJEKFVZShsKag74ZaUYIF6FevLYzs3hRc/template/preview#gid=640449855)

---

## 📊 Insights Principais
A análise do 1º trimestre de 2019 e 2020 revelou padrões distintos:

1.  **Membros:** Utilizam o serviço para transporte diário (comutação), com uso constante de segunda a sexta-feira.
2.  **Casuais:** Têm viagens com duração muito superior (média significativamente maior) e utilizam o serviço principalmente para lazer aos finais de semana e turismo.

> ![Gráfico de Comparação Membros vs Casuais](/Visualizações/corridas_tempo_dia_da_semana.png)

---

## 💡 Recomendações Estratégicas (Baseadas no PPT)

Com base nos dados, propus as seguintes frentes de ação presentes na apresentação executiva [Bike-share.pdf](./Bike-share.pdf):

> ![Gráfico de Comparação entre Estações](/Visualizações/mapa_estacoes.png.png)

### **ESTRATÉGIA A - Foco em Clientes Casuais**
* **Pacotes de Fim de Semana:** Criar assinaturas específicas que incluam viagens mais longas (45-60 min).
* **Passe de Exploração:** Lançar passes de 3 a 7 dias com foco em turistas.
* **Marketing Localizado:** Concentrar publicidade nas 10 estações mais usadas por casuais.

### **ESTRATÉGIA B - Foco em Clientes Membros**
* **Parcerias Corporativas:** Focar em empresas e universidades próximas às estações de maior fluxo de membros.
* **Campanhas em Áreas Comerciais:** Redirecionar o orçamento de mídia digital para regiões com foco em deslocamento diário.

---
**Desenvolvido por Shaini Dittberner** Analista de Dados em formação | [Meu LinkedIn](https://www.linkedin.com/in/shainidittberner/)
