# 🍜 Yakisoba PDV

Sistema de ponto de venda para restaurante de yakisoba. Arquivo único em HTML, CSS e JavaScript puro — sem dependências, sem servidor, sem instalação.

## ✨ Funcionalidades

- Registro de pedidos em 4 etapas com barra de progresso
- Seleção de tamanho: Médio (R$30) ou Grande (R$32)
- Personalização de molho, gergelim e talheres (garfo ou hashi)
- Formas de pagamento: Dinheiro, Pix, Crédito e Débito
- Nome do cliente vinculado ao pedido
- Numeração automática sequencial dos pedidos
- Cupom da cozinha com tamanho em destaque (fonte grande)
- Impressão via `window.print()` ao finalizar
- Relatório de caixa com totais por forma de pagamento
- Lista de todos os pedidos do dia com detalhes
- Dados salvos no navegador (localStorage) — persistem mesmo fechando a aba
- Design responsivo otimizado para uso em tablet/celular
- Identidade visual japonesa: tons creme, vermelho escuro e dourado

## 🚀 Como usar

Abra o `index.html` diretamente no navegador. Sem servidor, sem internet.

### No GitHub Pages (recomendado para tablet no balcão)
1. Crie um repositório no GitHub
2. Faça upload do `index.html`
3. Ative o GitHub Pages em **Settings → Pages**
4. Acesse a URL pelo tablet e salve como atalho na tela inicial

## 🖨️ Impressão térmica

Ao finalizar o pedido, o sistema chama `window.print()` automaticamente.
O CSS de impressão já está configurado para largura de 58mm (cupom padrão).

Para integração direta com impressora térmica via USB/rede, recomenda-se o **QZ Tray** (qz.io).

## 🗂️ Estrutura

```
yakisoba-pdv/
└── index.html   # Aplicação completa em arquivo único
```

## 🛠️ Tecnologias

- HTML5 / CSS3 / JavaScript vanilla
- Google Fonts: Noto Serif JP + DM Sans
- localStorage para persistência dos pedidos
- `window.print()` para impressão do cupom

---

Desenvolvido como PDV simples para pequeno restaurante de yakisoba.
