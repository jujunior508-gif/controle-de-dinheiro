# Dinheiro no Controle

Landing page do ebook **Dinheiro no Controle: Kit de Organização Financeira para Autônomos**, vendido pela Kiwify.

A página inteira está em um único arquivo: `index.html` (HTML, CSS e JS inline, sem dependências além das fontes do Google Fonts).

## Antes de publicar

Edite o bloco `window.LP_CONFIG` no topo do `index.html`:

| Campo      | O que colocar                              |
|------------|--------------------------------------------|
| `checkout` | Link do checkout da Kiwify                 |
| `preco`    | Preço à vista, ex.: `R$ 47,00`             |
| `parcelas` | Número máximo de parcelas no cartão        |
| `politica` | Link da Política de privacidade            |
| `termos`   | Link dos Termos de uso                     |

Enquanto algum campo continuar entre colchetes, a página mostra uma faixa de "Rascunho" no topo.

## Publicar com GitHub Pages

Em **Settings → Pages**, escolha a branch `main` e a pasta `/ (root)`.
