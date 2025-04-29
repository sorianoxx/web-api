# 🌐 Formulário Web com CEP Automático e Arquivo JSON

Este projeto é uma página HTML interativa que permite:

- Preenchimento automático de endereço via CEP (usando a [BrasilAPI](https://brasilapi.com.br));
- Upload de um arquivo `.json` com dados pessoais;
- Salvamento dos dados preenchidos em um novo arquivo `.json`.


## ⚙️ Funcionalidades

- 🧠 **Busca de endereço por CEP**: Ao sair do campo de CEP, os dados são preenchidos automaticamente via [BrasilAPI](https://brasilapi.com.br).
- 📂 **Importar JSON**: Ao selecionar um arquivo `.json`, os dados são carregados no formulário.
- 💾 **Exportar JSON**: Ao clicar em "Salvar", um arquivo `dados.json` é gerado com os dados do formulário.

## ▶️ Como Usar

1. Abra o arquivo `webapi.html` no navegador.
2. Digite um nome e um CEP válido (ex: `58056600`).
3. O restante do endereço será preenchido automaticamente.
4. Clique em **"Salvar"** para baixar os dados como `dados.json`.
5. Você também pode importar um `dados.json` clicando em **"Escolher arquivo"**.

## 🛠️ Tecnologias Usadas

- HTML5  
- JavaScript  
- [BrasilAPI - CEP](https://brasilapi.com.br)


## 📁 Arquivos do Projeto

- `webapi.html`: Interface HTML e JavaScript para preenchimento de formulário, integração com API e manipulação de arquivos JSON.
- `dados.json`: Exemplo de arquivo JSON compatível com o formulário.

### 📦 Exemplo de `dados.json`

```json
{
  "nome": "Pedro",
  "cep": "58056600",
  "rua": "Rua Pedro Segundo",
  "bairro": "Logradouro",
  "cidade": "Joao Pessoa",
  "estado": "PB"
}
