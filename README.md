# Web App Nomes - IBGE

Uma aplicação web desenvolvida com Streamlit que permite consultar dados de frequência de nomes por década através da API do IBGE (Instituto Brasileiro de Geografia e Estatística).

## 📋 Sobre o Projeto

Este projeto consome a API de nomes do IBGE para exibir estatísticas sobre a frequência de nomes ao longo das décadas no Brasil. A aplicação apresenta os dados em formato de tabela e gráfico de linha, facilitando a visualização da evolução da popularidade dos nomes ao longo do tempo.

**Fonte dos dados:** [API de Nomes do IBGE](https://servicodados.ibge.gov.br/api/docs/nomes?versao=2)

## 🚀 Tecnologias Utilizadas

- **Python** - Linguagem de programação
- **Streamlit** - Framework para criação de aplicações web
- **Pandas** - Biblioteca para manipulação e análise de dados
- **Requests** - Biblioteca para fazer requisições HTTP à API do IBGE

## 📦 Pré-requisitos

Antes de começar, você precisará ter instalado:

- Python 3.7 ou superior
- pip (gerenciador de pacotes do Python)

## 🔧 Instalação

1. **Clone o repositório ou baixe o projeto:**
   ```bash
   git clone <url-do-repositório>
   cd MiniprojetoWebAppIBGE
   ```

2. **Crie um ambiente virtual (recomendado):**
   ```bash
   python -m venv venv-webapp-ibge
   ```

3. **Ative o ambiente virtual:**
   
   **Windows:**
   ```bash
   venv-webapp-ibge\Scripts\activate
   ```
   
   **Linux/Mac:**
   ```bash
   source venv-webapp-ibge/bin/activate
   ```

4. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Como Executar

1. **Certifique-se de que o ambiente virtual está ativado**

2. **Execute a aplicação:**
   ```bash
   streamlit run miniprojeto_webapp_ibge.py
   ```

3. **Acesse no navegador:**
   
   A aplicação será aberta automaticamente no navegador padrão. Caso isso não aconteça, acesse:
   ```
   http://localhost:8501
   ```

## 🎯 Funcionalidades

- **Consulta de nomes:** Digite qualquer nome para consultar sua frequência ao longo das décadas
- **Visualização em tabela:** Veja os dados organizados por década em formato tabular
- **Gráfico de evolução:** Visualize a evolução da popularidade do nome através de um gráfico de linha
- **Interface interativa:** Interface simples e intuitiva construída com Streamlit

## 📁 Estrutura do Projeto

```
MiniprojetoWebAppIBGE/
│
├── miniprojeto_webapp_ibge.py    # Arquivo principal da aplicação
├── requirements.txt               # Dependências do projeto
├── README.md                      # Documentação do projeto
└── venv-webapp-ibge/             # Ambiente virtual (não versionar)
```

## 🛠️ Funcionamento

1. O usuário insere um nome no campo de texto
2. A aplicação faz uma requisição à API do IBGE para buscar os dados do nome
3. Os dados são processados e organizados por década
4. Os resultados são exibidos em uma tabela e em um gráfico de linha

## 📝 Notas

- A aplicação requer conexão com a internet para acessar a API do IBGE
- Se um nome não for encontrado na base de dados do IBGE, uma mensagem de aviso será exibida
- Os dados são atualizados conforme a disponibilidade da API do IBGE

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## 📄 Licença

Este projeto é de código aberto e está disponível para uso educacional e pessoal.

## 👤 Autor

Desenvolvido como parte de um miniprojeto web utilizando dados do IBGE.

---

**Desenvolvido com ❤️ usando Streamlit**

