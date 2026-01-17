HACKATHON-ONE-II-2026

Este repositório reúne o projeto completo de análise automatizada de sentimentos, integrando três módulos principais:

sentimentAPI/ → Back-End (Java Spring Boot)

sentiment_Front_End/ → Front-End (React)

sentimentIA/ → Data Science (Python/Notebooks)

🚀 Como rodar cada parte

1. Back-End (sentimentAPI)

Requisitos: Java 17+, Maven

Rodar localmente:

cd sentimentAPI
mvn spring-boot:run

Rodar com Docker:

cd sentimentAPI
docker-compose up --build

2. Front-End (sentiment_Front_End)

Requisitos: Node.js 18+, npm ou yarn

Instalar dependências:

cd sentiment_Front_End
npm install

Rodar localmente:

npm run dev

O projeto estará disponível em http://localhost:5173 (ou porta configurada).

3. Data Science (sentimentIA)

Requisitos: Python 3.10+, Jupyter Notebook

Instalar dependências:

cd sentimentIA
pip install -r requirements.txt

Rodar notebooks:

jupyter notebook

Abra os notebooks .ipynb para explorar análises e modelos de Machine Learning.

🔄 Atualização com o projeto original (SentimentONE)

Cada módulo pode ser sincronizado com o repositório original usando upstream.

Exemplo de fluxo:

cd sentimentAPI
# ou sentiment_Front_End, ou sentimentIA

# Buscar mudanças do repositório original
git fetch upstream

# Mesclar mudanças
git merge upstream/main

# Voltar para a raiz
cd ..

# Registrar e enviar para o GitHub
git add .
git commit -m "Atualiza módulo com mudanças do SentimentONE"
git push origin main

Para detalhes completos, consulte o arquivo UPDATE_GUIDE.md.

📂 Estrutura Final

HACKATHON-ONE-II-2026/
 ├── sentimentAPI/         # Back-End
 ├── sentiment_Front_End/  # Front-End
 ├── sentimentIA/          # Data Science
 └── README.md             # Este guia geral

✨ Objetivo

O projeto HACKATHON-ONE-II-2026 integra Back-End, Front-End e Data Science em um único repositório, facilitando a colaboração, manutenção e evolução contínua da solução de análise de sentimentos.

📄 Modelo de README.md para a raiz
markdown
# HACKATHON-ONE-II-2026

Este repositório reúne o projeto completo de **Análise Automatizada de Sentimentos**, integrando três módulos principais:

- **sentimentAPI/** → Back-End (Java Spring Boot)
- **sentiment_Front_End/** → Front-End (React)
- **sentimentIA/** → Data Science (Python/Notebooks)

---

## 🚀 Como rodar cada parte

### 1. Back-End (sentimentAPI)
- **Requisitos:** Java 17+, Maven
- **Rodar localmente:**
  ```bash
  cd sentimentAPI
  mvn spring-boot:run
Rodar com Docker:

bash
cd sentimentAPI
docker-compose up --build
2. Front-End (sentiment_Front_End)
Requisitos: Node.js  18+, npm ou yarn

Instalar dependências:

bash
cd sentiment_Front_End
npm install
Rodar localmente:

bash
npm run dev
O projeto estará disponível em http://localhost:5173 (ou porta configurada).

3. Data Science (sentimentIA)
Requisitos: Python 3.10+, Jupyter Notebook

Instalar dependências:

bash
cd sentimentIA
pip install -r requirements.txt
Rodar notebooks:

bash
jupyter notebook
Abra os notebooks .ipynb para explorar análises e modelos de Machine Learning.

🔄 Atualização com o projeto original (SentimentONE)
Cada módulo pode ser sincronizado com o repositório original usando upstream.

Exemplo de fluxo:
bash
cd sentimentAPI
# ou sentiment_Front_End, ou sentimentIA

# Buscar mudanças do repositório original
git fetch upstream

# Mesclar mudanças
git merge upstream/main

# Voltar para a raiz
cd ..

# Registrar e enviar para o GitHub
git add .
git commit -m "Atualiza módulo com mudanças do SentimentONE"
git push origin main
Para detalhes completos, consulte o arquivo UPDATE_GUIDE.md.

📂 Estrutura Final
Código
HACKATHON-ONE-II-2026/
 ├── sentimentAPI/         # Back-End
 ├── sentiment_Front_End/  # Front-End
 ├── sentimentIA/          # Data Science
 └── README.md             # Este guia geral
✨ Objetivo
O projeto HACKATHON-ONE-II-2026 integra Back-End, Front-End e Data Science em um único repositório, facilitando a colaboração, manutenção e evolução contínua da solução de análise de sentimentos.

Código

---

👉 Sugestão: copie esse conteúdo para um arquivo chamado **`README.md`** na raiz do seu repositório (`C:\Users\eduar\HACKATHON-ONE-II-2026`).  
Depois rode:

```bash
git add README.md
git commit -m "Adiciona README geral explicando execução e atualização"
git push origin main
