# 📊 Portfólio — Kaique Soares de Souza

### Analista de Dados | SQL • Python • Power BI • ETL

> Portfólio interativo demonstrando competências em análise de dados, visualização e engenharia de dados para operações logísticas.

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-00d4ff?style=for-the-badge&logo=github)](https://kzzkaiquesds.github.io/portfolio-kaique-soares/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/kaique-soares-de-souza-732b15259/)

---

## 🎯 Sobre

Aplicação web de portfólio profissional desenvolvida para demonstrar competências técnicas em **análise e engenharia de dados**. O projeto apresenta dashboards interativos, exemplos de código em SQL/Python/DAX e uma visão completa da minha trajetória profissional no setor logístico.

O portfólio foi construído inteiramente com tecnologias web modernas, sem dependência de frameworks pesados, priorizando performance e acessibilidade.

---

## 🏗️ Arquitetura do Projeto

```
portfolio-kaique-soares/
│
├── index.html                          # Página principal do portfólio
├── curriculo-ats.html                  # Currículo otimizado para ATS (imprimível em PDF)
│
├── css/
│   └── style.css                       # Estilos globais (modo escuro, responsivo, animações)
│
├── js/
│   ├── main.js                         # Navegação, smooth scroll e interatividade geral
│   ├── dashboards.js                   # Dashboards interativos com Chart.js
│   └── code-tabs.js                    # Tabs de código com syntax highlighting
│
├── scripts/
│   └── gerar_dados_sinteticos.py       # Gerador de dados sintéticos logísticos (Python)
│
├── dados/                              # Bases analíticas sintéticas (CSV e JSON)
│   ├── dim_regioes.csv                 # Dimensão de regiões de atendimento e prazos de SLA
│   ├── dim_armazens.csv                # Dimensão de Centros de Distribuição (CDs)
│   ├── dim_clientes.csv                # Dimensão de clientes e segmentações
│   ├── dim_produtos.csv                # Catálogo de produtos, custos, preços e Curva ABC
│   ├── fato_entregas.csv               # Fato de entregas operacionais e métricas de SLA
│   ├── fato_inventario.csv             # Fato de auditorias cíclicas e acurácia de estoque
│   └── fato_avarias.csv                # Fato de ocorrências de avarias por sistema ERP
│
├── assets/                             # Recursos estáticos (imagens, ícones)
│
└── README.md                           # Documentação do projeto (este arquivo)
```

---

## ✨ Funcionalidades

### 🖥️ Portfólio Interativo

- Design moderno em **modo escuro** com paleta ciano/escura
- Totalmente **responsivo** — adaptado para mobile, tablet e desktop
- Navegação com smooth scroll e destaque automático da seção ativa
- Animações suaves de entrada (fade-in, slide-up) nos elementos
- Seções organizadas: Sobre, Experiência, Dashboards, Código, Contato

### 📊 Dashboards Interativos

Três painéis analíticos funcionais com filtros dinâmicos, construídos com **Chart.js**:

| Painel | Descrição | KPIs |
|--------|-----------|------|
| **Indicadores B2C e Atendimento** | Análise de pedidos e performance de entrega | Taxa de entrega no prazo, tempo médio, satisfação do cliente, filtros por canal |
| **Gestão de Inventário** | Controle de estoque e acurácia | Acurácia de inventário, giro de estoque, classificação ABC, top SKUs por armazém |
| **Controle de Avarias (WMS/SAP/TOTVS)** | Monitoramento de perdas operacionais | Avarias por sistema, tipo, tendência mensal e análise de causa raiz |

### 💻 Engenharia de Dados

Demonstração de código real em **tabs interativas** com syntax highlighting:

- **SQL (PostgreSQL/Oracle)** — Queries complexas com CTEs, window functions, agregações e joins multi-tabela
- **Python (Pandas/SQLAlchemy)** — Pipeline ETL completo para operações logísticas
- **DAX & Linguagem M** — Medidas calculadas avançadas e transformações para Power BI

### 📄 Currículo ATS

- Currículo otimizado para sistemas **ATS** (Applicant Tracking Systems)
- Formato HTML imprimível diretamente em PDF via navegador
- Layout de página única A4, limpo e profissional
- Palavras-chave otimizadas para vagas de **Analista de Dados Pleno**

---

## 🧠 Competências Demonstradas

### Análise de Dados

- Análise exploratória de dados (EDA) com Python e SQL
- Criação de KPIs e métricas operacionais para logística
- Storytelling com dados e visualização orientada a decisão
- Tratamento e limpeza de dados com Pandas

### Engenharia de Dados

- Pipelines ETL com Python, Pandas e SQLAlchemy
- Modelagem dimensional (fato/dimensão) para data warehousing
- Geração de dados sintéticos realistas para simulação
- Integração com bancos de dados relacionais (PostgreSQL, Oracle, SQL Server)

### Business Intelligence

- Dashboards interativos com Chart.js e Power BI
- Medidas DAX avançadas (CALCULATE, ALLEXCEPT, RANKX, SWITCH)
- Transformações com Linguagem M no Power Query
- Relatórios executivos para tomada de decisão

### SQL Avançado

- Common Table Expressions (CTEs) e subqueries correlacionadas
- Window functions (ROW_NUMBER, LAG, LEAD, NTILE, PERCENT_RANK)
- Joins complexos e otimização de queries
- Procedures, views e funções analíticas

### Domínio de Negócio — Logística

- Gestão de indicadores B2C e fulfillment
- Controle de inventário com classificação ABC/Curva XYZ
- Monitoramento de avarias e análise de causa raiz
- Operações em WMS, SAP e TOTVS

---

## 🛠️ Tecnologias Utilizadas

| Categoria | Tecnologias |
|-----------|-------------|
| **Frontend** | HTML5, CSS3, JavaScript (ES6+) |
| **Gráficos** | Chart.js |
| **Ícones** | Font Awesome 6 |
| **Fontes** | Google Fonts (Inter, JetBrains Mono) |
| **Design** | CSS Grid, Flexbox, Custom Properties, Media Queries |
| **Deploy** | GitHub Pages |
| **Scripts** | Python 3 (Faker, Pandas, NumPy) |
| **Ferramentas** | Git, VS Code, Power BI Desktop |

---

## 🚀 Como Executar Localmente

### Pré-requisitos

- Navegador moderno (Chrome, Firefox, Edge)
- Python 3.8+ (opcional, apenas para gerar dados sintéticos)
- Git

### Passo a passo

```bash
# 1. Clone o repositório
git clone https://github.com/kzzkaiquesds/portfolio-kaique-soares.git

# 2. Acesse o diretório do projeto
cd portfolio-kaique-soares

# 3. Abra o portfólio no navegador
# Opção A — abrir diretamente:
start index.html          # Windows
open index.html           # macOS
xdg-open index.html       # Linux

# Opção B — usar servidor local (recomendado):
python -m http.server 8000
# Acesse http://localhost:8000 no navegador
```

---

## 📈 Dados Sintéticos

O script [`scripts/gerar_dados_sinteticos.py`](scripts/gerar_dados_sinteticos.py) gera bases de dados realistas simulando operações logísticas completas, incluindo:

| Tabela | Formato | Registros | Descrição e Métricas Principais |
|--------|---------|-----------|----------------------------------|
| `dim_regioes` | CSV / JSON | 8 | Regiões com distribuição de volume, UFs e prazos padrão de SLA |
| `dim_armazens` | CSV / JSON | 3 | Centros de distribuição (São Paulo, Rio de Janeiro e Curitiba) |
| `dim_produtos` | CSV / JSON | 150 | SKUs categorizados com custo unitário, preço e classificação ABC |
| `fato_entregas` | CSV / JSON | 1.200 | Histórico com tempo de transporte, frete, status e indicador SLA (95.2%) |
| `fato_inventario` | CSV / JSON | 400 | Contagens com divergências físicas vs. WMS e acurácia ponderada (97.8%) |
| `fato_avarias` | CSV / JSON | 250 | Ocorrências por ERP (WMS/SAP/TOTVS), causa raiz e taxa de resolução (94.4%) |

### Como gerar os dados

```bash
# Instalar dependências (Faker é opcional)
pip install faker pandas numpy

# Executar o gerador
python scripts/gerar_dados_sinteticos.py
```

Os arquivos CSV serão salvos na pasta `dados/` na raiz do projeto.

---

## 📬 Contato

| Canal | Informação |
|-------|------------|
| 📧 **Email** | [kzzkaiquesds@gmail.com](mailto:kzzkaiquesds@gmail.com) |
| 💼 **LinkedIn** | [Kaique Soares de Souza](https://linkedin.com/in/kaique-soares-de-souza-732b15259/) |
| 📱 **Telefone** | (11) 94364-4063 |
| 🌐 **Portfólio** | [kzzkaiquesds.github.io/portfolio-kaique-soares](https://kzzkaiquesds.github.io/portfolio-kaique-soares/) |

---

## 📝 Licença

Este projeto está sob a licença [MIT](https://opensource.org/licenses/MIT). Sinta-se à vontade para usar como referência.

---

<p align="center">
  Desenvolvido com 💙 por <strong>Kaique Soares de Souza</strong>
  <br>
  ⭐ Se este portfólio te ajudou de alguma forma, considere dar uma estrela!
</p>
