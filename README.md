# 🗳️ Análise de Raça nas Eleições 2022

Este projeto tem como objetivo analisar a **autodeclaração racial de candidatos às eleições de 2014, 2018 e 2022 no Brasil**, buscando compreender como a raça, o gênero, o nível de escolaridade e o cargo disputado se distribuem entre os candidatos de diferentes estados.

---

## 📌 Motivação

Embora o Brasil tenha uma população majoritariamente composta por pessoas negras (pretas e pardas), essa diversidade **ainda não se reflete proporcionalmente nos cargos políticos**. Este projeto visa:

- Investigar **a representatividade racial** nas candidaturas.
- Analisar relações entre **raça, escolaridade, gênero e cargo**.
- Produzir **relatórios e gráficos acessíveis** com base em dados oficiais.

---

## 🧰 Tecnologias utilizadas

| Ferramenta       | Finalidade                             |
|------------------|----------------------------------------|
| Python           | Análise e tratamento de dados          |
| Jupyter Notebook | Organização e execução dos scripts     |
| Pandas           | Leitura e manipulação de dados         |
| Plotly           | Visualizações gráficas interativas     |
| OpenPyXL         | Exportação de relatórios em Excel      |

---

## 📂 Estrutura do projeto

```
analise-raca-eleicoes/
└── 2022/
    └── REGIÃO/
        └── ESTADO/
            ├── AnaliseXX.ipynb
            ├── consulta_cand_2022_XX.csv
            ├── dadosXX.xlsx
            ├── relatorioXX.csv
            └── outros notebooks auxiliares
```

- `AnaliseXX.ipynb`: análise principal do estado
- `verifica_genero.ipynb`: análise cruzada de gênero e cargo
- `civil_escolaridade.ipynb`: escolaridade vs estado civil
- `relatorioXX.csv/xlsx`: dados consolidados por estado

---

## 📊 Exemplos de análises realizadas

- ✅ Percentual de candidatos por raça: branco, preto, pardo, indígena, amarelo
- ✅ Correlação entre **cor/raça e escolaridade**
- ✅ Distribuição de **raça por cargo disputado**
- ✅ Análise cruzada entre **raça e gênero**
- ✅ Geração de relatórios e médias por estado

---

## 📥 Fontes dos dados

Todos os dados utilizados neste projeto são públicos e foram obtidos diretamente do [Tribunal Superior Eleitoral (TSE)](https://www.tse.jus.br/).

---

## 👥 Público-alvo

Este projeto pode ser útil para:

- Pesquisadores e cientistas sociais
- Jornalistas e comunicadores
- Estudantes e educadores
- Cidadãos interessados em representatividade política

---

## 🚀 Como executar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/GabriellCabrall/analise-raca-eleicoes.git
   ```
2. Instale as dependências:
   ```bash
   pip install pandas openpyxl plotly jupyter
   ```
3. Inicie o Jupyter:
   ```bash
   jupyter notebook
   ```
4. Acesse os notebooks dentro da pasta do estado desejado.

---

## 🤝 Contribuições

Contribuições são bem-vindas! Você pode:

- Corrigir erros
- Sugerir novas análises ou visualizações
- Ajudar a unificar os dados por região ou nacionalmente

---

## 📬 Contato

Gabriell Cabral  
📧 gscabral42@gmail.com  
🔗 [Gabriel Cabral (linkedin)](https://www.linkedin.com/in/gabriel-cabral-b32090248/)

---

**🌱 Um passo em direção à compreensão e à equidade na política brasileira.**
