# Clima

É um projeto que mostra o clima atual na sua região. Podendo ser bairro, cidade/estado ou país.

As informações que ele fornece são:
- Nome da região;
- Temperatura mínima e máxima;
- Umidade;
- Velocidade do vento;
- Condição climática.

Este projeto foi desenvolvido com o objetivo de colocar em prática e consolidar meus conhecimentos e estudos em **React** e **TypeScript**.

## O que aprendi nesse projeto

Esse foi meu primeiro projeto usando React e TypeScript.

Nesse projeto aprendi:
- Requisição e manipulação dos dados retornados da API;
- UseState e reutilização de componentes;
- Variáveis de ambiente e git ignore;

## Tecnologias utilizadas

- React
- TypeScript
- CSS
- Git
- Vite

## API utilizada

- OpenWeather

## Dependências e versões necessárias

- Node.js - versão: v22.19.0 ou superior

## 🖥️ Como rodar o projeto na sua máquina

### Pré-requisitos

- Tenha uma IDE instalada.
	- Recomendo o **VS Code**, pois é um programa leve e simples de usar.
- Cadastre-se na [**OpenWeather**](https://openweathermap.org/) para pegar uma **chave** gerada. O projeto utiliza essa chave para realizar as requisições à API.

#### Passo a passo

1. No repositório do projeto, clique em **Code**.
2. Clique em **Download ZIP**. Faça o download no seu desktop.
3. Após o download, extraia o arquivo ZIP.
4. Clique com botão direito na pasta extraída.
5. Clique em **Abrir com o Code**.
6. Abra o terminal na sua IDE.
7. Instale as dependências:

```
npm install
```

Aguarde até que o comando seja concluído.

8. Acesse a sua conta da OpenWeather e copie a sua chave de api.
9. Na raiz do projeto, localize `.env-exemplo` e altere o nome dele para `.env`.
10. Acesse o arquivo e substitua `sua-chave` pela chave copiada.
11. Volte para linha de comando do terminal e rode o projeto:

```
npm run dev -- --host
```

12. Copie a URL do Local/Network e cole na barra de endereço do seu navegador.

Para acessar em outros dispositivos, use a URL do Network do projeto.
