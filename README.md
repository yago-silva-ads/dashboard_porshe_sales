# 🏎️ Porsche Sales Intelligence Dashboard

Uma dashboard analítica interativa e refinada desenvolvida para monitorar e extrair KPIs estratégicos sobre as vendas de veículos da marca Porsche. O design foi totalmente inspirado na identidade visual oficial e minimalista da **Porsche Brasil**.


Uma dashboard analítica interativa e refinada desenvolvida para monitorar e extrair KPIs estratégicos sobre as vendas de veículos da marca Porsche. O design foi totalmente inspirado na identidade visual oficial e minimalista da **Porsche Brasil**.

🚀 **[Clique aqui para acessar o Dashboard em produção](https://yago-silva-ads.github.io/dashboard_porshe_sales/)**

---

## 🛠️ Tecnologias e Conceitos Utilizados

Este projeto não foi programado da forma tradicional. Ele marca a transição para o **Desenvolvimento Baseado em Agentes (Agentic Development)**:

*   **Antigravity IDE:** Ambiente de desenvolvimento utilizado para orquestrar agentes autônomos locais.
*   **Claude 3.5 Sonnet / Gemini:** Modelos de linguagem avançados que leram a base de dados física e geraram a aplicação de forma autônoma.
*   **HTML5 & CSS3 Premium:** Estrutura responsiva com design elegante, paleta de cores premium (tons escuros e tipografia limpa) focado em experiência do usuário (UI/UX).
*   **JavaScript (Chart.js / Vanilla):** Mecanismo de filtros reativos e plotagem de gráficos dinâmicos em tempo real.
*   **GitHub Pages:** Infraestrutura de deploy automatizado em nuvem.

---

## 📊 Estrutura e Funcionalidades

A dashboard consome dados higienizados e padronizados da base de dados (`PORSHE_TRATADO`), respondendo de forma imediata a dores do negócio através de painéis visuais:

### 🎛️ Filtros Dinâmicos
*   **Modelo do Porsche** (Ex: 911, Taycan, Cayenne, Macan)
*   **Ano de Fabricação** (Model Year)
*   **Cidade da Venda**
*   **Método de Pagamento** (Pay Method)

### 📈 KPIs e Perguntas de Negócio Respondidas
1.  **Volume por Região:** Quais são os principais modelos de carros vendidos em cada cidade específica?
2.  **Sazonalidade e Preferência:** Qual o ano de modelo de carro que mais saiu dentro do período analisado?
3.  **Análise de Mercado (Insights):** Mapeamento automático indicando o comportamento dos modelos mais populares em cada praça de vendas.

---

## 🤖 Como este projeto foi construído?

A construção utilizou a autonomia de um agente local no ecossistema do **Antigravity**. O agente recebeu a planilha estruturada, realizou os seguintes passos de forma automatizada via terminal:
1.  Executou scripts Python locais para varrer e processar os 100 registros higienizados.
2.  Estruturou os componentes visuais baseando-se no ecossistema web da marca.
3.  Consolidou a aplicação em um arquivo único e funcional (`index.html`) pronto para distribuição.

---

## ⚙️ Como executar localmente

Se você deseja clonar o repositório e rodar o projeto na sua máquina:

1. Clone o repositório:
   ```bash
   git clone https://github.com
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd dashboard_porshe_sales
   ```
3. Inicialize um servidor local rápido (Python):
   ```bash
   python -m http.server 8000
   ```
4. Abra o seu navegador e digite: `http://localhost:8000`

---
<p align="center">Desenvolvido com 🏁 e Inteligência Artificial por <a href="https://github.com">Yago Santos Silva</a>.</p>
