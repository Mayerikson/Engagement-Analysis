# 📊 Análise de Campanhas de Marketing 

Este projeto tem como objetivo analisar os dados de campanhas da empresa fictícia MYK Marketing, especializada em tráfego pago, para responder perguntas estratégicas relacionadas ao engajamento de conteúdo.

## 🧠 Contexto do Projeto

Este estudo tem como foco principal a análise de engajamento nas campanhas digitais, entendendo que o engajamento é um indicador antecipado de performance e influência direta no ROI.

Embora o retorno financeiro (ROI) não tenha sido mensurado diretamente neste projeto, ele será abordado em uma próxima etapa.

A proposta atual visa identificar padrões de alto engajamento, os quais serão base para estratégias que maximizem o ROI em futuras campanhas.

A literatura de marketing digital e casos anteriores demonstram que campanhas com maior engajamento têm mais chance de conversão em receita.

Assim, os padrões identificados aqui como o uso de vídeos, hashtags específicas e foco regional têm potencial de elevar o ROI, sendo recomendados para testes em campanhas futuras com acompanhamento de KPIs financeiros.

A análise é conduzida com base em dados históricos das campanhas para responder às seguintes perguntas:

1)Quais formatos de postagens geram o maior volume de engajamento absoluto?

2)Quais combinações de conteúdo, região e hashtag maximizam o engajamento?

3)Quais sinergias entre tipo de conteúdo e região devem ser exploradas?

4)Qual o valor médio de engajamento por hashtag, controlando por plataforma e região?

5)Quais características se repetem entre os posts de alto engajamento?


---

## 🗂️ Estrutura do Projeto

- `Campanha.ipynb`: Notebook principal com toda a análise.
- `dados/`: Diretório com os dados utilizados na análise.
- `imagens/`: Gráficos e outputs gerados durante a exploração.

---

## 🛠️ Técnicas e Ferramentas

- Python (Pandas, Seaborn, Matplotlib)
- Análise Exploratória de Dados (EDA)
- Análise SWOT
- Visualização de dados
- Métricas de Engajamento (likes, comentários, alcance, etc.)
- Insights acionáveis com base em evidências

---

## 📈 Principais Descobertas

Tipos de conteúdo com maior pontuação média de engajamento por plataforma:

Instagram: Live Stream (338.76)

TikTok: Shorts (664.10)

Twitter: Vídeo (213.05)

YouTube: Live Stream (322.34)

Variáveis mais relevantes na previsão de alto engajamento: Hashtag, Região, Tipo de Conteúdo

Nenhuma variável categórica teve associação forte isoladamente

Melhores combinações identificadas:
Shorts + USA (Efeito: 3.29)

Shorts + Brazil (0.83)

Vídeo + Brazil (0.80)

TikTok apresenta maior variabilidade no engajamento (σ = 8.068)

Hashtags têm impacto variável dependendo da plataforma e região

Likes_per_View (0.40) → Forte indicador de popularidade

Engagement_per_View (0.38) → Reflete qualidade da interação

Views (0.17) → Importante para alcance, mas não decisivo sozinho

---

## ✅ Conclusões e Recomendação

Priorizar vídeos e lives em plataformas com boa performance.

Realizar testes A/B para confirmar performance dos formatos.

Redirecionar investimento para canais com melhor ROI.

Implementar segmentação geográfica com conteúdo adaptado

Explorar as hashtags com maior correlação com engajamento alto

Personalizar campanhas por cluster regional

Testar campanhas piloto com as sinergias destacadas

Priorizar hashtags no top 10 de desempenho (ajustado por plataforma)

Realizar testes A/B em plataformas com alta variabilidade como o TikTok

Otimizar posts com maior taxa de curtidas por visualização

Focar em qualidade da interação mais do que quantidade



---

## 📌 Próximos Passos

- Monitorar os resultados das próximas campanhas com base nas recomendações.
- Expandir a análise para outras plataformas sociais.
- Criar um dashboard em tempo real com métricas de engajamento.

---
obs: esse projeto foi inspitado no desafio do Kaggle:https://www.kaggle.com/datasets/atharvasoundankar/viral-social-media-trends-and-engagement-analysis/data
