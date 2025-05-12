# ClimaBR 🌤️

Aplicação web que mostra a previsão do tempo em cidades do Brasil, utilizando a API do OpenWeather e dados do IBGE para busca de estados e cidades.

![Captura de Tela](/app_clima.png)

## 🚀 Funcionalidades

- Busca inteligente por estado e cidade

- Autocomplete para estados e cidades

- Exibição em tempo real de:
  - Temperatura atual
  - Sensação térmica
  - Umidade relativa do ar
  - Velocidade do vento
  - Pressão atmosférica

- Interface totalmente responsiva

- Ícones ilustrativos para cada métrica

## 🛠️ Tecnologias

- HTML5
- CSS3
- JavaScript (ES6)
- React (via CDN)
- Axios (requisições HTTP)

- **APIs**
  - OpenWeatherMap (dados climáticos)
  - IBGE (dados geográficos)

## 📦 Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/climabr.git

2. Abra o arquivo index.html no navegador:

    - Método 1: Clique duplo no arquivo

    - Método 2: Use a extensão Live Server no VS Code

⚠️ Este projeto não requer instalação de dependências (usa React e Babel via CDN).

## 🔑 Chave da API
O app usa a chave gratuita da API do OpenWeather (appid). Se quiser usar sua própria chave:

1. Cadastre-se em: https://openweathermap.org/api

2. Gere sua chave API

3. No arquivo principal, substitua:

``` bash
    const API_KEY = "SUA_CHAVE_AQUI";
```
Linha 327

## 📄 Licença
Este projeto está sob a licença MIT.

## Créditos:

- Dados meteorológicos por OpenWeatherMap

- Ícones por Font Awesome

- Dados geográficos por IBGE

## 👨‍💻 Desenvolvido por [Gabriel](https://github.com/Pfabiano32) com 💻 e ☕
