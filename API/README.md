# 🌍 Informações sobre Países

Aplicação web que permite buscar informações detalhadas sobre qualquer país do mundo utilizando uma API pública.

## 📋 Descrição

O usuário digita o nome de um país e a aplicação consulta a [REST Countries API](https://restcountries.com/) para exibir dados como capital, população, área, região e a bandeira do país em tempo real.

## 🚀 Funcionalidades

- Busca de países pelo nome completo
- Exibição da bandeira do país
- Informações sobre capital, população, área e região
- Tratamento de erros para países não encontrados

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura da página |
| CSS3 | Estilização e layout |
| JavaScript (ES6+) | Lógica e consumo de API |
| REST Countries API | Fonte dos dados dos países |

## 📁 Estrutura do Projeto

```
API/
├── index.html       # Página principal
├── app.js           # Lógica JavaScript e chamadas à API
└── css/
    └── styles.css   # Estilos da aplicação
```

## ▶️ Como Executar

1. Clone ou baixe o repositório
2. Abra o arquivo `index.html` diretamente no navegador
3. Digite o nome de um país em inglês no campo de busca e clique em **Buscar**

> Nenhuma instalação ou dependência necessária — o projeto roda diretamente no navegador.

## 🔗 API Utilizada

- **REST Countries** — `https://restcountries.com/v3.1/name/{nome}`
