import { useState, useEffect, useCallback } from "react";

const SUBJECTS = [
  {
    id: "penal",
    title: "I – Direito Penal",
    color: "#c0392b",
    accent: "#e74c3c",
    topics: [
      { id: "p_principios", label: "Princípios do Direito Penal (legalidade, anterioridade, intervenção mínima, proporcionalidade, etc.)" },
      { id: "p_aplicacao", label: "Aplicação da lei penal (no tempo, no espaço, territorialidade, extraterritorialidade)" },
      { id: "p_teoria_crime", label: "Teoria do crime (conceito analítico: fato típico, ilicitude e culpabilidade)" },
      { id: "p_iter", label: "Iter criminis (cogitação, preparação, execução e consumação)" },
      { id: "p_ilicitude", label: "Ilicitude e causas de exclusão da ilicitude" },
      { id: "p_excludente", label: "Excludentes de ilicitude (legítima defesa, estado de necessidade, estrito cumprimento do dever legal, exercício regular de direito)" },
      { id: "p_culpabilidade", label: "Culpabilidade (imputabilidade, potencial consciência da ilicitude, exigibilidade de conduta diversa)" },
      { id: "p_erro", label: "Erro de tipo e erro de proibição" },
      { id: "p_concurso_pessoas", label: "Concurso de pessoas (coautoria, participação, comunicabilidade de circunstâncias)" },
      { id: "p_concurso_crimes", label: "Concurso de crimes (material, formal e crime continuado)" },
      { id: "p_pena", label: "Pena (espécies, cominação, aplicação, circunstâncias, dosimetria — fases)" },
      { id: "p_extincao", label: "Extinção da punibilidade (morte, anistia, graça, indulto, prescrição, decadência, perempção, etc.)" },
      { id: "p1", label: "Parte Geral do Código Penal" },
      { id: "p2", label: "Parte Especial – Crimes contra a vida (homicídio e feminicídio)" },
      { id: "p2b", label: "Parte Especial – Crimes contra o patrimônio em ambiente digital" },
      { id: "p2c", label: "Parte Especial – Crimes contra a dignidade sexual" },
      { id: "p2d", label: "Parte Especial – Crimes contra a administração pública e finanças públicas" },
      { id: "p3", label: "Lei de Contravenções Penais" },
      { id: "p4_1", label: "Crimes contra a Economia Popular" },
      { id: "p4_2", label: "Crimes de responsabilidade de Prefeitos Municipais" },
      { id: "p4_3", label: "Crimes eleitorais" },
      { id: "p4_4", label: "Crimes referentes ao parcelamento do solo urbano" },
      { id: "p4_5", label: "Crimes de preconceito de raça, cor, etnia, religião e procedência nacional" },
      { id: "p4_6", label: "Crimes contra pessoas com deficiência" },
      { id: "p4_7", label: "Crimes relativos à Criança e ao Adolescente (inclusive digital)" },
      { id: "p4_8", label: "Crimes hediondos" },
      { id: "p4_9", label: "Crimes contra o consumidor" },
      { id: "p4_10", label: "Crimes contra a ordem tributária e as relações de consumo" },
      { id: "p4_11", label: "Crime de desobediência na Lei de Alimentos" },
      { id: "p4_12", label: "Crimes de tortura" },
      { id: "p4_13", label: "Crimes de trânsito" },
      { id: "p4_14", label: "Crimes contra o meio ambiente" },
      { id: "p4_15", label: "Crimes de lavagem ou ocultação de bens, direitos e valores" },
      { id: "p4_16", label: "Crimes contra a pessoa idosa" },
      { id: "p4_17", label: "Estatuto do Desarmamento" },
      { id: "p4_18", label: "Crimes referentes à falência e recuperação judicial/extrajudicial" },
      { id: "p4_19", label: "Crimes referentes a drogas" },
      { id: "p4_20", label: "Crimes referentes ao abuso de autoridade" },
      { id: "p4_21", label: "Crimes relativos à interceptação telefônica" },
      { id: "p4_22", label: "Crime de organização criminosa e infrações penais correlatas" },
      { id: "p4_23", label: "Tratamento jurídico do tráfico de pessoas" },
      { id: "p4_24", label: "Violência doméstica e familiar (CEDAW 35 e Protocolo de Gênero)" },
      { id: "p4_25", label: "Crime de discriminação dos portadores de HIV e doentes de aids" },
      { id: "p4_26", label: "Tratamento jurídico do terrorismo" },
      { id: "p4_27", label: "Violação de sigilo processual em depoimento de criança e adolescente" },
      { id: "p4_28", label: "Crimes do Estatuto do Torcedor" },
      { id: "p4_29", label: "Crimes relativos à propriedade industrial" },
      { id: "p4_30", label: "Crimes da Lei de Transplante de Órgãos" },
      { id: "p4_31", label: "Crimes da Lei Geral do Esporte" },
      { id: "p4_32", label: "Crimes da Lei de Licitações" },
      { id: "p4_33", label: "Crimes contra o Estado Democrático de Direito (Lei nº 14.197/2021 — arts. 359-L ao 359-T do CP)" },
      { id: "p_lmp", label: "Lei Maria da Penha (Lei nº 11.340/2006): conceito de violência doméstica e familiar, formas de violência, sujeitos, medidas protetivas de urgência e aspectos penais" },
    ],
  },
  {
    id: "proc_penal",
    title: "II – Direito Processual Penal",
    color: "#8e44ad",
    accent: "#9b59b6",
    topics: [
      { id: "pp1", label: "Princípios e estrutura acusatória do processo penal brasileiro" },
      { id: "pp2", label: "Aplicação e interpretação da lei processual" },
      { id: "pp3", label: "Inquérito policial, Investigação Criminal e Ação Penal" },
      { id: "pp3_1", label: "Justiça penal negociada: ANPP, Colaboração premiada, Transação penal, Suspensão condicional" },
      { id: "pp3_2", label: "ANPP — Acordo de Não Persecução Penal (art. 28-A CPP): requisitos, vedações, procedimento, homologação, descumprimento e rescisão" },
      { id: "pp4", label: "Jurisdição e Competência" },
      { id: "pp4_1", label: "Juiz de garantias" },
      { id: "pp5", label: "Reparação do dano ex delicto. Ação civil e execução civil da sentença penal" },
      { id: "pp6", label: "Questões e processos incidentes" },
      { id: "pp6_1", label: "Medidas cautelares patrimoniais: sequestro, arresto, hipoteca legal, alienação antecipada" },
      { id: "pp7", label: "Teoria geral da prova" },
      { id: "pp7_2", label: "Proposição, admissão, produção e valoração da prova" },
      { id: "pp7_3", label: "Provas em espécie e meios de obtenção de prova" },
      { id: "pp7_5", label: "Sigilos bancário, fiscal, telefônico e de dados" },
      { id: "pp8", label: "Sujeitos do processo. Papel da vítima. Resolução 243/21 CNMP" },
      { id: "pp9", label: "Prisão em flagrante, temporária, preventiva, cautelares pessoais, audiência de custódia" },
      { id: "pp10", label: "Fatos e atos processuais. Citação, notificação e intimação" },
      { id: "pp11", label: "Sentença. Coisa Julgada" },
      { id: "pp12", label: "Procedimentos comuns ordinário e sumário" },
      { id: "pp13", label: "Procedimento no Tribunal do Júri" },
      { id: "pp14", label: "Procedimentos especiais (funcionários públicos, honra, propriedade imaterial)" },
      { id: "pp15", label: "Nulidades" },
      { id: "pp16", label: "Recursos (Teoria Geral, Apelação, RSE, Embargos, REsp, RE)" },
      { id: "pp17", label: "Revisão criminal. Habeas corpus. Mandado de segurança criminal" },
      { id: "pp18", label: "Execução Criminal (LEP, regimes, remição, livramento condicional)" },
      { id: "pp19", label: "Disposições processuais penais na legislação especial" },
      { id: "pp20", label: "Cooperação jurídica internacional; extradição, expulsão e deportação" },
      { id: "pp_lmp", label: "Lei Maria da Penha (Lei nº 11.340/2006): procedimento especial, medidas protetivas, atuação do MP, juizados de violência doméstica, ação penal e execução" },
    ],
  },
  {
    id: "civil",
    title: "III – Direito Civil",
    color: "#16a085",
    accent: "#1abc9c",
    topics: [
      { id: "c1", label: "LINDB. Princípios fundamentais do direito civil" },
      { id: "c2", label: "Das pessoas naturais e jurídicas. Personalidade, capacidade, direitos da personalidade" },
      { id: "c3", label: "Das pessoas jurídicas. Associações, fundações, sociedades. Desconsideração da personalidade" },
      { id: "c4", label: "Do domicílio" },
      { id: "c5", label: "Dos bens (imóveis, móveis, fungíveis, consumíveis, divisíveis, coletivos, públicos)" },
      { id: "c6", label: "Dos fatos jurídicos. Negócio jurídico: modalidade, defeitos, nulidades, invalidade" },
      { id: "c7", label: "Prescrição e decadência. Supressio e surrectio. Forma e prova" },
      { id: "c8", label: "Direito das obrigações. Adimplemento, extinção e inadimplemento. Cláusula Penal" },
      { id: "c9", label: "Responsabilidade civil: culpa, dano, nexo de causalidade, responsabilidade objetiva" },
      { id: "c10", label: "Contratos em geral. Vícios redibitórios. Evicção. Extinção. Espécies" },
      { id: "c11", label: "Direito das coisas. Posse: classificação, aquisição, efeitos e perda" },
      { id: "c12", label: "Direitos Reais. Propriedade. Usucapião (urbana, rural, coletiva, administrativa, indígena)" },
      { id: "c13", label: "Condomínio, servidões, usufruto, penhor, hipoteca, Estatuto da Cidade, conflitos fundiários" },
      { id: "c14", label: "Direito de família: casamento, filiação, adoção, poder familiar, guarda, tutela, curatela" },
      { id: "c15", label: "Sucessões: legítima, testamentária, testamento, legados, herdeiros necessários" },
      { id: "c16", label: "Redução e revogação de testamento. Testamenteiro" },
      { id: "c17", label: "Inventário e partilha" },
      { id: "c18", label: "Registros Públicos. Registro de imóveis. Princípios do Registro" },
      { id: "c19", label: "Registro Civil das Pessoas Naturais. Nascimento, casamento, óbito, retificações" },
      { id: "c20", label: "Proteção de Dados" },
    ],
  },
  {
    id: "proc_civil",
    title: "IV – Direito Processual Civil",
    color: "#2980b9",
    accent: "#3498db",
    topics: [
      { id: "pc1", label: "Normas fundamentais do processo civil. Interpretação e aplicação" },
      { id: "pc2", label: "Função Jurisdicional: jurisdição, limites, cooperação internacional" },
      { id: "pc3", label: "Competência interna: critérios, absoluta e relativa. Cooperação nacional" },
      { id: "pc4", label: "Sujeitos do processo. Partes e Procuradores. Capacidade processual" },
      { id: "pc5", label: "Despesas, honorários advocatícios e multas. Gratuidade da justiça" },
      { id: "pc6", label: "Litisconsórcio. Intervenção de terceiros. Amicus curiae" },
      { id: "pc7", label: "Juiz: poderes, deveres, responsabilidades, impedimentos e suspeição" },
      { id: "pc8", label: "Ministério Público: perfil constitucional, intervenção, poderes investigatórios" },
      { id: "pc9", label: "Advocacia pública. Defensoria pública. Regime processual" },
      { id: "pc10", label: "Métodos de resolução de litígios individuais e coletivos" },
      { id: "pc11", label: "Autocomposição: negociação, mediação, conciliação, arbitragem (Res. CNMP 118/2014)" },
      { id: "pc12", label: "Política Nacional de Atuação Resolutiva do MP (Rec. CNMP 54/2017)" },
      { id: "pc13", label: "Ação. Direito de ação. Direito de defesa. Exceções e objeções" },
      { id: "pc14", label: "Processo. Atos processuais. Forma, tempo e lugar. Prazos" },
      { id: "pc15", label: "Fatos jurídicos processuais. Pressupostos processuais. Invalidades" },
      { id: "pc16", label: "Tutela jurisdicional: formas, classificações, tutela provisória e definitiva" },
      { id: "pc17", label: "Processo e procedimento. Jurisdição contenciosa e voluntária" },
      { id: "pc18", label: "Procedimento comum: petição inicial, contestação, saneamento, audiência" },
      { id: "pc19", label: "Sentença. Coisa julgada. Cumprimento provisório e definitivo" },
      { id: "pc20", label: "Processo de execução: espécies, responsabilidade patrimonial, fraudes" },
      { id: "pc21", label: "Oposição à execução: impugnação, embargos à execução" },
      { id: "pc22", label: "Recursos: apelação, agravo de instrumento, agravo interno, embargos de declaração" },
      { id: "pc23", label: "Recursos para STF e STJ. Repercussão Geral. Recursos repetitivos" },
      { id: "pc24", label: "Precedentes e julgados vinculantes. Distinção e superação" },
      { id: "pc25", label: "IRDR. Incidente de assunção de competência" },
      { id: "pc26", label: "Usucapião. Mandado de segurança. Mandado de injunção. Habeas data. Ação Popular" },
    ],
  },
  {
    id: "const",
    title: "V – Direito Constitucional",
    color: "#d35400",
    accent: "#e67e22",
    topics: [
      { id: "co1", label: "Teoria da constituição. Constitucionalismo contemporâneo" },
      { id: "co2", label: "Poder constituinte. Titularidade, classificação, limites" },
      { id: "co3", label: "Teoria da Recepção. Repristinação e desconstitucionalização" },
      { id: "co4", label: "Reforma constitucional. Mutação constitucional" },
      { id: "co5", label: "Interpretação constitucional. Princípios" },
      { id: "co6", label: "Eficácia e aplicabilidade das normas constitucionais" },
      { id: "co7", label: "Relações entre direito internacional e ordem constitucional. Dualismo e monismo" },
      { id: "co8", label: "Objetivos e Princípios fundamentais da República Federativa do Brasil" },
      { id: "co9", label: "Direitos e garantias fundamentais. Direitos individuais e coletivos" },
      { id: "co10", label: "Direitos sociais. Ações Constitucionais" },
      { id: "co11", label: "Nacionalidade e direitos políticos. Partidos políticos" },
      { id: "co12", label: "Controle de constitucionalidade. Tipologia. Efeitos da declaração" },
      { id: "co13", label: "Controle de convencionalidade" },
      { id: "co14", label: "Representação de inconstitucionalidade perante Constituição Estadual de SP" },
      { id: "co15", label: "Organização do Estado. Federalismo. Repartição de competências. Intervenção" },
      { id: "co16", label: "Organização dos poderes" },
      { id: "co17", label: "Ministério Público na CF/88: organização, princípios, funções, garantias e vedações" },
      { id: "co18", label: "Sistema tributário nacional. Finanças públicas. Orçamento" },
      { id: "co19", label: "Ordem Econômica e Financeira. Estatuto da Cidade. Reforma agrária" },
      { id: "co20", label: "Ordem Social: saúde, educação, meio ambiente, família, criança, idoso" },
    ],
  },
  {
    id: "infancia",
    title: "VI – Direito da Infância e da Juventude",
    color: "#27ae60",
    accent: "#2ecc71",
    topics: [
      { id: "ij1", label: "Doutrina da proteção integral. Convenção sobre Direitos da Criança. Princípios do ECA" },
      { id: "ij1_1", label: "Direito à vida e à saúde. Direito à liberdade, respeito e dignidade" },
      { id: "ij1_3", label: "Direito à convivência familiar e comunitária. Apadrinhamento. Entrega voluntária" },
      { id: "ij1_4", label: "Direito à educação, cultura, esporte, lazer e profissionalização" },
      { id: "ij2", label: "Medidas de prevenção geral e especial do ECA" },
      { id: "ij2_1", label: "Educação sem castigo. Prevenção da violência. Escuta especializada e depoimento especial" },
      { id: "ij3", label: "Política de atendimento. Entidades. Serviços de Acolhimento" },
      { id: "ij4", label: "Medidas de proteção. Audiências concentradas (Provimento CNJ 118/2021)" },
      { id: "ij5", label: "Prática de ato infracional: conceito, processo socioeducativo, oitiva informal e remissão" },
      { id: "ij6", label: "Medidas socioeducativas. SINASE. Execução. Audiências concentradas" },
      { id: "ij7", label: "Medidas pertinentes aos pais ou responsável. Conselho Tutelar" },
      { id: "ij8", label: "Acesso à Justiça. Competência. Procedimentos e recursos" },
      { id: "ij9", label: "Crimes e infrações administrativas do ECA" },
      { id: "ij10", label: "Educação em direitos humanos. Cultura Afro-brasileira. Primeira Infância e Políticas Públicas" },
    ],
  },
  {
    id: "comercial",
    title: "VII – Direito Comercial e Empresarial",
    color: "#7f8c8d",
    accent: "#95a5a6",
    topics: [
      { id: "em1", label: "Direito de empresa. Empresário: caracterização, inscrição e capacidade" },
      { id: "em2", label: "Direitos humanos e empresas. Estabelecimento. Nome empresarial" },
      { id: "em3", label: "Concorrência empresarial. Infrações da ordem econômica. Propriedade industrial" },
      { id: "em4", label: "Empresário e Direito do Consumidor. Desconsideração da personalidade jurídica" },
      { id: "em5", label: "Sociedades: tipos societários (simples, limitada, S.A., cooperativa, etc.)" },
      { id: "em6", label: "Sociedades coligadas, controladas, grupos, consórcios. Incorporação, fusão, cisão" },
      { id: "em7", label: "Mercados financeiros. Sistema Financeiro Nacional. Mercado de capitais. CVM" },
      { id: "em8", label: "Operadoras de planos de saúde, consórcios e cooperativas de crédito" },
      { id: "em9", label: "Contratos mercantis: compra e venda, franquia, leasing, contratos bancários, câmbio" },
      { id: "em10", label: "Títulos de crédito: letra de câmbio, nota promissória, cheque, duplicata" },
      { id: "em11", label: "Recuperação de empresas e falência: sujeitos, modalidades, procedimentos, crimes" },
      { id: "em12", label: "Regime de intervenção, administração especial temporária e liquidação extrajudicial" },
    ],
  },
  {
    id: "difusos",
    title: "VIII – Tutela de Interesses Difusos e Coletivos",
    color: "#1a6b4a",
    accent: "#27ae60",
    topics: [
      { id: "d1", label: "Interesses difusos, coletivos e individuais homogêneos. Princípios gerais" },
      { id: "d2_1", label: "Meio Ambiente: princípios, instrumentos, EIA, licenciamento, dano ambiental" },
      { id: "d2_2", label: "Patrimônio Público: improbidade, ACP, licitações, Lei Anticorrupção, acordos de leniência" },
      { id: "d2_3", label: "Pessoa Idosa, Deficiente, Saúde Pública, Assistência Social, LGBTQIA+, população carcerária" },
      { id: "d2_4", label: "Consumidor: CDC, proteção contratual, ACP, superendividamento, Marco Civil" },
      { id: "d2_5", label: "Infância e Juventude: MP como indutor de políticas públicas" },
      { id: "d2_6", label: "Habitação e Urbanismo: Regularização Fundiária, Plano Diretor, Mobilidade" },
      { id: "d3", label: "Inquérito civil: instauração, TAC, arquivamento, Inquérito Civil Estrutural" },
      { id: "d4", label: "Ação civil pública: objeto, tutela, competência, sentença, coisa julgada" },
      { id: "d5", label: "Processo Estrutural: conceito, objeto, características, mecanismos de participação" },
      { id: "d6", label: "Ação Popular: legitimidade, objeto, requisitos, procedimento, coisa julgada, execução" },
      { id: "d7", label: "Lei Anticorrupção (Lei nº 12.846/2013): responsabilidade objetiva da pessoa jurídica, acordos de leniência, sanções, cadastro de empresas punidas, Decreto nº 11.129/2022" },
      { id: "d8", label: "Mandado de Segurança individual e coletivo: cabimento, legitimidade, objeto, liminar, sentença e coisa julgada" },
    ],
  },
  {
    id: "dhumanos",
    title: "IX – Direitos Humanos",
    color: "#c0392b",
    accent: "#e74c3c",
    topics: [
      { id: "dh1", label: "Conceito, evolução histórica e dimensões dos Direitos Humanos" },
      { id: "dh2", label: "Sistema Internacional e Interamericano de promoção e proteção dos DH" },
      { id: "dh3", label: "Tratados e Convenções Internacionais incorporados pelo Brasil. Conflito com normas constitucionais" },
      { id: "dh4", label: "O MP e a defesa dos DH. Direitos humanos das minorias e grupos vulnerabilizados" },
      { id: "dh5", label: "Direito Sanitário. SUS: princípios, diretrizes, financiamento, vigilância, saúde mental" },
      { id: "dh6", label: "Direito à educação: FUNDEB, educação inclusiva, Planos nacional e estadual, LDB" },
      { id: "dh7", label: "Sistema Único de Assistência Social. SISAN" },
      { id: "dh8", label: "Racismo: estrutural, institucional, ações afirmativas, Estatuto da Igualdade Racial" },
      { id: "dh9", label: "Proteção dos povos tradicionais (Resolução CNMP 230/2021)" },
      { id: "dh10", label: "Pessoas com deficiência: Convenção, Estatuto, autismo, capacitismo" },
      { id: "dh11", label: "Pessoas idosas: Estatuto, políticas públicas, idadismo, interseccionalidades" },
      { id: "dh12", label: "Violência de gênero e orientação sexual. Protocolo de Gênero. Direitos LGBTQIA+" },
      { id: "dh13", label: "População carcerária: direitos, LGBTQIA+ privados de liberdade, diversidade religiosa" },
      { id: "dh14", label: "Justiça de Transição: mecanismos, Comissão Nacional da Verdade, PNDH-3" },
    ],
  },
  {
    id: "admin",
    title: "X – Direito Administrativo",
    color: "#2c3e50",
    accent: "#34495e",
    topics: [
      { id: "a1", label: "Administração Pública. Descentralização e desconcentração" },
      { id: "a2", label: "Órgãos públicos. Regime jurídico administrativo" },
      { id: "a3", label: "Princípios da Administração Pública. Poderes administrativos" },
      { id: "a4", label: "Agentes públicos. Conceito, regime jurídico, agente de fato" },
      { id: "a5", label: "Ato administrativo: conceito, elementos, discricionariedade, invalidação e revogação" },
      { id: "a6", label: "Processo administrativo" },
      { id: "a7", label: "Licitação: fundamentos, modalidades, critérios, dispensa e inexigibilidade (Lei 14.133)" },
      { id: "a8", label: "Contratos da Administração. Parcerias, convênios e consórcios" },
      { id: "a9", label: "Serviços públicos: regime jurídico, concessão, permissão, PPP" },
      { id: "a10", label: "Bens públicos: conceito, classificação, formas de aquisição, uso privativo" },
      { id: "a11", label: "Intervenção do Estado na propriedade. Função social: rural e urbana" },
      { id: "a12", label: "Responsabilidade patrimonial extracontratual do Estado: objetiva, subjetiva, excludentes" },
      { id: "a13", label: "Controle da Administração Pública: interno, externo, Tribunal de Contas" },
      { id: "a14", label: "Improbidade administrativa. ANPC. Proteção ao patrimônio público" },
      { id: "a15", label: "Responsabilidade da pessoa jurídica. Lei Anticorrupção. Sistema de Integridade" },
      { id: "a16", label: "Responsabilidade fiscal. Solução alternativa de conflitos. Terceiro setor" },
      { id: "a17", label: "Liberdade econômica. Proteção de dados. Acesso à informação" },
    ],
  },
  {
    id: "eleitoral",
    title: "XI – Direito Eleitoral",
    color: "#8e44ad",
    accent: "#9b59b6",
    topics: [
      { id: "el1", label: "Direitos Políticos: fundamentais e privação dos direitos políticos" },
      { id: "el2", label: "Direito Eleitoral: conceito, fontes, princípios e hermenêutica eleitoral" },
      { id: "el3", label: "Poder representativo. Sufrágio: natureza, extensão, valor, modo e formas" },
      { id: "el4", label: "Organização eleitoral: distribuição territorial e sistemas eleitorais" },
      { id: "el5", label: "Justiça Eleitoral: características, órgãos, competências, controle da legalidade" },
      { id: "el6", label: "Ministério Público Eleitoral: composição, atribuições e lisura eleitoral" },
      { id: "el7", label: "Capacidade eleitoral. Alistamento eleitoral: fases, efeitos, cancelamento" },
      { id: "el8", label: "Elegibilidade. Registro de candidaturas. Inelegibilidades (constitucionais e legais)" },
      { id: "el9", label: "Partidos políticos: sistemas, criação, filiação, fidelidade, financiamento" },
      { id: "el10", label: "Garantias eleitorais: liberdade de escolha, contenção ao poder econômico, violência política" },
      { id: "el11", label: "Campanha eleitoral: financiamento e prestação de contas" },
      { id: "el12", label: "Propaganda eleitoral: conceito, desinformação, internet, IA, direito de resposta" },
      { id: "el13", label: "Votação, apuração, diplomação e eleição suplementar" },
      { id: "el14", label: "Ações judiciais eleitorais (AIRC, AIJE, captação ilícita de sufrágio, fraude à cota de gênero)" },
      { id: "el15", label: "Recursos eleitorais. Perda do mandato eletivo" },
      { id: "el16", label: "Crimes eleitorais: puros, acidentais, corrupção, coação, violência política" },
      { id: "el17", label: "Processo penal eleitoral: competência, ação penal eleitoral, medidas despenalizadoras" },
    ],
  },
  {
    id: "resolucoes",
    title: "XII – Resoluções CNMP e correlatas",
    color: "#b7791f",
    accent: "#ed8936",
    topics: [
      { id: "res_pp1", label: "Resolução CNMP nº 310/2025 — Investigação criminal do Ministério Público (Dir. Proc. Penal)" },
      { id: "res_pp2", label: "Resolução CNMP nº 243/2021 — O papel da vítima no processo penal (Dir. Proc. Penal)" },
      { id: "res_pc1", label: "Resolução CNMP nº 118/2014 — Política Nacional de Incentivo à Autocomposição no âmbito do MP (Dir. Proc. Civil)" },
      { id: "res_pc2", label: "Recomendação CNMP nº 54/2017 — Política Nacional de Incentivo à Atuação Resolutiva do MP (Dir. Proc. Civil)" },
      { id: "res_ij1", label: "Resolução CNMP nº 198/2019 — Direito à convivência familiar e comunitária (Dir. Infância e Juventude)" },
      { id: "res_dh1", label: "Resolução CNMP nº 154/2016 — Pessoas idosas (Direitos Humanos)" },
      { id: "res_dh2", label: "Resolução CNMP nº 228/2021 — Política Nacional de Inclusão da Pessoa com Deficiência (Direitos Humanos)" },
      { id: "res_dh3", label: "Resolução CNMP nº 230/2021 — Proteção e defesa dos povos tradicionais (Direitos Humanos)" },
      { id: "res_conanda", label: "Resolução CONANDA nº 231/2022 — Conselho Tutelar: Processo Eleitoral (Dir. Infância e Juventude)" },
      { id: "res_cnj1", label: "Resolução CNJ nº 485/2023 — Entrega voluntária para adoção (Dir. Infância e Juventude)" },
      { id: "res_cnj2", label: "Resolução CNJ nº 348/2020 — Direitos da população LGBTQIA+ privada de liberdade (Direitos Humanos)" },
      { id: "res_tse1", label: "Resolução TSE nº 23.662/2021 — Ação de Suspensão de Órgão Partidário - SOP (Dir. Eleitoral)" },
      { id: "res_tse2", label: "Resolução TSE nº 23.709/2022 — Execução e cumprimento de decisões de multa e sanções pecuniárias (Dir. Eleitoral)" },
      { id: "res_cnj3", label: "Provimento CNJ nº 118/2021 — Audiências Concentradas em medidas de proteção (Dir. Infância e Juventude)" },
    ],
  },
];

const STATUS = {
  pending: { label: "Não estudado", color: "#718096", bg: "rgba(113,128,150,0.1)", icon: "○" },
  studied: { label: "Estudado", color: "#38a169", bg: "rgba(56,161,105,0.1)", icon: "✓" },
  review: { label: "Revisar", color: "#dd6b20", bg: "rgba(221,107,32,0.1)", icon: "↺" },
};

const STORAGE_KEY = "mpsp-tracker-v1";

export default function MPSPTracker() {
  const [progress, setProgress] = useState({});
  const [openSubjects, setOpenSubjects] = useState({});
  const [filter, setFilter] = useState("all");
  const [loading, setLoading] = useState(true);
  const [saveStatus, setSaveStatus] = useState("saved");
  const [activeTab, setActiveTab] = useState("tracker");

  useEffect(() => {
    async function load() {
      try {
        const result = await window.storage.get(STORAGE_KEY);
        if (result && result.value) {
          setProgress(JSON.parse(result.value));
        }
      } catch (e) {
        // no data yet
      }
      setLoading(false);
    }
    load();
  }, []);

  const save = useCallback(async (newProgress) => {
    setSaveStatus("saving");
    try {
      await window.storage.set(STORAGE_KEY, JSON.stringify(newProgress));
      setSaveStatus("saved");
    } catch (e) {
      setSaveStatus("error");
    }
  }, []);

  const setTopicStatus = useCallback((topicId, status) => {
    setProgress((prev) => {
      const updated = { ...prev, [topicId]: status };
      save(updated);
      return updated;
    });
  }, [save]);

  const getTopicStatus = (topicId) => progress[topicId] || "pending";

  const cycleStatus = (topicId) => {
    const current = getTopicStatus(topicId);
    const next = current === "pending" ? "studied" : current === "studied" ? "review" : "pending";
    setTopicStatus(topicId, next);
  };

  const toggleSubject = (id) => {
    setOpenSubjects((prev) => ({ ...prev, [id]: !prev[id] }));
  };

  const getSubjectStats = (subject) => {
    const total = subject.topics.length;
    const studied = subject.topics.filter((t) => progress[t.id] === "studied").length;
    const review = subject.topics.filter((t) => progress[t.id] === "review").length;
    const pending = total - studied - review;
    return { total, studied, review, pending };
  };

  const allTopics = SUBJECTS.flatMap((s) => s.topics);
  const totalTopics = allTopics.length;
  const totalStudied = allTopics.filter((t) => progress[t.id] === "studied").length;
  const totalReview = allTopics.filter((t) => progress[t.id] === "review").length;
  const totalPending = totalTopics - totalStudied - totalReview;
  const overallPct = Math.round((totalStudied / totalTopics) * 100);

  const markAll = async (subjectId, status) => {
    const subject = SUBJECTS.find((s) => s.id === subjectId);
    if (!subject) return;
    setProgress((prev) => {
      const updated = { ...prev };
      subject.topics.forEach((t) => { updated[t.id] = status; });
      save(updated);
      return updated;
    });
  };

  if (loading) {
    return (
      <div style={{ display: "flex", alignItems: "center", justifyContent: "center", height: "100vh", background: "#f7f8fa", color: "#2d3748", fontFamily: "Georgia, serif", fontSize: 18 }}>
        Carregando seu progresso...
      </div>
    );
  }

  return (
    <div style={{ minHeight: "100vh", background: "#f7f8fa", color: "#1a202c", fontFamily: "'Georgia', serif" }}>
      {/* Header */}
      <div style={{ background: "#ffffff", borderBottom: "1px solid #e2e8f0", padding: "28px 24px 20px", boxShadow: "0 1px 4px rgba(0,0,0,0.06)" }}>
        <div style={{ maxWidth: 900, margin: "0 auto" }}>
          <div style={{ display: "flex", alignItems: "flex-start", justifyContent: "space-between", flexWrap: "wrap", gap: 12 }}>
            <div>
              <div style={{ fontSize: 11, letterSpacing: 3, color: "#a0aec0", textTransform: "uppercase", marginBottom: 4 }}>97º Concurso de Ingresso</div>
              <h1 style={{ margin: 0, fontSize: 24, fontWeight: 700, color: "#1a202c", letterSpacing: -0.5 }}>
                MPSP · Controle de Estudos
              </h1>
              <div style={{ fontSize: 13, color: "#718096", marginTop: 4 }}>Ministério Público do Estado de São Paulo</div>
            </div>
            <div style={{ textAlign: "right" }}>
              <div style={{ fontSize: 11, color: saveStatus === "error" ? "#e53e3e" : "#38a169", letterSpacing: 1 }}>
                {saveStatus === "saving" ? "⟳ Salvando..." : saveStatus === "error" ? "✗ Erro ao salvar" : "✓ Progresso salvo"}
              </div>
            </div>
          </div>

          {/* Overall Progress */}
          <div style={{ marginTop: 24, padding: "16px 20px", background: "#f0f4ff", borderRadius: 12, border: "1px solid #dde3f5" }}>
            <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginBottom: 10 }}>
              <span style={{ fontSize: 13, color: "#4a5568" }}>Progresso Geral — {totalTopics} tópicos</span>
              <span style={{ fontSize: 28, fontWeight: 700, color: "#38a169" }}>{overallPct}%</span>
            </div>
            <div style={{ height: 8, background: "#e2e8f0", borderRadius: 4, overflow: "hidden" }}>
              <div style={{ display: "flex", height: "100%" }}>
                <div style={{ width: `${(totalStudied / totalTopics) * 100}%`, background: "#38a169", transition: "width 0.4s ease" }} />
                <div style={{ width: `${(totalReview / totalTopics) * 100}%`, background: "#dd6b20", transition: "width 0.4s ease" }} />
              </div>
            </div>
            <div style={{ display: "flex", gap: 20, marginTop: 10, flexWrap: "wrap" }}>
              {[
                { label: "Estudados", count: totalStudied, color: "#38a169" },
                { label: "Para revisar", count: totalReview, color: "#dd6b20" },
                { label: "Pendentes", count: totalPending, color: "#a0aec0" },
              ].map((item) => (
                <div key={item.label} style={{ display: "flex", alignItems: "center", gap: 6, fontSize: 12, color: "#4a5568" }}>
                  <div style={{ width: 8, height: 8, borderRadius: "50%", background: item.color }} />
                  <strong style={{ color: item.color }}>{item.count}</strong> {item.label}
                </div>
              ))}
            </div>
          </div>

          {/* Tabs */}
          <div style={{ display: "flex", gap: 4, marginTop: 16 }}>
            {["tracker", "resumo"].map((tab) => (
              <button key={tab} onClick={() => setActiveTab(tab)}
                style={{ padding: "7px 18px", borderRadius: 8, border: "1px solid transparent", cursor: "pointer", fontSize: 13, fontFamily: "Georgia, serif",
                  background: activeTab === tab ? "#ffffff" : "transparent",
                  borderColor: activeTab === tab ? "#e2e8f0" : "transparent",
                  color: activeTab === tab ? "#1a202c" : "#718096",
                  boxShadow: activeTab === tab ? "0 1px 3px rgba(0,0,0,0.08)" : "none",
                  transition: "all 0.2s" }}>
                {tab === "tracker" ? "📋 Tópicos" : "📊 Resumo por Matéria"}
              </button>
            ))}
            {/* Filter */}
            <div style={{ marginLeft: "auto", display: "flex", gap: 4 }}>
              {["all", "pending", "studied", "review"].map((f) => (
                <button key={f} onClick={() => setFilter(f)}
                  style={{ padding: "5px 12px", borderRadius: 6,
                    border: `1px solid ${filter === f ? "#cbd5e0" : "#e2e8f0"}`,
                    cursor: "pointer", fontSize: 11, fontFamily: "Georgia, serif", letterSpacing: 0.5,
                    background: filter === f ? "#ffffff" : "transparent",
                    color: filter === f ? "#2d3748" : "#a0aec0",
                    boxShadow: filter === f ? "0 1px 2px rgba(0,0,0,0.06)" : "none" }}>
                  {f === "all" ? "Todos" : f === "pending" ? "Pendentes" : f === "studied" ? "Estudados" : "Revisar"}
                </button>
              ))}
            </div>
          </div>
        </div>
      </div>

      {/* Content */}
      <div style={{ maxWidth: 900, margin: "0 auto", padding: "20px 24px 60px" }}>
        {activeTab === "resumo" ? (
          <div style={{ display: "grid", gridTemplateColumns: "repeat(auto-fill, minmax(260px, 1fr))", gap: 14 }}>
            {SUBJECTS.map((subject) => {
              const stats = getSubjectStats(subject);
              const pct = Math.round((stats.studied / stats.total) * 100);
              return (
                <div key={subject.id} style={{ background: "#ffffff", border: "1px solid #e2e8f0", borderRadius: 12, padding: "16px 18px", boxShadow: "0 1px 3px rgba(0,0,0,0.05)" }}>
                  <div style={{ fontSize: 11, color: subject.color, letterSpacing: 1, marginBottom: 6, textTransform: "uppercase", fontWeight: 700 }}>
                    {subject.title.split("–")[0].trim()}
                  </div>
                  <div style={{ fontSize: 13, color: "#2d3748", marginBottom: 12, lineHeight: 1.4 }}>
                    {subject.title.split("–")[1]?.trim()}
                  </div>
                  <div style={{ height: 5, background: "#edf2f7", borderRadius: 3, overflow: "hidden", marginBottom: 8 }}>
                    <div style={{ display: "flex", height: "100%" }}>
                      <div style={{ width: `${(stats.studied / stats.total) * 100}%`, background: "#38a169" }} />
                      <div style={{ width: `${(stats.review / stats.total) * 100}%`, background: "#dd6b20" }} />
                    </div>
                  </div>
                  <div style={{ display: "flex", justifyContent: "space-between", fontSize: 11, color: "#718096" }}>
                    <span><span style={{ color: "#38a169" }}>{stats.studied}</span>/{stats.total} estudados</span>
                    <span style={{ color: subject.color, fontWeight: 700 }}>{pct}%</span>
                  </div>
                  {stats.review > 0 && (
                    <div style={{ fontSize: 11, color: "#dd6b20", marginTop: 4 }}>↺ {stats.review} para revisar</div>
                  )}
                </div>
              );
            })}
          </div>
        ) : (
          <div style={{ display: "flex", flexDirection: "column", gap: 10 }}>
            {SUBJECTS.map((subject) => {
              const stats = getSubjectStats(subject);
              const isOpen = openSubjects[subject.id];
              const pct = Math.round((stats.studied / stats.total) * 100);

              const filteredTopics = subject.topics.filter((t) => {
                if (filter === "all") return true;
                return (progress[t.id] || "pending") === filter;
              });

              if (filter !== "all" && filteredTopics.length === 0) return null;

              return (
                <div key={subject.id} style={{ background: "#ffffff", border: "1px solid #e2e8f0", borderRadius: 14, overflow: "hidden", boxShadow: "0 1px 3px rgba(0,0,0,0.05)" }}>
                  {/* Subject Header */}
                  <div onClick={() => toggleSubject(subject.id)}
                    style={{ padding: "14px 18px", cursor: "pointer", display: "flex", alignItems: "center", gap: 14,
                      background: isOpen ? "#f7fafc" : "#ffffff",
                      borderBottom: isOpen ? "1px solid #e2e8f0" : "none" }}>
                    <div style={{ width: 4, height: 36, borderRadius: 2, background: subject.accent, flexShrink: 0 }} />
                    <div style={{ flex: 1, minWidth: 0 }}>
                      <div style={{ fontSize: 14, fontWeight: 600, color: "#1a202c" }}>{subject.title}</div>
                      <div style={{ fontSize: 11, color: "#a0aec0", marginTop: 2 }}>{stats.total} tópicos</div>
                    </div>
                    <div style={{ display: "flex", alignItems: "center", gap: 10 }}>
                      <div style={{ textAlign: "right" }}>
                        <div style={{ fontSize: 18, fontWeight: 700, color: pct === 100 ? "#38a169" : subject.color }}>{pct}%</div>
                        <div style={{ width: 80, height: 3, background: "#edf2f7", borderRadius: 2, overflow: "hidden" }}>
                          <div style={{ display: "flex", height: "100%" }}>
                            <div style={{ width: `${(stats.studied / stats.total) * 100}%`, background: "#38a169" }} />
                            <div style={{ width: `${(stats.review / stats.total) * 100}%`, background: "#dd6b20" }} />
                          </div>
                        </div>
                      </div>
                      <span style={{ fontSize: 16, color: "#a0aec0", transform: isOpen ? "rotate(90deg)" : "none", transition: "transform 0.2s", display: "inline-block" }}>›</span>
                    </div>
                  </div>

                  {/* Topics */}
                  {isOpen && (
                    <div>
                      {/* Quick actions */}
                      <div style={{ padding: "8px 18px", display: "flex", gap: 8, borderBottom: "1px solid #f0f4f8", background: "#fafbfc" }}>
                        <span style={{ fontSize: 11, color: "#a0aec0", alignSelf: "center", marginRight: 4 }}>Marcar todos:</span>
                        {["studied", "review", "pending"].map((s) => (
                          <button key={s} onClick={() => markAll(subject.id, s)}
                            style={{ padding: "3px 10px", borderRadius: 5, border: `1px solid ${STATUS[s].color}44`, cursor: "pointer", fontSize: 11,
                              fontFamily: "Georgia, serif", background: STATUS[s].bg, color: STATUS[s].color }}>
                            {STATUS[s].icon} {STATUS[s].label}
                          </button>
                        ))}
                      </div>
                      {filteredTopics.map((topic, idx) => {
                        const status = getTopicStatus(topic.id);
                        const st = STATUS[status];
                        return (
                          <div key={topic.id} onClick={() => cycleStatus(topic.id)}
                            style={{ padding: "11px 18px 11px 22px", display: "flex", alignItems: "center", gap: 12, cursor: "pointer",
                              background: idx % 2 === 0 ? "#ffffff" : "#fafbfc",
                              borderBottom: idx < filteredTopics.length - 1 ? "1px solid #f0f4f8" : "none",
                              transition: "background 0.15s" }}>
                            <div style={{ width: 26, height: 26, borderRadius: "50%", border: `2px solid ${st.color}`, background: st.bg,
                              display: "flex", alignItems: "center", justifyContent: "center", fontSize: 13, color: st.color, flexShrink: 0, fontWeight: 700 }}>
                              {st.icon}
                            </div>
                            <span style={{ fontSize: 13, color: status === "studied" ? "#a0aec0" : "#2d3748", flex: 1, lineHeight: 1.4,
                              textDecoration: status === "studied" ? "line-through" : "none" }}>
                              {topic.label}
                            </span>
                            <span style={{ fontSize: 10, color: st.color, whiteSpace: "nowrap", letterSpacing: 0.5 }}>
                              {st.label}
                            </span>
                          </div>
                        );
                      })}
                    </div>
                  )}
                </div>
              );
            })}
          </div>
        )}
      </div>

      {/* Footer legend */}
      <div style={{ position: "fixed", bottom: 0, left: 0, right: 0, background: "rgba(255,255,255,0.97)", backdropFilter: "blur(10px)",
        borderTop: "1px solid #e2e8f0", padding: "10px 24px", display: "flex", justifyContent: "center", gap: 24,
        boxShadow: "0 -1px 8px rgba(0,0,0,0.06)" }}>
        {Object.entries(STATUS).map(([key, val]) => (
          <div key={key} style={{ display: "flex", alignItems: "center", gap: 6, fontSize: 11, color: "#718096" }}>
            <div style={{ width: 16, height: 16, borderRadius: "50%", border: `2px solid ${val.color}`, background: val.bg,
              display: "flex", alignItems: "center", justifyContent: "center", fontSize: 9, color: val.color }}>
              {val.icon}
            </div>
            {val.label} · <strong style={{ color: val.color }}>clique para alternar</strong>
          </div>
        ))}
      </div>
    </div>
  );
}
