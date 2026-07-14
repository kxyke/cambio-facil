# CâmbioFácil

> Conversor de moedas simples e direto, escrito em HTML, CSS e JavaScript puro.

## Funcionalidades

- Conversão de **Dólar Americano (USD)**, **Euro (EUR)** e **Libra Esterlina (GBP)** para **Real (BRL)**
- Interface limpa e responsiva
- Validação de entrada (aceita somente números)
- Exibição da cotação utilizada e do valor total convertido, formatados no padrão monetário brasileiro (`pt-BR`)

## Como usar

```bash
git clone git@github.com:kxyke/cambio-facil.git
cd cambio-facil
```

Depois é só abrir o `index.html` no navegador (ou usar uma extensão como o Live Server do VS Code).

1. Digite o valor
2. Selecione a moeda
3. Clique em **Converter em reais**

## Tecnologias

- HTML5
- CSS3
- JavaScript (Vanilla)

## Estrutura do projeto

```
├── index.html      # Estrutura da página
├── styles.css      # Estilização
├── scripts.js      # Lógica de conversão
└── img/            # Ícones e imagens
```

## Observações

As cotações utilizadas são fixas no código (`scripts.js`) e servem para fins de demonstração. Para uso em produção, o ideal é integrar uma API de câmbio em tempo real, como a [AwesomeAPI](https://docs.awesomeapi.com.br/api-de-moedas) ou a [ExchangeRate-API](https://www.exchangerate-api.com/).
