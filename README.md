# api-docs
Documentação das APIs abertas da Férias&amp;Co.

[https://ferias-co.github.io/api-docs/](https://ferias-co.github.io/api-docs/)

## Desenvolvimento

Documentação gerada com o [ReDoc](https://github.com/Redocly/redoc/blob/master/README.md).

```
# Clonar e instalar dependências:

git clone https://github.com/Ferias-Co/api-docs.git
cd api-docs
npm install

# Rodar localmente em localhost:8080:

npm run serve

# Gerar o html:

npm run bundle
```

As definições da API estão no arquivo `swagger.yml` em formato OpenAPI 2.0. [Ver referência](https://swagger.io/specification/v2/).

## Customização e tema

Opções de exibição e customização do tema podem ser definidas no elemento `<redoc>` do em `template.hbs`. [Ver referência](https://github.com/Redocly/redoc#redoc-options-object).

Para alterar o logo, adicionar o arquivo em `/docs` e substituir a url nas definições da API:

```
  title: "API title"
  x-logo:
    url: https://ferias-co.github.io/api-docs/logo.jpg
    altText: API title
```
