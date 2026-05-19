# 01 — AI na Produção Agrícola (Campo)

> Pesquisa de mercado — foco soja / milho safrinha / algodão em Mato Grosso, com olhar especial para Sorriso/MT. Data-base: maio/2026. Os números aqui apresentados são de fontes públicas (imprensa setorial, sites institucionais, releases das empresas e Embrapa).

---

## 1. Agricultura de Precisão com AI

### 1.1 Plantio de precisão e taxa variável (sementes, fertilizantes, corretivos)
- **Taxa variável já é tecnologia mainstream em MT.** Levantamento do programa SIGA/MS apontou que **65,6% dos produtores** entrevistados utilizam alguma tecnologia de precisão (GPS, mapas de solo, taxa variável), com uso concentrado em fertilidade, plantio e aplicação [1]. Em Mato Grosso, **42% dos produtores de soja** declaram usar agricultura de precisão, índice que ultrapassa **50% no sudeste e oeste** do estado [2].
- **Ganhos quantificados:** estudos da CNA indicam **até 29% de aumento de produtividade** e **23% de economia em insumos** com taxa variável bem implementada [3]. O Sistema Control gera economia de **5,7% no plantio do milho e 4% na soja** [4].
- **Cropwise Planting (Syngenta)** opera no Brasil desde 2023, com aumento médio de **3% de potencial produtivo** e **redução de até 25% no custo de fertilização** observada nas validações; alguns produtores reportaram até **+6 sacas/ha em soja** [5].
- **xarvio FIELD MANAGER (BASF)** entrega mapas de semeadura em taxa variável e Powerzone para soja/algodão (lançamento previsto 2024-2025 após validação no milho com >70% precisão de previsão de doenças e >92% de aderência ao modelo de crescimento) [6].

### 1.2 Mapeamento de fertilidade do solo com ML
- **InCeres (Piracicaba/SP)** desenvolve software que cruza dados de entrada/saída de nutrientes, clima, cultura e imagens de satélite para prever fertilidade. Em resultados preliminares, **correlação de 77%**, meta de 95% [7].
- **Agrorobótica + Embrapa Instrumentação — AGLIBS 1.0:** robô com espectroscopia LIBS (mesmo princípio do Rover Curiosity da NASA) analisa **1.500 amostras de solo por dia**, sem resíduos químicos, medindo **22 parâmetros** (carbono orgânico, textura, pH, macro e micronutrientes, estoque de carbono). Plataforma de IA quantifica os elementos a partir do espectro [8]. A tecnologia já é usada em ações do IMAmt (Instituto Mato-grossense do Algodão) para cotonicultores [9].

### 1.3 Adoção entre grandes produtores de MT
- Pesquisa AgriHub/Famato (2024): **76% dos produtores rurais de MT têm perfil "inovador" ou "altamente inovador"** [10].
- **IA + ML são prioridade #1** para 71% das empresas do agro brasileiro nos próximos 12 meses [11].
- Em MT, **57% da área de soja** já é seguida por milho safrinha — operação de alto desempenho que demanda gestão digital sofisticada [12].

---

## 2. Monitoramento por Satélite e Drones com AI

### 2.1 Plataformas que operam no Brasil
- **Climate FieldView (Bayer):** **+28 milhões de ha monitorados no Brasil** (segundo mercado mundial); produtores que usam colhem em média **7 sacas a mais de soja/ha** vs. média Conab. Mais de **130 produtores de MT/MS/GO/BA/PR/RS/MG** participaram dos testes em **380 mil ha** antes do lançamento oficial em 2017. Crescimento anual de 63% em 2020. Acesso gratuito foi oferecido em municípios como Lucas do Rio Verde, Sinop, Sorriso e Rondonópolis [13][14][15].
- **John Deere Operations Center:** **+17 a 27 milhões de ha conectados** no Brasil (números crescentes entre 2024-2025); o Campo Conectado (Claro + SOL + JD) traz conectividade 5.0 ao campo [16][17].
- **EarthDaily Agro (ex-Geosys):** monitoramento por satélite de cerca de **3,4 milhões de ha produtivos** em 2021, principalmente soja e milho, com forte presença em seguro agrícola e detecção precoce de seca via NDVI [18].
- **Sensix (FieldScan):** plataforma de manejo inteligente; já atendia **+400 mil ha** no Brasil em 2021, atendendo Raízen, Philip Morris e Algar Farming, com data analytics e IA [19].
- **Agrosatélite:** referência em geoinformação para monitoramento de soja, parceira de iniciativas como Moratória da Soja [linha geral; ver fonte 18].

### 2.2 Drones com visão computacional em fazendas de soja
- **Horus Aeronaves (Florianópolis/SC):** drones 100% nacionais (homologados Anatel/ANAC). O **Maptor** voa **1h20min** e cobre **até 2.000 ha por voo**. Software **MAPPA** identifica falhas de plantio, doenças, pragas, deficiência hídrica/nutricional, contagem de plantas — parceria com BASF/Embrapii/Sebrae em soja [20].
- **Perfect Flight (São João da Boa Vista/SP):** plataforma de gestão e rastreabilidade da pulverização aérea. **+25 milhões de ha digitalizados/monitorados** [21].
- **Sensix:** integra imagens de drones, satélites, sensores e máquinas em plataforma única [19].
- **Cromai:** opera drones com deep learning (>150 milhões de referências) para detectar plantas daninhas em soja e cana — em cliente com 20 mil ha, economizou **5 mil L de herbicida, 2 milhões de L de água e 86 t CO₂** em 3 meses [22].

### 2.3 NDVI + AI
- Satélites **Planet (SuperDoves)** entregam **8 bandas espectrais** com resolução até 3 m diária; **Sentinel-2 (ESA)** entrega 10 m a cada 5 dias, gratuito. Ambos alimentam pipelines de NDVI com ML para detectar estresse, falhas e vigor [23][24].
- Plataformas brasileiras integram NDVI + clima + dados de operação para gerar alertas automatizados.

### 2.4 Custo por hectare (R$/ha) — sinalização pública
- Serviços simples de monitoramento por satélite: **R$ 10 a R$ 12/ha**.
- Serviços com sensoriamento mais sofisticado (multiespectral + IA + recomendação): **R$ 70 a R$ 80/ha** [25].
- Aegro (gestão rural ampla, não específico de campo): planos a partir de **R$ 99/mês** (área mínima 300 ha em algumas distribuições) [26].
- Solinftec Solix (robô autônomo): hardware ~**R$ 370 mil/unidade**; Solinftec projetou 700 robôs em campo até 2026 (faturamento ~R$ 55 mi com Solix em 2025) [27].
- Pricing público específico das plataformas (FieldView/Cropwise/xarvio) não foi encontrado — venda B2B custom — dado não encontrado nas fontes pesquisadas.
- Para referência: **custo total de produção de soja safra 2025/26 em MT (IMEA) projetado em ~R$ 7.430/ha**, e em Sorriso especificamente saindo de **R$ 5.599 → R$ 6.598/ha** [28][29].

---

## 3. Detecção de Pragas e Doenças

### 3.1 Apps de detecção por foto/câmera
- **Cromai:** visão computacional + Gemini AI (Google) para identificar plantas daninhas; redução **>65%** no uso de herbicidas e água, com retorno imediato de **~R$ 120/ha** ao produtor. Foco crescente em soja [22][30].
- **Strider (Syngenta Digital Brasil):** software mobile/satélite para captura de ocorrências de pragas com GPS, big data e mapas; **redução de até 15%** no uso de defensivos [31].
- Apps tipo "que praga é essa?" combinam câmera do celular com redes neurais treinadas em milhares de imagens, com escalada acadêmica chegando ao campo [22].

### 3.2 Deep learning para pragas de soja treinados no Brasil
- Pesquisas brasileiras (USP, Unoeste, UFSCar, UEL) atingem **99% de acurácia em bases públicas** e **81% em imagens próprias** para identificação de plantas daninhas em soja [32].
- Imagens hiperespectrais + ML para detectar ataque de insetos em plantas de soja já são linha ativa em programas de pós-graduação brasileiros [33].

### 3.3 Armadilhas inteligentes e monitoramento automatizado
- **xarvio SCOUTING + iMETOS iSCOUT (BASF + Metos/Pessl):** parceria desde 2021 para soja, milho e algodão no Brasil — armadilhas eletrônicas + IA de reconhecimento de imagem [34].
- **Tarvos (BR):** estações inteligentes de monitoramento de lagartas. Primeiro teste comercial 20/21: **50 mil ha em 23 fazendas de soja e algodão em MT e BA** [35].
- **Jacto Next — MIIP (Monitoramento Integrado Inteligente de Pragas)** no módulo EKOS: armadilhas eletrônicas para monitoramento remoto [35].

### 3.4 Pesquisa Embrapa
- **CIA-Agro (Centro de Inteligência Artificial no Agronegócio, Londrina/PR):** Embrapa Soja + UEL + UTFPR + IDR-PR + Fundação ABC. Foco inicial: **modelos preditivos para ferrugem asiática e mofo branco** da soja [36][37].
- **Plataforma com IA + Cadeias Ocultas de Markov** (UFSCar + Embrapa Instrumentação) atingiu **100% de correspondência** em cenários de ferrugem; testes em **Poxoréu/MT** com cultivar BRS 537 da Embrapa Soja, usando 2 GB de dados/ciclo [38].
- Embrapa: **ferrugem asiática causa perdas de até 80%** na lavoura, e custos de controle ultrapassam **US$ 2 bi por safra** — daí a prioridade [38].
- **Embrapa Agricultura Digital (ex-Informática Agropecuária, Campinas/SP)** mantém AgroAPI e projetos de visão computacional com Unicamp para contagem de frutos, reconhecimento de cultivos e modelos de IA em malware/IoT/blockchain para agro [39].

---

## 4. Previsão Climática e Modelos de Safra

### 4.1 Empresas com AI climática agro
- **Agrosmart (BR):** estação Cultivo Inteligente + ATMOS (previsão geolocalizada 7 dias diária e 48h horária) + alertas customizados via e-mail/WhatsApp; atende soja em larga escala via Orbia [40][41].
- **Climatempo / Agroclima:** notícias e previsões diárias para soja, milho, café, cana, algodão; integração com Syngenta [42].
- **ClimateAi (US):** foco em previsões sazonais com IA para grandes commodities; presença no Brasil via parcerias com tradings — dado público específico de adoção em MT não encontrado nas fontes pesquisadas.
- **Agroclima PRO (BASF):** previsão personalizada por fazenda dentro do ecossistema xarvio [40].
- **IBM Watson Decision Platform for Agriculture / PAIRS Geoscope:** combina IoT, satélites, drones e dados de Weather Company; modelos para soja, milho, algodão, trigo, cevada, cana, sorgo, batata [43].

### 4.2 Modelos preditivos de produtividade
- Pesquisas brasileiras (UFR/MT, FAPESP, ResearchGate) aplicam ML em dados agrometeorológicos para estimar produtividade da soja com horizonte de 30-90 dias antes da colheita [44].
- **IMEA** publica estimativas robustas para MT — safra 2025/26 projetada em **51,56 milhões de toneladas de soja** (recorde) [45].
- Climate FieldView, Cropwise e xarvio entregam estimativas próprias por talhão (não há benchmark público comparativo entre elas).

### 4.3 Integração com estações meteorológicas em fazendas
- Agrosmart entrega telemetria (estação, pluviômetro, sensores de umidade do solo, módulo para hidrômetro de irrigação) com transmissão por satélite — útil em áreas sem 4G/5G [41].
- BASF/Metos com iMETOS conecta clima + armadilhas + xarvio [34].
- Jacto OTMIS / EKOS integra dados de operação + clima [46].

### 4.4 Como grandes produtores de MT acessam essas informações hoje
- Combinação típica: plataforma do fornecedor de defensivo/semente (FieldView/Cropwise/xarvio) + estação Agrosmart/Metos + boletins do IMEA + análises Climatempo/INMET + integração via Operations Center (JD) ou plataforma OEM (AGCO PTx, Case IH AFS).

---

## 5. Pulverização Inteligente

### 5.1 Pulverização seletiva com AI (See & Spray / ALICE)
- **John Deere See & Spray™:** sistema com câmeras + processadores que identifica daninhas e ativa só os bicos necessários. **Redução média de 60%** no volume de herbicida; **See & Spray Select pode reduzir até 90%** [47]. Integrado com Operations Center.
- **Solinftec ALICE / Solix Ag Robotics:** robôs solares autônomos com visão computacional + RTK; em soja, **redução de >90% no uso de herbicidas** e **+10 sacas/ha** em média em MT comparado a áreas vizinhas com mesmos insumos/clima [48][49]. **Resultados gerais de 2024/25 em soja: redução média de 80%** no uso de defensivos, chegando a **95% em alguns casos** [50]. Em fazenda pioneira em MT, sistema da Solinftec reduziu **15% em fertilizantes/defensivos** e aumentou **8% na produtividade de soja** [51]. Atualmente ~200 robôs Solix em operação global; plano de 700 unidades até 2026 [27].
- **Case IH SaveFarm (CNH):** câmeras na barra do pulverizador + IA identificam daninhas em condição "green on green" durante aplicação em culturas estabelecidas; **>80% de redução no uso de herbicida** [52].
- **AIM Command Flex II (Case IH Patriot Série 50):** controle bico a bico para pulverização sob demanda [52].

### 5.2 Drones de pulverização — regulamentação e adoção
- **ANAC** aboliu a gestão obrigatória de aeronavegabilidade para drones agrícolas em 2023, destravando o crescimento [53][54].
- **Portaria MAPA nº 1187/2024** define regras para formação de operadores (CAAR — Curso de Aplicador Aeroagrícola Remoto), com critérios para registro [54].
- **Portaria MAPA nº 298/2021** + **RBAC-E nº 94 (ANAC)** formam o arcabouço regulatório.
- Brasil está entre os países com **maior ritmo de adoção** de drones para pulverização, sobretudo em milho, cana, café (e crescente em soja e algodão) [54].

### 5.3 Ofertas dos OEMs
- **Jacto:** pulverizador autônomo **Arbus 4000 JAV** (citrus, com IA, laser, GPS, câmeras); plataforma **OTMIS** com M2M (compartilhamento de mapas entre máquinas para evitar sobreposição); **ganhos de 10–30%** em rendimento operacional [46][55]. EKOS + MIIP para pragas.
- **John Deere:** See & Spray + ExactApply + Operations Center; aporte de **R$ 700 milhões** anunciado para nacionalizar máquinas inteligentes [47][56].
- **AGCO / PTx (Precision Planting + PTx Trimble):** marca dedicada à agricultura de precisão e digital, integra ML em todo o ciclo (plantio → colheita), com soluções compatíveis com qualquer OEM [57].
- **CNH / Case IH:** drone **P150** (maior drone de pulverização do Brasil em 2025, autonomia 8-12 min cíclica, faixa 20 m, altura 5-10 m, ajuste autônomo por IA); SaveFarm; AIM Command [52].

### 5.4 Casos de redução de uso de defensivos (% economia)
| Solução | Redução de defensivo/herbicida | Cultura | Fonte |
|---|---|---|---|
| Solinftec Solix (ALICE) | >90% herbicida; 80% defensivos (média 2024/25); até 95% (casos) | Soja | [48][50] |
| John Deere See & Spray Select | até 90% | Soja/milho/algodão | [47] |
| John Deere See & Spray (média) | 60% | Milho/algodão/soja | [47] |
| Case IH SaveFarm | >80% herbicida | Soja/milho/algodão | [52] |
| Cromai | >65% herbicida + água; ~R$120/ha ROI | Soja/cana | [22] |
| Strider | até 15% defensivos | Soja/milho | [31] |

---

## 6. Empresas a investigar com profundidade

### Solinftec (ALICE A.I., Solix, integração com ChatGPT)
Headquartered em Araraquara/SP, é a maior empresa de IA do agro brasileiro. **ALICE A.I.** é descrita como "engenheiro agrônomo mais poderoso do mundo", treinada em >18 anos de dados de campo, hoje integrada ao ChatGPT para recomendações por áudio. O robô solar autônomo **Solix Ag Robotics** já é vendido a ~R$ 370 mil/unidade; **40 equipamentos operam em fazendas de grãos, cana e HF na BA, MT, GO, MS e SP**. Resultados em soja em MT: **+8% produtividade, -15% insumos** (fazenda pioneira), **+10 sacas/ha em média** e **redução >90% de herbicida**. Captou R$ 1,3 bi; planeja 700 robôs até 2026, faturando R$ 55 mi só com Solix em 2025 [27][48][49][51]. A parceria com **ADAMA** (defensivos) mencionada no briefing não apareceu nas fontes públicas pesquisadas — dado não encontrado.

### Climate FieldView (Bayer)
Plataforma global com **+60 milhões de ha mapeados mundialmente**, sendo o **Brasil o líder de mercado com 28+ milhões de ha** e quase 12 mil equipamentos conectados. Produtores brasileiros que usam colhem **7 sacas/ha a mais de soja vs. média nacional Conab**. Crescimento de 63% a/a em 2020. Foi disponibilizada gratuitamente em municípios de MT (Lucas do Rio Verde, Sinop, Sorriso, Rondonópolis). Pricing público específico não divulgado [13][14][15].

### Cropwise (Syngenta)
Família de **8 soluções** (Planting, Operations, Protector, etc.) integradas; **monitora 80+ milhões de ha globalmente**. Cropwise Planting no Brasil entrega **+3% de potencial produtivo** e **-25% no custo de fertilização** em algumas culturas; em soja, casos de **+6 sacas/ha**. Diagnóstico digital de nematoides já disponível [5][58].

### xarvio (BASF)
Plataforma FIELD MANAGER com Timing de Aplicação (>70% de precisão preditiva de doenças, 92% efetividade de modelo de crescimento), Powerzone Maps e Variable Rate Seeding. Validação em soja/algodão prevista para 2024-2025. Parceria com Metos (Pessl) para armadilhas iSCOUT integradas ao SCOUTING (reconhecimento de imagem) para pragas de soja, milho e algodão [6][34].

### InCeres
Startup de Piracicaba/SP focada em fertilidade do solo via IA. Cruza nutrientes (entrada/saída), clima, cultura e imagens de satélite; em P&D atingiu **77% de correlação** preditiva, meta 95%. Plataforma SaaS para gestão de fertilidade no portfólio do produtor [7].

### Sensix
Plataforma **FieldScan** processa dados de drones, satélites, solo, sensores e máquinas. **+400 mil ha** atendidos no Brasil em 2021. Clientes: Raízen, Philip Morris, Algar Farming. Funcionalidades: variabilidade nutricional, fertilidade, contagem de plantas, daninhas, pragas, mapas de produtividade [19].

### Perfect Flight
Plataforma SaaS para gestão e rastreabilidade de pulverização aérea. **+25 milhões de ha digitalizados/monitorados** [21]. Lê arquivos GPS de aeronaves agrícolas; considera fatores externos (clima, proximidade de pessoas/água) para indicar o melhor momento da aplicação. Parceria com Strider para integração de softwares [21].

### Strider (Syngenta Digital Brasil)
Pioneira (2013) em monitoramento de pragas via software mobile. Hoje **Syngenta Digital Brasil**, integra mapas, mobilidade e big data; **reduz uso de defensivos em até 15%**. Atende monitoramento de máquinas + pragas via imagens de satélite [31].

### Horus Aeronaves
Fabricante brasileira (Florianópolis) de drones (Maptor, autonomia 1h20min, 2.000 ha/voo) homologados Anatel. Software **MAPPA** com visão computacional para falhas de plantio, daninhas, pragas, doenças e contagem. Parceria BASF/Embrapii/Sebrae para soja [20].

### Jacto
**Arbus 4000 JAV** — primeiro pulverizador autônomo brasileiro (laser, GPS, câmeras, IA). Plataforma **OTMIS** com M2M para evitar sobreposição entre máquinas. Plataforma **EKOS** com módulo MIIP (armadilhas eletrônicas inteligentes). Ganhos de 10-30% no rendimento operacional [46][55].

### AGCO / Precision Planting (PTx)
AGCO adquiriu a Precision Planting da Climate Corporation; em 2024 lançou a marca **PTx** consolidando Precision Planting + PTx Trimble. No Brasil desde 2015. Sistemas para monitoramento, controle de aplicação de líquidos e plantabilidade compatíveis com todos os OEMs [57].

### John Deere Operations Center
**+17 a 27 milhões de ha conectados no Brasil**. Plataforma digital online para gestão da fazenda em tempo real. Ecossistema com tratores/colheitadeiras/pulverizadores conectados, Campo Conectado (Claro + SOL) para conectividade rural. See & Spray (60–90% redução de herbicida). Aporte de R$ 700 mi para nacionalização [16][17][47].

### Cromai
Startup brasileira (2017), >170 funcionários, **+90 clientes em 9 estados**. Visão computacional + Gemini (Google) para daninhas em soja e cana. Em 20 mil ha de cliente: **5.000 L herbicida + 2 milhões L água + 86 t CO₂ poupados**; ROI **~R$ 120/ha**. Parceria com Embratel para distribuição [22][30].

### Agrorobótica
Em parceria com **Embrapa Instrumentação**, opera o **AGLIBS 1.0** (espectroscopia LIBS + IA) — analisa **1.500 amostras/dia, 22 parâmetros** (carbono, textura, pH, macro/micronutrientes). Tecnologia limpa, sem resíduos químicos. Já em uso pelo **IMAmt** para algodoeiros em MT. Captou aporte da VOX para mira de R$ 1 bi em crédito de carbono no solo [8][9][59].

---

## 7. Instituições de Pesquisa

### Embrapa Soja (Londrina/PR)
Sede do Consórcio Anti-Ferrugem; coordenadora do **CIA-Agro (Centro de Inteligência Artificial no Agronegócio)** com UEL + UTFPR + IDR-PR + Fundação ABC. Foco inicial (2024-26): **modelos preditivos para ferrugem asiática e mofo branco** da soja, automação da rede de coletores (>200 coletores em PR). Tempo de obtenção de dados climáticos para alertas caiu de **2 semanas para 2 dias** [36][37].

### Embrapa Agricultura Digital (ex-Informática Agropecuária, Campinas/SP)
Unidade especializada da Embrapa em transformação digital. Mantém a plataforma **AgroAPI** com modelos disponíveis para terceiros (startups e empresas). Projetos: **EcontaFruto** (contagem automatizada de frutos em citros, com Fundecitrus), reconstrução 3D de plantas e identificação de cultivos com visão computacional (em parceria com Unicamp). Linhas: IA, ML, robótica, blockchain, IoT, computer vision [39].

### Fundação MT (Rondonópolis/MT)
Criada em 1993 por 23 produtores/sementeiros, é um dos principais centros de P&D do agro brasileiro. Trabalha com 9 áreas (data science, entomologia, fitopatologia, biológicos, fitotecnia, daninhas, mecanização, nematologia, solos e nutrientes) em soja, milho, algodão e pecuária. **Programa de Difusão de Tecnologia (PDT)** e expansão recente para o extremo norte de MT [60][61].

### APROSOJA MT
Associação dos Produtores de Soja e Milho de MT. Mantém **2 centros tecnológicos** próprios: **CTECNO Parecis** (solos arenosos e médios, 9 anos) e **CTECNO Araguaia** (único centro independente especializado em solos siltosos do Brasil, <3 anos). Realiza Circuito Aprosoja MT em cidades como Campos de Júlio, conectando produtores a soluções tecnológicas [62][63]. Celebrou 20 anos em 2025 [64].

### IMEA (Instituto Mato-grossense de Economia Agropecuária)
Sediado em Cuiabá, vinculado ao Sistema Famato (junto com Aprosoja, Ampa, Acrimat, Aprosmat). Estrutura **dashboards de inteligência de dados** (soja, milho, algodão, bovinos, leite, perspectiva econômica), boletins semanais/mensais e o projeto **Imea em Campo** (2025). Projeta safra 2025/26 de soja em MT em **51,56 milhões de toneladas** (recorde) [45][65]. Para qualquer iniciativa de IA, **IMEA é a principal fonte de dados estruturados** sobre custos, área, produtividade e mercado em MT.

### AgriHub (Sistema Famato + Senar-MT)
"Casa da Inovação" do produtor rural de MT, em Cuiabá. Programa **AgriHub Conecta** mapeia desafios em propriedades e conecta a startups; estudo 2024 identificou **76% dos produtores de MT como inovadores ou altamente inovadores**. Sorriso, Sinop e Lucas do Rio Verde foram a região "nortão" do AgriHub Conecta 2025 [10][66]. Levou inovação do agro mato-grossense à COP30.

---

## 8. Síntese: o que JÁ existe vs. o que NÃO existe

| Categoria | Maturidade no Brasil | Players principais | Gap / Oportunidade |
|---|---|---|---|
| **Taxa variável (sementes/fertilizantes)** | Alta (>40% dos produtores MT) | AGCO/PTx, Precision Planting, Stara, John Deere, Cropwise Planting, xarvio | Integração com mapas de solo em tempo real, alfabetização do gerente de fazenda médio |
| **Monitoramento por satélite com IA** | Alta — várias plataformas competem | FieldView, Cropwise, JD Operations Center, EarthDaily Agro, Sensix | Custo/ha ainda salgado para média propriedade; falta padrão aberto de dados |
| **Drones de mapeamento (visão computacional)** | Média-Alta | Horus, Sensix, Cromai, Perfect Flight | Adoção massiva entre médios produtores ainda limitada; conectividade rural |
| **Detecção de daninhas / pragas com IA** | Média-Alta (visão computacional embarcada) | Solinftec, JD See & Spray, Case SaveFarm, Cromai | Modelos específicos para "green on green" em MT em validação |
| **Pulverização seletiva (See & Spray)** | Média (chegando ao mercado 2024-26) | JD, CNH/Case IH, Solinftec | Preço dos pulverizadores topo de linha; ROI ainda em prova para soja |
| **Drones de pulverização** | Crescente (regulamentação 2023-24 destravou) | Case IH (P150), DJI Agras (importadores), ARPAC, Perfect Flight (gestão) | Capacitação de operadores (CAAR) ainda limitada; logística de cargas |
| **Previsão climática localizada com IA** | Alta | Agrosmart, Climatempo/Agroclima, IBM Watson, BASF Agroclima PRO | Falta integração entre previsão e prescrição agronômica em uma tela só |
| **Modelos preditivos de produtividade** | Média (acadêmica → comercial) | FieldView, Cropwise, IBM, Embrapa, IMEA, ClimateAi | Modelo público brasileiro abrangente e auditável ainda inexistente |
| **Armadilhas inteligentes** | Média | xarvio+Metos, Jacto MIIP, Tarvos | Escala — Tarvos com 50 mil ha em MT/BA é ainda um piloto avançado |
| **Análise de solo com ML/LIBS** | Inicial-Média | Agrorobótica (AGLIBS), InCeres | Tempo de resposta vs. laboratório tradicional precisa cair |
| **Robôs autônomos no campo (soja)** | Inicial-Crescente | Solinftec Solix (~200 globais; 700 plano 2026), Jacto JAV | Custo (R$ 370k/unidade); ainda baixa escala vs. ~615 mil ha de Sorriso |
| **IA generativa para o produtor** | Inicial | Solinftec ALICE + ChatGPT (áudio) | Adoção massiva e LLM agronômico em português brasileiro |
| **Plataforma única "cockpit" agronômico** | Inicial — todos competem por isso | Cropwise, FieldView, OpCenter, OTMIS | Interoperabilidade entre marcas — oportunidade clara |
| **Crédito de carbono no solo com IA** | Inicial | Agrorobótica (target R$ 1 bi), Embrapa | Metodologia, MRV e mercado ainda em estruturação |

**Principais gaps identificados para Sorriso/MT:**
- **Integração de dados entre fornecedores diferentes** (a soja em Sorriso é cultivada com mix de defensivos Bayer + sementes Syngenta + maquinário JD/AGCO/Case e cada um tem sua plataforma).
- **LLM agronômico em português** treinado em dados brasileiros (Cerrado, soja transgênica RR/IPRO, milho safrinha) — ALICE + ChatGPT é um primeiro passo.
- **Modelos preditivos públicos** de produtividade por talhão que conversem com o IMEA.
- **Análise de solo em larga escala e baixo custo** (AGLIBS aponta o caminho).
- **Capacitação técnica massiva** dos operadores de campo (CAAR para drones, gestão de plataformas digitais).

---

## 9. Fontes

1. **SIGA / Senar-MT** — Mais de 40% dos produtores realizam agricultura de precisão em MT: https://sistemafamato.org.br/senarmt/2015/06/24/mais-de-40-dos-produtores-realizam-agricultura-de-precisao-em-mt/
2. **CompreRural / agriconline** — IA + Agricultura de Precisão: Revolução no Agro Brasileiro 2026: https://agriconline.com.br/portal/artigo/ia-agricultura-de-precisao-revolucao-no-agro-brasileiro-2026/
3. **CNA Brasil** — Com agricultura de precisão, produtores rurais alcançam até 29% de aumento na produtividade: https://cnabrasil.org.br/noticias/com-agricultura-de-precisao-produtores-rurais-alcancam-ate-29-de-aumento-na-produtividade
4. **GeoAgri** — Taxa variável de plantio de sementes de milho e soja: https://geoagri.com.br/blog/62/taxa-variavel-de-plantio-de-sementes-de-milho-e-soja
5. **Syngenta** — Cropwise Planting no Brasil: https://www.syngenta.com.br/syngenta-digital-lanca-cropwise-planting-no-brasil-ferramenta-que-aprimora-gestao-de-dados-e-ajuda
6. **BASF** — xarvio FIELD MANAGER / Timing de Aplicação: https://www.basf.com/br/pt/media/news-releases/2023/01/xarvio-Agrishow-2023
7. **FAPESP / InCeres** — Inteligência artificial para o controle da fertilidade do solo: https://pesquisaparainovacao.fapesp.br/inteligencia_artificial_para_o_controle_da_fertilidade_do_solo/625
8. **Embrapa / SNA** — Embrapa e startup do agro criam laser para análise de solos: https://sna.agr.br/inteligencia-artificial-embrapa-e-startup-do-agro-criam-laser-para-analise-de-solos-em-larga-escala-e-de-forma-limpa/
9. **Revista Cultivar / IMAmt** — Tecnologia com laser e IA para análise de solos para cotonicultores: https://revistacultivar.com.br/noticias/tecnologia-com-laser-e-inteligencia-artificial-para-analise-de-solos-integra-acao-do-imamt-para-cotonicultores
10. **Famato / AgriHub** — Estudo: 76% dos produtores de MT têm perfil inovador: https://sistemafamato.org.br/blog/2024/10/30/estudo-inedito-do-agrihub-revela-que-76-dos-produtores-rurais-de-mato-grosso-tem-perfil-inovador/
11. **SINDPD-MT** — Mato Grosso lidera avanço tecnológico no agro com foco em IA: https://sindpd-mt.org.br/mato-grosso-avanco-tecnologico-agro-com-foco-ia/
12. **Primeira Hora** — Tecnologia e agro em Mato Grosso: https://primeirahora.com.br/tecnologianoagro/
13. **AgroRevenda / Bayer** — Climate FieldView em 60 milhões de hectares: https://agrorevenda.com.br/climate-fieldview-da-bayr-em-60-milhoes-de-hec/
14. **Bayer Brasil** — Climate FieldView oficialmente lançada no Brasil: https://climate.com/pt-br/noticias/plataforma-de-agricultura-digital-climate-fieldview-oficialmente-lan-ada-no-brasil.html
15. **AgroPlanning** — Bayer oferece acesso gratuito ao FieldView (Lucas RV, Sinop, Sorriso, Rondonópolis): https://www.agroplanning.com.br/2020/06/12/bayer-impulsiona-a-agricultura-digital-no-brasil-oferecendo-acesso-gratuito-a-ferramenta-climate-fieldview/
16. **John Deere** — Operations Center: https://www.deere.com.br/pt/agricultura-de-precis%C3%A3o/gerenciamento-de-informa%C3%A7%C3%B5es/operations-center/
17. **AgFeed / John Deere** — A John Deere revoluciona o campo acelerando a conectividade rural: https://agfeed.com.br/agro-brands/apresentado-por-john-deere/a-john-deere-revoluciona-o-campo-acelerando-a-conectividade-rural/
18. **Revista Cultivar / EarthDaily Agro** — Cresce área agrícola monitorada no Brasil: https://revistacultivar.com.br/noticias/cresce-area-agricola-monitorada-no-brasil-pela-earthdaily-agro
19. **Startupi / Sensix** — Sensix recebe aporte e atende 400 mil ha: https://startupi.com.br/startup-que-utiliza-tecnologia-para-mapeamento-de-propriedades-agricolas-recebe-aporte-de-r1-milhao/
20. **AgEvolution / Horus** — Horus une drone e software para combate de pragas em soja: https://agevolution.canalrural.com.br/horus-une-drone-e-software-para-combate-de-pragas-em-soja/
21. **Revista Cultivar / Perfect Flight** — Perfect Flight atinge 25 milhões de hectares: https://revistacultivar.com.br/noticias/perfect-flight-atinge-25-milhoes-de-hectares-digitalizados-e-monitorados-sobre-pulverizacao-aerea
22. **Projeto Draft / Cromai** — Cromai com IA para detectar pragas e falhas: https://www.projetodraft.com/com-inteligencia-artificial-para-detectar-pragas-e-falhas-nas-plantacoes-a-cromai-quer-tornar-o-agro-mais-eficiente-e-sustentavel-2/
23. **Audsat / Planet** — Como a Audsat utiliza as imagens Planet no Agro: https://www.audsat.com.br/blog/satelite-planet-e-a-audsat/
24. **EngeSat / Sentinel-2**: https://www.engesat.com.br/sentinel-2/
25. **Aegro Blog** — Imagens de satélite na agricultura (custos R$/ha): https://blog.aegro.com.br/imagens-de-satelite-na-agricultura/
26. **Aegro** — Software de gestão rural: https://aegro.com.br/
27. **Solinftec** — Solinftec supera R$ 1,3 bi e planeja 700 robôs Solix: https://www.solinftec.com/pt-br/solinftec-supera-r-13-bi-em-captacoes-e-planeja-colocar-cerca-de-700-robos-solix-em-campo-ate-2026/
28. **AgroAdvance** — Custo de produção da soja 2025/2026: https://agroadvance.com.br/blog-custo-de-producao-da-soja-2025-2026/
29. **MFA / IMEA** — Custo de produção soja safra 2025/26 Sorriso: https://blog.myfarmagroeducacao.com.br/custo-de-producao-da-soja-safra-2025-26/
30. **Startups.com.br / Cromai** — Cromai: agro sustentável também mais lucrativo: https://startups.com.br/negocios/sustentabilidade/cromai-com-tecnologia-agro-sustentavel-e-tambem-mais-lucrativo/
31. **StartAgro / Strider** — Syngenta adquire Strider: https://www.startagro.agr.br/syngenta-adquire-strider/
32. **TESES USP** — Detecção de plantas daninhas com aprendizado profundo: https://www.teses.usp.br/teses/disponiveis/76/76135/tde-11092024-115349/pt-br.php
33. **Colloquium Exactarum (Unoeste)** — ML para identificação de soja sob ataque de insetos com dados hiperespectrais: https://journal.unoeste.br/index.php/ce/article/view/4518
34. **BASF / Metos** — Parceria xarvio + Metos no Brasil para soja/algodão/milho: https://www.basf.com/br/pt/media/news-releases/2021/09/xarvio--e-metos-firmam-parceria-no-brasil-para-monitorar-pragas-
35. **FAPESP / Tarvos** — Armadilha inteligente monitora infestação de lagartas: https://agencia.fapesp.br/armadilha-inteligente-monitora-infestacao-de-lagartas-em-lavouras/35037
36. **Folha de Londrina / CIA-Agro** — Centro de inteligência no agro foca soja: https://www.folhadelondrina.com.br/folha-rural/centro-de-inteligencia-no-agro-foca-soja-em-pesquisas-iniciais-3221604e.html
37. **Governo PR** — Pesquisadores do PR usam IA para combate da ferrugem da soja: https://www.parana.pr.gov.br/aen/Noticia/Pesquisadores-do-Parana-usam-Inteligencia-Artificial-para-combate-da-ferrugem-da-soja
38. **O Presente Rural** — Plataforma com IA aprimora diagnóstico da ferrugem asiática (Poxoréu/MT): https://opresenterural.com.br/plataforma-com-inteligencia-artificial-aprimora-diagnostico-da-ferrugem-asiatica-da-soja/
39. **Embrapa** — Embrapa Informática Agropecuária participa da transformação digital: https://www.embrapa.br/en/busca-de-noticias/-/noticia/38988362/embrapa-informatica-agropecuaria-participa-da-transformacao-digital-do-campo
40. **Agrosmart** — Inteligência climática na produção de soja e milho: https://agrosmart.com.br/blog/inteligencia-climatica-na-pratica/
41. **Orbia / Agrosmart ATMOS** — Previsão do tempo localizada: https://www.orbia.ag/produto/65596/RA0655/0/agrosmart-atmos-previsao-do-tempo-localizada
42. **Climatempo Agroclima**: https://agroclima.climatempo.com.br/
43. **Radar do Futuro / IBM** — IBM fortalece IA nos agronegócios (Watson Decision Platform): https://radardofuturo.com.br/ibm-fortalece-atuacao-da-inteligencia-artificial-nos-agronegocios/
44. **ResearchGate** — Aplicação de Machine Learning na Previsão da Produtividade da Soja: https://www.researchgate.net/publication/386551318_Aplicacao_de_Machine_Learning_na_Previsao_da_Produtividade_da_Soja
45. **IMEA** — Relatórios de mercado / safra 2025/26: https://www.imea.com.br/
46. **MundoCoop / Jacto** — Agricultura de precisão e veículos autônomos (OTMIS): https://mundocoop.com.br/jacto-otmis/agricultura-de-precisao-e-a-tecnologia-dos-veiculos-autonomos-na-melhoria-da-gestao-agricola/
47. **John Deere** — See & Spray Select e Premium: https://www.deere.com.br/pt/tecnologia-de-produtos/agricultura-de-precis%C3%A3o/john-deere-precision-upgrades/upgrades-para-pulverizadores/introdu%C3%A7%C3%A3o%20definitiva/
48. **AgFeed / Solinftec** — Solinftec mostra resultados de robô com IA: https://agfeed.com.br/grande-slam-do-agro/agrishow/apresentado-por-solinftec/solinftec-mostra-primeiros-resultados-de-robo-com-inteligencia-artificial/
49. **Solinftec** — Resultados do robô Solix em lavouras e canaviais brasileiros: https://www.solinftec.com/pt-br/solinftec-anuncia-os-primeiros-resultados-obtidos-com-o-seu-robo-solix-em-lavouras-e-canaviais-brasileiros/
50. **Máquinas e Equipamentos / Solinftec** — Solinftec usa IA no agro e integra robô Alice e ChatGPT: https://maquinasequipamentos.com.br/solinftec-usa-inteligencia-artificial-no-agro-e-integra-robo-alice-e-chatgpt/
51. **Compraco / Solinftec** — Monitoramento de cultivos com IA: https://compraco.com.br/blogs/atualidades-e-noticias/monitoramento-de-cultivos-com-ia-pela-solinftec-otimizando-a-produtividade-agricola
52. **Revista Cultivar / Case IH** — Case IH lança AIM Command e SaveFarm: https://revistacultivar.com.br/noticias/especial-agrishow-case-ih-lanca-sistema-de-pulverizacao-aim-command-na-linha-patriot
53. **Mundo Conectado** — Brasil facilita regulamentação de drones agrícolas: https://www.mundoconectado.com.br/drones/brasil-facilita-regulamentacao-drones-agricolas/
54. **MAPA** — Mapa apresenta normas sobre uso de drones na agricultura: https://www.gov.br/agricultura/pt-br/assuntos/noticias/2024/mapa-apresenta-normas-sobre-uso-de-drones-na-agricultura-na-drone-show
55. **Jacto** — Pulverizador autônomo Arbus 4000 JAV: https://blog.jacto.com.br/pulverizador-autonomo/
56. **AgFeed / John Deere** — Aporte de R$ 700 mi para nacionalizar máquinas inteligentes: https://agfeed.com.br/negocios/com-aporte-de-r-700-milhoes-john-deere-comeca-a-nacionalizar-maquinas-inteligentes/
57. **AGCO** — Precision Planting (Brasil): https://www.agco.com.br/brands/precision-planting.html
58. **Syngenta Digital** — Cropwise: plataforma global para cada fazenda: https://blog.syngentadigital.ag/cropwise/
59. **The AgriBiz / Agrorobótica** — Aporte VOX e R$ 1 bi em crédito de carbono no solo: https://www.theagribiz.com/mudancas-climaticas/com-aporte-da-vox-agrorobotica-mira-r-1-bi-em-credito-de-carbono-no-solo
60. **Fundação MT** — Site oficial / boletins de pesquisa: https://www.fundacaomt.com.br/servicos-por-area/boletim-de-pesquisa
61. **Revista Cultivar / Fundação MT** — 30 anos de pesquisas: https://revistacultivar.com.br/noticias/como-30-anos-de-pesquisas-da-fundacao-mt-contribuiram-com-o-agronegocio
62. **Aprosoja-MT** — Centros Tecnológicos contribuem para o avanço das práticas agrícolas: https://aprosoja.com.br/comunicacao/release/centros-tecnologicos-da-aprosoja-mt-contribuem-para-o-avanco-das-praticas-agricolas
63. **Aprosoja-MT** — Circuito Aprosoja MT chega a Campos de Júlio: https://aprosoja.com.br/comunicacao/release/circuito-aprosoja-mt-chega-a-campos-de-julio-e-destaca-a-importancia-da-tecnologia-no-campo
64. **Canal Rural / Aprosoja MT** — Aprosoja MT completa 20 anos: https://www.canalrural.com.br/agricultura/projeto-soja-brasil/aprosoja-mato-grosso-completa-20-anos-confira-a-trajetoria
65. **CNA Brasil / IMEA** — Imea lança pesquisa do perfil do agricultor na era digital: https://www.cnabrasil.org.br/noticias/imea-lanca-pesquisa-inedita-do-perfil-do-agricultor-na-era-digital
66. **AgriHub** — AgriHub Conecta 2025: impulsionando inovação em Mato Grosso: https://agrihub.com.br/agrihub-conecta-2025-impulsionando-a-inovacao-no-campo-em-mato-grosso/
67. **Agência Brasil** — Sorriso MT tem maior PIB agrícola do país: https://agenciabrasil.ebc.com.br/economia/noticia/2025-09/sorriso-no-mt-tem-maior-pib-agricola-do-pais-veja-o-ranking
68. **Gazeta do Povo** — O que faz Sorriso ser o maior produtor de soja do mundo: https://www.gazetadopovo.com.br/brasil/municipio-sorriso-mato-grosso-maior-produtor-soja-mundial/
69. **CompreRural / Case IH** — Maior drone de pulverização do país (P150): https://www.comprerural.com/gigante-dos-tratores-lanca-maior-drone-de-pulverizacao-do-pais-em-2025-relembre/
70. **Embrapa Digital Agriculture** — Portal Embrapa: https://www.embrapa.br/en/agricultura-digital
