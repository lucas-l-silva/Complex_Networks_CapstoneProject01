# 📘 Relatório - Análise de Redes Complexas

Este repositório contém o relatório e os notebooks utilizados na disciplina **Análise de Redes Complexas**, ofertada no curso de **Ciência de Dados - UFC**.

---

## 📌 Descrição

O trabalho consiste na análise de três redes distintas com base em propriedades estruturais, métricas de centralidade e visualizações. As redes analisadas são:

- `san200-0-9-3.mtx`: Rede sintética quase completa.
- `ia-infect-dublin.mtx`: Rede de contatos urbanos durante um surto infeccioso.
- `ia-hospital-ward-proximity-attr.csv`: Rede hospitalar baseada em contatos por categoria profissional.

---

## 📂 Estrutura do Repositório
```
├── Trabalho1_LucasSilva_ARC.ipynb     # Notebook com todas as análises e gráficos
├── trabalho_comp1.ipynb               # Notebook com as instruções do trabalho
├── data/                              # Arquivos de dados utilizados
│   ├── san200-0-9-3.mtx
│   ├── ia-infect-dublin.mtx
│   └── ia-hospital-ward-proximity-attr.csv
└── README.md                          
```
---

## 🧪 Tecnologias e Bibliotecas

- Python 3.10+
- Jupyter Notebook
- [NetworkX](https://networkx.org/)
- Matplotlib, Seaborn, Plotly
- Pandas, NumPy, SciPy

---

## 🧠 Objetivos de Aprendizado

- Aplicar conceitos da Teoria de Redes para caracterização estrutural de grafos.
- Calcular métricas como densidade, excentricidade, coeficientes de centralidade e k-cores.
- Gerar visualizações interpretáveis das redes.
- Compreender padrões de conectividade em contextos reais (hospital, cidade) e sintéticos.

---

## 📈 Resultados Destacados

- A rede `san200-0-9-3` é quase completa, com alto grau de conectividade e baixa excentricidade.
- A rede `ia-infect-dublin` apresenta estrutura em camadas, evidenciada por sua decomposição em k-cores.
- A rede hospitalar é heterofílica, com assortatividade negativa entre os papéis de vértices.

---

## 👨‍💻 Autor

**Lucas Lopes Silva**
Curso: Ciência de Dados – Universidade Federal do Ceará

---

## 📄 Licença

Este projeto é parte de um trabalho acadêmico e está disponível apenas para fins educacionais.
