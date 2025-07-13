<center><h1 style="color:#FA8072">📊 Telecom X - Etapa 2</h1></center>

<center><h2 style="color:#FA8072">🧠 Modelagem Preditiva de Evasão de Clientes</h2></center>

Este projeto tem como objetivo desenvolver modelos preditivos supervisionados com foco na **identificação de clientes com maior probabilidade de evasão (cancelamento de serviços)** em uma empresa do setor de telecomunicações fictícia: **Telecom X**.

---

<h3 style="color:#FA8072">✅ Objetivo Geral</h3>

- Criar um pipeline robusto de Ciência de Dados para prever **evasão de clientes**.
- Auxiliar a empresa na **tomada de decisões estratégicas** voltadas à **retenção de clientes**.

---

<h3 style="color:#FA8072">🧰 Tecnologias, Bibliotecas e Ferramentas Utilizadas</h3>

<h4 style="color:#FA8072">📦 Bibliotecas Python</h4>

- `pandas` – manipulação e estruturação de dados  
- `numpy` – operações matemáticas e vetorização  
- `matplotlib` – criação de gráficos  
- `seaborn` – visualização estatística  
- `scikit-learn` – pré-processamento, modelagem, avaliação e métricas  
- `joblib` – salvamento de modelos  
- `IPython.display` – exibição personalizada de outputs  
- `typing` – anotação de tipos (boas práticas)  

<h4 style="color:#FA8072">🛠️ Ferramentas e Ambiente</h4>

- **Jupyter Notebook / VS Code** – ambiente de desenvolvimento  
- **Python 3.10+**  
- **Sistema Operacional Windows**  
- **Git** – versionamento de código  
- **Markdown e HTML** – formatação de relatórios no notebook  

---

<h3 style="color:#FA8072">🔍 Etapas do Projeto</h3>

<h4 style="color:#FA8072">1. Extração de Dados</h4>
- Leitura da base de dados `.csv`.
- Visualização inicial da estrutura da tabela.

<h4 style="color:#FA8072">2. Análise Exploratória de Dados (EDA)</h4>
- Inspeção de tipos de variáveis.
- Proporção da variável-alvo `churn`.
- Gráficos de distribuição, histogramas, correlações.

<h4 style="color:#FA8072">3. Limpeza e Pré-processamento</h4>
- Exclusão de colunas irrelevantes.
- Codificação de variáveis.
- Normalização e tratamento de dados ausentes.

<h4 style="color:#FA8072">4. Seleção de Variáveis</h4>
- Avaliação de correlação.
- Eliminação de atributos redundantes.

<h4 style="color:#FA8072">5. Divisão Treino/Teste</h4>
- Split de 70% treino e 30% teste com estratificação.

<h4 style="color:#FA8072">6. Modelagem Preditiva</h4>
- Modelos: Regressão Logística, Random Forest, etc.
- Treinamento e predição com `scikit-learn`.

<h4 style="color:#FA8072">7. Avaliação dos Modelos</h4>
- Acurácia, Precisão, Recall, F1-Score.
- Interpretação de métricas.

---

<h3 style="color:#FA8072">🧠 Conclusão e Insights Estratégicos</h3>

- **Regressão Logística** teve melhor desempenho (acurácia ~79,96%).  
- **Random Forest** teve bom desempenho geral, mas menor sensibilidade.  
- Variáveis mais relevantes para evasão:
  - **Tempo de contrato** (menor tempo, maior evasão)
  - **Valor mensal elevado**
  - **Tipo de contrato** e **forma de pagamento**

---

<h3 style="color:#FA8072">📝 Possíveis Melhorias Futuras</h3>

- Validação cruzada estratificada (`StratifiedKFold`)  
- Algoritmos como XGBoost ou LightGBM  
- Técnicas de balanceamento (SMOTE, `class_weight`)  
- Criação de dashboard com visualização interativa dos resultados  

---

<h3 style="color:#FA8072">📁 Estrutura de Arquivos</h3>

├── Challenge_TelecomX_2_BR_.ipynb

├── README.md ← (este arquivo)

└── data/

└── dados_tratados.csv


---

<h3 style="color:#FA8072">👤 Autor</h3>

**Danilo Pelaes de Almeida**  
Biólogo | Cientista de Dados Júnior | Doutorando em Biodiversidade Tropical  
📧 danilopelaes@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/danilo-almeida-00107b64)

---

