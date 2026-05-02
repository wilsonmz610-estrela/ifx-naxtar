# Especificações — Página de Vendas Manual Low Carb

**Status:** Blueprint completo recebido em 02/05/2025. Página construída.

---

## Produto

- **Nome:** Manual Low Carb
- **Plataforma de venda:** Kiwify
- **Preço:** R$ 47,00 (ou 6x de R$ 8,78 sem juros)
- **Entrega:** PDF digital, acesso imediato por e-mail
- **Garantia:** 7 dias, incondicional

## Conteúdo incluído

- Manual Low Carb — 50 receitas organizadas por momento do dia
- Bônus 1: 10 Receitas de Sorvete Low Carb
- Bônus 2: 20 Receitas de Sobremesa Low Carb

## Funil de vendas (configurar no Kiwify)

- **Order bump:** Ebook Receitas de Aves — R$ 29,90
- **Upsell pós-compra:** Combo Detox — R$ 97
- **Downsell:** Sucos Detox — R$ 29,90
- ⚠️ Nada disso aparece na página de vendas — é invisível até o checkout/pós-compra

## Paleta de cores

| Papel | Hex |
|-------|-----|
| Fundo principal | #FAF6F1 |
| Fundo alternado | #F3EDE4 |
| Texto principal | #3B2314 |
| Headlines | #2A1708 |
| CTA (botões/preço) | #D4762C |
| CTA hover | #B8621F |
| Accent/bordas | #E8D5BF |
| Verde garantia | #6B8E5A |

## Pendências para ativar a página completa

- [ ] **URL do checkout Kiwify** — substituir `href="#"` nos 3 botões CTA do `index.html`
- [ ] **Mockup 3D do ebook** — inserir em `assets/images/mockup-ebook.webp` (max 200 KB)
- [ ] **Pixel do Meta** — descomentar o bloco no `<head>` e inserir o Pixel ID
- [ ] **Depoimentos reais** — substituir os placeholders na seção 7 (ou ocultar com `display:none` no MVP)
- [ ] **Fotos dos depoimentos** — `assets/images/depoimento-1.webp`, `depoimento-2.webp`, `depoimento-3.webp`

## Estrutura da página (11 seções)

1. Hero — headline + sub + CTA 1 + mockup
2. Você se identifica? — copy do problema
3. Solução — apresentação do produto
4. Conteúdo do Manual — lista de itens
5. Benefícios — 5 cards
6. Bônus inclusos — 2 cards + tabela de valor
7. Prova social — 3 depoimentos (placeholder)
8. Oferta — checklist + preço + CTA 2
9. Garantia — 7 dias incondicional
10. FAQ — 7 perguntas (accordion)
11. CTA final — fundo escuro + CTA 3

## Métricas-alvo (primeira semana)

- CTR dos anúncios: > 1.5%
- Taxa de clique no CTA: > 10% dos visitantes
- Taxa de conversão: > 2% para tráfego frio
- ROAS mínimo: 1.5x
- CPC referência SP: R$ 0,80 a R$ 2,00
