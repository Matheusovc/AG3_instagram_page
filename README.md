# AG3 — Modas Masculinas

Site institucional e vitrine da **AG3 | Menswear** — moda masculina com estilo atemporal, em Brasília/DF.

O objetivo do site é o cliente **conhecer a loja**, ver as **peças mais procuradas** e **falar direto com um vendedor** pelo WhatsApp. Não há carrinho nem checkout: todo o atendimento acontece no WhatsApp.

## Estrutura

```
AG3/
├── index.html          # Site completo (HTML + CSS + JS, sem dependências de build)
├── assets/
│   ├── logo.png            # Logo AG3 (explosão)
│   ├── look-camisa.png     # Look de camisa texturizada (hero + destaque)
│   ├── produto-polo.png    # Polo premium
│   └── produto-camiseta.png# Camiseta essencial
└── README.md
```

## Seções

- **Início / Hero** — boas-vindas, assinatura "Essencial. Moderno. Você." e status de loja aberta/fechada em tempo real.
- **Destaques** — as peças mais procuradas, cada uma com botão "Tenho interesse" que abre o WhatsApp com a peça já no texto.
- **Categorias** — Polos, Camisetas, Camisas, Bermudas, Calças & Jeans, Suéter & Tricô, Bonés, Regatas (cada card abre o WhatsApp).
- **Por que AG3** — Qualidade, Conforto, Elegância.
- **A Loja** — endereço (Feira Mix Ceasa), horário (Qua–Dom, 9h às 18h), Instagram e mapa.
- **Vendedores** — Matheus e Gabriela, com WhatsApp direto.

## Contato

- **Matheus:** (61) 98159-2930
- **Gabriela:** (61) 98106-2952
- **Instagram:** [@ag3modas](https://instagram.com/ag3modas)
- **Horário:** Quarta a domingo, 9h às 18h (fechado seg. e ter.)

## Desenvolvimento

É um site estático — basta abrir o `index.html`. Para visualizar com os assets carregando corretamente, sirva a pasta localmente:

```bash
npx serve .
```

## Deploy

Publicado via **Netlify** (site estático, pasta raiz). Qualquer push na branch principal publica automaticamente.
