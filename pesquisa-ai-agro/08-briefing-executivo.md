# Briefing Executivo — AI no Agro de Sorriso/MT

**Para**: reunião com o Sindicato Rural de Sorriso (e/ou Núcleo Aprosoja Sorriso) e a Prefeitura de Sorriso (Alei Fernandes)
**Por**: consultoria de AI vendor-agnostic (software + serviços)
**Em**: 5 dias

---

## 1. O Cenário

A IA no agro brasileiro passou o ponto de inflexão. Segundo a FGV/Oscar Burd, **41,9% das fazendas e agroindústrias do país já usam alguma solução de IA em 2025**, contra 16,9% em 2022 (arq 03, 04). O farm management software global vale US$ 2,75 bi em 2024 e chega a US$ 4,67 bi em 2029 (CAGR 11,2%); o mercado brasileiro de carbono salta de US$ 2,11 bi (2024) para US$ 25,2 bi (2034). Os gatilhos regulatórios já estão na mesa: EUDR em 30/12/2026, PNIB de rastreabilidade bovina até 2032, SBCE/Lei 15.042/2024 atingindo 5.000 empresas, e a Moratória da Soja em MT (lei estadual 12.709/2024) voltou a vigorar em janeiro/2026. **A janela competitiva é agora.**

## 2. Por que Sorriso é o lugar certo

- **Maior PIB agrícola do Brasil pelo 6º ano consecutivo**: R$ 7,2 bi em 2024, com 615 mil ha de soja, 500 mil ha de milho safrinha e 59 mil ha de algodão (IBGE/PAM 2024; arq 06).
- **Maior produtor individual de soja do mundo**: 2,08 Mt em 2024 (USDA/IBGE; arq 06) — R$ 3,3 bi só de soja em um município.
- **76% dos produtores de MT com perfil "inovador" ou "altamente inovador"** (FAMATO/AgriHub 2024) e Sorriso é um dos 3 centros de treinamento de operadores do estado (arq 01, 06).
- **612 associados no Sindicato Rural de Sorriso** (presidente Diogo Damiani, triênio 2025/27); núcleo Aprosoja-MT em Sorriso (coordenador Rafael Krzyzanski). Maior PIB significa maior canal de distribuição organizada (arq 06).
- **332 recuperações judiciais no agro de MT em 2025** (34% ligadas à soja); margem do sojicultor em Sorriso na safra 23/24 caiu para 1,7 sc/ha. Há demanda real por serviços que recuperem margem (arq 06).
- **Déficit de armazenagem em MT de 45-52 Mt** (CONAB/IMEA); Sorriso lidera o país com 5,6 Mt instalados; Ferrovia Rumo chega à região em 2026, reordenando logística (arq 02, 06).

## 3. As 5 maiores oportunidades

### Oportunidade 1 — Cockpit Vendor-Agnostic de Decisão

O produtor de Sorriso usa em paralelo FieldView (28 Mi ha no BR), John Deere Operations Center, Aegro/Siagri, planilhas e boletins do IMEA — sem visão consolidada (arq 05, gap #3). Entregamos uma camada de integração via Leaf Agriculture API + Embrapa AgroAPI + IMEA + telemetria, com agente LLM em PT-BR que recomenda ação por talhão com ROI mensurável. Somos defensáveis porque nenhum fornecedor de plataforma quer integrar com concorrente — somos o único alinhado ao produtor. Mercado endereçável: ~2.000 propriedades em Sorriso × R$ 20-50 mil/ano = **R$ 40-100 milhões/ano só Sorriso** (10x em MT). Modelo: SaaS por hectare (R$ 5-15/ha) + setup (R$ 50-150k) + retainer (R$ 15-50k/mês). Primeiro resultado em 60-90 dias com piloto em 3-5 fazendas.

### Oportunidade 2 — EUDR White-Label para a Associação

A EUDR vigora em 30/12/2026 e afeta os **US$ 46,3 bi em exportações ao bloco europeu**; aproximadamente 1/3 são commodities-alvo (arq 02). Sorriso é fronteira Cerrado-Amazônia e tem áreas com desmatamento legal pré-2020 perto do corte temporal. Construímos plataforma white-label para o Sindicato/Aprosoja Sorriso cobrir os 612 associados — ingere CAR + polígonos + PRODES/DETER + certidões e gera dossiê EUDR automatizado, com helpdesk LLM via WhatsApp. Defensabilidade: Selo Verde dá o dado de graça; Agrotools/Serasa Smart ESG vendem caro para enterprise; ninguém entrega o serviço B2B2C sob marca da associação. Mercado em Sorriso: 612 × R$ 500-2.000/ano = **R$ 0,3-1,2 milhão/ano**, expansível para R$ 5-15 mi/ano em MT. Modelo: setup R$ 500 mil-1,5 mi + anuidade por produtor. MVP em 30-45 dias.

### Oportunidade 3 — Mesa de Inteligência Comercial

Soja a R$ 110-115/sc em 2025 vs. ponto de equilíbrio R$ 90,04/sc (arq 06); custo total 25/26 em R$ 7.430-7.657/ha. Estudo em Primavera do Leste/Sorriso mostrou que estratégia mista (físico + futuro) gerou +R$ 930/ha sobre a venda 100% spot (arq 06). Hedgepoint/StoneX vendem relatório corporativo genérico; nenhuma plataforma combina CBOT + basis local + frete Sifreca + clima em recomendação executável (arq 03, gap explícito). Entregamos retainer mensal de análise consultiva (não execução) para grupos familiares com 5+ fazendas, com reunião semanal e dashboard. Mercado: ~300 produtores médio-grandes em Sorriso × R$ 30-100k/ano = **R$ 9-30 milhões/ano só Sorriso**. Modelo: R$ 5-15 mil/mês + success fee opcional. Onboarding em 90 dias.

### Oportunidade 4 — Previsão de Fila Portuária

Frete Sorriso-Paranaguá saltou +38% em um mês; Sorriso-Miritituba +70% em pico (arq 02, 06). **"Não há solução comercial brasileira amplamente adotada que aplique IA preditiva para fila portuária de grãos — gap relevante de mercado"** (arq 02, achado #1). Os dados existem (portais dos portos, AIS de navios, Conab Boletim Logístico); ninguém empacotou. Construímos modelo preditivo de fila + recomendação de rota/janela, B2B para cooperativas e tradings (modelo B2B2B). Mercado: 10-20 clientes corporativos × R$ 50-200k/ano = **R$ 0,5-4 milhões/ano**, com escala nacional. Demo possível em 15-30 dias usando dados públicos — **factível como prova já na primeira reunião**.

### Oportunidade 5 — MRV de Carbono em Soja-Milho-ILPF

Mercado brasileiro de carbono salta de US$ 2,11 bi (2024) para US$ 25,2 bi (2034), CAGR 28,1% (arq 04). Bayer PRO Carbono já em 3+ Mi ha em programa; Cargill 3S e Bunge Regenerativa em expansão. Nenhum player especialista em soja-milho-MT: Agrorobótica/Carbonext/Mombak focam outras culturas ou floresta (arq 05, gap #6). Sorriso tem 25% da soja já certificada RTRS — conversão para programas de carbono é o próximo passo natural. Orquestramos elegibilidade do produtor para o programa mais lucrativo, com MRV via Sentinel-2 + ML + AGLIBS (Agrorobótica) para carbono no solo, e laudos Verra/Bureau Veritas. Mercado: 615 mil ha de soja × R$ 30-80/ha de fee de orquestração = **R$ 18-50 milhões/ano só Sorriso** em cenário maduro. Modelo: success fee + retainer. Primeiro contrato em 6-9 meses.

## 4. O que já vimos funcionar (cases verificados)

- **Solinftec ALICE/Solix em MT**: ROI documentado de +8% produtividade e -15% custo de insumos; unicórnio com R$ 1,3 bi captados; plano de 700 robôs até 2026; sede em Sinop, a 80 km de Sorriso (arq 01, 05).
- **John Deere See & Spray**: 60-90% de redução de herbicida em pulverização seletiva; em fazenda MT de 7.400 acres gera incremental US$ 115/acre/ano (arq 01, 05).
- **Climate FieldView (Bayer)**: 28 milhões de ha mapeados no Brasil; oferecido grátis em campanhas (arq 01, 05).
- **Cromai (visão computacional, daninhas)**: ROI documentado de R$ 120/ha; 90+ clientes incluindo Bunge, Amaggi, SLC, Syngenta (arq 01, 05).
- **Bunge VEGA/LYRA**: 100% de rastreabilidade satelital no Cerrado, gratuito para rede de revendas — solução EUDR proprietária (arq 02, 05).
- **FreteBras/CargoX**: R$ 800 milhões em IA em 3 anos; **agro = 50% das cargas movimentadas**; 900 mil motoristas, 20 milhões de análises/ano (arq 02).
- **Kepler Weber + Procer**: R$ 50,8 milhões pela aquisição (50%+1) de sensores IoT; Silo 156 (35 mil t) em Primavera do Leste/MT; robô de nivelamento (arq 02).
- **Bayer PRO Carbono**: 3.000+ produtores, 3+ milhões de ha em programa; soja com pegada 50% menor; 47 especialistas, 19 instituições parceiras (arq 04).
- **Grão Direto**: 12 Mt em 2025, meta 18-20 Mt em 2026; primeira venda 100% por IA fechada em 2024-25 (arq 03).
- **Cocamar + SENAI**: 97% de acurácia em pré-classificação de soja por visão computacional; CNA favorável à regulamentação de IA na IN 11/2007 (arq 02).

## 5. Nossa proposta de entrada (3 serviços iniciais)

| Serviço | O que entrega | Prazo | Ticket | ICP |
|---|---|---|---|---|
| **1. Diagnóstico AI 360** | Auditoria de "ativos digitais ociosos" da fazenda (FieldView, Operations Center, Aegro etc.); mapa de 10-20 quick wins de extração de valor; análise satelital independente; benchmark vs. pares; roadmap de implementação | 6-8 semanas | R$ 80-200 mil por projeto | Top 50 fazendas: 3.000-30.000 ha, gestor profissional |
| **2. EUDR White-Label** | Plataforma sob marca do Sindicato/Aprosoja para cobrir os 612 associados até dez/2026: cadastro de polígonos, dossiê EUDR automatizado, helpdesk LLM via WhatsApp | 90-120 dias para go-live | R$ 500 mil-1,5 mi setup + R$ 500-2.000/produtor/ano | Sindicato Rural de Sorriso + Núcleo Aprosoja Sorriso (B2B2C) |
| **3. Mesa de Inteligência Comercial** | Retainer mensal de análise B3+CBOT+IMEA+Sifreca+clima+livro de contratos, com reunião semanal e dashboard; recomendação de janela de venda/hedge por contrato | 90 dias de onboarding | R$ 5-15 mil/mês por grupo familiar | Grupos com 5+ fazendas, faturamento R$ 200 mi+ |

**Ticket conjunto anualizado projetado (5 fazendas + Sindicato + 8 grupos)**: R$ 3,5-7,5 milhões em ARR no primeiro ciclo; ARR alvo mês 12 entre R$ 5 mi (base) e R$ 12-15 mi (cenário com EUDR ramp).

## 6. Próximos passos

- **Acesso a 3-5 fazendas-âncora** dispostas a piloto pago do Diagnóstico AI 360 com case público (idealmente entre top grupos da região: Bom Futuro, SLC, Amaggi, família Tessaro, família Beledelli, família Belusso).
- **Endosso institucional** (não exclusividade) do Sindicato Rural de Sorriso e/ou Núcleo Aprosoja Sorriso para campanha de EUDR junto aos 612 associados.
- **Dados anônimos de 1-2 safras** (CAR, custos consolidados, polígonos) para calibrar modelos de carbono, EUDR e cockpit.
- **Carta de intenção em 30 dias** definindo escopo do piloto, governança e cronograma de entrega.
- **Co-marketing** em ao menos 1 evento de referência em 2026 (Tecnoshow Comigo, Show Safra BR-163, Exporriso ou dia de campo da Embrapa Agrossilvipastoril em Sinop).
- **Comitê Técnico de IA** com 5-7 produtores + consultoria + 1 agrônomo Embrapa Sinop como observador; modelo de governança definido em 60 dias e relatório trimestral de impacto (hectares cobertos, ROI por produtor, hectares em compliance EUDR).

---

## Fontes principais

1. FGV/Oscar Burd — Adoção de IA em 41,9% das fazendas BR (2025): https://agronamidia.com.br/ia-no-agro-como-a-tecnologia-ja-monitora-pragas-gado-e-precos-em-419-das-fazendas-brasileiras/
2. IBGE/PAM 2024 — Sorriso, maior PIB agrícola do Brasil: https://agenciabrasil.ebc.com.br/economia/noticia/2025-09/sorriso-no-mt-tem-maior-pib-agricola-do-pais-veja-o-ranking
3. FAMATO/AgriHub 2024 — 76% dos produtores de MT com perfil inovador: https://sistemafamato.org.br/blog/2024/10/30/estudo-inedito-do-agrihub-revela-que-76-dos-produtores-rurais-de-mato-grosso-tem-perfil-inovador/
4. Aprosoja-MT — déficit de armazenagem 45-52 Mt: https://aprosoja.com.br/comunicacao/release/com-inicio-da-safra-2526-reducao-no-plano-safra-acende-alerta-sobre-deficit-de-armazenagem-em-mato-grosso
5. IMEA — custos e rentabilidade soja 25/26 em MT: https://publicacoes.imea.com.br/relatorio-de-mercado/bs-soja/833
6. Sindicato Rural de Sorriso — 612 associados, presidência Diogo Damiani 2025/27: https://www.noticiasagricolas.com.br/noticias/agronegocio/388673-sindicato-rural-de-sorriso-elege-nova-diretoria-para-o-trienio-2025-2027.html
7. AgFeed — FreteBras R$ 800 mi em IA, 50% das cargas no agro: https://agfeed.com.br/negocios/unicornio-dos-fretes-investe-r-800-milhoes-e-em-ia-para-transportar-supersafra/
8. Bayer PRO Carbono — 3 mi ha, 3.000+ produtores: https://www.agro.bayer.com.br/nossa-bayer/pro-carbono-lidera-solucoes-de-agricultura-regenerativa-na-america-latina-e-acelera-a-descarbonizacao-do-campo-a-industria
