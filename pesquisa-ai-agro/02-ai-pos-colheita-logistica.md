# 02 — AI em Pós-Colheita, Armazenamento e Logística

> Pesquisa de mercado para consultoria de AI — foco em soja e Sorriso/MT
> Data de referência: maio/2026
> Maior cidade exportadora de soja do Brasil; PIB agrícola nº 1 do país (R$ 7,2 bi em 2024)

---

## 1. Armazenamento e Silos

### 1.1 O problema brasileiro: déficit e perdas estruturais

- **Perdas pós-colheita no Brasil**: a Embrapa estima que **cerca de 10% da produção nacional de grãos é perdida durante o armazenamento**. Outras estimativas mais agressivas indicam que o Brasil perde **~13% da produção (≈ 36 milhões de toneladas/ano)** por falhas logísticas e falta de infraestrutura — impacto financeiro estimado em **R$ 84 bilhões/ano**. ([O Presente Rural](https://opresenterural.com.br/brasil-colhe-mais-mas-ainda-perde-10-dos-graos-no-armazenamento/), [Destaque Rural](https://destaquerural.com.br/agricultura/armazenagem-e-um-dos-maiores-gargalos-do-agro/))
- **Déficit nacional de armazenagem**: capacidade estática estimada em **212–231 milhões de t**, suficiente para apenas **64% da safra**. Déficit total entre **111,6 e 135 milhões de t**. Investimento necessário para zerar o gap: **R$ 102 a R$ 148 bilhões**; necessário aporte de **~R$ 15 bi/ano** (ABIMAQ). ([Portal do Agronegócio](https://www.portaldoagronegocio.com.br/gestao-rural/analise-de-mercado/noticias/brasil-enfrenta-deficit-de-armazenagem-de-graos-e-precisa-investir-r-102-bilhoes-para-acompanhar-producao), [Tecnologística](https://www.tecnologistica.com.br/br/noticias/armazenagem/19960/deficit-de-armazenagem-de-graos-no-brasil-alcanca-120-milhoes-de-toneladas/), [Notícias do Campo](https://noticiasdocampo.com.br/brasil-precisa-de-r-148-bilhoes-para-zerar-deficit-de-armazenagem/))
- **Mato Grosso (estado)**: capacidade prevista para 2025 de **52,32 milhões de t**, com déficit de **~52,6 milhões de t (~51% do necessário)**. ([Aprosoja MT](https://aprosoja.com.br/comunicacao/release/em-mato-grosso-armazenagem-nao-acompanha-evolucao-da-safra-e-pode-gerar-risco-para-safras-futuras), [CenárioMT](https://www.cenariomt.com.br/agro/safra-recorde-de-graos-em-2025-e-o-desafio-da-armazenagem-no-brasil/))
- **Sorriso/MT — dado-chave**: lidera o ranking nacional de capacidade de armazenagem com **5,6 milhões de t** (75,7% em armazéns graneleiros). Sorriso responde por ~9% da capacidade total de MT. Produção de soja em Sorriso (2024): **2,08 milhões de t** — valor da produção R$ 3,3 bilhões (só soja). ([Momento MT](https://momentomt.com.br/momento-agro/producao-de-graos-ressalta-gargalo-de-armazenagem-em-mato-grosso/), [Agência Brasil](https://agenciabrasil.ebc.com.br/economia/noticia/2025-09/sorriso-no-mt-tem-maior-pib-agricola-do-pais-veja-o-ranking))

### 1.2 AI para monitoramento de temperatura/umidade em silos

**Como funciona**: sensores IoT (termometria digital, umidade, CO₂, nível) + plataforma em nuvem com IA emite alertas, prevê deterioração, aciona aeração automática. ([Nivetec](https://nivetec.com.br/estocagem-eficiente-como-o-monitoramento-inteligente-de-silos-transforma-o-agronegocio-brasileiro/), [Embratel/IPNews](https://teletime.com.br/23/04/2024/embratel-lanca-solucao-de-monitoramento-de-graos/))

**Soluções principais no Brasil:**

- **Kepler Weber — plataforma Sync / sensores Procer**: maior fabricante nacional de silos. Em 2023 adquiriu **50% + 1 ação da Procer** (sensores IoT) por **R$ 50,8 milhões**; Procer faturou R$ 60,4 mi em 2022 (EBITDA 26,3%). Construiu o **Silo 156 (35.000 t)** em Primavera do Leste/MT em parceria com Uniagro. Lançou robô (com Procer) para nivelamento automatizado de grãos armazenados. ([Brazil Journal](https://braziljournal.com/kepler-weber-usa-internet-of-things-para-aumentar-receita-recorrente/), [Cultivar](https://revistacultivar.com.br/noticias/kepler-weber-anuncia-aquisicao-da-procer-automacao), [Logweb](https://logweb.com.br/robo-para-graos-kepler-weber-procer-armazenagem/))
- **Embratel Smart Silo** (com Telemática Sistemas Inteligentes): IoT + big data + IA em nuvem; monitora CO₂, temperatura, umidade, volume, tonelagem. Sem cabos. Painel em tempo real com autodiagnóstico e alertas. Lançado em abr/2024. ([Teletime](https://teletime.com.br/23/04/2024/embratel-lanca-solucao-de-monitoramento-de-graos/), [Telesintese](https://telesintese.com.br/smart-silo-promete-aprimorar-monitoramento-de-graos-no-agronegocio/))
- **ALLTIS — sensor DOMO**: monitoramento em tempo real do volume e variações internas via satélite LEO (cobertura em regiões sem 3G/4G). Aplicação em silos rurais isolados — relevante para fazendas longe de centros urbanos de MT. ([Folha Agrícola](https://folhaagricola.com.br/2026/05/09/tecnologia-com-ia-permite-controle-em-tempo-real-de-racao-e-graos-nas-granjas/))
- **Tago.io Smart Feed Bin**: plataforma de monitoramento preditivo com analytics em tempo real. ([Tago.io](https://tago.io/use-cases/smart-feed-bin-predictive-grain-monitoring-with-real-time-analytics))
- **Macnica DHW / Nivetec / Idugel**: integradoras nacionais que oferecem stack IoT+IA. ([Macnica DHW](https://blog.macnicadhw.com.br/agronegocio/monitoramento-silos-agronegocio/), [Idugel](https://idugel.com.br/en/armazenamento-e-conservacao-de-graos/))

### 1.3 Sistemas preditivos de deterioração

Algoritmos de ML processam big data dos sensores para **prever spoilage, detectar anomalias e otimizar condições de aeração**. Aplicações incluem controle de umidade, infestação por pragas e gestão de inventário em tempo real. ([ScienceDirect 2025](https://www.sciencedirect.com/science/article/pii/S0022474X25000475))

**Quanto AI pode reduzir?** Cases internacionais documentados em literatura científica mostram potencial de **redução de 30–50% nas perdas de armazenagem** com sensoriamento + IA preditiva. No Brasil, dado quantificado específico **dado não encontrado** em base com nome de empresa local — gap para preencher em entrevistas com Kepler Weber e clientes.

### 1.4 Visão computacional para classificação de grãos

- **Brasil Agritest — GRAS (Grain Analytic System)**: parceria com Embrapa Instrumentação (São Carlos/SP). Visão computacional + técnicas fotônicas + IA para análise de defeitos (fermentados, ardidos, queimados, mofados, esverdeados, imaturos) **sem cortar o grão**. Tempo: **4 minutos vs. 10–90 min manual** (até 22× mais ágil). Prêmio Embrapii. ([Portal Agro Summit](https://portal.agrosummit.com.br/tecnologia-para-classificacao-automatica-de-defeitos-de-graos-de-soja-recebe-premio-embrapii), [VLI](https://www.vli-logistica.com.br/vli-apoia-brasil-agritest-no-desenvolvimento-de-uma-solucao-tecnologica-inovadora-e-100-nacional-para-a-cultura-da-soja/))
- **Neosilos (Curitiba/PR) — NVisio**: máquina do tamanho de um frigobar com câmera + ML para classificação automática de soja/milho. **1 min 20 s/análise**. Clientes: Cocamar, Lar, Frísia, Inpasa. ([AgFeed](https://agfeed.com.br/agtech/startup-neosilos-tenta-aposentar-o-olhometro-e-automatizar-a-classificacao-de-graos-com-cameras-e-ia/))
- **Cocamar + SENAI/PR**: cooperativa paranaense usa IA + visão computacional para classificar soja: **97% de acurácia**, redução drástica do tempo. Prêmio Somoscoop 2024. Parceria estendida à Neosilos. ([Cocamar](https://www.cocamar.com.br/comunicacao/noticia/6384/com-classificacao-da-qualidade-da-soja-por-ia-cocamar-e-premiada-no-somoscoop-em-brasilia), [SENAI/PR](https://www.senaipr.org.br/tecnologiaeinovacao/blog/cooperativa-faz-uso-de-inteligencia-artificial-para-classificar-graos-de-soja-com-apoio-do-senai-no-parana-1-36126-450326.shtml))
- **Tbit (Lavras/MG) — Soy GroundEye**: IA + leitura 360°. Análise em <2 min, capacidade ~250 análises/dia. ([Tbit](https://www.tbit.com.br/en/soybean-classification/))
- **Bühler — SORTEX J SpectraVision (MerlinAi)**: equipamento fabricado em Blumenau/SC; classificação óptica baseada em cor e formato, em homologação para soja. Bühler comprou Sanmak em 2010. ([Abitrigo](https://www.abitrigo.com.br/buhler-apresenta-uma-nova-era-da-selecao-optica/))

> **Bottleneck regulatório**: a IN 11/2007 do MAPA ainda exige classificação por **pessoa física** registrada. CNA já se posicionou favoravelmente a regular IA para esta tarefa. Mudança regulatória prevista é o gatilho de escala para Neosilos, Tbit e Brasil Agritest. ([Embrapa](https://www.embrapa.br/en/busca-de-noticias/-/noticia/71632904/tecnologia-para-classificacao-da-qualidade-de-graos-de-soja-e-destaque-no-famato-embrapa-show))

---

## 2. Logística e Transporte

### 2.1 Custo logístico Sorriso → portos (DADO CRÍTICO)

| Origem → Destino | Distância | Frete R$/t (2025-26) | Fonte |
|---|---|---|---|
| Sorriso → Santos (SP) | ~2.000 km | **R$ 490/t** (fev/2025) | [Canal Rural](https://www.canalrural.com.br/economia/logistica/valor-do-frete-para-o-transporte-de-milho-e-soja-oscila-nas-principais-rotas-do-pais/) |
| Sorriso → Paranaguá (PR) | 2.295 km | **R$ 460–510/t** | [CNA Brasil](https://cnabrasil.org.br/noticias/soja-pre%C3%A7o-do-frete-sobe-38-em-um-m%C3%AAs-a-partir-de-sorriso-mt) |
| Sorriso → Miritituba (PA) — Arco Norte | 1.017 km | **R$ 223 a R$ 277/t** | [Diário do Estado MT](https://www.diariodoestadomt.com.br/noticias/sorriso-mirititubafreteparalevarsojasubiumaisde70emumm-us/33249224), [Agronews](https://www.agronews.tv.br/frete-agricola-em-11-01-2026-pressiona-soja-agora) |
| Sorriso → Rondonópolis | ~600 km | R$ 118/t | [Canal Rural](https://www.canalrural.com.br/economia/logistica/valor-do-frete-para-o-transporte-de-milho-e-soja-oscila-nas-principais-rotas-do-pais/) |
| Sorriso → Cuiabá | ~410 km | R$ 129,42/t | [Agronews](https://www.agronews.tv.br/frete-agricola-em-11-01-2026-pressiona-soja-agora) |

- **Custo logístico da soja brasileira = 25% do preço de produção** (vs. 15% nos EUA). Diferença ≈ 10 pontos percentuais — uma "vantagem" americana estrutural que IA logística pode mitigar marginalmente. ([SNA](https://www.sna.agr.br/custo-com-transporte-no-brasil-representa-de-30-a-40-do-valor-recebido-pela-soja/), [Portal do Agronegócio](https://www.portaldoagronegocio.com.br/gestao-rural/logistica-e-transporte/noticias/transporte-de-cargas-custa-r-1-3-trilhao-ao-ano-e-evidencia-deficiencia-logistica-no-brasil))
- Em picos de safra, frete sobe **38–70% em um mês** (Sorriso → Paranaguá; Sorriso → Miritituba). Volatilidade é o oxigênio de soluções IA de hedge e otimização. ([CNA](https://cnabrasil.org.br/noticias/soja-pre%C3%A7o-do-frete-sobe-38-em-um-m%C3%AAs-a-partir-de-sorriso-mt))

### 2.2 AI para otimização de rotas

- **Solinftec — Flow + WAY**: empresa brasileira (Araçatuba/SP), 800 funcionários globais (330 em P&D), unidades em EUA, Colômbia, Canadá, China. **Flow** = gestão de frota end-to-end (campo → usina → retorno). **WAY** = IA decide melhor rota em segundos. Plataforma **Alice A.I.** integra decisão. Aplicação maior em cana, mas extensível a grãos. ([Solinftec](https://www.solinftec.com/pt-br/blog/inteligencia-artificial-na-agricultura-solinftec/), [blog Solinftec WAY](https://www.solinftec.com/pt-br/blog/logistica-no-agronegocio-2/))
- **FreteBras / CargoX (holding Frete.com — unicórnio R$ 6 bi+)**: investiu **R$ 800 milhões em IA nos últimos 3 anos**. **Agro = 50% das cargas movimentadas**. Base com **900 mil motoristas ativos**, **25 mil transportadoras**, **20 milhões de análises de frete/ano**. Algoritmo de matchmaking carga↔caminhoneiro (geolocalização, histórico, tipo de carga). Exemplo dado pela empresa: caminhão de Santos que esteja em Sorriso recebe rota de retorno otimizada. ([AgFeed](https://agfeed.com.br/negocios/unicornio-dos-fretes-investe-r-800-milhoes-e-em-ia-para-transportar-supersafra/), [blog FreteBras](https://blog.fretebras.com.br/nova-fretebras-inteligencia-artificial-revoluciona-fretes-do-agro/))
- **Strada (ex-Carguero + TipBank)**: plataforma com IA + pagamentos de frete para o agro. ([AgFeed](https://agfeed.com.br/agtech/na-esburacada-logistica-brasileira-startup-strada-avanca-turbinada-por-quatro-gigantes/))
- **Hive Trucks**: **dado não encontrado**. A busca por "Hive Trucks" não retornou referência de startup brasileira ativa com esse nome. Possíveis confusões: Hive.app (operações internacionais, não-agro) ou nome próximo a outra startup. Recomenda-se validação direta com cliente sobre referência exata.
- **MBRF (BRF + Marfrig)**: implementou IA para otimização de rotas de entrega — case fora da soja, mas demonstra adoção corporativa do agro brasileiro. ([Radar Digital BSB](https://radardigitalbrasilia.com.br/agronegocio/mbrf-implementa-ia-para-otimizar-rotas-e-aumentar-eficiencia-na-logistica-de-entregas/))

### 2.3 Previsão de filas em portos

- **Estado da arte**: portos brasileiros (Santos, Paranaguá, Itaqui, Barcarena) **divulgam dados de atracação e fila em tempo real via portais públicos**. Não há solução comercial brasileira amplamente adotada que aplique IA preditiva para fila portuária de grãos — **gap relevante de mercado**. ([Porto de Santos](https://www.portodesantos.com.br/informacoes-operacionais/operacoes-portuarias/navegacao-e-movimento-de-navios/atracacoes-programadas/), [Portos do Paraná](https://www.portosdoparana.pr.gov.br/Pagina/Tempo-Real))
- **Hidrovias do Brasil (HBSA)**: usa tecnologia para "antecipar riscos climáticos, aumentar eficiência operacional e apoiar tomada de decisão" nos corredores. Atua principalmente no Corredor Norte (Tapajós) e Santos. Não publica detalhes técnicos sobre IA preditiva específica. ([HBSA](https://www.hbsa.com.br/nossas-solucoes/))
- **Quantum/dimensão de gargalo**: corredores hidroviários do Arco Norte movimentaram **49,7 milhões de t de soja + milho** (jan–out 2025). ([CNN Brasil](https://www.cnnbrasil.com.br/infra/arco-norte-se-consolida-mas-gargalos-logisticos-freiam-avanco/))

### 2.4 Gestão de frota com AI

- **Solinftec Flow** (descrito acima) — case dominante em sucroenergético, em expansão.
- **VLI / Rumo**: principais operadores ferroviários — automação de pátios via PLC + analytics, mas IA preditiva de cadeia ainda em maturação.
- **TruckPad / FreteBras**: gestão de frota com matching baseado em ML.

### 2.5 Logística multimodal

- **Rumo Logística — Malha Norte**: 41% market share de exportação de grãos em MT; expandindo de Rondonópolis para **Lucas do Rio Verde (LRV)** — extensão de **743 km**, R$ 2 bi investidos em 2025; primeira fase Rondonópolis → terminal Dom Aquino/Campo Verde (162 km) prevista para **2º semestre de 2026**. ([CNN Brasil](https://www.cnnbrasil.com.br/economia/macroeconomia/maior-obra-ferroviaria-do-pais-avanca-1-km-por-dia-em-mato-grosso/), [Revista Ferroviária](https://revistaferroviaria.com.br/2026/03/rumo-divulga-desempenho-de-2025-e-projeta-conclusao-da-ferrovia-de-mato-grosso/), [Logweb](https://logweb.com.br/rumo-movimentacao-ferroviaria-produtos-agroindustriais-2025/))
- **Rumo participação Santos**: 54% do market share. Volume total transportado: 84,2 bi TKU (+5,4% YoY). ([Logweb](https://logweb.com.br/rumo-movimentacao-ferroviaria-produtos-agroindustriais-2025/))
- **Ferrogrão (EF-170)**: 933 km de Sinop/MT → Miritituba/PA. CAPEX **R$ 33,3 bi**; OPEX R$ 103,8 bi previstos. Capacidade madura: **66 milhões t/ano**. Edital previsto jun/2025, leilão **set/2025–2026**. Projeto continua envolto em controvérsia (impactos ambientais e indígenas). ([Revista OE](https://revistaoe.com.br/ferrograo-rota-alternativa/), [Revista Ferroviária](https://revistaferroviaria.com.br/2025/02/viabilidade-da-construcao-da-ferrograo-continua-motivo-de-polemica/), [Amazon Watch](https://amazonwatch.org/pt/news/2025/0719-soy-dictates-the-path-how-ferrograo-is-reshaping-life-in-the-amazon))
- **Hidrovia do Tapajós + Miritituba (PA)**: ETCs (estações de transbordo de carga) com capacidade de **18 milhões t/ano**. Arco Norte foi responsável por **35% das exportações de soja em nov/2024** (vs. Santos 28,9% e Paranaguá 13,9%). ([Brasil de Fato](https://www.brasildefato.com.br/2024/12/11/de-agrovila-pacata-a-grande-porto-de-graos-miritituba-e-engolida-pela-chegada-da-soja-a-amazonia/), [MT Econômico](https://matogrossoeconomico.com.br/agronegocio-mato-grosso/hidrovias-do-arco-norte-se-consolidam-como-eixo-estrategico-ao-agro-especialmente-de-mt/), [Conab](https://www.conab.gov.br/ultimas-noticias/5886-boletim-logistico-mostra-desempenho-das-exportacoes-de-soja-e-milho-em-2023-24-e-aponta-tendencia-para-2024-25))
- **Porto de Itaqui (MA)**: maior crescimento entre os portos do Arco Norte — saltou de **11,21 Mt (2020) para 20,22 Mt (2024)**. **+80,3% em 4 anos**. Movimento de soja em 2024: 13,74 Mt (recorde histórico). ([Portal Barcarena](https://portalbarcarena.com.br/barcarena-e-itaqui-puxam-alta-de-mais-de-57-nas-exportacoes-de-graos-pelo-arco-norte-nos-ultimos-anos/), [Investing.com](https://br.investing.com/news/stock-market-news/porto-de-itaqui-exportou-mais-soja-em-2024-apesar-da-quebra-de-safra-aponta-conab-1575465))
- **Barcarena (PA)**: 9,7 Mt em 2024 (-600 mil t YoY).

---

## 3. Rastreabilidade e Compliance

### 3.1 EU Deforestation Regulation (EUDR) — o gatilho regulatório

- **Cronograma atualizado (dezembro/2025)**: aplicação adiada para **30/12/2026** para todos os operadores (grande, médio e pequeno); micro/pequenos têm 6 meses extras. Valor original era dez/2024 → dez/2025 → agora dez/2026. ([EU Access2Markets](https://trade.ec.europa.eu/access-to-markets/pt/news/aplicacao-do-regulamento-delegado-da-ue-relativo-aos-produtos-nao-associados-desflorestacao-adiada), [Milaré](https://milare.adv.br/eudr-o-impacto-do-segundo-adiamento-e-o-cenario-para-o-brasil/))
- **Commodities cobertas**: soja, carne bovina (carne+couro), café, cacau, borracha, óleo de palma, madeira.
- **Marco temporal de corte**: não pode ter desmatamento (mesmo legal) **após 31/12/2020**.
- **Exigências**: prova digital, geolocalização (geometria do polígono da plot), due diligence completa da origem do grão.
- **Exposição financeira do Brasil**: **US$ 46,3 bilhões em exportações para a UE** em jogo; ~1/3 desse total = commodities afetadas pelo EUDR. ([IT Forum](https://itforum.com.br/noticias/regulamentacao-europeia-agronegocio-brasileiro/), [Diovane Franco](https://diovanefranco.com.br/eudr-regulamento-europeu-desmatamento/))
- **Custo de não conformidade**: produção **retida no porto europeu** + perda de mercado. Multa específica **dado não encontrado** (varia por país membro UE).

### 3.2 Players de rastreabilidade

#### Agrosatélite (Florianópolis/SC)
- Monitoramento por satélite das obrigações da **ABIOVE + ANEC** sob a Moratória da Soja na Amazônia desde 2006.
- Identificou que **97,1% da expansão da soja na Amazônia ocorreu sem desmatamento** no período; no Cerrado situação inversa — **>17.000 km² de vegetação nativa desmatada para soja**. ([Reporter Brasil](https://reporterbrasil.org.br/wp-content/uploads/2022/11/Monitor_Cerrado_NOV_V3.pdf), [Greenpeace](https://www.greenpeace.org/brasil/blog/moratoria-da-soja-na-amazonia-dez-anos-de-resultados/))

#### Agrotools (São José dos Campos/SP)
- Maior banco de dados do agro do mundo (autodescrito), com **30 milhões de análises/ano**.
- **60% das operações de carne e até 40% de grãos** no Brasil passam pelas plataformas da empresa.
- Receita **R$ 200 milhões** (2024). Lançou marketplace de **pagamentos por serviços ambientais (PSA)** — autodenominado "maior do mundo".
- Monitora **280 milhões de hectares** de vegetação nativa em propriedades rurais brasileiras. ([Exame](https://exame.com/esg/agrotools-lanca-maior-plataforma-de-pagamentos-ambientais-do-mundo-e-mira-investidores/), [Bloomberg Línea](https://www.bloomberglinea.com.br/agro/agrotools-chegou-a-r-200-mi-em-receitas-com-dados-made-in-brazil-o-ceo-quer-mais/), [PIT SJC](https://pitsjc.org.br/empresas/agrotools-gestao-e-monitoramento-geo-espacial-de-riscos-s-a/))

#### Niceplanet Geotecnologia
- 13+ anos em rastreabilidade e sourcing responsável.
- Cliente-âncora: **Minerva Foods** — desenvolveu **app SMGeo Prospec** para conformidade socioambiental. ([Niceplanet](https://niceplanet.com.br/en), [ADVFN](https://br.advfn.com/jornal/2021/10/minerva-lanca-em-parceria-com-a-niceplanet-geotecnologia-aplicativo-de-apoio-aos-produtores-rurais))

#### Serasa Experian Agro — Smart ESG
- Monitora **80 milhões de hectares/dia** em MT+MS+GO.
- Estudo (out/2025): **90,7% das áreas de soja monitoradas em compliance** (zero overlap com desmatamento recente); **MT = 91,9%**, MS = 90,3%, GO = 82,9%.
- Parceria com MBRF cobre **44 milhões de hectares**. ([Canal Rural](https://www.canalrural.com.br/agricultura/projeto-soja-brasil/mais-de-90-de-soja-cresce-sem-desmatamento-na-amazonia-legal-revela-estudo-da-serasa-experian/), [Serasa Experian Agro](https://www.serasaexperian.com.br/solucoes/agro/))

#### TerraMagna (São Paulo)
- Maior agfintech da América Latina (fundada 2017). Carteira de crédito de **R$ 1 bi+** já alcançada; meta **R$ 18 bi sob gestão de risco em 2025** (via spinoff TM Digital para distribuidores de insumos).
- Combina dados de satélite + agronomia + finanças. Produtos: análise de crédito, pré-financiamento, monitoramento satélite, performance de carteira. ([TerraMagna](https://terramagna.com.br/), [AgFeed](https://agfeed.com.br/agtech/terramagna-lanca-nova-empresa-de-olho-nos-riscos-e-em-r-18-bi-das-revendas-de-insumos/), [Exame](https://exame.com/invest/mercados/fintech-que-aproxima-a-faria-lima-do-agro-terramagna-quer-chegar-a-r-2-bi-em-credito-em-2024/))

#### Vega Monitoramento (parceira Bunge)
- Plataforma **LYRA** = imagens de satélite + sensoriamento remoto + IA + dados estruturados.
- Bunge oferece acesso gratuito a revendas via **programa Parceria Sustentável**. ([Bunge](https://www.bunge.com.br/Press-Releases/Bunge-anuncia-ampliacao-do-monitoramento-da-soja-de-sua-cadeia-de-suprimentos-indiretos-no-Brasil))

#### Selo Verde (PA, depois MT/AC/RO)
- Plataforma **gratuita** que usa dados governamentais para rastrear compliance EUDR. Iniciada em 2021 (PA) para soja+carne; adotada por mais 3 estados. ([Mongabay](https://news.mongabay.com/2026/02/in-brazil-a-free-platform-uses-government-data-to-track-eudr-compliance/))

### 3.3 Blockchain + AI para certificação de origem

- **Bunge + Bangkok Produce (CP Foods)**: blockchain para rastreabilidade de soja livre de desmatamento + pegada de carbono dos volumes vendidos. Sistema cobre **>16 mil fazendas / 20 milhões de hectares na América do Sul**. ([Bunge](https://www.bunge.com.br/Press-Releases/Bunge-e-CP-Foods-aumentam-transparencia-no-embarque-de-soja-livre-de-desmatamento), [Cultivar](https://revistacultivar.com.br/noticias/bunge-testa-plataforma-de-rastreabilidade-por-blockchain-para-soja-sustentavel))
- **Bunge primeira exportadora a alcançar 100% de rastreabilidade no Cerrado** (cadeia direta e indireta). ([Money Times](https://www.moneytimes.com.br/bunge-se-torna-1a-exportadora-a-ter-100-de-rastreabilidade-da-soja-no-cerrado-pads/))
- **Cargill + ADM + Bunge — Soft Commodities Forum**: comprometimento setorial com cadeia de suprimento transparente. ([Cargill Brasil](https://www.cargill.com.br/pt_BR/2019/f%C3%B3rum-de-commodities-agr%C3%ADcolas))
- **GS1 Brasil**: padrão para identificação de produtos compatíveis com EUDR. ([GS1](https://www.gs1br.org/europe-deforestation-regulation))

### 3.4 Créditos de carbono no agro

- **NaturAll Carbon**: primeiro projeto **das Américas** a emitir créditos certificados sob padrão **Verra VM0042** (agricultura regenerativa). Usa sensores de solo + satélites + IA para quantificar sequestro de carbono. ([Exame](https://exame.com/esg/brasil-lanca-primeiros-creditos-de-carbono-por-agricultura-regenerativa-nas-americas/), [GreenIO](https://greenio.com.br/noticias/creditos-carbono-agricultura-regenerativa-brasil/))
- **Iniciativa Carbono Bayer**: 1.200 produtores Brasil+EUA, ~500 no Brasil em 14 estados (predominância soja+milho). ([Bayer](https://www.agro.bayer.com.br/conteudos-impulso-bayer/rastreabilidade-de-alimentos))
- **Metodologia validada Bureau Veritas** (Brasil): combina dados NASA/ESA + IA, **>200 índices vegetais** (clorofila, biomassa, umidade), área mínima **100 ha**, precisão ~100%. ([Terra](https://www.terra.com.br/noticias/chega-ao-pais-nova-tecnica-para-mensurar-creditos-de-carbono,a7659479ce6a832a9410388c47fada58ennf9ol8.html))

### 3.5 Moratória da Soja — virada de jogo em 2026

- **Status atual (jan/2026)**: lei estadual de MT que **retira benefícios fiscais** de empresas que aderirem à Moratória entrou em vigor em **01/01/2026**, após STF derrubar liminar.
- **ABIOVE saiu da Moratória** seguida pelos principais traders. Greenpeace alerta que **fim da moratória pode aumentar desmatamento Amazônia em até 30% até 2045**.
- **Impacto**: ruptura do principal mecanismo voluntário de governança setorial brasileiro — aumenta pressão por **rastreabilidade individual via IA/satélite** (substituto técnico). ([Agência Brasil](https://agenciabrasil.ebc.com.br/meio-ambiente/noticia/2026-01/lei-que-pune-participantes-da-moratoria-da-soja-volta-valer-em-mt), [Brazil Journal](https://braziljournal.com/a-moratoria-da-soja-acabou-o-que-vira-em-seu-lugar/), [Greenpeace](https://www.greenpeace.org/brasil/imprensa/moratoria-da-soja-sob-ataque-traders-precisam-decidir-entre-desmatamento-zero-ou-beneficios-fiscais/))

### 3.6 Soja Plus

- Programa de gestão voluntária criado pela **Aprosoja/MT em 2010**. Hoje em MT, MS, BA, MG, MA, SP.
- Reconhecido pela **FEFAC + IDH** — usado como evidência de sustentabilidade da soja mato-grossense para União Europeia. ([Aprosoja MT](https://aprosoja.com.br/comunicacao/release/programa-soja-plus-e-referencia-mundial-em-gestao-de-propriedade-rural), [IBS](https://www.biosistemico.org.br/noticias/programa-soja-plus-completa-10-anos-de-atividades-no-brasil/))

---

## 4. Gestão de Qualidade

### 4.1 Players consolidados

| Player | Tecnologia | Tempo de análise | Onde está | Cliente-âncora |
|---|---|---|---|---|
| Brasil Agritest | GRAS (Embrapa) — visão + IA + fotônica | 4 min | São Carlos/SP | VLI; pilotos com cooperativas |
| Neosilos | NVisio — ML + câmera | 1m20s | Curitiba/PR | Cocamar, Lar, Frísia, Inpasa |
| Tbit | Soy GroundEye — IA 360° | <2 min | Lavras/MG | 250 análises/dia |
| Bühler | SORTEX J SpectraVision (MerlinAi) | Em-linha | Blumenau/SC | Foco indústrias processadoras |
| Cocamar (cliente) | + SENAI/PR | 97% acurácia | Maringá/PR | Use case interno |

### 4.2 Integração com trading (CBOT, B3)

- Tema de **convergência futura** — não há ainda solução brasileira amplamente adotada que integre classificação automatizada por IA → cotação dinâmica em B3/CBOT.
- **TerraMagna** e **FreteBras** têm a infraestrutura de dados mais próxima de habilitar essa convergência (crédito + frete em tempo real).

---

## 5. Empresas a investigar com profundidade

### 5.1 Kepler Weber (KEPL3 — B3)
- **O que faz**: maior fabricante de silos do Brasil. Plataforma **Sync** (IoT). Sensores via Procer (adquirida em 2023 por R$ 50,8 milhões por 50%+1).
- **Presença em MT**: **fábrica em MS + Silo 156 (35 mil t) em Primavera do Leste**. Forte presença comercial em todo o estado.
- **Pricing**: dado não encontrado publicamente (B2B, depende do projeto).
- **Cases**: parceria Uniagro/MT; robô de nivelamento; Caramuru Alimentos. ([Brazil Journal](https://braziljournal.com/kepler-weber-usa-internet-of-things-para-aumentar-receita-recorrente/), [Kepler RI](https://ri.kepler.com.br/en/noticia/kepler-weber-registra-receita-de-r-5158-milhoes-e-avanco-de-rentabilidade-no-terceiro-trimestre/))

### 5.2 Agrotools
- **O que faz**: SaaS de monitoramento geoespacial + risco socioambiental. 30 mi de análises/ano. Marketplace PSA.
- **Presença em MT**: 40% das operações de grãos no Brasil — MT é o maior cliente implícito.
- **Pricing**: dado não encontrado (B2B enterprise).
- **Cases**: clientes ABIOVE, ANEC, traders globais. ([Exame](https://exame.com/esg/agrotools-lanca-maior-plataforma-de-pagamentos-ambientais-do-mundo-e-mira-investidores/))

### 5.3 Niceplanet
- **O que faz**: rastreabilidade + conformidade socioambiental.
- **Cliente principal**: Minerva Foods (carne, não soja diretamente).
- **Pricing**: dado não encontrado. ([Niceplanet](https://niceplanet.com.br/en))

### 5.4 Serasa Experian Agro
- **O que faz**: Smart ESG (80 mi ha/dia em MT+MS+GO); score de crédito; rastreabilidade.
- **Presença em MT**: forte (MT é o maior parquímetro de dados).
- **Cases**: parceria MBRF (44 mi ha). ([Serasa Experian Agro](https://www.serasaexperian.com.br/solucoes/agro/))

### 5.5 Agrosatélite
- **O que faz**: monitoramento satelital com IA da Moratória da Soja (ABIOVE + ANEC).
- **Cases dominantes**: relatório anual da Moratória; Monitor Cerrado.
- **Forte em pesquisa publicada** — diferenciação científica. ([Greenpeace](https://www.greenpeace.org/brasil/blog/moratoria-da-soja-na-amazonia-dez-anos-de-resultados/))

### 5.6 TerraMagna
- **O que faz**: agfintech + monitoramento satélite + gestão de risco de crédito.
- **Cases**: FMC, AgroGalaxy. Carteira de crédito R$ 1 bi+.
- **TM Digital**: R$ 18 bi sob gestão projetados para 2025. ([TerraMagna](https://terramagna.com.br/))

### 5.7 Solinftec
- **O que faz**: IA + SaaS + IoT (Alice A.I., Flow, WAY). Logística forte em cana — expansão a grãos.
- **Presença internacional**: EUA, Canadá, Colômbia, China. ([Solinftec](https://www.solinftec.com/pt-br/blog/inteligencia-artificial-na-agricultura-solinftec/))

### 5.8 Hive Trucks
- **Dado não encontrado**. Buscas em PT-BR e EN não retornaram empresa ativa com esse nome no espaço de logística agrícola brasileira. Recomenda-se validação com cliente.

### 5.9 Rumo Logística (RAIL3 — B3)
- **O que faz**: maior operadora ferroviária de carga do Brasil. Malha Norte (MT principal).
- **Investimento atual**: R$ 2 bi (2025) na extensão Rondonópolis → Lucas do Rio Verde.
- **Market share**: 41% grãos MT; 54% Santos.
- **Uso de IA**: dado público específico **não encontrado** sobre soluções de IA; foco no avanço da malha física. ([Rumo](https://www.rumolog.com/), [Revista Ferroviária](https://revistaferroviaria.com.br/2026/03/rumo-divulga-desempenho-de-2025-e-projeta-conclusao-da-ferrovia-de-mato-grosso/))

### 5.10 Hidrovias do Brasil (HBSA3 — B3)
- **O que faz**: logística hidroviária. Corredor Norte (Tapajós/Miritituba/Barcarena) é o ativo principal para soja de MT.
- **Uso de IA**: declara uso para "antecipar riscos climáticos" — detalhes técnicos não divulgados. ([HBSA](https://www.hbsa.com.br/nossas-solucoes/))

---

## 6. EUDR e Compliance Internacional

### 6.1 Calendário consolidado

| Data | Evento |
|---|---|
| 31/12/2020 | Marco temporal (não pode haver desmatamento posterior) |
| 30/12/2024 | Data original (adiada) |
| 30/12/2025 | Segunda data (adiada) |
| **30/12/2026** | **Aplicação para todos os operadores** (acordo dez/2025) |
| jun/2027 | Fim do período extra para micro/pequenos |

### 6.2 Custo de não conformidade para produtor brasileiro

- **Cenário pessimista**: produção **retida no porto** europeu se não houver geolocalização + due diligence.
- **Mercado em risco**: US$ 46,3 bi (exportações totais à UE); fração afetada ~1/3.
- **Custo individual de adequação**: dado não encontrado em fontes públicas consolidadas (varia por tamanho de fazenda; consultorias estimam R$ 5–50/ha conforme complexidade).

### 6.3 Quem oferece soluções AI prontas para EUDR no Brasil

- **Selo Verde** — plataforma **gratuita** (PA, MT, AC, RO). Usa dados públicos (CAR, PRODES, DETER) — recomendada como entry point.
- **Agrotools** — pacote enterprise para traders.
- **Serasa Smart ESG** — usado por grandes financeiros + traders.
- **TerraMagna** — embute compliance em crédito.
- **Vega Monitoramento (Bunge LYRA)** — gratuito para revendas da rede Bunge.
- **STCP** — consultoria especializada em conformidade EUDR (madeira, mas expansão prevista para grãos). ([STCP](https://www.stcp.com.br/servicos-de-conformidade-eudr/))
- **PwC** — consultoria + suporte AI/dados. ([PwC](https://www.pwc.com.br/pt/consultoria/agtech-innovation/agtech-innovation-news/artigos/2025/EUDR-na-pratica-como-o-agro-brasileiro-pode-liderar-a-nova-era-da-rastreabilidade.html))

### 6.4 Oportunidade para Sorriso

- **Sorriso é maior PIB agrícola do Brasil** (R$ 7,2 bi em 2024) e exportadora pesada de soja, principalmente para UE e China.
- **Risco específico**: produtores em fronteira agrícola (Sorriso fica no limite Cerrado-Amazônia) podem ter áreas com **desmatamento legal pré-2020 mas próximo ao corte temporal**.
- **Oportunidade B2B**: Aprosoja/Sorriso poderia operar **white-label** de plataforma EUDR para seus associados (modelo replicável).
- **Sinergia com Soja Plus**: já existe infra de gestão Aprosoja, basta camada de geo-IA.

---

## 7. Síntese: o que JÁ existe vs. o que NÃO existe

| Categoria | Maturidade no Brasil | Players principais | Gap |
|---|---|---|---|
| Monitoramento de silos (IoT+IA) | **Alta** | Kepler Weber + Procer, Embratel Smart Silo, ALLTIS, Nivetec, Macnica | Penetração baixa em fazendas pequenas/médias; falta integração entre players |
| Classificação visão computacional de grãos | **Média-alta** (tecnologia) / **baixa** (escala) | Brasil Agritest (GRAS), Neosilos, Tbit, Bühler, Cocamar | Bloqueio regulatório (IN 11/2007 do MAPA exige humano) |
| Predição de deterioração com ML | **Média** | Embratel, Tago.io, sensores Kepler/Procer | Falta benchmarking com dados reais brasileiros |
| Otimização de rotas com IA | **Alta (em sucroenergético)** / **Média (grãos)** | Solinftec (Flow/WAY), FreteBras+CargoX, Strada | Adoção pulverizada; falta camada portuária |
| Previsão de filas portuárias | **Baixa** | Portais públicos; HBSA usa internamente | **Gap claro de mercado** — oportunidade verde |
| Gestão de frota end-to-end | **Média** | Solinftec, TruckPad | Falta integração ferrovia↔caminhão↔hidrovia |
| Rastreabilidade satelital (Moratória/EUDR) | **Alta** | Agrosatélite, Agrotools, Serasa Agro, Niceplanet, Vega/LYRA, Selo Verde, TerraMagna | Múltiplos padrões — falta interoperabilidade |
| Blockchain + IA para origem | **Pioneira/teste** | Bunge+CP Foods, GS1 | Pouca padronização; escala limitada |
| Créditos de carbono via IA | **Emergente** | NaturAll Carbon (Verra VM0042), Bayer Carbono, Embrapa+startups | Mercado regulatório brasileiro (PL 528) ainda em construção |
| Integração classificação ↔ trading (CBOT/B3) | **Inexistente** comercial | — | **Gap puro** — oportunidade |
| IA para pricing de frete (hedge) | **Inexistente** consolidada | — | **Gap puro** — FreteBras tem dados, falta produto |
| Plataforma white-label EUDR para associações de produtores | **Inexistente** | — | **Gap puro** — oportunidade direta para Sorriso |

### Três achados principais para o cliente:

1. **Logística é o maior gap proporcional**: o custo logístico da soja brasileira é **25% do preço de produção vs. 15% nos EUA**. Em picos de safra, frete Sorriso→Paranaguá sobe 38–70% em um mês. Não existe solução comercial brasileira amplamente adotada que combine previsão de fila portuária + matching dinâmico de frete + hedge de preço — espaço para um produto novo.
2. **Rastreabilidade EUDR é mercado de bilhões em risco e ainda pulverizado**: US$ 46 bi em exportações ao bloco europeu dependem de geolocalização + due diligence até dez/2026. Há **>7 players competindo (Agrotools, Serasa, Agrosatélite, TerraMagna, Vega, Selo Verde, Niceplanet)** sem padrão único — janela curta para consolidação ou para uma camada de interoperabilidade.
3. **Sorriso tem ativos únicos para virar polo de AI agro**: maior PIB agrícola do Brasil, maior capacidade de armazenagem do país (5,6 Mt = ~9% de MT), Aprosoja sediada no estado, malha física se conectando a 3 corredores (Santos, Paranaguá, Miritituba) e ferrovia chegando a LRV em 2026. Combinação rara — uma consultoria de AI pode oferecer pacote integrado: (a) pré-classificação de soja na recepção, (b) monitoramento preditivo de silos, (c) compliance EUDR white-label, (d) hedge de frete inteligente.

---

## 8. Fontes

### Armazenagem e silos
1. [O Presente Rural — Brasil colhe mais mas perde 10% no armazenamento](https://opresenterural.com.br/brasil-colhe-mais-mas-ainda-perde-10-dos-graos-no-armazenamento/)
2. [Nivetec — Monitoramento inteligente de silos](https://nivetec.com.br/estocagem-eficiente-como-o-monitoramento-inteligente-de-silos-transforma-o-agronegocio-brasileiro/)
3. [Portal Embrapa — Sistema inteligente armazena grãos](https://www.embrapa.br/en/busca-de-noticias/-/noticia/17916557/sistema-inteligente-armazena-graos)
4. [Macnica DHW — IoT em silos](https://blog.macnicadhw.com.br/agronegocio/monitoramento-silos-agronegocio/)
5. [Idugel — Tecnologias emergentes armazenamento](https://idugel.com.br/en/armazenamento-e-conservacao-de-graos/)
6. [Tago.io — Smart Feed Bin](https://tago.io/use-cases/smart-feed-bin-predictive-grain-monitoring-with-real-time-analytics)
7. [Folha Agrícola — ALLTIS sensor DOMO](https://folhaagricola.com.br/2026/05/09/tecnologia-com-ia-permite-controle-em-tempo-real-de-racao-e-graos-nas-granjas/)
8. [Kepler Weber — site institucional](https://www.kepler.com.br/)
9. [Brazil Journal — Kepler Weber IoT receita recorrente](https://braziljournal.com/kepler-weber-usa-internet-of-things-para-aumentar-receita-recorrente/)
10. [Cultivar — Kepler adquire Procer](https://revistacultivar.com.br/noticias/kepler-weber-anuncia-aquisicao-da-procer-automacao)
11. [Logweb — Kepler+Procer robô de nivelamento](https://logweb.com.br/robo-para-graos-kepler-weber-procer-armazenagem/)
12. [Embratel Smart Silo — Teletime](https://teletime.com.br/23/04/2024/embratel-lanca-solucao-de-monitoramento-de-graos/)
13. [Embratel Smart Silo — Agro Summit](https://portal.agrosummit.com.br/embratel-lanca-solucao-para-monitoramento-de-graos-no-agronegocio)
14. [ScienceDirect — AI-driven grain storage 2025](https://www.sciencedirect.com/science/article/pii/S0022474X25000475)
15. [Aprosoja MT — armazenagem não acompanha evolução](https://aprosoja.com.br/comunicacao/release/em-mato-grosso-armazenagem-nao-acompanha-evolucao-da-safra-e-pode-gerar-risco-para-safras-futuras)
16. [CenárioMT — armazenagem 2025](https://www.cenariomt.com.br/agro/safra-recorde-de-graos-em-2025-e-o-desafio-da-armazenagem-no-brasil/)
17. [Momento MT — Sorriso lidera armazenagem](https://momentomt.com.br/momento-agro/producao-de-graos-ressalta-gargalo-de-armazenagem-em-mato-grosso/)
18. [Agência Brasil — Sorriso maior PIB agrícola](https://agenciabrasil.ebc.com.br/economia/noticia/2025-09/sorriso-no-mt-tem-maior-pib-agricola-do-pais-veja-o-ranking)
19. [Notícias do Campo — R$ 148 bi armazenagem](https://noticiasdocampo.com.br/brasil-precisa-de-r-148-bilhoes-para-zerar-deficit-de-armazenagem/)
20. [Portal do Agronegócio — R$ 102 bi armazenagem](https://www.portaldoagronegocio.com.br/gestao-rural/analise-de-mercado/noticias/brasil-enfrenta-deficit-de-armazenagem-de-graos-e-precisa-investir-r-102-bilhoes-para-acompanhar-producao)

### Classificação por visão computacional
21. [Cocamar — IA classifica soja, prêmio Somoscoop](https://www.cocamar.com.br/comunicacao/noticia/6384/com-classificacao-da-qualidade-da-soja-por-ia-cocamar-e-premiada-no-somoscoop-em-brasilia)
22. [SENAI/PR — Cooperativa IA classificação soja](https://www.senaipr.org.br/tecnologiaeinovacao/blog/cooperativa-faz-uso-de-inteligencia-artificial-para-classificar-graos-de-soja-com-apoio-do-senai-no-parana-1-36126-450326.shtml)
23. [Embrapa — GRAS Famato Embrapa Show](https://www.embrapa.br/en/busca-de-noticias/-/noticia/71632904/tecnologia-para-classificacao-da-qualidade-de-graos-de-soja-e-destaque-no-famato-embrapa-show)
24. [AgFeed — Neosilos NVisio](https://agfeed.com.br/agtech/startup-neosilos-tenta-aposentar-o-olhometro-e-automatizar-a-classificacao-de-graos-com-cameras-e-ia/)
25. [Tbit — Soy GroundEye](https://www.tbit.com.br/en/soybean-classification/)
26. [Abitrigo — Bühler SORTEX MerlinAi](https://www.abitrigo.com.br/buhler-apresenta-uma-nova-era-da-selecao-optica/)
27. [Brasil Agritest — site](https://brasilagritest.com/)
28. [VLI — apoio Brasil Agritest](https://www.vli-logistica.com.br/vli-apoia-brasil-agritest-no-desenvolvimento-de-uma-solucao-tecnologica-inovadora-e-100-nacional-para-a-cultura-da-soja/)

### Logística e transporte
29. [Canal Rural — frete Sorriso → portos](https://www.canalrural.com.br/economia/logistica/valor-do-frete-para-o-transporte-de-milho-e-soja-oscila-nas-principais-rotas-do-pais/)
30. [CNA Brasil — frete Sorriso sobe 38%](https://cnabrasil.org.br/noticias/soja-pre%C3%A7o-do-frete-sobe-38-em-um-m%C3%AAs-a-partir-de-sorriso-mt)
31. [Diário do Estado MT — Sorriso→Miritituba +70%](https://www.diariodoestadomt.com.br/noticias/sorriso-mirititubafreteparalevarsojasubiumaisde70emumm-us/33249224)
32. [Agronews — frete agrícola jan/2026](https://www.agronews.tv.br/frete-agricola-em-11-01-2026-pressiona-soja-agora)
33. [Conab — boletim logístico soja milho 2023/24](https://www.conab.gov.br/ultimas-noticias/5886-boletim-logistico-mostra-desempenho-das-exportacoes-de-soja-e-milho-em-2023-24-e-aponta-tendencia-para-2024-25)
34. [SNA — custo logística 25% soja BR vs 15% EUA](https://www.sna.agr.br/custo-com-transporte-no-brasil-representa-de-30-a-40-do-valor-recebido-pela-soja/)
35. [Solinftec — IA na agricultura](https://www.solinftec.com/pt-br/blog/inteligencia-artificial-na-agricultura-solinftec/)
36. [AgFeed — FreteBras R$ 800 mi em IA](https://agfeed.com.br/negocios/unicornio-dos-fretes-investe-r-800-milhoes-e-em-ia-para-transportar-supersafra/)
37. [Blog FreteBras — Nova FreteBras IA](https://blog.fretebras.com.br/nova-fretebras-inteligencia-artificial-revoluciona-fretes-do-agro/)
38. [AgFeed — Strada e logística](https://agfeed.com.br/agtech/na-esburacada-logistica-brasileira-startup-strada-avanca-turbinada-por-quatro-gigantes/)
39. [Rumo Logística — site](https://www.rumolog.com/)
40. [CNN Brasil — Ferrovia MT avança 1 km/dia](https://www.cnnbrasil.com.br/economia/macroeconomia/maior-obra-ferroviaria-do-pais-avanca-1-km-por-dia-em-mato-grosso/)
41. [Revista Ferroviária — Rumo 2025 + 1ª fase MT](https://revistaferroviaria.com.br/2026/03/rumo-divulga-desempenho-de-2025-e-projeta-conclusao-da-ferrovia-de-mato-grosso/)
42. [Logweb — Rumo +5,4% agroindustriais 2025](https://logweb.com.br/rumo-movimentacao-ferroviaria-produtos-agroindustriais-2025/)
43. [Revista OE — Ferrogrão CAPEX R$ 33,3 bi](https://revistaoe.com.br/ferrograo-rota-alternativa/)
44. [Revista Ferroviária — Ferrogrão polêmica](https://revistaferroviaria.com.br/2025/02/viabilidade-da-construcao-da-ferrograo-continua-motivo-de-polemica/)
45. [HBSA — Corredor Norte](https://hbsa.com.br/solucoes/sistema-norte/)
46. [HBSA — Nossas Soluções](https://www.hbsa.com.br/nossas-solucoes/)
47. [MT Econômico — Arco Norte eixo MT](https://matogrossoeconomico.com.br/agronegocio-mato-grosso/hidrovias-do-arco-norte-se-consolidam-como-eixo-estrategico-ao-agro-especialmente-de-mt/)
48. [CNN Brasil — Arco Norte gargalos](https://www.cnnbrasil.com.br/infra/arco-norte-se-consolidam-mas-gargalos-logisticos-freiam-avanco/)
49. [Portal Barcarena — Itaqui+Barcarena +57%](https://portalbarcarena.com.br/barcarena-e-itaqui-puxam-alta-de-mais-de-57-nas-exportacoes-de-graos-pelo-arco-norte-nos-ultimos-anos/)
50. [Investing.com — Itaqui exportou mais soja 2024](https://br.investing.com/news/stock-market-news/porto-de-itaqui-exportou-mais-soja-em-2024-apesar-da-quebra-de-safra-aponta-conab-1575465)
51. [Porto de Santos — atracações programadas](https://www.portodesantos.com.br/informacoes-operacionais/operacoes-portuarias/navegacao-e-movimento-de-navios/atracacoes-programadas/)
52. [Portos do Paraná — tempo real](https://www.portosdoparana.pr.gov.br/Pagina/Tempo-Real)
53. [Primeira Página — Rota da soja em MT](https://primeirapagina.com.br/agro/rota-da-soja-em-mato-grosso-caminhos-e-desafios/)

### Rastreabilidade, EUDR, sustentabilidade
54. [PwC — EUDR na prática](https://www.pwc.com.br/pt/consultoria/agtech-innovation/agtech-innovation-news/artigos/2025/EUDR-na-pratica-como-o-agro-brasileiro-pode-liderar-a-nova-era-da-rastreabilidade.html)
55. [Diovane Franco — EUDR e produtor rural](https://diovanefranco.com.br/eudr-regulamento-europeu-desmatamento/)
56. [EU Access2Markets — EUDR adiado dez/2026](https://trade.ec.europa.eu/access-to-markets/pt/news/aplicacao-do-regulamento-delegado-da-ue-relativo-aos-produtos-nao-associados-desflorestacao-adiada)
57. [Milaré — segundo adiamento EUDR](https://milare.adv.br/eudr-o-impacto-do-segundo-adiamento-e-o-cenario-para-o-brasil/)
58. [IT Forum — EUDR US$ 46,3 bi](https://itforum.com.br/noticias/regulamentacao-europeia-agronegocio-brasileiro/)
59. [Revista Amazônia — adequar soja EUDR 2026](https://revistaamazonia.com.br/como-adequar-soja-brasileira-ao-eudr-2026/)
60. [Mongabay — Selo Verde plataforma gratuita](https://news.mongabay.com/2026/02/in-brazil-a-free-platform-uses-government-data-to-track-eudr-compliance/)
61. [GS1 Brasil — EUDR](https://www.gs1br.org/europe-deforestation-regulation)
62. [STCP — serviços EUDR](https://www.stcp.com.br/servicos-de-conformidade-eudr/)
63. [Exame — Agrotools PSA marketplace](https://exame.com/esg/agrotools-lanca-maior-plataforma-de-pagamentos-ambientais-do-mundo-e-mira-investidores/)
64. [Bloomberg Línea — Agrotools R$ 200 mi](https://www.bloomberglinea.com.br/agro/agrotools-chegou-a-r-200-mi-em-receitas-com-dados-made-in-brazil-o-ceo-quer-mais/)
65. [Niceplanet — site](https://niceplanet.com.br/en)
66. [Niceplanet — blog](https://niceplanet.com.br/blog)
67. [ADVFN — Minerva+Niceplanet app SMGeo](https://br.advfn.com/jornal/2021/10/minerva-lanca-em-parceria-com-a-niceplanet-geotecnologia-aplicativo-de-apoio-aos-produtores-rurais)
68. [Canal Rural — Serasa 90% soja em compliance](https://www.canalrural.com.br/agricultura/projeto-soja-brasil/mais-de-90-de-soja-cresce-sem-desmatamento-na-amazonia-legal-revela-estudo-da-serasa-experian/)
69. [Serasa Experian Agro — soluções](https://www.serasaexperian.com.br/solucoes/agro/)
70. [TerraMagna — site](https://terramagna.com.br/)
71. [AgFeed — TerraMagna TM Digital R$ 18 bi](https://agfeed.com.br/agtech/terramagna-lanca-nova-empresa-de-olho-nos-riscos-e-em-r-18-bi-das-revendas-de-insumos/)
72. [Bunge — 100% rastreabilidade Cerrado](https://www.bunge.com.br/Press-Releases/Bunge-alcanca-monitoramento-de-100-da-cadeia-indireta-de-soja-em-areas-prioritarias-no-Brasil)
73. [Bunge + CP Foods blockchain](https://www.bunge.com.br/Press-Releases/Bunge-e-CP-Foods-aumentam-transparencia-no-embarque-de-soja-livre-de-desmatamento)
74. [Cultivar — Bunge blockchain soja](https://revistacultivar.com.br/noticias/bunge-testa-plataforma-de-rastreabilidade-por-blockchain-para-soja-sustentavel)
75. [Cargill — Fórum Commodities Agrícolas](https://www.cargill.com.br/pt_BR/2019/f%C3%B3rum-de-commodities-agr%C3%ADcolas)
76. [Greenpeace — Moratória da Soja 10 anos](https://www.greenpeace.org/brasil/blog/moratoria-da-soja-na-amazonia-dez-anos-de-resultados/)
77. [Reporter Brasil — Monitor Cerrado 2022](https://reporterbrasil.org.br/wp-content/uploads/2022/11/Monitor_Cerrado_NOV_V3.pdf)
78. [Agência Brasil — lei MT punição Moratória 2026](https://agenciabrasil.ebc.com.br/meio-ambiente/noticia/2026-01/lei-que-pune-participantes-da-moratoria-da-soja-volta-valer-em-mt)
79. [Brazil Journal — fim da Moratória](https://braziljournal.com/a-moratoria-da-soja-acabou-o-que-vira-em-seu-lugar/)
80. [Aprosoja MT — Soja Plus referência mundial](https://aprosoja.com.br/comunicacao/release/programa-soja-plus-e-referencia-mundial-em-gestao-de-propriedade-rural)
81. [Exame — créditos carbono agricultura regenerativa](https://exame.com/esg/brasil-lanca-primeiros-creditos-de-carbono-por-agricultura-regenerativa-nas-americas/)
82. [Terra — metodologia créditos carbono Bureau Veritas](https://www.terra.com.br/noticias/chega-ao-pais-nova-tecnica-para-mensurar-creditos-de-carbono,a7659479ce6a832a9410388c47fada58ennf9ol8.html)
83. [Bayer — rastreabilidade alimentos](https://www.agro.bayer.com.br/conteudos-impulso-bayer/rastreabilidade-de-alimentos)

### Documentos técnicos
84. [INESC — Relatório técnico soja corredor logístico norte 2025](https://inesc.org.br/wp-content/uploads/2025/04/clua-soja_corredor_logistico_norte_epicc-v3.pdf)
85. [Conab — Relatório de Gestão 2024](https://www.gov.br/conab/pt-br/acesso-a-informacao/auditorias/prestacao-de-contas/relatorio-de-gestao/relatorio-de-gestao-2024/relatorio-de-gestao-2024.pdf)
86. [IMEA — indicador soja](https://www.imea.com.br/imea-site/indicador-soja)
87. [Mongabay BR — Sorriso a Santarém indústria soja](https://brasil.mongabay.com/2017/03/de-sorriso-a-santarem-industria-da-soja-transforma-bacia-do-tapajos-em-um-tabuleiro-de-grandes-obras/)
