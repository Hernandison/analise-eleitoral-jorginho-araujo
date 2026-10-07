# Análise Eleitoral — Jorginho Araujo (55777 · PSD)

Site interativo com a análise de inteligência eleitoral do candidato a **Deputado Estadual**
**Jorginho Araujo (nº 55777, PSD)** nas **Eleições 2026 — Sergipe, 1º turno**.

🔗 **Site publicado:** veja a aba *Deployments / GitHub Pages* deste repositório.

## Conteúdo
- **Resumo executivo** com os principais indicadores
- **Mapa coroplético interativo** dos 75 municípios (% dos válidos e votos absolutos)
- **Ranking estadual** dos candidatos a Deputado Estadual
- **Desempenho por município** com gráficos e tabela pesquisável/ordenável
- **Análise por seção/urna** (distribuição e urnas mais produtivas)
- **Redutos eleitorais** (municípios onde foi o mais votado)
- **Downloads** dos relatórios em PDF e planilhas CSV

## Dados
- **Fonte:** TSE — Boletim de Urna Web (BWEB), 1º turno 2026.
- **Malha municipal:** IBGE.
- **Votos válidos** = nominais + legenda do cargo.

## Como funciona
Site estático (HTML/CSS/JS puro). Visualizações com [Leaflet](https://leafletjs.com) (mapa)
e [Chart.js](https://www.chartjs.org) (gráficos). Todos os dados ficam em `data/dados.js`.

```
index.html
assets/css/style.css
assets/js/app.js
data/dados.js          # dados consolidados (resumo, municípios, ranking, malha)
downloads/             # PDFs e CSVs
```

## Desenvolvimento local
Abra `index.html` direto no navegador, ou sirva a pasta:

```bash
python -m http.server 8000
# acesse http://localhost:8000
```

---
Relatório analítico independente baseado em dados públicos oficiais.
