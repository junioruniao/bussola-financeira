# Controle financeiro pessoal: análise profunda e prompt para o projeto

## Parte 1 — Por que controle financeiro pessoal é o problema que vale resolver

Controle financeiro pessoal não é planilha de gastos. É o conjunto de hábitos, indicadores e decisões que conectam o dinheiro que entra hoje aos objetivos de médio e longo prazo — reserva de emergência, uma viagem, a entrada de um imóvel, a aposentadoria. A maior parte das pessoas que "perde o controle" das finanças não tem um problema de renda, tem um problema de visibilidade: não sabe, em tempo real, quanto pode gastar sem comprometer uma meta. É exatamente esse é o vazio que um bom produto de controle financeiro preenche, e é por isso que esse tipo de ferramenta continua sendo um dos apps mais baixados na categoria financeira todos os anos.

A literatura sobre o tema (guias como o da Rendio e o da TizFin, citados nas fontes ao final) converge para cinco pilares que qualquer sistema de controle financeiro — manual ou digital — precisa cobrir. O primeiro é o diagnóstico: levantar renda líquida, todos os gastos fixos e variáveis, e o saldo de dívidas existentes, sem julgamento, apenas para ter um retrato real do ponto de partida. O segundo é a definição de objetivos no formato SMART (específicos, mensuráveis, atingíveis, relevantes e com prazo) — "guardar dinheiro" não é uma meta, "acumular R$ 30.000 de reserva até dezembro de 2026" é. O terceiro é o orçamento propriamente dito, a régua que distribui a renda entre categorias antes que o mês comece. O quarto é a execução: automatizar transferências para poupança no dia do pagamento, revisar o orçamento semanalmente e evitar decisões financeiras por impulso. O quinto é a revisão periódica — ajustar o orçamento mês a mês, avaliar o progresso das metas a cada trimestre e repensar os objetivos uma vez por ano.

### Métodos de orçamento — e quando cada um faz sentido

Três métodos dominam a prática de orçamento pessoal, e eles não são excludentes. A regra 50/30/20 divide a renda líquida em 50% para necessidades (moradia, contas, alimentação básica), 30% para desejos (lazer, assinaturas, restaurantes) e 20% para o futuro (poupança, investimentos, quitação de dívidas além do mínimo). É o ponto de partida mais simples porque não exige categorizar cada gasto, só três grandes baldes — por isso é o método mais indicado para quem está começando. O orçamento base zero é mais rigoroso: cada real da renda recebe um destino antes de o mês começar, de forma que renda menos todas as alocações resulte em zero. Ele força decisões conscientes sobre cada categoria e costuma revelar gastos "invisíveis" que a regra 50/30/20 esconde dentro dos grandes baldes. O sistema de envelopes é o mais restritivo dos três: cada categoria recebe um limite fixo (fisicamente, em dinheiro num envelope; digitalmente, num saldo por categoria) e, quando acaba, os gastos naquela categoria param até o mês seguinte — é o método mais eficaz para quem tem dificuldade real de disciplina, mas o mais difícil de manter no longo prazo por sua rigidez.

Para dívidas, dois métodos concorrem. O método bola de neve (snowball) prioriza quitar primeiro a menor dívida, independente da taxa de juros, porque a vitória rápida gera motivação psicológica para continuar. O método avalanche prioriza a dívida com a maior taxa de juros primeiro, o que é matematicamente mais eficiente porque reduz o total pago em juros — mas exige mais disciplina emocional, já que a primeira vitória pode demorar mais para aparecer. Um bom projeto de controle financeiro deveria permitir que a pessoa escolha entre os dois, porque a resposta certa depende mais de perfil comportamental do que de matemática.

### Os indicadores que realmente importam (os KPIs pessoais)

Um punhado de indicadores resume, de forma confiável, a saúde financeira de uma pessoa, e são esses que qualquer dashboard deveria priorizar mostrar de forma proeminente:

- **Taxa de poupança** — (receitas − despesas) ÷ receitas. É o indicador mais direto de progresso: uma taxa de poupança de 20% ou mais é geralmente considerada saudável.
- **Tamanho da reserva de emergência**, medido em meses de despesas cobertos pelo saldo guardado — a referência de mercado fica entre 3 e 12 meses, dependendo da estabilidade da renda.
- **Nível de comprometimento de renda com dívidas** — quanto da renda mensal já está tomado por parcelas fixas. Acima de 30% costuma acender alerta.
- **Patrimônio líquido** — soma de tudo que a pessoa possui menos tudo que deve; é o indicador que mostra evolução real ao longo dos anos, mais do que o saldo do mês.
- **Orçado vs. realizado por categoria** — não é um número único, mas é o indicador operacional que mostra, mês a mês, onde o plano e a realidade divergem.

### O componente comportamental

Nenhum desses métodos funciona sem levar em conta como as pessoas realmente se comportam com dinheiro. Vieses como a inflação de estilo de vida (gastar mais automaticamente conforme a renda cresce) e o gasto por impulso são responsáveis por boa parte do fracasso de orçamentos bem desenhados no papel. É por isso que "pagar-se primeiro" (transferir para poupança automaticamente antes de gastar) supera consistentemente estratégias que dependem de guardar o que sobra no fim do mês — e por isso que automação e visualização clara (o dinheiro que "sobrou" fica visível, não escondido numa planilha) fazem mais diferença no resultado do que a sofisticação do método escolhido.

### Sources

- [Planejamento financeiro pessoal: guia completo para 2026 — Rendio](https://www.rendio.com.br/blog/planejamento-financeiro-pessoal)
- [Controle Financeiro Pessoal: Guia Definitivo para Sair do Vermelho em 2026 — TizFin](https://tizfin.com.br/blog/controle-financeiro-pessoal-guia-completo-2026)
- [Método 50-30-20: como organizar o orçamento mensal — Blog Serasa](https://www.serasa.com.br/score/blog/metodo-50-30-20-como-utilizar/)
- [Regra 50/30/20: O Simulador de Orçamento Pessoal para 2026 — Blog da INCO](https://blog.inco.vc/financas/simulador-orcamento-pessoal-regra-50-30-20/)
- [Controle financeiro: passo a passo para se organizar em 2026 — Bom Pra Crédito](https://blog.bompracredito.com.br/controle-financeiro-como-fazer/)

---

## Parte 2 — O prompt detalhado para construir o projeto

Este é o brief que você pode reaproveitar: cole em uma conversa com uma IA, entregue a um desenvolvedor ou use como checklist para evoluir o protótipo entregue junto com esta análise (`dashboard.html`). Ele traduz os conceitos da Parte 1 em decisões concretas de produto.

**Contexto e objetivo.** Construir um produto de controle financeiro pessoal — um dashboard visual, moderno, com tema claro e escuro — que ajude qualquer pessoa a enxergar rapidamente sua saúde financeira e a progredir em direção às suas metas, sem exigir que ela entenda de finanças antes de começar a usar. O produto deve funcionar como template: a estrutura, os componentes e o sistema visual precisam se sustentar mesmo quando alimentados com dados de usuários diferentes.

**Público.** Pessoas físicas organizando as próprias finanças, majoritariamente leigas em educação financeira, que hoje usam (ou tentam usar) planilhas soltas ou nada. Secundariamente, o próprio dashboard funciona como um template replicável — para outras pessoas usarem como base de um produto ou de um curso.

**Funcionalidades essenciais para a primeira versão (o que o protótipo entregue já demonstra em tela estática):**

1. Alternância de tema claro/escuro, respeitando tanto a preferência do sistema operacional quanto uma escolha manual persistida por usuário.
2. Um cabeçalho de indicadores (KPIs) com saldo do mês, receitas, despesas e taxa de poupança, cada um com variação em relação ao mês anterior e uma mini tendência (sparkline).
3. Um gráfico de fluxo de caixa comparando receitas e despesas ao longo dos últimos meses, com leitura interativa (hover) e uma versão em tabela para acessibilidade.
4. Um gráfico de despesas por categoria (donut), com legenda e valores diretos — nunca cor como único código de identificação.
5. Uma comparação visual da divisão real da renda contra a regra 50/30/20, o método mais didático para introduzir alguém ao orçamento.
6. Cartões de metas financeiras no formato SMART, com barra de progresso, valor atual, valor-alvo e prazo.
7. Orçado vs. realizado por categoria, sinalizando com cor semântica (não decorativa) quando uma categoria estourou o limite.
8. Uma síntese de saúde financeira (um "placar" único) que combine taxa de poupança, meses de reserva de emergência e comprometimento de renda com dívidas num único número interpretável.

**Estrutura de dados (o schema mínimo por trás das telas):**

- `transacao`: id, data, valor, tipo (receita/despesa), categoria_id, descrição, meio de pagamento.
- `categoria`: id, nome, cor, tipo_orcamento (necessidade / desejo / futuro — para alimentar o comparativo 50/30/20), limite_orcado_mensal.
- `meta`: id, nome, valor_atual, valor_alvo, prazo, categoria_ícone, status_calculado (no caminho / abaixo do ritmo / concluída — calculado comparando progresso real ao progresso esperado até a data).
- `usuario`: id, renda_mensal_líquida, preferência_de_tema, meses_de_reserva_desejados.
- `resumo_mensal` (view derivada, não tabela): receitas, despesas, saldo, taxa_de_poupança, calculados a partir de `transacao` por período.

**Sistema de design usado no protótipo (para manter consistência ao evoluir o projeto):** fundo neutro levemente esverdeado (não o bege genérico de IA), tipografia combinando uma serifada de apoio (Fraunces) para títulos e números de destaque com uma sans humanista (Work Sans) para texto e interface, e uma paleta funcional dividida em três papéis que nunca se misturam: cor de marca (verde-azulado, para ações e destaques neutros), cores categóricas (cinco tons distintos e validados para daltonismo, usados exclusivamente para identificar categorias de despesa) e cores de status (verde, âmbar e vermelho, reservadas exclusivamente para bom/atenção/crítico e sempre acompanhadas de texto, nunca só cor).

**Stack técnica sugerida para evoluir do protótipo estático para um produto real:**

- Front-end: React ou Vue com uma biblioteca de gráficos leve (Recharts, Visx ou D3 puro, mantendo os mesmos princípios de acessibilidade do protótipo) — ou, se o objetivo é continuar simples, o próprio HTML/CSS/JS do protótipo evoluído com um pequeno *state management*.
- Dados: se for produto real com múltiplos usuários, um banco relacional (Postgres) modelado a partir do schema acima; para uso pessoal single-user, mesmo um arquivo local (SQLite, ou até um JSON sincronizado) resolve.
- Integração futura: Open Finance (Banco Central) para importar transações automaticamente em vez de exigir lançamento manual — esse é o salto que mais aumenta a chance de adesão de longo prazo, porque remove o maior ponto de atrito do controle financeiro manual.
- Autenticação e multiusuário: necessários apenas se o objetivo for transformar o template num produto (SaaS) para terceiros, não para uso pessoal.

**Roadmap de evolução sugerido:**

- *V1 (o protótipo entregue):* dashboard estático e navegável, com dados fictícios, demonstrando o sistema visual e todos os componentes acima.
- *V2:* dados dinâmicos — formulário de lançamento de transações, metas editáveis pelo usuário, persistência local.
- *V3:* importação automática via Open Finance, alertas proativos ("você já usou 90% do orçamento de Lazer"), e recomendações simples baseadas nos indicadores (ex.: sugerir aumento da taxa de poupança quando a reserva de emergência já está completa).

---

## Parte 3 — O que já foi entregue

Junto a este documento, você recebeu `dashboard.html`: o protótipo inicial descrito no roadmap como V1, já implementando o sistema de design, os KPIs, o gráfico de fluxo, a divisão 50/30/20, as metas e o comparativo de orçamento — nos dois temas, claro e escuro, e responsivo para celular. Uma versão publicada como página vem no link enviado na conversa, para você abrir, revisar e compartilhar diretamente. A Carteira de investimentos, adicionada depois, também já simula visualmente cotações em tempo real (ver Parte 4).

---

## Parte 4 — Dados de mercado em tempo real: a arquitetura por trás do "ao vivo"

Um arquivo HTML único, sem servidor por trás, não consegue abrir um WebSocket de verdade contra uma bolsa nem receber um Webhook de uma corretora — não existe "backend" nenhum para o mundo externo chamar. Por isso, o que a Carteira de investimentos do protótipo faz é *simular* esse comportamento inteiramente no navegador: a cada poucos segundos, o preço de cada ativo oscila sozinho dentro de uma faixa de volatilidade coerente com sua classe (mais para criptomoeda, menos para renda fixa, nada para caixa), e a tela inteira — KPIs, gráfico de evolução, donut de composição e a tabela de ativos — se redesenha na hora, com um pequeno flash verde ou vermelho marcando o que mudou. Um indicador "Cotações ao vivo" com o ponto pulsando, um botão para pausar, e o horário da última atualização completam a sensação de um feed real, como o do Investidor10. Dentro do modal de lançamento, o mesmo mecanismo mostra o preço de mercado do ativo selecionado em tempo real, com um atalho para usá-lo — mesmo com o modal aberto, o preço continua atualizando por trás.

Para essa simulação virar dado de mercado de verdade, o produto precisaria de uma arquitetura orientada a eventos entre um provedor de cotações (a B3, um agregador como a Brapi, ou a corretora do usuário via Open Finance) e o navegador. Cada uma das seis peças que você listou cumpre um papel específico e diferente nessa cadeia — elas não são intercambiáveis, cada uma resolve um trecho específico do caminho que o preço percorre até a tela:

- **Streaming de dados** é o primeiro trecho, entre o provedor de cotações e o seu backend: a maioria dos provedores de bolsa oferece uma conexão de streaming contínua que empurra o preço de cada ativo a cada negócio fechado no pregão, sem que seu servidor precise ficar perguntando "mudou alguma coisa?" a cada poucos segundos.
- **Webhook** cobre um tipo diferente de evento na mesma borda: não o preço em si (que é streaming, contínuo), mas fatos discretos — uma corretora ou o Open Finance chamando um endpoint seu (`POST /webhooks/corretora`) sempre que uma ordem for executada ou um provento for pago, para manter a posição do usuário sincronizada sem polling.
- **Event-Driven Architecture** é o padrão que amarra os dois pontos acima ao resto do sistema: cada evento recebido — preço mudou, provento caiu, ordem executada — dispara reações independentes (recalcular o patrimônio, atualizar o gráfico, checar se uma meta foi atingida) sem que os módulos internos fiquem checando um ao outro em loop.
- **Pub/Sub** é como esses eventos se espalham dentro do seu backend sem acoplar os serviços entre si: o serviço que recebe o preço da bolsa publica um evento `preco_atualizado` num tópico (Redis Pub/Sub, Kafka, SNS/SQS), e qualquer serviço interessado — o que recalcula patrimônio, o que dispara alertas — se inscreve nesse tópico sem que o publicador precise saber quem está ouvindo.
- **WebSockets** é o trecho final da cadeia, entre o seu backend e o navegador do usuário: a única forma prática de empurrar o novo preço para a tela sem o navegador ficar recarregando a página ou fazendo polling a cada segundo. É exatamente o comportamento que a simulação do protótipo imita no cliente.
- **Push Notification / Push API** resolve o mesmo problema de "empurrar sem que o cliente peça", mas fora da aba aberta: para avisar o usuário mesmo com o app fechado (ex.: "sua ação XPTO caiu 8% hoje"), via Service Worker e a Push API do navegador, ou uma notificação nativa num app mobile.

Na prática, a maioria dos produtos de carteira de investimento não constrói streaming de bolsa do zero — contrata um provedor de dados de mercado que já entrega WebSocket ou webhook prontos, e concentra a própria engenharia na camada de eventos internos (pub/sub) e na entrega em tempo real para o navegador (WebSocket, com polling como plano B). O roadmap da Parte 2 (V3: alertas proativos) é exatamente o ponto onde essa arquitetura entraria — os mesmos eventos que atualizariam o preço na tela também alimentariam os alertas.
