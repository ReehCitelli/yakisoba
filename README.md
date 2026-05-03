# 🍜 Yakisoba PDV

Sistema de ponto de venda (PDV) para restaurante de yakisoba. Desenvolvido com HTML, CSS e JavaScript puro — sem dependências externas.

## ✨ Funcionalidades

- **Registro de pedidos** em 4 etapas simples
- **Personalização** de molho, gergelim e talheres (garfo ou hashi)
- **Formas de pagamento**: dinheiro, Pix, crédito e débito
- **Numeração automática** dos pedidos
- **Cupom da cozinha** com tamanho em destaque para fácil identificação
- **Impressão** via `window.print()` ao finalizar pedido
- **Relatório de caixa** com totais por forma de pagamento e produtos vendidos
- **Modo escuro** automático (respeita preferência do sistema)
- **Dados salvos localmente** no navegador (localStorage)

## 🚀 Como usar

Basta abrir o arquivo `index.html` no navegador. Não precisa de servidor, instalação ou internet.

Para usar no tablet/celular do balcão:
1. Coloque o arquivo em qualquer servidor web (GitHub Pages, por exemplo)
2. Acesse a URL pelo navegador do dispositivo
3. Salve como atalho na tela inicial para parecer um app

## 🖨️ Impressão

Ao clicar em "Finalizar e imprimir", o sistema chama `window.print()` automaticamente. Para conectar a uma impressora térmica real, recomenda-se o uso do **QZ Tray** (qz.io) como intermediário entre o navegador e a impressora.

## 🗂️ Estrutura

```
yakisoba-pdv/
└── index.html   # Aplicação completa em arquivo único
```

## 🛠️ Tecnologias

- HTML5
- CSS3 (variáveis CSS, dark mode, responsivo)
- JavaScript vanilla
- localStorage para persistência dos dados

---

Desenvolvido como sistema de PDV simples para pequeno restaurante.
