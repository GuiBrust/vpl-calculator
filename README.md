# 📊 Calculadora de VPL (Valor Presente Líquido)

Uma aplicação web interativa para calcular o Valor Presente Líquido (VPL) de projetos de investimento, desenvolvida com React e TypeScript.

## 🎯 O que é Valor Presente Líquido (VPL)?

O **Valor Presente Líquido (VPL)** é um indicador financeiro fundamental usado para avaliar a viabilidade de projetos de investimento. Ele é calculado através da subtração do investimento inicial do projeto do valor presente de suas entradas de caixa, descontados às taxas de juros da empresa.

Na aplicação, o período de tempo é obtido automaticamente a partir da quantidade de fluxos de caixa adicionados.

### Fórmula
```
VPL = -I₀ + Σ [FCₜ / (1 + i)ᵗ]
```

Onde:
- **I₀** = Investimento inicial
- **FCₜ** = Fluxo de caixa no período t
- **i** = Taxa de desconto
- **t** = Período de tempo

## ✨ Funcionalidades

- ✅ Cálculo dinâmico de VPL em tempo real
- ✅ Interface intuitiva e responsiva
- ✅ Suporte para múltiplos fluxos de caixa
- ✅ Visualização de fórmulas matemáticas
- ✅ Navegação simples entre seções

## 🚀 Como Usar

### Pré-requisitos
- Node.js (v12 ou superior)
- npm ou yarn

### Instalação

```bash
# Clone o repositório
git clone https://github.com/GuiBrust/vpl-calculator.git
cd vpl-calculator

# Instale as dependências
npm install
# ou
yarn install
```

### Executar Localmente

```bash
# Inicia o servidor de desenvolvimento
npm start
# ou
yarn start
```

A aplicação abrirá em [http://localhost:3000](http://localhost:3000)

### Build para Produção

```bash
npm run build
# ou
yarn build
```

## 🛠 Tecnologias Utilizadas

- **React** 16+ - Biblioteca JavaScript para construção de interfaces
- **TypeScript** - Tipagem estática para JavaScript
- **React Router DOM** - Roteamento de aplicação
- **Styled Components** - Estilização com CSS-in-JS
- **React MathJax** - Renderização de equações matemáticas
- **Jest & React Testing Library** - Testes automatizados

## 📁 Estrutura do Projeto

```
vpl-calculator/
├── public/              # Arquivos públicos
├── src/                 # Código-fonte
│   ├── components/      # Componentes React
│   ├── pages/           # Páginas da aplicação
│   ├── App.tsx          # Componente principal
│   └── index.tsx        # Ponto de entrada
├── package.json         # Dependências do projeto
├── tsconfig.json        # Configuração TypeScript
└── README.md            # Este arquivo
```

## 🧪 Testes

Para executar os testes:

```bash
npm test
# ou
yarn test
```

## 📝 Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

## 👤 Autor

**Guilherme Brust**

Repositório: [GuiBrust/vpl-calculator](https://github.com/GuiBrust/vpl-calculator)

---

**Desenvolvido com ❤️ para análise e avaliação de investimentos**