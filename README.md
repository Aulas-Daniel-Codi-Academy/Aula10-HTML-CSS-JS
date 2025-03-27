# 📍 Buscar Endereço pelo CEP

Pequeno sistema de busca de endereço através do CEP, utilizando a [BrasilAPI](https://brasilapi.com.br).

## 🚀 Tecnologias Utilizadas

- **HTML**
- **CSS**
- **JavaScript**
- **[BrasilAPI](https://brasilapi.com.br)** - API pública utilizada para buscar os dados dos endereços via CEP.

## 🎯 Funcionalidades

- Busca de endereço a partir da digitação de um CEP válido.
- Exibição dos dados retornados pela API (rua, bairro, cidade, estado, etc.).
- Validação básica do CEP antes da requisição.

## 🖼️ Demonstração

> _(Opcional: insira aqui um print ou um gif da aplicação em funcionamento)_

## 💻 Como utilizar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/buscar-endereco-cep.git
```

2. Abra o arquivo `index.html` em seu navegador.

> Não é necessário servidor ou backend — o projeto roda 100% no navegador.

## 🔗 Exemplo de requisição à API

```
GET https://brasilapi.com.br/api/cep/v1/01001-000
```

Resposta:

```json
{
  "cep": "01001-000",
  "state": "SP",
  "city": "São Paulo",
  "neighborhood": "Sé",
  "street": "Praça da Sé"
}
```

## 📁 Estrutura de Arquivos

```
📦 buscar-endereco-cep
├── index.html
├── style.css
└── script.js
```

## 📝 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usá-lo e modificá-lo.
