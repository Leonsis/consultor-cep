# 📍 Consultor de CEP

O **Consultor de CEP** é um projeto web cujo objetivo é permitir que o usuário informe um **CEP brasileiro** e, a partir disso, o sistema retorne **os dados do endereço de forma clara, rápida e organizada**.

---

## 🎯 Objetivo do Projeto

Criar uma página simples e intuitiva onde o usuário possa:

- Informar um CEP válido  
- Consultar os dados relacionados a esse CEP  
- Visualizar as informações de forma rápida, responsiva e amigável  

O projeto tem foco em:

- ✅ Facilidade de uso  
- ✅ Organização do código  
- ✅ Separação entre frontend e backend  
- ✅ Boas práticas de desenvolvimento  

---

## 🧠 Funcionamento Geral

1. O usuário acessa a página de consulta  
2. Informa o **CEP** no campo disponível  
3. O sistema valida o formato do CEP  
4. O backend processa a requisição  
5. Os dados do endereço são retornados e exibidos na tela  

### 📌 Exemplos de dados retornados:

- Logradouro  
- Bairro  
- Cidade  
- Estado (UF)  
- Complemento (se houver)  
- Código IBGE (se aplicável)  

---

## 🛠️ Tecnologias Utilizadas

O projeto utiliza as seguintes tecnologias:

### 🌐 Frontend

- **HTML5** → Estrutura da página  
- **CSS3** → Estilização  
- **Bootstrap** → Layout responsivo e componentes visuais  
- **JavaScript** → Interações, validações e requisições assíncronas (AJAX / Fetch API)  

### ⚙️ Backend

- **PHP** → Processamento das requisições e comunicação com API externa  

### 🌍 API Externa

- API pública de consulta de CEP (ex: ViaCEP)

### 🗄️ Banco de Dados (Opcional)

- **MySQL** → Pode ser utilizado para:
  - Histórico de consultas  
  - Cache de resultados  
  - Logs do sistema  

---

## 📂 Estrutura do Projeto (Sugestão)

```
consultor-cep/
│── public/
│ ├── index.html
│ ├── css/
│ ├── js/
│── backend/
│ ├── consultar-cep.php
│── database/
│ ├── schema.sql
│── README.md
```

---

## ✅ Requisitos Funcionais

- Campo para entrada do CEP  
- Validação básica do formato (ex: 00000-000 ou 00000000)  
- Tratamento de erro para CEP inválido  
- Retorno dos dados do endereço  
- Exibição clara e organizada das informações  
- Interface responsiva  

---

## 🔐 Requisitos Não Funcionais

- Código organizado e comentado  
- Separação entre frontend e backend  
- Tempo de resposta rápido  
- Tratamento adequado de erros da API  

---

## 🚀 Futuras Melhorias

- Máscara automática para o campo de CEP  
- Preenchimento automático de formulários  
- Histórico de consultas por usuário  
- Cache de resultados para otimização  
- Sistema de autenticação  
- Transformar em API própria  

---

## 👨‍💻 Colaboração

O projeto segue um fluxo de trabalho padronizado com:

- Uso de branches  
- Commits organizados  
- Pull Requests  
- Merge realizado pelo desenvolvedor responsável  

---

## 📌 Considerações Finais

O **Consultor de CEP** é um projeto voltado para aprendizado e prática de:

- Consumo de APIs externas  
- Comunicação entre frontend e backend  
- Manipulação de requisições assíncronas  
- Estruturação organizada de projetos web  

O sistema pode evoluir facilmente para uma aplicação mais robusta e escalável.

Contribuições são bem-vindas 🚀  

---

## 👥 Colaboradores

- **Caio Leonni** - [GitHub](https://github.com/Leonsis)  