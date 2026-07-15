<!-- SEED: re-run $impeccable document once there's code to capture the actual tokens and components. -->
---
name: FIS — Fórum de Investimentos Sustentáveis
description: Landing page do evento da ABVCAP que conecta capital privado à agenda brasileira de sustentabilidade
---

# Design System: FIS — Fórum de Investimentos Sustentáveis

## 1. Overview

**Creative North Star: "A Rede Viva"**

O FIS não é um relatório institucional estático — é o ponto de encontro entre capital privado e a agenda de sustentabilidade, e o design precisa carregar essa energia de conexão. A base é o navy profundo que a marca ABVCAP/FIS já carrega (credibilidade, seriedade financeira), mas o verde deixa de ser um acento discreto e passa a dominar boa parte da superfície: hero, CTAs, destaques de dado. O sistema rejeita explicitamente o que a edição anterior entregou — um hero pequeno e estático sem vídeo, uma parede de 30+ retratos de palestrantes em grade uniforme, e blocos de texto corrido sem apoio visual. Em vez disso: hero imersivo com motion, apresentação de rede/curadoria em vez de galeria plana, e cada seção liderando com um dado ou visual antes do parágrafo.

**Key Characteristics:**
- Navy profundo como âncora de credibilidade, verde vibrante como motor de energia (30-60% da superfície)
- Movimento coreografado: entradas orquestradas, seções que reagem ao scroll, hero com vídeo/motion de fundo
- Tipografia sans geométrica única, em múltiplos pesos, para títulos grandes e dinâmicos
- Conteúdo escaneável: dado/ícone/visual antes de texto corrido
- Curadoria de rede (palestrantes, patrocinadores) apresentada com hierarquia, não em grade uniforme

## 2. Colors

Paleta **Committed**: o verde carrega a maior parte da energia visual da página, ancorado por um navy profundo que preserva a credibilidade institucional da marca.

### Primary
- **Verde FIS** ([to be resolved during implementation] — tom vibrante próximo ao verde já usado pela marca): domina hero, CTAs principais, destaques de dado e elementos de conexão/rede. Carrega 30-60% de qualquer tela.

### Secondary
- **Navy Profundo** ([to be resolved during implementation]): base institucional — seções de dados do evento, rodapé, texto sobre fundo claro. Âncora de credibilidade que evita que o verde vire "app de bem-estar".

### Neutral
- **Off-white / neutro claro** ([to be resolved during implementation]): fundos de seções de conteúdo denso (palestrantes, patrocinadores), texto sobre navy.
- **Neutro escuro para texto** ([to be resolved during implementation]): corpo de texto sobre fundos claros, sempre validado a ≥4.5:1 de contraste.

### Named Rules
**The Living Green Rule.** O verde não é um acento pontual — ele carrega a energia da página (30-60% da superfície visível). Se uma seção parece "só mais um evento institucional azul", o verde não está presente o suficiente.

## 3. Typography

**Display Font:** [a definir na implementação — sans geométrica moderna, múltiplos pesos]
**Body Font:** [mesma família, peso regular/medium]

**Character:** Uma única família sans geométrica cobrindo todo o espectro — de display bold e apertado até corpo de texto legível — para reforçar a sensação de um sistema vivo e conectado, sem a formalidade de um pareamento serif+sans.

### Hierarchy
- **Display** (peso bold/black, escala grande e responsiva): título do hero e chamadas de seção — deve comunicar energia, não apenas informar.
- **Headline**: títulos de seção (dados do evento, LP Day, palestrantes, patrocinadores).
- **Title**: subtítulos, nomes de palestrantes/patrocinadores.
- **Body** (65-75ch de largura máxima): parágrafos curtos, sempre precedidos por um dado, ícone ou visual de apoio.
- **Label**: datas, horários, tags de categoria (Planeta/Humanidade/Biodiversidade/Ecossistema).

### Named Rules
**The Data-Leads Rule.** Nenhum bloco de texto corrido aparece sem um dado, ícone ou elemento visual que o preceda — o texto denso e desacompanhado da edição anterior é o que este sistema existe para evitar.

## 4. Elevation

Sistema em camadas (layered), não flat: a energia coreografada do motion pede profundidade real entre hero, seções de conteúdo e elementos flutuantes (CTAs, cards de dado), não apenas troca de cor de fundo. [Valores exatos de shadow a definir na implementação.]

### Named Rules
**The Depth-With-Purpose Rule.** Sombra e camadas aparecem para suportar hierarquia e movimento (hero sobre vídeo, CTA flutuante, seção que "entra" no scroll) — nunca como decoração estática.

## 5. Components

Nenhum componente implementado ainda; a documentar na primeira passada de `$impeccable document` em modo scan, após o código existir.

## 6. Do's and Don'ts

### Do:
- **Do** construir um hero imersivo com vídeo ou motion de fundo — a primeira dobra precisa comunicar o propósito do evento em segundos, não em um banner pequeno.
- **Do** liderar cada seção com um dado, ícone ou visual antes de qualquer parágrafo.
- **Do** apresentar palestrantes e patrocinadores com hierarquia e curadoria (destaques, categorias, storytelling), não como uma grade uniforme de retratos.
- **Do** manter o navy profundo como âncora de credibilidade mesmo com o verde dominando a energia visual.
- **Do** coreografar o motion (entradas por scroll, transições de seção) respeitando sempre `prefers-reduced-motion`.

### Don't:
- **Don't** repetir a grade de 30+ fotos de palestrantes em 6 colunas da edição anterior — pesada, uniforme, sem hierarquia.
- **Don't** usar um hero pequeno e estático sem vídeo ou movimento.
- **Don't** empilhar parágrafos de texto corrido sem apoio visual ou de dados.
- **Don't** deixar o verde virar um acento raro (<10%) — nesta edição ele carrega a energia da página.
- **Don't** usar glassmorphism, gradientes de texto ou faixas coloridas de borda lateral como decoração.
