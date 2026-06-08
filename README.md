# 🏠 Abatimento do Aluguel

Tracker interativo para controle de abatimento de dívida no aluguel. Desenvolvido em HTML, CSS e JavaScript puro — sem frameworks, sem dependências externas.

## ✨ Funcionalidades

- **Clique para marcar** parcelas como pagas ou pendentes
- **Progresso visual** com barra animada e gráficos donut
- **Cards de resumo** com total descontado, saldo restante e próxima parcela
- **Persistência local** via `localStorage` — os dados são salvos no navegador
- **Funciona offline** — nenhuma requisição externa além das fontes Google
- **Totalmente responsivo** — funciona em mobile e desktop

## 💰 Contexto

Controle de desconto mensal no aluguel referente a dois serviços:

| Item | Valor |
|------|-------|
| Blindex + vazamento pia | R$ 2.300 |
| Pedreiro | R$ 1.500 |
| **Total** | **R$ 3.700** |

**Plano de pagamento:** 9 parcelas de R$ 400 (Abr/2026 → Dez/2026) + 1 parcela final de R$ 200 (Jan/2027)

## 🗓️ Cronograma

| # | Mês | Valor |
|---|-----|-------|
| 01 | Abril 2026 | R$ 400 |
| 02 | Maio 2026 | R$ 400 |
| 03 | Junho 2026 | R$ 400 |
| 04 | Julho 2026 | R$ 400 |
| 05 | Agosto 2026 | R$ 400 |
| 06 | Setembro 2026 | R$ 400 |
| 07 | Outubro 2026 | R$ 400 |
| 08 | Novembro 2026 | R$ 400 |
| 09 | Dezembro 2026 | R$ 400 |
| 10 | Janeiro 2027 | R$ 200 |

## 🚀 Como usar

1. Abra o arquivo `index.html` diretamente no navegador
2. Clique nas parcelas para marcar como **paga** ou **pendente**
3. Os dados são salvos automaticamente no navegador

Sem instalação. Sem servidor. Sem banco de dados.

## 🛠️ Tecnologias

- HTML5 semântico
- CSS3 (variáveis, animações, grid, gradientes)
- JavaScript ES6+ (sem frameworks)
- `localStorage` para persistência de estado
- Fontes: [Syne](https://fonts.google.com/specimen/Syne) + [DM Mono](https://fonts.google.com/specimen/DM+Mono)

## 📁 Estrutura
