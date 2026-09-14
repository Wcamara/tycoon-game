# Direção do Tycoon Web

## Princípio

O jogo é um sandbox. O jogador escolhe livremente entre empreender, investir, comprar clubes, entrar na política, especular ou construir uma cidade. Não haverá campanha obrigatória. O conteúdo surge da simulação, das decisões do jogador e das reações dos outros agentes.

## Mundo vivo

- Economia com ciclos, inflação, juros, desemprego, demanda e choques por setor.
- Rivais com caixa, estratégia, personalidade, memória e ações próprias.
- Empresas, governos, imprensa, funcionários, torcedores e investidores reagindo ao jogador.
- Calendário com eventos recorrentes e acontecimentos inesperados.
- Notícias montadas com os dados reais do estado do jogo.

## Reputação

A reputação será separada em dimensões:

- Consumidores.
- Funcionários e sindicatos.
- Governo e órgãos reguladores.
- Imprensa.
- Investidores e mercado.
- Torcedores, no futebol.

Cada decisão alterará essas dimensões. Reputação baixa pode gerar boicote, greve, fiscalização, juros maiores, perda de patrocinadores ou queda de torcida. Reputação alta pode reduzir custos, atrair talentos e melhorar negociações.

## Consequências

As consequências serão graduais e persistentes. Uma empresa pode lucrar com corte de custos no curto prazo, mas perder funcionários e clientes depois. Uma compra agressiva pode aumentar patrimônio, mas provocar reação de rivais, imprensa e reguladores.

## Dinheiro e dificuldade

O crescimento não deve ser automático. A economia usará:

- Receita com ramp-up, em vez de lucro imediato.
- Custos fixos, folha, manutenção, impostos e capital de giro.
- Demanda variável e capacidade ociosa.
- Risco de dívida e juros compostos.
- Necessidade de reinvestimento para crescer.
- Eventos que podem destruir caixa.
- Reservas mínimas e possibilidade real de falência.

O jogador deverá escolher entre crescer rápido com risco ou crescer devagar com caixa saudável.

## Futebol vivo

O jogador é dono ou controlador do clube por padrão. Ele pode assumir também o cargo de treinador quando quiser, mas isso será uma escolha opcional. O futebol será uma simulação contínua dirigida por governança:

- Partidas, calendário, forma, lesões e suspensões.
- Contratação e demissão de técnicos, diretores e comissão.
- Metas de orçamento, estilo esportivo e planejamento de elenco.
- Elenco, contratos e salários acompanhados pelo proprietário.
- Transferências, empréstimos e formação de jogadores.
- Bilheteria, produtos, TV, patrocínios e manutenção.
- Torcida, pressão da imprensa, rivalidades e crises.
- Campeonato, classificação, títulos, rebaixamento e promoções.
- Conselho do clube reagindo à gestão do proprietário.

O proprietário poderá aprovar contratações, definir orçamento, escolher o perfil do técnico, estabelecer metas, intervir em crises, vender ou comprar participação e demitir a direção. Escalação, treino e tática ficam sob responsabilidade da equipe técnica, salvo decisões especiais de intervenção do dono.

No modo proprietário, o técnico contratado cuida de escalação, treino e tática. No modo proprietário-treinador, o jogador passa a controlar também escalação, estilo de jogo, treinos e decisões de partida. Ele poderá deixar o cargo técnico a qualquer momento e contratar outro profissional, mantendo o controle acionário.

Entrevistas e coletivas são sempre manuais. Só aparecem quando o proprietário decide falar, principalmente antes de clássicos, crises ou decisões importantes.

O valor da participação deverá depender do desempenho esportivo, caixa, torcida, contratos e reputação, e não apenas de um número fixo.

## Ordem de implementação

1. Motor de reputação e consequências.
2. Gerador de eventos e noticiário personalizado.
3. Rivais com decisões autônomas.
4. Balanceamento econômico e dificuldade financeira.
5. Motor de partidas e calendário do futebol.
6. Finanças, torcida, mídia e conselho dos clubes.
7. Sons, animações e feedback visual para acontecimentos importantes.

## Implementado na primeira versão

- Reputação visível em seis dimensões.
- Eventos interativos com escolhas, custo e efeitos persistentes.
- Notícias personalizadas baseadas no jogador, rivais e clubes.
- Confiança do mercado e consequências graduais de reputação baixa.
- Rivais movimentando empresas e fazendo ofensivas comerciais.
- Economia com inflação, ramp-up, utilização de capacidade e confiança dos consumidores.
- Futebol com partidas mensais, forma, lesões, pontuação, bilheteria, merchandising, TV, salários e manutenção.
- Notícias globais independentes das propriedades do jogador.
- Linha do tempo persistente e consequências atrasadas.
- Memória de eventos e ofensivas autônomas dos rivais.
- Entrevista esportiva manual e opcional, acionada somente pelo presidente.
- Governança do clube com papéis de dono, presidente e técnico.
- Perfil esportivo, confiança do conselho, patrocinadores, dividendos e investimento na base.
- Moral individual, forma, lesões e troca automática de treinador em crise.
- Match Center com histórico de partidas e rumores de transferências.
- Governança com confiança da torcida, grupos de torcedores, patrocinadores, dividendos e categorias de base.
- Aba Minha Vida com saúde, estresse, idade, educação, relacionamentos, família e plano de sucessão.
- Ações pessoais com custo e efeito persistente: estudar, descansar, fazer networking, cuidar da família e planejar herdeiro.
- Empresas com investimento separado em P&D e marca, progresso de pesquisa e impacto na receita, custo e reputação.
- Cadeia de suprimentos dinâmica por empresa, com atrasos que reduzem confiança e geram notícias de crise.
- Patrimônio pessoal jogável: residência, veículo, iate e aeronave com compra, venda, valorização pelo preço pago e manutenção mensal.
- Benefícios pessoais de patrimônio sobre estresse, saúde e mobilidade social.
- Sucessão executável a partir dos 50 anos, com herdeiro, aposentadoria, transferência do patrimônio e reinício da vida do sucessor aos 18 anos.
- Carreira inicial com vagas, exigência de educação, salário mensal, experiência e demissão voluntária.
- Novo começo econômico com caixa inicial menor e fundação de empresa por coworking, sem exigir imóvel próprio.
- Manutenção do patrimônio pessoal contabilizada no DRE e no fluxo de caixa mensal.
- Painel visual de jornada pessoal com elementos de ambientação para reduzir a sensação de planilha.

## Ideias avaliadas para as próximas versões

### Vida e carreira

- Histórico profissional com currículo, entrevistas, promoções e demissões por desempenho.
- Especializações por área: vendas, tecnologia, finanças, política, esporte e comunicação.
- Rotina semanal com escolhas de trabalho, estudo, lazer, saúde e família.
- Relações com pessoas nomeadas, cada uma com personalidade, profissão, interesses e memória das decisões do jogador.
- Crises pessoais contextualizadas, como burnout, mudança de cidade, divórcio, doença e oportunidades inesperadas.
- Dinastia real: herdeiros com atributos próprios, educação, ambições e chance de contestar decisões do antecessor.

### Empresas

- Conselho de administração com metas e votos de acionistas.
- Funcionários-chave com competência, salário, lealdade e risco de saída para concorrentes.
- Produtos individuais, preço, qualidade, marketing, estoque e satisfação do cliente.
- Contratos com prazo, fornecedores alternativos e risco de concentração.
- Pesquisa com projetos que desbloqueiam tecnologias, em vez de bônus genéricos.
- Falência, recuperação judicial, venda parcial e reestruturação de dívidas.
- Substituir Fake News e sabotagem por inteligência competitiva, lobby legal, auditoria e disputa de mercado.

### Futebol

- Metas de temporada negociadas com a diretoria e consequências por descumprimento.
- Orçamento separado para salários, transferências, base, estádio e departamento médico.
- Jogadores com personalidade, ambição, adaptação, histórico de lesões e desenvolvimento por treinamento.
- Agentes, cláusulas, empréstimos, luvas, bônus e conflitos de vestiário.
- Identidade da torcida, clássicos, preço de ingresso, presença e pressão organizada.
- Centro de notícias esportivas com manchetes baseadas em resultados e decisões do proprietário.

### Mundo e imersão

- Cidades com emprego, renda, criminalidade, educação, moradia e qualidade de vida.
- Empresas rivais criando produtos, contratando pessoas e reagindo a preços e campanhas.
- Calendário de eleições, juros, crises logísticas, eventos esportivos e mudanças regulatórias.
- Jornal visual com capas, fotos ilustrativas, gráficos e linha do tempo da vida do personagem.
- Sistema de objetivos opcionais, como construir uma marca familiar, dominar um setor ou salvar um clube.

### Prioridade recomendada

1. Corrigir e aprofundar a carreira, com promoções e entrevistas.
2. Criar pessoas nomeadas e relações com memória.
3. Transformar empresas em operações de produtos, estoque e contratos.
4. Criar metas de temporada e orçamento detalhado no futebol.
5. Evoluir o jornal e a ambientação visual.
6. Adicionar cidades e macroeconomia mais profundas.

## Implementado nesta iteração

- Barra mobile compacta: navegação horizontal, indicadores financeiros reduzidos, data no cabeçalho e controles de tempo ocultos da área principal.
- Experiência profissional preservada ao clicar no cargo atual.
- Promoções automáticas condicionadas a tempo de casa e formação.
- Salário contabilizado no fluxo de caixa mensal e no DRE.
- Qualidade de produto e contratos comerciais com investimento por empresa.
