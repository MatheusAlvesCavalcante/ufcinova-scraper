# 🕸️ Projeto de Web Scraping da UFCINOVA  


**Universidade:** Universidade Federal do Ceará (UFC)  
**Curso:** Ciência de Dados  

---

## Objetivo  
Este projeto realiza **web scraping** do portal [UFCINOVA](https://ufcinova.ufc.br/pt/vitrinetecnologica/), coletando informações das **tecnologias desenvolvidas na UFC**, como:

- 🧾 **Título da tecnologia**  
- 🧩 **Descrição detalhada**  
- 💡 **Benefícios principais**  
- 📊 **TRL (Technology Readiness Level)**  
- ⚙️ **Status de desenvolvimento**  
- 👨‍🔬 **Inventores e pesquisadores**  

O resultado é salvo em arquivos **CSV** e **JSON**, prontos para análise e visualização.

---

##  Tecnologias Utilizadas  
| Categoria | Ferramentas |
|------------|-------------|
| Linguagem | 🐍 Python |
| Web Scraping | `requests`, `BeautifulSoup4` |
| Manipulação de dados | `pandas` |
| Confiabilidade | `time`, `urllib`, `tenacity` |
| Ambiente de execução | Google Colab / Jupyter Notebook |

---

##  Como Executar  

###  Instalar dependências:
```bash
pip install requests beautifulsoup4 pandas tenacity urllib3 lxml
