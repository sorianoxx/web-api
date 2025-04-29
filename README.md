
---

### 📁 2. `README.md` para o **Formulário HTML com CEP e JSON**

```markdown
# 🧾 Formulário com CEP e Arquivo JSON

Este é um formulário HTML interativo com funcionalidades de:

- 🔎 Busca automática de endereço ao digitar o **CEP**.
- 💾 Salvamento dos dados em um arquivo `.json`.
- 📂 Carregamento de dados via upload de arquivo `.json`.

## ✅ Funcionalidades

- Preenchimento automático de **rua**, **bairro**, **cidade** e **estado** com base no CEP informado.
- Upload de arquivo `.json` para preencher os campos automaticamente.
- Download de um arquivo `.json` com os dados preenchidos no formulário.

## 💻 Tecnologias

- HTML5
- JavaScript
- [BrasilAPI](https://brasilapi.com.br) (para consulta de CEP)

## 📦 Como usar

1. **Digite seu nome.**
2. **Digite um CEP válido** e saia do campo para preenchimento automático.
3. **Complete ou revise os dados.**
4. **Clique em "Salvar"** para baixar um arquivo `dados.json`.
5. **Use o campo de upload** para carregar um arquivo `.json` com dados já salvos.

### Exemplo de JSON gerado:

```json
{
  "nome": "João da Silva",
  "cep": "01001-000",
  "rua": "Praça da Sé",
  "bairro": "Sé",
  "cidade": "São Paulo",
  "estado": "SP"
}
