<!--START_SECTION:header-->
<div align="center">
  <p align="center">
    <img 
      alt="DIO Education" 
      src="https://raw.githubusercontent.com/digitalinnovationone/template-github-trilha/main/.github/assets/logo.webp" 
      width="100px" 
    />
    <h1>Roadmap de Carreira — Analista de Dados</h1>
  </p>
</div>
<!--END_SECTION:header-->

<p align="center">
  <img src="https://img.shields.io/static/v1?label=DIO&message=Education&color=E94D5F&labelColor=202024" alt="DIO Project" />
  <img src="https://img.shields.io/static/v1?label=Nivel&message=Transição%20%26%20Crescimento&color=2B8A3E&labelColor=202024" alt="Nivel" />
  <img src="https://img.shields.io/static/v1?label=Horas%2Fsemana&message=7h&color=0052CC&labelColor=202024" alt="Horas por semana" />
</p>

---

## 💼 Sobre este Repositório

**Resumo:** Este repositório contém o **Roadmap de Carreira (120 dias)** para quem está em transição para **Analista de Dados** com disponibilidade de **7 horas/semana**. Inclui plano de estudos detalhado, mapa de skills, roteiro de entrevistas, trilha DIO recomendada e um **projeto de portfólio** com template de README e estrutura de repositório para publicar no GitHub.

**Valor para a carreira:** o material foi desenhado para transformar aprendizado em entregáveis concretos que recrutadores valorizam: código versionado, notebooks reproduzíveis, dashboards e documentação clara.

---

## 🎯 Objetivo do Roadmap

- **Público:** pessoas em transição para Analista de Dados (experiência: zero).  
- **Meta:** primeiro emprego / crescimento na área, com portfólio público no GitHub.  
- **Carga:** 7 horas por semana, 120 dias (≈ 6 meses).

---

## 🧠 Mapa de Skills (foco do roadmap)

**Core skills**
- SQL (consultas, joins, agregações, window functions)  
- Estatística descritiva e análise exploratória  
- Python para dados (pandas, numpy)

**Nice-to-have**
- Visualização e dashboards (Power BI / Tableau)  
- Noções de ML (scikit-learn)  
- Git / GitHub (versionamento e documentação)

**Ferramentas**
- PostgreSQL / MySQL  
- Jupyter / Google Colab  
- Power BI Desktop / Power BI Service  
- GitHub, Kaggle

---

## 📅 Roadmap de 120 Dias (resumo prático)

**Mês 1 — Fundamentos (Sem 1–4)**  
- SQL básico → consultas práticas; exercícios hands-on.  
- Estatística descritiva; Excel avançado (tabelas dinâmicas).

**Mês 2 — Python e Limpeza (Sem 5–8)**  
- Python básico; pandas para leitura e manipulação.  
- Pipeline de limpeza: nulos, duplicatas, tipos, transformações.

**Mês 3 — Visualização e ML simples (Sem 9–12)**  
- Visualização com matplotlib/seaborn; interpretação.  
- Regressão/avaliação simples; métricas (RMSE, MAE, accuracy).

**Mês 4 — Power BI e Dashboards (Sem 13–16)**  
- Modelagem no Power BI; visualizações interativas; DAX básico.  
- Publicação e preparação de demo.

**Mês 5 — GitHub e Documentação (Sem 17–20)**  
- Git básico; estrutura de repositório; README profissional.  
- Versionamento de notebooks e uso de branches/PRs.

**Mês 6 — Projeto Final e Preparação (Sem 21–24)**  
- Execução do projeto de portfólio; publicação no GitHub.  
- Preparação para entrevistas: storytelling, perguntas técnicas, demo.

---

## 🚀 Projeto de Portfólio (entregável principal)

**Nome sugerido:** Portfólio — Roadmap de Carreira (Analista de Dados)

**Escopo:** demonstrar todo o fluxo de trabalho de um analista: ingestão, limpeza, EDA, visualização, modelo simples e documentação. O projeto serve como prova prática do seu progresso no roadmap.

**Entregáveis mínimos:**
- `data/` com dataset original e versão tratada.  
- `notebooks/` com pipeline comentado (Jupyter/Colab).  
- `dashboard/` com arquivo Power BI (`.pbix`) ou imagens do dashboard.  
- `reports/` com relatório executivo (1–2 páginas).  
- `README.md` profissional (template abaixo).  
- `requirements.txt` com dependências.

**Critérios de aceitação:**
- Pipeline reprodutível e dataset tratado.  
- Pelo menos 3 insights acionáveis documentados.  
- Dashboard funcional com filtros e visual limpo.  
- Repositório com commits claros e README completo.

---

## ✅ README Template (para usar no repositório do projeto)

**Título:** Roadmap de Carreira — Analista de Dados (Projeto Portfólio)  
**Descrição curta:** Projeto que acompanha o roadmap de 120 dias para transição a Analista de Dados; inclui notebooks, dashboard e documentação.  

**Como reproduzir (exemplo):**
```bash
git clone https://github.com/seuusuario/roadmap-analista-dados.git
cd roadmap-analista-dados
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
pip install -r requirements.txt
jupyter notebook notebooks/analise_roadmap.ipynb
