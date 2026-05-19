# 07 — Síntese e Oportunidades: AI no Agro de Sorriso/MT

> Documento estratégico para reunião com a maior associação de produtores de Sorriso/MT (Sindicato Rural de Sorriso — 612 associados — e/ou Núcleo Aprosoja-MT Sorriso) e com o prefeito Alei Fernandes.
> Base: 6 relatórios de pesquisa (arquivos 01-06). Data-referência: maio/2026.
> Cliente: consultoria + implementação de AI (software + serviços, **sem hardware proprietário** — integra com o que já existe na fazenda).

---

## Sumário Executivo

**(a) Mercado de AI no agro brasileiro está em ponto de inflexão.** Segundo a FGV/Oscar Burd, **41,9% das fazendas e agroindústrias brasileiras** já usam alguma solução de IA em 2025, contra 16,9% em 2022 — adoção mais do que dobrou em três anos (arquivo 03, 04). O mercado global de farm management software vale US$ 2,75 bi (2024) e chega a US$ 4,67 bi em 2029 (CAGR 11,2%); o mercado brasileiro de SaaS soma US$ 7,9 bi (2025) com CAGR 13,87% até 2034 (arquivo 03). Solinftec virou unicórnio com R$ 1,3 bi captados e plano de 700 robôs Solix até 2026; FreteBras investiu R$ 800 mi em IA em 3 anos; TerraMagna mira R$ 18 bi sob gestão de risco em 2025 (arquivos 01, 02, 03, 05). O Radar Agtech 2024/2025 contabiliza **~2.072 agtechs ativas** no Brasil. O mercado existe, está crescendo, mas é **denso em SaaS de prateleira e raso em consultoria vertical aplicada** — exatamente o nicho do cliente.

**(b) Sorriso/MT é o lugar/timing certo.** Sorriso é **maior PIB agrícola do Brasil** (R$ 7,2 bi em 2024, líder pelo 6º ano consecutivo) e **maior produtor individual de soja do mundo** (615 mil ha de soja, 500 mil de milho safrinha, 59 mil de algodão; 2,08 Mt de soja em 2024 = R$ 3,3 bi só de soja — arquivos 02, 06). Lidera o ranking nacional de **capacidade de armazenagem** com 5,6 Mt (9% de MT — arquivo 02). Concentra ~2.000 propriedades médias/grandes, predominância de fazendas >1.000 ha, com grupos gigantes na região (Bom Futuro 650 mil ha; SLC 734 mil ha; Amaggi com base em Cuiabá; Tessaro, Beledelli, Belusso etc. — arquivo 06). **76% dos produtores de MT têm perfil "inovador" ou "altamente inovador"** (AgriHub/Famato 2024) e Sorriso é um dos 3 centros de treinamento de operadores do estado. Mas é também onde mais dói: lucro do sojicultor em Sorriso safra 23/24 caiu para **1,7 sc/ha**; custo total da soja 25/26 subiu para **R$ 7.430-7.657/ha**; rentabilidade projetada cai de R$ 3.080/ha (24/25) para R$ 1.946/ha (25/26); apenas **18,15% das lavouras de MT têm cobertura 4G/5G** (pior do Brasil entre grandes produtores); **MT lidera as recuperações judiciais do agro com 332 pedidos em 2025**, 34% ligados à soja (arquivo 06). É um mercado grande, sofisticado e financeiramente pressionado — terreno fértil para AI que entregue ROI mensurável.

**(c) A janela competitiva é "consultoria vendor-agnostic de AI aplicada com bota suja em Sorriso".** O cenário competitivo já mapeado (arquivo 05) mostra que **hardware (John Deere/CNH/AGCO/Jacto), plataformas SaaS de campo (FieldView/Cropwise/xarvio/Solinftec), crédito (TerraMagna/Agrolend/Traive/A de Agro) e score enterprise (Agrotools/Serasa/Agrosatélite) estão dominados por gigantes**. Mas há **espaço claro** em: (i) consultoria de IA de "integração + decisão + treinamento de equipes" — ninguém faz "bota suja" em Sorriso; (ii) LLM agronômico em português treinado em corpus BR (Solinftec ALICE+ChatGPT é o único concorrente, e embarcado na sua plataforma); (iii) compliance EUDR white-label para associações; (iv) hedge inteligente para produtor (gap puro); (v) MRV de carbono em soja-milho; (vi) "mesa de inteligência" combinando preço+clima+produção+frete; (vii) treinamento e cultura digital. **Posicionamento sugerido**: "consultoria de AI vendor-agnostic que integra o que o produtor já tem (FieldView + Operations Center + ERP + Aegro + planilhas) com foco em decisão e ROI mensurável por talhão e por safra". Sem hardware é vantagem, não fraqueza: o cliente é o único alinhado ao produtor.

---

## A. MAPA DE MATURIDADE AI NO AGRO BRASILEIRO

| Segmento da Cadeia | Maturidade | Players principais | Adoção estimada | Gap/Oportunidade |
|---|---|---|---|---|
| **Plantio de precisão (taxa variável)** | Maduro | John Deere, AGCO/Precision Planting, CNH, Trimble, Hexagon, Topcon, Jacto, Stara, Cropwise Planting, xarvio | 42% dos produtores MT; >50% sudeste/oeste de MT (arq 01) | Integração mapas-solo↔plantio em tempo real; alfabetização do gerente médio |
| **Mapeamento de solo com ML** | Emergente→Crescente | Agrorobótica (AGLIBS, 1.500 amostras/dia, 22 parâmetros), InCeres (77% correlação) | ~5% (estimativa, baseada em adoção LIBS ainda piloto) | Tempo de resposta vs. lab tradicional; integração com taxa variável |
| **Monitoramento por satélite + NDVI** | Maduro | Climate FieldView (28 Mi ha BR), JD Operations Center (17-27 Mi ha), EarthDaily Agro, Sensix (>2 Mi ha), Agronow, Agrosatélite/Serasa (370 Mi ha) | NDVI/satélite adotado por maioria dos grandes (arq 01) | Custo/ha alto para médio (R$ 10-80/ha); falta padrão aberto de dados |
| **Drones (sensoriamento)** | Crescente | Horus Aeronaves (Maptor), Sensix, Cromai, Perfect Flight (25 Mi ha) | Adoção limitada entre médios; massiva em grandes | Logística de operação; capacitação CAAR limitada |
| **Drones (pulverização)** | Crescente (regulamentação destravou 2023-24) | CNH P150, DJI Agras, ARPAC; Perfect Flight para gestão | 2.500 drones de pulverização no BR; projeção +10 mil/ano até 2028 (arq 06) | Capacitação operadores; analytics agnóstico de marca |
| **Detecção de pragas/doenças (visão)** | Crescente | Cromai (170 funcionários, 90+ clientes), Strider/Syngenta, xarvio SCOUTING + iMETOS, Tarvos (50k ha MT/BA), Jacto MIIP | Comercial em ramp-up; pesquisas BR atingem 99% em base pública (arq 01) | Modelos "green on green" específicos MT; LLM PT-BR para diagnóstico |
| **Pulverização inteligente (seletiva)** | Crescente (chegando a mercado) | JD See & Spray (60-90% redução herbicida), Solinftec Solix/ALICE (>90% redução), Case IH SaveFarm (>80%), AIM Command | <5% dos pulverizadores em MT (estimativa, Solinftec ~200 robôs globais) | Preço alto; ROI ainda em prova ampla na soja |
| **Previsão climática micro-localizada** | Maduro | Agrosmart (BoosterPRO), Climatempo/Agroclima, BASF Agroclima PRO, IBM Watson, ClimateAi | Múltiplas plataformas; baixa integração | Integração previsão↔prescrição agronômica num só dashboard |
| **Previsão de safra/produtividade** | Crescente | FieldView, Cropwise, Agronow/A de Agro, IBM, EarthDaily, IMEA, ClimateAi | B2B (tradings, financeiras); pouca chegada ao produtor direto | Modelo público brasileiro abrangente e auditável; integração com IMEA |
| **ERP/gestão de fazendas** | Maduro | Aegro (60k instalações, 3 Mi ha), Siagri/AgriManager (Aliare, >2.000 ha sweet spot), TOTVS Agro, SAP, Senior (7 dos 10 maiores produtores BR), MyFarm, Solterra ST7 COOP | 40-61% dos produtores BR usam algum software de gestão (arq 03, 06) | AI ainda "add-on", não nativa; agentes generativos para fluxo de caixa/barter |
| **Crédito rural com AI** | Maduro | TerraMagna (R$ 1 bi+ carteira), A de Agro (R$ 700M com BTG), Nagro (R$ 1 bi cedido), Tarken (11% do crédito agro), Agrolend (SCFI), Traive (US$ 17M+) | Cresce rápido; 18,6% das agtechs em "antes da porteira" (arq 03) | Integração ESG+clima+IoT para precificação dinâmica |
| **Seguro agrícola com AI** | Emergente | Newe (paramétrico), Swiss Re, Brasilseg, Mapfre, Essor, A de Agro (monitoramento) | **Penetração caiu para 3,3% da área plantada em 2025** (arq 03) | Soja com só 20% de subvenção PSR; espaço gigante para paramétrico baseado em índice satelital |
| **Comercialização/preço (trading)** | Crescente | Grão Direto (12 Mt em 2025, meta 18-20 Mt em 2026), Hedgepoint, StoneX, Safras & Mercado, CME, Agrity, Agribrasil, B3 Futuro de Soja (+22% YoY) | Marketplace já é hábito; AI ainda incipiente (primeira venda por IA em 2024-25) | Robô de hedge auto-executável; PT-BR para grande produtor combinando CBOT+basis+frete |
| **Rastreabilidade EUDR** | Crescente | Agrotools (40% das operações de grãos), Serasa Smart ESG (80 Mi ha/dia em MT+MS+GO), Agrosatélite, Niceplanet, Vega/LYRA (Bunge), Selo Verde (gratuito), TerraMagna, STCP | Múltiplos padrões competindo; deadline EUDR dez/2026 | Falta camada de interoperabilidade; white-label para associações de produtores |
| **Crédito de carbono** | Emergente | Pachama, Carbonext (1 Mi ha Amazônia), Moss (1,7 Mt transacionadas), Agrorobótica (AGLIBS), NaturAll Carbon (Verra VM0042), reNature, Bayer PRO Carbono (3 Mi ha) | Mercado BR US$ 2,7 bi (2025) → US$ 25,2 bi (2034 CAGR 28,1%) — arq 04 | MRV barato; foco em soja-milho-pecuária integradas (não só floresta) |
| **Pecuária de precisão** | Crescente | Cowmed (35k+ bovinos, 400 fazendas), Allflex/MSD, BeefTrader (34 confinamentos, 70-80k cabeças), BovControl, JBS/Frigol+Ecotrace | Avanço 29% em automação na pecuária (Índice Agrotech GS1 2025); 8,5 Mi cabeças em confinamento em 2025 (+11,9%) | Gatilho PNIB 2025-2032 (rastreabilidade obrigatória); produto extensivo tropical |
| **ILPF otimizada por AI** | Pesquisa avançada (Embrapa Sinop); comercial baixa | Embrapa Agrossilvipastoril, Unicamp (GeoABC), Imea (modelos econômicos) | MT tem 1,5-2,6 Mi ha ILP (2º BR); meta 1,3 Mi ha 2030 | Quase ninguém transformou pesquisa em produto comercial — **gap claro** |
| **Logística de escoamento** | Crescente | Solinftec Flow/WAY (cana), FreteBras/CargoX (R$ 800 Mi em IA, 50% das cargas de agro), Strada, HBSA (uso interno) | Sorriso→Paranaguá R$ 490/t (fev/25); +38-70% em pico (arq 02) | **Previsão de fila portuária = gap puro**; hedge dinâmico de frete; integração rodoviária-ferroviária-hidroviária |
| **Armazenagem inteligente** | Crescente | Kepler Weber/Procer (Sync), Embratel Smart Silo (abr/24), ALLTIS DOMO, Tago.io, Macnica DHW, Nivetec | Sorriso lidera país com 5,6 Mt; só 14% das fazendas BR têm armazenagem on-farm (vs 65% EUA) | Penetração baixa em médios; integração entre players; ML preditivo brasileiro |
| **Agrônomo digital (LLM PT-BR)** | Inexistente como produto comercial maduro | Solinftec ALICE + ChatGPT (embarcado), Embrapa AgroAPI, papers (AgroLLM mar/25) | Inicial | **Gap puro**: LLM treinado em corpus BR (Embrapa+Aprosoja+Conab+IMEA) — oportunidade clara |
| **RH / gestão de operadores** | Quase inexistente | TOTVS RH, Senior HCM (genéricos); Sofit (telemetria); JD Operations Center (dados por operador) | Sem produto vertical específico | **Gap puro**: produto que correlacione produtividade-do-operador × dados-agronômicos × turnover. 70% dos produtores MT citam falta de mão de obra qualificada |

---

## B. TOP 10 OPORTUNIDADES PARA SORRISO/MT

> Critério de ranqueamento: dor real × viabilidade técnica × tamanho de mercado MT × ausência de concorrência forte.

### Oportunidade #1 — Cockpit de Decisão Agronômica Vendor-Agnostic
- **Dor**: produtor de Sorriso usa **FieldView + Operations Center + Aegro/Siagri + planilhas + boletins do IMEA** em paralelo, sem visão consolidada. "Aliare/Aegro fazem ERP; Climate/Solinftec fazem agronomia; TerraMagna/Traive fazem crédito. Ninguém costura tudo num data layer para o produtor" (arq 05, gap #3). 76% dos produtores de MT são inovadores mas só **18% das lavouras têm 4G/5G** (arq 06).
- **Solução com AI**: plataforma de integração (consumindo Leaf Agriculture API + Embrapa AgroAPI + IMEA boletins + dados de máquinas) com agente LLM em PT-BR. Dashboard único: "como está cada talhão de cada fazenda, qual a margem projetada, o que fazer hoje".
- **Por que nós podemos fazer**: somos vendor-agnostic. Nenhum dos players de SaaS quer integrar com concorrente — todos querem vender o ecossistema deles. O cliente é o único alinhado ao produtor.
- **Quem já faz algo similar**: Leaf Agriculture (só infra, não decisão); Solinftec ALICE (embarcado no ecossistema próprio); Climate FieldView (só Bayer); Aegro (gestão fiscal, pouca decisão).
- **Como nos diferenciamos**: não vendemos software de prateleira; vendemos **integração + análise + decisão por talhão** com SLA. O produtor já gastou em FieldView/Operations Center — extraímos valor disso.
- **Mercado endereçável Sorriso/MT**: ~2.000 propriedades de Sorriso × ticket conservador R$ 20-50 mil/ano = **R$ 40-100 milhões/ano só Sorriso**. MT inteiro (com ~50 mil propriedades médio-grandes) seria 10x.
- **Complexidade**: Média-Alta. Integrações são técnicas mas dominadas. Vantagem: Leaf MCP (2025) acelera; APIs Embrapa estão prontas.
- **Tempo para primeiro resultado**: 60-90 dias (piloto com 3-5 fazendas).
- **Modelo**: SaaS por hectare/ano (R$ 5-15/ha) + projeto inicial de setup (R$ 50-150k) + retainer de consultoria (R$ 15-50k/mês).

### Oportunidade #2 — Compliance EUDR White-Label para a Associação
- **Dor**: EUDR vigora **30/12/2026** para todos os operadores. **US$ 46,3 bi em exportações ao bloco europeu** dependem de georreferenciamento + due diligence; ~1/3 são commodities afetadas (arq 02). Sorriso é fronteira Cerrado-Amazônia e tem áreas com desmatamento legal pré-2020 perto do corte temporal. Soja Plus existe mas não cobre EUDR. Lei estadual MT que pune signatários da Moratória voltou a vigorar em jan/2026 (arq 02, 06).
- **Solução com AI**: plataforma white-label para o Sindicato Rural / Aprosoja Sorriso que ingere CAR, polígonos de talhão, PRODES/DETER, certidões ambientais; gera dossiê EUDR automatizado por produtor; agente LLM responde dúvidas em PT-BR. Modelo: a associação oferece como benefício aos 612 associados.
- **Por que nós podemos fazer**: consultoria + software combinados é o produto certo — Selo Verde dá os dados grátis, Agrotools/Serasa cobram caro para enterprise, falta o serviço para a associação.
- **Quem já faz algo similar**: Agrotools (enterprise para traders), Serasa Smart ESG (financeiros), Niceplanet (B2B), Selo Verde (gratuito, mas só dados), Vega/LYRA (gratuito para revendas Bunge), STCP/PwC (consultoria mas sem produto).
- **Como nos diferenciamos**: produto + consultoria sob a marca da associação. Selo Verde dá o dado, nós damos o serviço. White-label cria barreira de entrada.
- **Mercado Sorriso/MT**: Sindicato Rural Sorriso 612 associados × R$ 500-2.000/produtor/ano = **R$ 0,3-1,2 milhão/ano só Sorriso**, expansível para Aprosoja-MT (milhares). Em MT inteiro: R$ 5-15 mi/ano realista.
- **Complexidade**: Baixa-Média. Dados públicos abundantes; AI conversacional é commodity. A complexidade está na **governança institucional** com a associação.
- **Tempo para primeiro resultado**: 30-45 dias (MVP com Selo Verde + LLM PT-BR).
- **Modelo**: anuidade por produtor (subsidiada pela associação) + setup pago pelo Sindicato/Aprosoja.

### Oportunidade #3 — Mesa de Inteligência de Comercialização (Hedge + Frete + Clima)
- **Dor**: soja a **R$ 110-115/sc** (2025) vs. ponto de equilíbrio **R$ 90,04/sc** (arq 06); margem espremida. Volatilidade extrema: frete Sorriso→Paranaguá saltou 38% em um mês; Sorriso→Miritituba +70% (arq 02). Estratégia mista (físico+futuro) provou-se a mais rentável em Sorriso (estudo Primavera do Leste/Sorriso: R$ 930/ha extra no futuro — arq 06). Hedge ainda subutilizado pelo médio. Nenhuma plataforma combina CBOT + basis local + frete + clima em recomendação executável (arq 03, gap explícito).
- **Solução com AI**: "mesa de inteligência" que recebe dados B3 + CBOT + IMEA + Sifreca + Climatempo, com agente LLM que recomenda janelas ótimas de venda/hedge por talhão e por contrato (físico, termo, futuro). Não executa; aconselha.
- **Por que nós podemos fazer**: combinamos dados públicos com o livro de cada produtor. Hedgepoint/StoneX/Safras vendem relatório genérico; nós entregamos recomendação individualizada.
- **Quem já faz algo similar**: Hedgepoint (recomendação corporativa), StoneX (corporativa), Tarken (price forecast B2B), Grão Direto (primeira venda por IA), Uhedge (calculadora), CME (relatórios diários AI).
- **Como nos diferenciamos**: produto **PT-BR para grande produtor** com dados locais MT (basis Sorriso, frete por rota, custo IMEA). Nenhum dos atuais combina os 3 vetores.
- **Mercado Sorriso/MT**: ~300 produtores médios-grandes em Sorriso × R$ 30-100k/ano = **R$ 9-30 milhões/ano só Sorriso**; MT-inteiro 10x.
- **Complexidade**: Alta no modelo; Média no produto (LLM + dashboards). Risco: produtor precisa confiar na recomendação.
- **Tempo**: 90-120 dias para piloto crível.
- **Modelo**: retainer mensal (R$ 5-15k/mês) + success fee opcional (% sobre receita incremental vs. baseline).

### Oportunidade #4 — Previsão de Fila Portuária + Otimização de Janela de Escoamento
- **Dor**: Sorriso é o município que mais sofre com pico de frete: **+38% Paranaguá em 1 mês, +70% Miritituba**. Em fev/2021 frete chegou a +57% em algumas rotas (arq 02, 06). Filas em Miritituba/Itaqui/Barcarena são gargalo em pico de safra. **"Não há solução comercial brasileira amplamente adotada que aplique IA preditiva para fila portuária de grãos — gap relevante de mercado"** (arq 02, achado #1).
- **Solução com AI**: ingerir dados públicos dos portais dos portos (Santos, Paranaguá, Itaqui, Barcarena, Miritituba) + AIS de navios + clima + boletins logísticos Conab → modelo preditivo de fila + recomendação de rota/janela.
- **Por que nós podemos fazer**: dados são públicos; ML é viável; ninguém empacotou. HBSA usa internamente (sem produto); Solinftec foca cana.
- **Quem já faz algo similar**: HBSA (uso interno), Solinftec Flow/WAY (cana), Conab (boletim genérico), FreteBras (matching, não previsão portuária).
- **Como nos diferenciamos**: produto vertical para soja MT; demo gera autoridade já na primeira reunião (todo produtor sente essa dor).
- **Mercado Sorriso/MT**: piloto Aprosoja + tradings + cooperativas; modelo B2B2B. Tickets R$ 50-200k/ano por cliente corporativo; alvo 10-20 clientes em 12 meses = **R$ 0,5-4 milhões/ano**.
- **Complexidade**: Média. Dados existem; modelagem é trabalhosa mas factível.
- **Tempo**: **15-30 dias** (esta é uma demo possível para a primeira reunião com dados públicos).
- **Modelo**: SaaS B2B para tradings/cooperativas; API para integradores logísticos.

### Oportunidade #5 — Agrônomo Digital LLM em Português Brasileiro
- **Dor**: 70% dos produtores MT apontam falta de mão de obra qualificada; 57% citam qualificação técnica como maior problema; 36% indicam déficit de operadores (arq 06). Solinftec ALICE+ChatGPT é o único pré-produto, e está embarcado no ecossistema próprio (arq 03, 05). "Não existe LLM treinado em corpus brasileiro de agro (Embrapa + Aprosoja + Conab + safras MT) como produto comercial maduro" (arq 03, gap explícito).
- **Solução com AI**: chatbot/copilot em PT-BR (WhatsApp + web) treinado em corpus público (Embrapa AgroAPI, AGROFIT, Agritec, AgroTermos, boletins IMEA, manuais Aprosoja, conteúdo Soja Plus). Foco em soja transgênica RR/IPRO, milho safrinha, algodão. Responde "que praga é essa?", "qual cultivar para esta janela?", "vou pulverizar em quanto tempo de chuva?".
- **Por que nós podemos fazer**: LLM moderno + RAG sobre corpus público é caminho conhecido; vantagem do PT-BR + nichado em MT.
- **Quem já faz algo similar**: Solinftec ALICE (embarcado), Embrapa AgroAPI (API, não produto final), AgroLLM (paper acadêmico mar/25), assistentes de rede varejo (genéricos).
- **Como nos diferenciamos**: agente neutro, multi-fonte, agnóstico de marca de defensivo/semente. Acesso por WhatsApp (canal #1 em MT — arq 06).
- **Mercado Sorriso/MT**: 612 associados Sindicato × R$ 100-500/ano = **R$ 0,06-0,3 mi**/ano só Sorriso; preço baixo, mas serve de "isca" — conversão para upsell (Cockpit #1, EUDR #2).
- **Complexidade**: Baixa-Média. RAG sobre dados públicos é well-trodden.
- **Tempo**: **30 dias** para MVP demo na primeira reunião.
- **Modelo**: freemium (gratuito com limite) + Premium R$ 49-99/mês por usuário + B2B2C white-label para associações.

### Oportunidade #6 — MRV de Carbono em Sistema Soja-Milho-ILPF
- **Dor**: mercado brasileiro de carbono salta de **US$ 2,11 bi (2024) → US$ 25,2 bi (2034)**, CAGR 28,1% (arq 04). Bayer PRO Carbono já em 3+ Mi ha; Cargill 3S; Bunge Regenerativa (250 mil ha). SBCE (Lei 15.042/2024) atinge 5.000 empresas com emissões >10 mil tCO₂/ano. Mas **nenhum player especialista em carbono em sistema soja-milho-MT**: Agrorobótica/Carbonext/Mombak focam outras culturas ou floresta (arq 05, gap #6).
- **Solução com AI**: serviço de MRV (Mensuração, Reporte, Verificação) usando Sentinel-2/Planet + ML para detectar plantio direto, cobertura, rotação, ILPF; integra com AGLIBS de Agrorobótica para carbono no solo; gera laudos Verra/Bureau Veritas.
- **Por que nós podemos fazer**: consultoria + plataforma é o produto certo para enquadrar produtores nos programas Bayer/Cargill/Bunge.
- **Quem já faz algo similar**: Bayer PRO Carbono (programa próprio), Cargill 3S, Bunge Regenerativa, NaturAll Carbon (próprio), Carbonext (floresta), Embrapa Soja Baixo Carbono.
- **Como nos diferenciamos**: especialização em soja-milho-MT (não cana, não floresta); independente dos programas dos tradings (orquestramos elegibilidade do produtor para o programa mais lucrativo).
- **Mercado Sorriso/MT**: Sorriso tem 25% da soja já certificada RTRS; conversão para programas carbono é caminho natural. 615 mil ha soja × R$ 30-80/ha de fee de orquestração = **R$ 18-50 milhões/ano só Sorriso** (cenário maduro 3-5 anos).
- **Complexidade**: Média-Alta (metodologia técnica + relacionamentos com Verra/Bureau Veritas).
- **Tempo**: 6-9 meses para primeiro contrato com produtor.
- **Modelo**: success fee (% sobre crédito de carbono gerado) + retainer de consultoria + setup.

### Oportunidade #7 — Monitoramento Preditivo de Silos para Cooperativas e Grandes Fazendas
- **Dor**: Brasil perde **10-13% da safra em armazenamento** (R$ 84 bi/ano — arq 02); déficit MT 45-52 Mi t. Sorriso lidera o BR em armazenagem (5,6 Mt) mas a tecnologia IoT+AI em silos está concentrada em poucos fabricantes (Kepler/Procer, Embratel Smart Silo).
- **Solução com AI**: camada de software em cima dos sensores que o silo já tem (não vendemos sensor) — ML preditivo de deterioração, otimização de aeração, alertas via WhatsApp/SMS. Funciona com sensores Kepler/Procer/Embratel.
- **Por que nós podemos fazer**: sem hardware é vantagem. Kepler/Procer/Embratel já têm os sensores; precisam de software de decisão. Cooperativas e grandes fazendas têm dados e nenhum analista.
- **Quem já faz algo similar**: Kepler Sync (próprio), Embratel Smart Silo, ALLTIS DOMO, Tago.io, Macnica DHW, Nivetec — todos vendem sensor + software bundled.
- **Como nos diferenciamos**: agnóstico de fabricante; consumimos dados via API; geramos alertas + relatórios + ROI.
- **Mercado Sorriso/MT**: ~50 unidades de armazenagem em Sorriso × ticket R$ 30-100k/ano = **R$ 1,5-5 milhões/ano só Sorriso**; armazéns de cooperativas e fazendas grandes em MT inteiro: 10x.
- **Complexidade**: Média. Integração com APIs proprietárias depende de parceria com fabricantes.
- **Tempo**: 60-90 dias por silo (parceria com fabricante para acesso a dados).
- **Modelo**: SaaS por silo/mês (R$ 1-5k/silo/mês).

### Oportunidade #8 — Pré-Classificação de Soja com Visão Computacional (Sob a Mudança Regulatória)
- **Dor**: classificação de soja por humano (IN 11/2007 do MAPA) é gargalo na recepção; Cocamar atingiu **97% de acurácia** com IA + SENAI; **CNA já se posicionou favoravelmente a regular IA para esta tarefa** (arq 02). Brasil Agritest faz em 4 min vs. 10-90 min manual; Neosilos NVisio em 1min20s; Tbit SoyGroundEye <2 min. Mudança regulatória prevista é o gatilho de escala.
- **Solução com AI**: serviço de pré-classificação consultiva (não substitui o classificador legal) que prepara a entrega na trading; gera laudo digital + previsão de descontos; recomenda ajustes (limpeza, secagem). Quando IN 11/2007 mudar, viramos o classificador.
- **Por que nós podemos fazer**: somos consultoria, não fabricante de hardware — podemos recomendar a melhor solução (Brasil Agritest, Neosilos, Tbit) e operar como serviço.
- **Quem já faz algo similar**: Brasil Agritest GRAS, Neosilos NVisio, Tbit Soy GroundEye, Bühler SORTEX (hardware enterprise), Cocamar (in-house).
- **Como nos diferenciamos**: serviço, não hardware; produtor não compra a máquina, paga por análise; preparo de negociação com a trading.
- **Mercado Sorriso/MT**: 2,08 Mt soja/ano em Sorriso × R$ 0,5-2/t = **R$ 1-4 milhões/ano só Sorriso**.
- **Complexidade**: Baixa-Média. Depende de parceria com fabricante de máquina.
- **Tempo**: 3-6 meses para piloto.
- **Modelo**: por análise (R$/t) ou por contrato com armazém/cooperativa.

### Oportunidade #9 — Copilot de Operação para Operador de Máquina + Gestão de RH Agro
- **Dor**: **70% dos produtores MT apontam falta de mão de obra qualificada**; 57% citam qualificação técnica como maior problema; 36% déficit de operadores (arq 06). "AI específica para RH agro é praticamente inexistente como categoria — é principalmente um buraco no mercado" (arq 03). Conjugar dados de John Deere Operations Center / AFS Connect com produtividade por operador, turnover, treinamento — ninguém faz (arq 03, gap explícito).
- **Solução com AI**: dashboard que correlaciona telemetria (JD/Case IH/AGCO/Jacto) com dados de RH + agronômicos; copilot LLM para o operador via tablet do trator ("qual a velocidade certa? por que está sobreaplicando?"); programa de treinamento gamificado.
- **Por que nós podemos fazer**: junção de telemetria + people analytics + LLM é nossa especialidade. Solinftec ALICE tem agente operacional como roadmap mas embarcado.
- **Quem já faz algo similar**: Solinftec ALICE (roadmap), Sofit (frota), JD Operations Center (dados), TOTVS RH/Senior HCM (genéricos).
- **Como nos diferenciamos**: foco vertical em operação agro, multi-marca, copilot de operador.
- **Mercado Sorriso/MT**: ~2.000 fazendas × 5-15 operadores × R$ 50-150/operador/mês = **R$ 6-54 milhões/ano só Sorriso**.
- **Complexidade**: Média-Alta. Integração com APIs JD/CNH/AGCO requer Leaf ou parceria.
- **Tempo**: 4-6 meses para piloto.
- **Modelo**: SaaS por operador/mês + retainer de implementação.

### Oportunidade #10 — Score Pré-Aprovação de Crédito + Plataforma de Originação para Distribuidoras
- **Dor**: **MT lidera recuperações judiciais do agro com 332 pedidos em 2025, 34% ligados à soja** (arq 06). Crédito caro (Selic 15%); participação do oficial caiu de 30% para 20%; agronegócio em RJ recorde de R$ 157 bi. Sorriso já tem caso público (Grupo Manso, R$ 241,7 mi). TerraMagna/Tarken/A de Agro/Nagro/Agrolend dominam o B2B financeiro mas o produtor não tem ferramenta para se preparar.
- **Solução com AI**: serviço para o produtor de Sorriso que analisa seu dossiê (CAR, CPRs, contratos, dados de safra) e gera score de pré-aprovação + recomendações para acessar funding privado; integra com TerraMagna/A de Agro/Agrolend para originar.
- **Por que nós podemos fazer**: somos o consultor; eles são originadores. Modelo de "broker de crédito agrícola com AI" não existe consolidado.
- **Quem já faz algo similar**: TerraMagna, A de Agro, Nagro (todos do lado financeiro); revendas de insumos (originadores). Nenhum atende o produtor como conselheiro independente.
- **Como nos diferenciamos**: lado do produtor, não do credor. Sem conflito de interesse.
- **Mercado Sorriso/MT**: 612 associados Sindicato × R$ 5-20k/ano por dossiê = **R$ 3-12 milhões/ano só Sorriso**.
- **Complexidade**: Média. Compliance financeiro + IA scoring + relacionamentos com originadores.
- **Tempo**: 4-6 meses para primeiro caso completo.
- **Modelo**: success fee % sobre crédito intermediado + setup do dossiê.

---

## C. QUICK WINS (resultados em < 30 dias)

Entregas factíveis em até 30 dias para impressionar já na reunião ou logo após:

1. **Dashboard público de fila portuária (Sorriso → Santos/Paranaguá/Miritituba)** — usando AIS dos navios + APIs públicas dos portais dos portos (Santos, Portos do Paraná, Conab Boletim Logístico). Tempo médio de espera por porto, projeção de pico, comparativo de rotas. **Demo: imprime/projeta no dia da reunião**. (arq 02)

2. **Chatbot WhatsApp "Agrônomo Sorriso"** — RAG sobre Embrapa AgroAPI + boletins IMEA + manual Soja Plus + AGROFIT. Responde dúvidas técnicas em PT-BR. **Demo: pede para o presidente do Sindicato perguntar "Quando aplicar fungicida para ferrugem?"**. (arq 01, 03)

3. **Análise satelital gratuita de uma fazenda-âncora do Sindicato** — Sentinel-2 + ML para mapa de NDVI, estresse hídrico, falhas de plantio nos últimos 3 anos. Identificar 2-3 talhões com potencial de +5-10 sc/ha. **Brindar a um produtor de referência para gerar word-of-mouth**. (arq 01)

4. **Relatório EUDR de risco para 10 propriedades** — cruzar CAR público + PRODES/DETER + polígonos do CAR + Selo Verde → classificação de risco EUDR para cada propriedade do Conselho do Sindicato. **Demo: planilha com semáforo verde/amarelo/vermelho**. (arq 02)

5. **Simulador de margem soja 25/26 + cenário hedge** — calculadora com custos IMEA + frete Sifreca + CBOT + basis B3, mostrando ponto de equilíbrio e R$/ha em 3 cenários de venda. Cobre dor #1 da matriz (margens espremidas). (arq 03, 06)

6. **Diagnóstico de "ativos digitais ociosos" no Sorriso médio-grande** — entrevistar 5 produtores associados e mapear: quantos compraram FieldView/Operations Center/Aegro mas não usam? Quanto custou? **Apresenta com lista de 10 quick wins de extração de valor de software já pago**. (arq 03, 05)

---

## D. ANÁLISE COMPETITIVA RESUMIDA

### Blue Ocean (sem concorrência forte) — 5 áreas onde podemos liderar
1. **Cockpit de decisão vendor-agnostic** (Oportunidade #1) — ninguém integra de verdade.
2. **EUDR white-label para associações** (Oportunidade #2) — Selo Verde dá dado, ninguém dá serviço B2B-associativo.
3. **Previsão de fila portuária de grãos** (Oportunidade #4) — gap puro de mercado (arq 02 explícito).
4. **LLM agronômico PT-BR neutro** (Oportunidade #5) — Solinftec ALICE é embarcado; ninguém oferece neutro.
5. **MRV de carbono em soja-milho-MT** (Oportunidade #6) — Agrorobótica/Carbonext focam outras culturas/biomas.

### Red Ocean fraco (concorrência genérica, podemos fazer melhor) — 5 áreas
1. **Mesa de inteligência de comercialização** (Oportunidade #3) — Hedgepoint/StoneX/Tarken não são vertical para produtor MT em PT-BR.
2. **Monitoramento preditivo de silos** (Oportunidade #7) — Kepler/Embratel vendem com sensor; falta software agnóstico.
3. **Pré-classificação de soja** (Oportunidade #8) — Brasil Agritest/Neosilos/Tbit competem; consultoria orquestradora é nova.
4. **Copilot de operador + RH agro** (Oportunidade #9) — ninguém consolidou; Solinftec só roadmap.
5. **Broker de crédito com AI** (Oportunidade #10) — TerraMagna/A de Agro são originadoras; broker pró-produtor não existe.

### NÃO entrar (dominado por gigantes) — 5 áreas com justificativa
1. **Hardware de máquinas agrícolas** — John Deere (NYSE: DE, market cap >US$ 100 bi), CNH/AGCO, Jacto, Stara, Trimble, Hexagon, Topcon. Capital e canal infinitos (arq 05).
2. **Plataforma SaaS abrangente "tipo FieldView"** — Bayer (28 Mi ha BR, FRA: BAYN), Solinftec (unicórnio R$ 1,3 bi). Competir é suicídio (arq 05).
3. **ERP agrícola** — Aliare (BTG Pactual), TOTVS Agro (acabou de ser comprada por multinacional US$ 30 bi em jan/2026), Aegro, SAP, Senior. Domínio total (arq 03, 05).
4. **Crédito agrícola direto (originação)** — TerraMagna (R$ 1 bi+ carteira), Agrolend (SCFI), Traive (US$ 17M+ BASF), Nagro (R$ 1 bi cedido), A de Agro (R$ 700 mi com BTG). Consultoria não tem balanço (arq 03, 05).
5. **Score de crédito/risco enterprise** — Agrotools (R$ 200 mi receita 2024), Agrosatélite (Serasa, adquirida 2023), Brain Ag, EarthDaily Agro, Tarken (11% do crédito). Dataset e relacionamentos bancários estabelecidos (arq 05).

---

## E. RECOMENDAÇÃO ESTRATÉGICA

### Posicionamento sugerido para a reunião

> "Somos uma consultoria de AI **vendor-agnostic** especializada em agro de soja em MT. Nosso trabalho não é vender mais um software — é **extrair valor do software que o produtor já comprou** (FieldView, Operations Center, AFS Connect, Aegro, Siagri) e **costurar tudo numa camada de decisão com ROI mensurável por talhão e por safra**. Diferente da Solinftec (que vende plataforma + robô), da FieldView (que é Bayer), da Aegro (ERP), nós **não temos hardware nem plataforma proprietária para defender** — só temos compromisso com a margem do produtor. Por isso podemos integrar tudo, recomendar a melhor combinação para cada fazenda e treinar a equipe. Nosso mantra: o produtor de Sorriso já tem AI espalhada pelo armário; queremos plugá-la num cockpit que ele entende e que dá lucro."

Esta narrativa enfrenta diretamente o ceticismo do produtor ("mais um vendedor de software?") e cria contraste defensável vs. Solinftec/FieldView/Cromai.

### 3 Serviços iniciais (high value, baixa complexidade)

**Serviço 1 — "Diagnóstico AI 360"**
- Descrição: auditoria de 4-6 semanas de uma fazenda (1-15 mil ha). Mapeamos todos os "ativos digitais" (plataformas, sensores, máquinas conectadas), identificamos 10-20 quick wins de extração de valor, entregamos roadmap de implementação. Inclui análise satelital independente e benchmark vs. pares.
- Ticket: R$ 80-200 mil por projeto.
- Prazo: 4-6 semanas.
- ICP: fazenda 3.000-30.000 ha, gestor profissional, já gasta em FieldView/Operations Center.

**Serviço 2 — "Compliance EUDR Sindicato Rural / Aprosoja Sorriso"**
- Descrição: plataforma white-label para a associação cobrir os 612 associados em 12 meses até deadline EUDR (dez/26). Inclui: cadastro de polígonos, dossiê EUDR por produtor, due diligence automatizada, helpdesk em PT-BR via WhatsApp.
- Ticket: R$ 500 mil-1,5 mi setup + R$ 500-2.000/produtor/ano.
- Prazo: 90-120 dias para go-live.
- ICP: associação/sindicato de produtores (B2B2C).

**Serviço 3 — "Mesa de Inteligência Comercial Soja"**
- Descrição: retainer mensal de análise de mercado + recomendação de hedge/comercialização para grupos com 5-50 mil ha. Combina dados B3+CBOT+IMEA+Sifreca+clima+seu livro de contratos. Reunião semanal por videoconferência + dashboard em tempo real.
- Ticket: R$ 5-15 mil/mês por grupo familiar.
- Prazo: 90 dias de implementação.
- ICP: grupo familiar com 5+ fazendas, R$ 200 mi+ de faturamento.

### Roadmap 6-12 meses

**Mês 1-2 — Aterrissagem**
- Estabelecer endereço/agente em Sorriso (mesmo que coworking + presença regular).
- Fechar 1-2 fazendas-âncora para piloto pago do "Diagnóstico AI 360".
- Assinar MoU com Sindicato Rural de Sorriso e/ou Núcleo Aprosoja Sorriso.
- Lançar Quick Win #2 (chatbot WhatsApp) gratuito para associados — gera tráfego e dado.
- Mapear 20-30 produtores-alvo dos top 50 da região.

**Mês 3-6 — Primeiros pilotos**
- Executar Diagnóstico AI 360 em 3-5 fazendas (ticket R$ 80-200k cada).
- Iniciar setup do EUDR white-label com a associação.
- Lançar MVP do Cockpit (Oportunidade #1) em 2-3 fazendas-piloto.
- Publicar 2-3 cases com números reais (ex.: "Fazenda X reduziu R$ 80/ha em fertilizante com taxa variável otimizada").
- Contratar 1-2 agrônomos seniors da região (rede + credibilidade).

**Mês 7-12 — Escala e produtos**
- Operar EUDR para 200-500 associados.
- Operar Mesa de Inteligência Comercial para 5-10 grupos.
- Lançar Previsão de Fila Portuária (Oportunidade #4) como produto B2B para tradings/cooperativas.
- Lançar MVP de MRV de Carbono (Oportunidade #6) com 1 produtor-piloto.
- Avaliar entrada em municípios vizinhos (Lucas do Rio Verde, Sinop, Nova Mutum) — mesmo perfil.
- ARR alvo no mês 12: **R$ 5-15 milhões**.

### Como estruturar a parceria com a associação

**Modelo**
- Anuidade base do produtor associado paga pelo Sindicato/Aprosoja (subsídio coletivo) cobrindo EUDR + chatbot.
- Serviços premium (Cockpit, Mesa Comercial, Diagnóstico) cobrados diretamente do produtor com **desconto de associado** (10-20%).
- Success fee opcional para crédito de carbono (% sobre crédito gerado, dividido com associação).

**Governança**
- Criar **Comitê Técnico de IA do Sindicato Rural / Aprosoja Sorriso** com 5-7 produtores + cliente + 1 agrônomo Embrapa Sinop como observador.
- Reuniões trimestrais; relatório de impacto (hectares cobertos, ROI por produtor, hectares em compliance EUDR).
- Diretoria do Sindicato (Diogo Damiani — presidente 2025/27) e coordenação Aprosoja Sorriso (Rafael Krzyzanski) como sponsors.

**O que pedimos da associação**
- Endosso institucional (não exclusividade) + acesso à base de associados para campanha.
- Acesso a dados agregados de safras anteriores (CAR, custos consolidados).
- Espaço em eventos (Exporriso, dia de campo, assembleias).
- 1-2 fazendas-âncora dispostas a piloto com case público.

**O que entregamos em troca**
- 612 associados com EUDR resolvido até dez/2026 (mitigação de risco bilionário em exportações).
- Chatbot agronômico gratuito (benefício de associação).
- Relatório anual público "Estado da AI no Agro de Sorriso" (PR e tráfego para o Sindicato).
- 1 reunião trimestral aberta com pauta livre dos associados.
- Desconto de 15-20% nos serviços premium.

---

## F. RISCOS E MITIGAÇÕES

1. **Ceticismo do produtor ("mais um vendedor de software")**
   - Mitigação: nunca vendemos software; vendemos *resultado*. Primeiro projeto sempre com ROI explícito em sacas/ha ou R$/ha. Casos em vídeo de produtor para produtor.

2. **Ciclo de venda longo (safra 25/26 já em curso)**
   - Mitigação: serviços de 30 dias (Diagnóstico AI 360 Lite, EUDR-light) para entrada; o "ciclo grande" segue normal mas há receita rápida.

3. **Sazonalidade da safra (caixa do produtor entra na colheita)**
   - Mitigação: ticket pago em 3-4 parcelas alinhadas ao calendário (preparo + plantio + entressafra + colheita); modalidades barter (mais comum no agro).

4. **Dependência de poucos clientes-âncora**
   - Mitigação: meta de no máximo 25% de receita em 1 cliente nos primeiros 18 meses. Estrutura comercial pulverizada com EUDR (B2B2C via associação).

5. **Concorrência de Solinftec (sede em Sinop, a 80 km de Sorriso)**
   - Mitigação: posicionamento explícito vendor-agnostic (Solinftec é plataforma + robô; somos integrador neutro). Evitar competir frontalmente em pulverização/robótica; jogar em decisão + integração + compliance.

6. **Mudança regulatória (EUDR pode ser adiado de novo; classificação IA pode demorar)**
   - Mitigação: produto EUDR funciona para Soja Plus, Moratória e outros mercados (CBIO, ABIOVE) mesmo se UE adiar. Pré-classificação é serviço consultivo, não depende de mudança da IN 11.

7. **Conectividade rural pobre (18% MT com 4G/5G)**
   - Mitigação: arquitetura offline-first; WhatsApp como interface (funciona com 2G/Starlink); parceria com Mato Grosso Conectado e Starlink Agro (promoção fev/2026 com 25% off).

---

## G. INDICADORES DE SUCESSO (KPIs)

**Primeiros 6 meses**
1. **Produtores associados ativos** (com algum serviço gratuito ou pago): **≥ 100** (de 612 do Sindicato)
2. **Fazendas em piloto pago (Diagnóstico AI 360 ou Cockpit)**: **3-5**
3. **Hectares cobertos pelos serviços**: **≥ 50.000 ha**
4. **ARR contratado**: **≥ R$ 1,5 milhão**

**Primeiros 12 meses**
5. **Produtores em compliance EUDR via nossa plataforma**: **≥ 250**
6. **Hectares cobertos**: **≥ 250.000 ha** (~40% da soja de Sorriso)
7. **ARR contratado**: **≥ R$ 5 milhões** (cenário base) ou **R$ 12-15 milhões** (cenário otimista com EUDR ramp)
8. **Cases publicados com ROI quantificado**: **≥ 3** (idealmente 1 com cada um dos top 5 grupos da região: Bom Futuro, SLC, Amaggi, família Tessaro, família Beledelli)

**KPIs qualitativos**
- Net Promoter Score (NPS) dos produtores atendidos: **≥ 60**
- Eventos com presença do cliente: **2/ano** (Exporriso, Show Safra BR-163)
- Mentions em mídia agro especializada (AgFeed, Canal Rural MT, The AgriBiz): **≥ 6/ano**

---

## Anexo — Cruzamentos críticos de dados

Cruzamentos não óbvios entre os 6 arquivos que sustentam as oportunidades:

| Cruzamento | Dado A | Dado B | Dado C | Oportunidade que sustenta |
|---|---|---|---|---|
| **Logística + Compliance + Mercado** | Frete Sorriso→Miritituba +70% em 1 mês (arq 02) | EUDR exige rastreabilidade até dez/2026 (arq 02) | Sorriso = 9% das exportações de MT em jan/24, principal destino China (arq 06) | Oportunidade #2 + #4 (EUDR white-label + Previsão de fila → posiciona Sorriso como hub logístico-compliance) |
| **Margem + Comercialização + Crédito** | Preço soja R$ 110-115/sc vs. ponto de equilíbrio R$ 90/sc (arq 06) | Hedge subutilizado pelo médio; estudo Primavera/Sorriso mostra +R$ 930/ha no futuro (arq 06) | MT lidera RJ no agro com 332 pedidos em 2025, 34% ligados à soja (arq 06) | Oportunidade #3 + #10 (Mesa de Inteligência + Broker de Crédito) |
| **Adoção + Conectividade + RH** | 76% inovadores em MT (arq 01, 06) | 18% das lavouras MT com 4G/5G (arq 06) | 70% dos produtores MT citam falta de mão de obra qualificada (arq 06) | Oportunidade #5 + #9 (LLM via WhatsApp offline-first + Copilot do operador) |
| **Armazenagem + Classificação + Trading** | Sorriso lidera BR com 5,6 Mt armazenagem (arq 02) | IN 11/2007 do MAPA pode mudar (CNA favorável) (arq 02) | Cocamar atingiu 97% acurácia com IA + SENAI (arq 02) | Oportunidade #7 + #8 (Monitoramento de Silos + Pré-classificação) |
| **Carbono + ILPF + Algodão + Sorriso** | Mercado carbono BR vai de US$ 2,7 bi (2025) para US$ 25,2 bi (2034) (arq 04) | Embrapa Agrossilvipastoril em Sinop (90 km de Sorriso) tem GeoABC (arq 04) | Algodão em MT = 1,46 Mi ha (70% BR); Sorriso tem 59 mil ha de algodão (arq 04, 06) | Oportunidade #6 (MRV soja-milho-algodão-ILPF integrado) |
| **Sucessão + Profissionalização + Ticket** | 79%/76% dos produtores MT preocupados com sucessão (arq 06) | Casos públicos em Sorriso (Beledelli, Belusso, Tessaro) — jovens com agronomia/administração (arq 06) | 60% dos empreendedores rurais BR entre 25-44 anos; 21% com superior (arq 06) | Sustenta TODOS os pilares: a próxima geração compra AI consultiva |
| **Solinftec proximidade + concorrência** | Solinftec sede em Sinop (MT), escritórios em Nova Mutum e Querência (arq 05) | Solinftec vende plataforma + robô R$ 370k/unidade + SaaS (arq 05) | Solinftec ALICE+ChatGPT é o único pré-LLM agro BR (arq 03, 05) | Justifica posicionamento vendor-agnostic (Oportunidade #1) e LLM neutro PT-BR (Oportunidade #5) |
| **Embrapa Sinop como aliado, não concorrente** | Embrapa Agrossilvipastoril em Sinop = maior plataforma experimental ILPF do mundo (arq 04) | Embrapa+Imea com parceria para modelos econômicos ILPF (arq 04) | Produtores de Sorriso já participam de dias de campo (arq 04) | Oportunidade #6 (MRV) + estratégia geral (parceria > competição com player público) |

---

> **Notas finais**
> - Todos os dados são citados com referência ao arquivo de origem (arq 01-06) ou URL nova.
> - Cenários de receita são estimativas baseadas em dados públicos × estrutura realista de pricing; assumem ramp-up gradual e taxa de conversão moderada (10-30% dos associados em 12 meses).
> - Interlocutores-chave confirmados (arq 06): **Diogo Damiani** (presidente Sindicato Rural Sorriso 2025/27), **Rafael Krzyzanski** (coordenador Aprosoja Sorriso), **Lucas Beber** (presidente Aprosoja-MT 24/26), **Alei Fernandes** (prefeito 2025/28).
