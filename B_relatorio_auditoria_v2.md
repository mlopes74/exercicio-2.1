# Relatório de Auditoria — v2 da pesquisa "Atores da jornada de emissão de passaporte comum (PF)"

**Objeto:** `B_relatorio_assistente_v2.md` (v2 pós-auditoria, 47 linhas de matriz + Seção 6 de rastreabilidade).
**Referência:** `B_relatorio_auditoria_v1.md` (falhas F1–F54).
**Data:** 14/11/2026.
**Escopo:** (a) tratamento real de cada falha F1–F54; (b) falhas novas introduzidas pela v2; (c) pontos que continuam abertos. Os pontos estão numerados de **P1** a **P44**.

---

## 0. Método e limites

- A Seção 6 da v2 (rastreabilidade) **não foi aceita como prova**. Cada afirmação de "corrigido", "defendido" ou "comprovado" foi conferida no corpo do texto e, quando possível, na fonte.
- Desta vez o texto consolidado do Decreto nº 5.978/2006 foi lido na base da Câmara dos Deputados, o que permitiu conferir os Arts. 5º, 13, 20, 24, 29, 30, 33, 38 e 42.
- **Limite:** páginas do domínio `gov.br/pf` e o PDF da IN 173/2020 não puderam ser abertos diretamente nesta sessão. Foram conferidos pelo trecho que o buscador indexa ou por fontes secundárias. Quando nem isso foi possível, o ponto aparece como **[NÃO VERIFICADO]**, e não como erro.
- **Gravidade:** A (alta), M (média), B (baixa), com o mesmo critério do audit_v1.

### Resumo

| Resultado sobre F1–F54 | Qtde |
|---|---|
| Resolvida (inclui 2 falhas retiradas pelo próprio auditor) | 36 |
| Parcialmente resolvida | 16 |
| Não resolvida | 2 |

| Achados desta auditoria | Pontos | Alta | Média | Baixa |
|---|---|---|---|---|
| Autocorreções do audit_v1 | P1–P3 | — | — | — |
| Falhas do v1 tratadas de forma incompleta ou não tratadas (P14, P19 e P20 são só remissões) | P4–P20 | 3 | 8 | 3 |
| Falhas novas introduzidas pela v2 | P21–P37 | 3 | 6 | 8 |
| Pontos abertos e remanescentes | P38–P44 | 0 | 4 | 3 |

**Conclusão geral:** a v2 corrigiu com fonte todos os erros factuais graves de orçamento, normas e taxas (F1–F9). Mas, em vários pontos, **trocou uma afirmação sem fonte por outra afirmação sem fonte, agora com aparência de documento primário**: número de processo do TCU, número de contrato, súmula do STJ, artigo de decreto. Esse padrão (P5, P21, P22, P23, P24) é mais grave que a falha original, porque a v2 o marca como "Fato Documentado" e "comprovado". A Seção 6 superestima o que foi feito.

---

## 1. Autocorreções do audit_v1 (transparência)

### P1 — F12 retirada: a regra da fotografia 5x7 para menores de 5 anos procede
O audit_v1 tratou o corte de 5 anos como "não verificado / conflitante". A FAQ oficial da PF confirma que só crianças **menores de 5 anos** levam fotografia 5x7, e que todo solicitante acima de 5 anos é fotografado no atendimento. **A defesa (b) da v2 procede.** Fica uma ressalva: o número do artigo "Art. 40, II, da IN 173/2020" não foi verificado (P15).

### P2 — F42 retirada: o vínculo entre a Lei 14.534/2023 e a exigência de CPF é declarado pela própria PF
A Lista Oficial de Documentação da PF diz literalmente que, em virtude da Lei 14.534/2023, todo solicitante de passaporte, inclusive menor, deve ter CPF válido. **A defesa (b) da v2 procede.**

### P3 — Premissa do F15 precisava de ajuste
O audit_v1 tratou o "Consórcio Iafis Idemia" como contratado do ABIS sem verificar. O extrato publicado no DOU em julho de 2021 (Pregão nº 4/2020-DTI/PF) indica como contratada a **IAFIS SYSTEMS DO BRASIL LTDA.** (CNPJ 05.742.247/0001-05), não um consórcio. A crítica central do F15 continua válida (a Griaule não é coautora), mas a v2 herdou e reforçou a premissa imprecisa. Ver P5.

---

## 2. Parte (a) — Tratamento das falhas F1–F54

### 2.1 Quadro de status

| Falha | Status | Observação / ponto |
|---|---|---|
| F1 | Resolvida | Decreto 11.249/2022 removido. |
| F2 | Resolvida | Art. 13 correto; texto do decreto separado do rol infralegal. O ato ministerial que define as hipóteses continua sem identificação (P40). |
| F3 | Resolvida | "Portaria MJ nº 927/2015" padronizada; o reajuste de julho de 2015 pelo MJ é confirmado pela imprensa. |
| F4 | Resolvida | Destinatário MPO/JEO, escopo e desfecho de 05/11/2025 corretos. |
| F5 | Resolvida | Ministério da Economia e bloqueio para o teto (2022) corretos. |
| F6 | Resolvida | Papel da CMB no passaporte de emergência incluído. |
| F7 | Resolvida | Prazo de 60 dias e condições de devolução corretos. |
| F8 | Resolvida com ressalva | Contrato 40/2022 documentado; "aditivos de 2025" não verificado (P42). |
| F9 | Resolvida | A Portaria MJSP 218/2018 existe e trata da isenção para regularização migratória; Art. 30, parágrafo único, conferido. |
| F10 | **Parcial** | P4 |
| F11 | Resolvida | — |
| F12 | Retirada (P1) | — |
| F13 | Resolvida | — |
| F14 | **Parcial** | P6 |
| F15 | **Parcial** | P5 |
| F16 | Resolvida | — |
| F17 | Resolvida | Com a cautela de que a frase "estrutura regimental (...) 2024–2026" é afirmada sem ato. |
| F18 | **Não resolvida (defesa refutada)** | P7 |
| F19 | Resolvida | — |
| F20 | **Parcial** | P8 |
| F21 | **Parcial** | P9 |
| F22 | **Parcial** (correção com afirmações novas sem fonte) | P29 |
| F23 | Resolvida (c) | — |
| F24 | Resolvida (c) | — |
| F25 | **Parcial** | P10 |
| F26 | **Parcial** | P11 |
| F27 | Resolvida | — |
| F28 | Resolvida | O Art. 24 de fato trata de passaportes diplomático e oficial. |
| F29 | **Parcial** | P12 |
| F30 | Resolvida com ressalva | P35 |
| F31 | Resolvida (c) com ressalva | P36 |
| F32 | **Parcial** | P4 |
| F33 | **Não resolvida (substituída por citação não verificada)** | P21 |
| F34 | Resolvida (c) | — |
| F35 | **Parcial** | P13 e P22 |
| F36 | Resolvida com ressalva | P34 |
| F37 | **Parcial** | P15 |
| F38 | Resolvida | Data errada no novo texto (P31). |
| F39 | **Parcial** | P16 |
| F40 | Resolvida | — |
| F41 | Resolvida | — |
| F42 | Retirada (P2) | — |
| F43 | Resolvida | Mas a v2 trouxe uma falha nova na base jurisprudencial (P23). |
| F44 | Resolvida | — |
| F45 | **Parcial** | P23 |
| F46 | **Parcial** | P17 |
| F47 | **Parcial** | P18 |
| F48 | Resolvida | — |
| F49 | Resolvida | Fusão de atores na matriz tratada em P8. |
| F50 | Resolvida | Base factual do BO tratada em P38. |
| F51 | Resolvida | — |
| F52 | Resolvida | — |
| F53 | Resolvida com ressalva | P26 |
| F54 | Resolvida | — |

### 2.2 Falhas tratadas de forma incompleta ou não tratadas

### P4 — F10/F32: o episódio de "Dezembro de 2016" ficou sem fonte, e o ano do defeito na perfuração a laser não foi provado · M
> "**Litígio ou Impasse Contratual PF × CMB (ex.: Dezembro de 2016)**" (Exceção 5); "**Impasse Contratual e Operacional PF × CMB (2016):** (...) inoperância de equipamento de perfuração a laser" (4.1)

**Justificativa:** a v2 aceitou a tipologia (litígio contratual ≠ LOA), mas removeu a referência do G1 que datava o episódio e não pôs outra no lugar. Hoje, "dezembro de 2016" não tem nenhuma fonte. O defeito do equipamento de perfuração, que o audit_v1 registrou **sem ano confirmado**, foi encaixado em 2016 sem evidência. A rastreabilidade afirma "mantido apenas o episódio verificado", mas o que foi verificado foi o fato, não o ano.

### P5 — F15: a contratada do ABIS e o número do contrato continuam não comprovados · A
> "...contratada originalmente em julho de 2021 via **Contrato nº 01/2021-DTI/PF** firmado com o **Consórcio IAFIS-IDEMIA** (formado por *Iafis Systems do Brasil Ltda.* e *IDEMIA*)" (passo 6; Ponto Cego 1; atores 14 e 30)

**Justificativa:**
1. O extrato do DOU de julho de 2021 registra como contratada a **IAFIS SYSTEMS DO BRASIL LTDA.**, pelo **Pregão nº 4/2020**, no valor de cerca de R$ 39,97 milhões e com vigência até 2024. Não aparece consórcio.
2. O número "Contrato nº 01/2021-DTI/PF" e a URL citada na Seção 5 não foram verificados.
3. A v2 fala do contrato no presente ("O Consórcio (...) opera o Contrato 01/2021") e omite que a vigência noticiada ia até 2024. A situação atual (prorrogação, novo contrato ou extinção) é desconhecida e não foi investigada, o que é coerente com a nova contratação de 2025.

A distinção Griaule × contratada, que era o núcleo do F15, foi feita. Mas a identificação da contratada continua errada ou sem prova, e o rótulo "Fato Documentado" no ator 30 não se sustenta.

### P6 — F14: definição da sigla SERMIL atribuída à PF sem fonte · B
> "**SERMIL — Sistema Eletrônico de Recrutamento Militar e Mobilização** (denominação oficial utilizada pela própria PF para a sigla SERMIL...)" (passo 6; rastreabilidade F14)

**Justificativa:** a FAQ da PF consultada diz só que o SINPA é integrado às bases do TSE e do "SERMIL", sem expandir a sigla. A afirmação de que a **PF** define o SERMIL dessa forma não foi demonstrada. A inclusão da DSM e das Juntas resolve a parte de atores omitidos.

### P7 — F18: a defesa do nome "Diretoria de Tecnologia da Informação e Inovação" é refutada · M · [REFUTADO]
> "...no organograma oficial (...) a diretoria intitula-se **'Diretoria de Tecnologia da Informação e Inovação — DTI'**, embora em minutas contratuais administrativas isoladas (como o Contrato nº 02/2025-DTI/PF) ainda apareça a **grafia legada** 'Diretoria de Tecnologia da Informação e Comunicação'" (Ponto Cego 1)

**Justificativa:** a v2 inverteu a cronologia.
- A estrutura regimental do MJSP (Anexo I do Decreto nº 11.348/2023, na redação alterada) lista, para a PF, a **"Diretoria de Tecnologia da Informação e Comunicação"** e define as competências dela.
- A Portaria DTI/PF nº 931, de 15/04/2026, é assinada pelo "Diretor de Tecnologia da Informação e **Comunicação**".
- O currículo oficial do atual diretor usa o mesmo nome.
- "Inovação" aparece em registros de 2019 a 2022 (agenda de 2022, extrato do DOU de 2021) e em rótulos de menu do portal ainda não atualizados.

Portanto, **"Comunicação" é o nome vigente e "Inovação" é o legado**. A matriz (ator 14) e as Seções 1, 2 e 5 usam o nome desatualizado, e chamar o nome vigente de "grafia legada" é erro.

### P8 — F20: desagregação incompleta; três novas fusões · M
> Ator 40: "**MPO/SOF, Junta de Execução Orçamentária (JEO — Fazenda, MPO e Casa Civil) e Congresso Nacional (CMO)**"; ator 41: "**Encarregado (...) e ANPD**"; ator 30: "**Sistema ABIS (...) Consórcio (...) / Concorrentes de Mercado (Griaule, Thales, etc.)**"

**Justificativa:** a v2 separou os quatro casos citados no F20, mas criou ou manteve outras fusões com o mesmo defeito.
- No **ator 40**, Executivo e Legislativo ficam numa linha só, embora tenham instrumentos distintos: remanejamento e limite de empenho de um lado, PLN de crédito do outro.
- No **ator 41**, o encarregado (função interna da PF) aparece junto da ANPD (autoridade reguladora externa).
- No **ator 30**, concorrentes de licitação são tratados como "atores da jornada", embora não participem da emissão.

### P9 — F21: o Regulamento Consular aparece com a data errada e com conteúdo não verificado · M
> "**Portaria MRE nº 428, de 16 de dezembro de 2022** (Aprova o Regulamento Consular Brasileiro — RCB, disciplinando o SCI, SCIng, e-Consular...)" (Seção 5); "Conforme o **Regulamento Consular Brasileiro (Portaria MRE nº 428/2022)** (...) a operação no exterior utiliza o SCI / SCIng com o módulo (...) SCEDV" (2.1-6)

**Justificativa:** a Portaria MRE nº 428 é de **15 de dezembro de 2022**, com vigência a partir de 29/12/2022. A afirmação de que o RCB "disciplina" SCI, SCIng, SCEDV e e-Consular não foi verificada no texto da portaria. O desdobramento da sigla "SCEDV" continua sem fonte. A demarcação da arquitetura interna como "em aberto" procede.

### P10 — F25: o prazo da entrega urgente continua sem fonte, apenas rotulado · M
> "Reduzido (informado em orientações de atendimento como **até 72h úteis a 5 dias úteis**...) `[Demarcado — F25 (a/c)]`" (Exceção 2)

**Justificativa:** o número continua sendo afirmado e atribuído a "orientações de atendimento" não identificadas. A rastreabilidade diz que o prazo foi "calibrado", mas calibrar exige fonte. A adoção do nome "Procedimento de Entrega Urgente" e o alerta de 2017 procedem. O prazo de **até 24 horas** do passaporte de emergência também segue sem fonte oficial (P43).

### P11 — F26: o artigo foi corrigido, mas o marco inicial dos 90 dias vem de fonte inadequada · M
> "...os passaportes não retirados em até **90 dias corridos (contados a partir do dia do atendimento presencial)**..." (passo 8); a rastreabilidade cita a "FAQ do MRE"

**Justificativa:** o Art. 29 está correto: o texto vigente prevê o cancelamento dos passaportes expedidos e não retirados em 90 dias. Mas **o decreto não define o marco inicial**, e a Carta de Serviços gov.br fala só em "prazo máximo de 90 dias corridos". A v2 fixou o marco com base na FAQ de um consulado (Barcelona), que é fonte do MRE para emissões no exterior e não regra da PF. O marco inicial continua aberto e deveria estar marcado como tal.

### P12 — F29: o shopping como cedente de pessoal continua sem fonte · B
> "...empregados terceirizados (contratados pelas Superintendências Regionais da PF **ou cedidos por administrações de shoppings**...)" (passo 5)

**Justificativa:** a v2 incluiu o Art. 42 (conferido: termos de cooperação ou convênios) e retirou da matriz o "custeio de atendentes". Mas o passo 5 mantém a cessão de pessoal pelos shoppings, que era justamente a parte sem fonte do F29. O conteúdo do Termo de Contrato nº 19/2022-SR/PF/SP continua sem nenhum trecho citado.

### P13 — F35: o ancoramento normativo do controle de impedimentos tem inciso errado e citação adulterada · A · [REFUTADO]
> "Conforme o **Art. 20, VI**, do Anexo ao Decreto nº 5.978/2006 e o Art. 3º, VIII, da IN nº 173/2020-DG/PF, é condição obrigatória *'não ser procurado nem impedido de obter passaporte ou de sair do país pela Justiça'*" (passo 6; atores 29 e 35)

**Justificativa:** no texto vigente, o **Art. 20, VI**, exige **submeter-se à coleta de dados biométricos**. A condição de impedimento está no **inciso VII**, cuja redação é "não ser procurado pela Justiça nem impedido judicialmente de obter passaporte". A frase entre aspas na v2 ("...ou de sair do país pela Justiça") **não corresponde ao texto do decreto**: é uma paráfrase apresentada como citação literal. O erro já existia na v1 (ator 26) e o audit_v1 não o detectou. A v2 o consolidou como base da correção do F35. O número "Art. 3º, VIII, da IN 173" não foi verificado.

### P14 — F35 (parte técnica): a demarcação do BNMP como "em aberto" é adequada · —
Sem falha. Registrado só para fechar o F35.

### P15 — F37: a IN 173/2020 foi declarada "comprovada" sem prova apresentada · M
> "**Defendida e comprovada** a data exata (21 de julho de 2020) e as duas URLs oficiais (...) além de incluídos os números dos artigos (Arts. 1º, 2º, 3º, 34, 40, II e 61)" (rastreabilidade F37)

**Justificativa:** só o **Art. 34** (reconhecimento de firma do genitor ausente) foi confirmado de forma independente, pela FAQ da PF. A data, os Arts. 3º (incisos II, III, IV e VIII), 40, II, e 61 (com § 3º) e as URLs não foram confirmados. A v2 não transcreve nenhum trecho da IN. "Comprovada" é um rótulo, não uma evidência. Como a IN agora sustenta dezenas de afirmações (passos 5 e 6, Exceções 2 e 6, atores 2, 3, 5, 10, 11, 25, 26 e 29), a falta de transcrição é material.

### P16 — F39: a recalibração da coluna 7 ficou incompleta · A
> Rastreabilidade F39: "Recalibradas **todas as linhas** da matriz com fontes primárias nominais"

**Justificativa:** várias linhas continuam como "Fato Documentado" com fonte genérica ou que não sustenta o papel atribuído:
- **12** (INI): "Estrutura do INI".
- **13** (DPA): "Portal Institucional e Estatísticas".
- **17** (terceirizadas): "Portal de Licitações", depois de removidos os contratos específicos.
- **20** (Serpro): um **domínio** e uma minuta de TR de 2019, que não provam a sustentação de SINPA, STI, PagTesouro e SIAFI.
- **40**: "registros de recomposição orçamentária".
- **44** (MPF): "representações durante a crise de 2017". O que está documentado é o Idec **pedindo** investigação ao MPF, não um ato do MPF.
- **45** (DPU) e **46** (AGU): só as leis orgânicas, que criam os órgãos mas não documentam atuação na jornada.
- **30** e **43**: acórdãos não verificados (P21).

Só 6 linhas foram rebaixadas.

### P17 — F46: URLs novas sem verificação · M
**Justificativa:** a v2 substituiu as URLs de imprensa que o audit_v1 questionou pelas que o próprio audit_v1 usou, e isso procede. Mas acrescentou URLs novas que ninguém verificou e que sustentam afirmações centrais: TCU (`btcu.../77657342`), Contrato 01/2021-DTI, PDF da IN 173, página da Portaria 927, "Quem é quem / órgãos centrais" e a revista de súmulas do STJ (cujo conteúdo não sustenta o que é afirmado, ver P23).

### P18 — F47: a fonte do MRE continua concentrada em um posto consular · B
**Justificativa:** a FGV foi substituída pelo RCB, o que procede, mas com a data errada (P9). Além disso, a única página consular citada (Barcelona) é usada para fixar uma regra da PF (P11).

### P19 — F22 · ver P29.

### P20 — F33 · ver P21.

---

## 3. Parte (b) — Falhas novas introduzidas pela v2

### P21 — Processo TC 011.515/2020-1 e Acórdãos 1.036/2024 e 299/2025 · A · [NÃO VERIFICADO]
> "...documentadas no **Processo TC 011.515/2020-1**, que resultou nos **Acórdãos nº 1.036/2024-TCU-Plenário** e **nº 299/2025-TCU-Plenário** (Relator Min. Aroldo Cedraz)" (Ponto Cego 1; 4.3; atores 30 e 43; rastreabilidade F33: "**Localizado** e substituído pelo número exato")

**Justificativa:** a busca não confirmou o processo, os acórdãos, o relator nem as partes. O audit_v1 recomendou **remover** a citação se ela não fosse confirmada. A v2 trocou um número não verificado por outro, declarou-o "localizado" e o usa como base de "Fato Documentado" em duas linhas da matriz. A cronologia é plausível (o pregão é de 2020), mas plausibilidade não é verificação. Isso precisa ser conferido na pesquisa de jurisprudência do TCU antes de qualquer uso.

### P22 — Citação literal inexistente atribuída ao decreto e à IN · A
Ver P13. É uma falha nova no sentido de que a v2 transformou uma referência a artigo em **citação entre aspas** que não corresponde ao texto legal.

### P23 — Súmula 412/STJ usada como fundamento da distinção entre taxa e tarifa para fins de CDC · A · [REFUTADO]
> "...diferencia-se o serviço público *ut singuli* remunerado por tarifa (sujeito ao CDC, conforme discutido nos **precedentes da Súmula 412/STJ**, como o *REsp 802.559/MS* e o *REsp 979.500/BA*)..." (Ponto Cego 3; Seção 5: "Súmula 412 e Precedentes sobre Distinção entre Taxa Tributária e Tarifa/Preço Público para fins de incidência do CDC")

**Justificativa:** a Súmula 412 do STJ trata de outro assunto: a ação de repetição de indébito de tarifas de água e esgoto está sujeita ao prazo prescricional do Código Civil. É uma súmula sobre **prazo prescricional**, não sobre a incidência do CDC nem sobre a distinção entre taxa e tarifa. Os precedentes dela não sustentam a tese.

Dos outros precedentes:
- O **REsp 625.144/SP** (Rel. Nancy Andrighi, 2006) trata de foro competente em ação contra tabelionato e é catalogado como afirmando que a atividade notarial não é regida pelo CDC. É uma analogia possível (emolumentos), mas a v2 o apresenta como precedente de "atos de polícia", o que ele não é.
- O **REsp 793.422/RS** não foi localizado.

O defeito do F45 (jurisprudência que não sustenta a tese) se repete, agora com aparência de verificação ("precedentes verificados").

### P24 — Nome da DTI invertido · M
Ver P7. Aparece como falha nova porque a v2 criou o argumento da "grafia legada", que não existia na v1.

### P25 — Contratada do ABIS e vigência · M
Ver P5. A afirmação "formado por *Iafis Systems do Brasil Ltda.* e *IDEMIA*" é nova na v2.

### P26 — Participantes e motivação da nova contratação do ABIS · M
> "...com participação de múltiplos *players* do mercado (IDEMIA, Griaule, Thales, NEC, Valid, **Akiyama**)"; "Em 2025, **visando substituir/evoluir o contrato e mitigar riscos de dependência tecnológica (*vendor lock-in*)**..." (Ponto Cego 1; 4.3)

**Justificativa:**
1. O relatório de respostas da audiência pública do ABIS lista as contribuições de Web, Griaule, IDEMIA, Innovatrics, Montreal, NEC, Positivo, Thales, Valid e IAFIS. **A Akiyama não está na lista**, e Innovatrics, Montreal e Positivo foram omitidas.
2. O ETP justifica a contratação pela **necessidade de adequar a capacidade do sistema atual** (de 50,2 milhões para 277,6 milhões de pessoas), não pela mitigação de *vendor lock-in*. A motivação foi atribuída à PF sem fonte. A tese de *lock-in* era uma inferência da v1 que agora aparece como objetivo declarado do órgão.

### P27 — "MP 902/2019 chegou a extinguir o monopólio" · B
> "a MP nº 902/2019 **chegou a extinguir** o monopólio legal da CMB sobre passaportes, mas perdeu a eficácia em 2020" (2.1-5)

**Justificativa:** a MP previa o fim da exclusividade, mas **mantinha até 2023** a exclusividade da CMB na fabricação de passaportes, segundo a Agência Câmara. Para passaportes, o monopólio não chegou a ser extinto durante a vigência da MP. A frase está imprecisa.

### P28 — Contagem de atores inconsistente · B
> "...os 6 grupos de atores omitidos foram incorporados (totalizando **48 atores**)" (Seção 3)

**Justificativa:** a tabela tem **47** linhas (1 a 47). Num documento que se apresenta como rastreável, a divergência entre o número anunciado e a tabela é falha de verificação interna.

### P29 — F22 "corrigido" com afirmações novas sem fonte · M
> "...o pedido online de restituição de taxa exige formalmente conta gov.br (**nível Prata ou Ouro**)"; "a exigência de autenticação gov.br (...) **oscila conforme atualizações da DTI/PF**, permanecendo o acesso primário baseado na tríade **CPF + Protocolo + Data de Nascimento com validação de CAPTCHA**" (passo 4)

**Justificativa:** a página oficial de devolução exige apenas "possuir uma conta gov.br", **sem especificar nível**. A tríade de acesso, o CAPTCHA e a "oscilação" não têm fonte. A afirmação de que a exigência "oscila conforme atualizações" é especulação que não pode ser auditada. A correção removeu um dado sem fonte e acrescentou três.

### P30 — Exigência de comparecimento presencial para menores na restituição · B · [NÃO VERIFICADO]
> "...(exigindo conta gov.br; **presencialmente quando o titular for menor de idade**...)" (Exceção 4)

**Justificativa:** a página oficial prevê a entrega presencial do requerimento pelo titular, pelo responsável pelo menor ou por procurador, e o pedido online por quem tem conta gov.br. Ela **não diz** que pedidos relativos a menores sejam obrigatoriamente presenciais. O ponto vem da v1 e o audit_v1 não o apontou. Está registrado aqui como remanescente.

### P31 — Ano do pedido de reajuste da taxa · B · [REFUTADO]
> "...razão pela qual a própria PF pleiteou ao governo federal **em 2025** a atualização inflacionária da taxa" (4.1, item 1)

**Justificativa:** reportagem de março de 2025 (Folhapress, publicada pelo Estado de Minas) informa que o tema foi levado ao MJSP "em março do ano passado", ou seja, **março de 2024**. Em 2025 houve a divulgação e o andamento do pedido, não o protocolo. Também é inferência dizer que o pedido é *consequência* da composição do financiamento: a PF justificou o pedido pela defasagem inflacionária.

### P32 — Controlador LGPD atribuído à DPA · B
> Ator 41: "Interage com a **DPA/PF (Controladora)**"

**Justificativa:** o extrato oficial do tratamento "Obter Passaporte" identifica como controlador e operador a **Polícia Federal**. A DPA aparece só no contato do encarregado. O próprio passo 6 da v2 diz que a PF é a controladora, o que contradiz a linha 41.

### P33 — Fundamentos atribuídos ao Idec e aos Procons sem fonte · B
> "...sustentando que a suspensão (...) violava o princípio da continuidade do serviço público (**Art. 22 do CDC e Art. 37 da CF/88**)"; "...além de os **Procons atuarem diretamente na repressão a sites falsos**" (Ponto Cego 3; ator 47 "autuações de Procons")

**Justificativa:** a fonte (JB, 2017) registra que o Idec invocou a CF e o CDC, sem citar artigos. Os artigos foram acrescentados pela v2. Nenhuma fonte citada mostra autuação de Procon contra sites de despachantes: o que está documentado é o **monitoramento pela PF** e os alertas da PF. O ator 47 marca essas autuações como "Fato Documentado".

### P34 — "Carteira de Identidade do Indígena (expedida pela FUNAI)" · M · [NÃO VERIFICADO]
> "...aceitam a **Carteira de Identidade do Indígena** (expedida pela **FUNAI**) como documento de identificação" (2.1-2; ator 5)

**Justificativa:** a defesa do F36 sobre o prazo de 1 ano das autorizações tem apoio razoável. Mas a afirmação sobre os indígenas é nova (a v1 falava em RANI), e nenhuma fonte foi conferida para ela. O documento administrativo que a FUNAI emite é tradicionalmente o RANI. A existência de uma "carteira de identidade" emitida pela FUNAI e aceita pela PF precisa de transcrição da Lista Oficial.

### P35 — Alerta contra sites falsos atribuído a "portal oficial do Vapt Vupt/PF" · B
> "...alertas oficiais do gov.br e dos postos conveniados (como o **portal oficial do Vapt Vupt/PF**)"; citação "NUNCA acesse sites de despachantes..." (4.2)

**Justificativa:** o Vapt Vupt é a rede estadual de atendimento de Goiás, não um portal da PF. A citação não foi localizada. Existe fonte melhor e não usada: a **página "Dúvidas" da própria PF**, que alerta para sites e anúncios que prometem assessoria, e a notícia de 2024 de que a PF passou a monitorar sites que cobram até R$ 149 pela intermediação.

### P36 — "Transportadoras protegidas por sigilo de segurança" · B
> "...os contratos específicos de transporte (...) têm **cláusulas de segurança sigilosas**" (passo 7; ator 36)

**Justificativa:** marcar o ponto como "em aberto" procede. Mas a v2 justifica a lacuna com outro fato sem fonte (a existência de sigilo contratual). O correto seria dizer apenas "não localizado em fonte pública".

### P37 — Seção 6 superestima o tratamento · M
**Justificativa:** a Seção 6 usa "comprovada" (F3, F37), "Localizado" (F33), "Recalibradas todas as linhas" (F39) e "Defendido com fonte primária" (F18) para itens que esta auditoria encontrou não verificados ou refutados (P7, P15, P16, P21). Uma tabela de rastreabilidade que declara mais do que o texto entrega compromete a confiança no conjunto.

---

## 4. Parte (c) — Pontos abertos e remanescentes

### P38 — Regra do BO para furto/roubo contra perda/extravio · M · [PARCIAL]
> "A PF dispensa o Boletim de Ocorrência (BO) para perda ou extravio simples (...) **Furto ou Roubo**: para ficar isento da taxa adicional (...) deve (...) apresentar BO (...) tipificando expressamente o crime" (Exceção 1)

**Justificativa:** a Carta de Serviços gov.br só diz que o passaporte anterior **válido extraviado ou perdido** gera a taxa adicional de R$ 257,25. Ela não trata expressamente de furto/roubo nem de BO. A exceção para furto/roubo com BO tem apoio só em fontes secundárias (guias de consumo), e a exigência de "tipificar expressamente" não tem fonte. A "dispensa do BO" para perda simples também não tem fonte primária. O audit_v1 não isolou esse ponto. Hoje ele sustenta o ator 28 como "Fato Documentado".

### P39 — Ato ministerial das hipóteses de emergência continua sem identificação · M
> "**Na regulamentação infralegal e orientação da PF:** detalham-se hipóteses como motivo de saúde grave (...)" (Exceção 2); ator 39 "define hipóteses emergenciais do Art. 13"

**Justificativa:** o Art. 13 remete a "ato dos Ministérios da Justiça ou das Relações Exteriores". A v2 afirma que o MJSP define as hipóteses, mas não identifica o ato (número, data). Também não menciona que o parágrafo único do Art. 13 permite dispensar exigências em situações excepcionais justificadas, o que é relevante para a autoridade policial que decide.

### P40 — Atuação recente do MPF e do controle sobre a taxa · M
**Justificativa:** o ator 44 se apoia em "representações durante a crise de 2017" (ver P16). Há registro na imprensa de procedimento da **Procuradoria** para apurar se a PF faz "cobrança abusiva" na emissão de passaportes, com resposta da PF citando o Decreto 5.978/2006 e a Portaria 927/2015. A data do procedimento não foi confirmada nesta auditoria. Se confirmado, é evidência mais forte e mais atual para o ator 44 e para a controvérsia do Ponto Cego 3 do que a usada.

### P41 — Incidentes de segurança e indisponibilidade do SINPA · M
**Justificativa:** a PF já suspendeu o agendamento online após uma **tentativa de invasão** dos sistemas, com o serviço fora do ar a partir de 17 de abril e retomado no dia 24, e orientou que urgências fossem enviadas com documentação a uma unidade emissora. O ano não foi confirmado nesta auditoria. A v2 discute bots e segurança (4.2, 4.3) sem registrar esse incidente documentado, que é um fluxo de exceção real da jornada (indisponibilidade do canal digital).

### P42 — Aditivos de 2025 ao Contrato 40/2022 · B · [NÃO VERIFICADO]
> "...sucessivamente prorrogado e aditivado em 2023, 2024, **2025** e 2026" (2.1-5)

**Justificativa:** os documentos encontrados mostram T1 e T2 (2023/2024) e aditivos de 2026 (nº 5/2026 e nº 7/2026). Nenhum aditivo de 2025 foi localizado. Pela numeração (um aditivo nº 5 em 2026), é provável que tenham existido os aditivos 3 e 4, mas isso precisa ser demonstrado.

### P43 — Prazo de até 24 horas do passaporte de emergência e restrições de aceitação · B · [NÃO VERIFICADO]
> "Em **até 24 horas** após a aprovação"; "podendo ser recusado por diversos países" (Exceção 2)

**Justificativa:** as duas afirmações vêm da v1 e não têm fonte oficial. O audit_v1 não as isolou. Ficam como abertas.

### P44 — Vigência atual do ABIS e transição para o novo contrato · B
**Justificativa:** como desdobramento de P5, a pesquisa não informa qual instrumento sustenta hoje (2026) o batimento biométrico do passaporte, nem em que fase está a contratação do ETP 19/2025. Para um mapeamento de atores "vigente", essa é uma lacuna de estado atual.

---

## 5. Recomendações para a v3

1. **Corrigir já:** P13/P22 (Art. 20, VII, com a citação literal correta), P23 (remover a Súmula 412 e os precedentes que não sustentam a tese), P7/P24 (adotar "Diretoria de Tecnologia da Informação e Comunicação"), P9 (data do RCB), P28 (contagem de atores), P31 (ano do pedido de reajuste) e P32 (controlador LGPD).
2. **Verificar ou remover:** P21 (processo e acórdãos do TCU), P5 (contratada e número do contrato do ABIS, pelo extrato do DOU), P34 (documento indígena), P15 (transcrever os artigos da IN 173 usados) e P29/P30 (regras de gov.br e de restituição).
3. **Rebaixar para "Inferência" ou "Não verificado"** as linhas listadas em P16 e as afirmações de P10, P11, P36, P38 e P43.
4. **Reescrever a Seção 6** com três estados honestos: corrigido e verificado, corrigido mas sem verificação independente, e em aberto. Não usar "comprovado" sem transcrição ou link conferível.
5. **Acrescentar:** o incidente de indisponibilidade do SINPA (P41), a atuação recente da Procuradoria (P40, após confirmar a data) e o estado atual do contrato do ABIS (P44).

---

## Fontes consultadas nesta auditoria

- Câmara dos Deputados — Decreto 5.978/2006, norma atualizada (Arts. 5º, 13, 20, 24, 29, 30, 33, 38 e 42): https://www2.camara.leg.br/legin/fed/decret/2006/decreto-5978-4-dezembro-2006-547404-normaatualizada-pe.html
- PF — Lista de documentação (CPF/Lei 14.534/2023; foto 5x7): https://www.gov.br/pf/pt-br/assuntos/passaporte/documentacao/lista
- PF — FAQ "Posso levar uma fotografia?": https://www.gov.br/pf/pt-br/assuntos/passaporte/ajuda/duvidas_/atendimento/atendimento-posso-levar-uma-fotografia
- PF — FAQ "Fotografia 5x7": https://www.gov.br/pf/pt-br/assuntos/passaporte/ajuda/duvidas_/documentacao/documentacao-fotografia-5x7-o-que-preciso
- PF — FAQ reconhecimento de firma (IN 173/2020, art. 34): https://www.gov.br/pf/pt-br/assuntos/passaporte/ajuda/duvidas_/documentacao/documentacao-reconhecimento-de-firma-em
- PF — Devolução da taxa: https://www.gov.br/pf/pt-br/assuntos/passaporte/documentacao/formulario/pagar-taxa/solicitar-devolucao
- PF — Pagar taxa: https://www.gov.br/pf/pt-br/assuntos/passaporte/documentacao/formulario/pagar-taxa
- PF — Dúvidas (alerta sobre sites de assessoria): https://www.gov.br/pf/pt-br/assuntos/passaporte/duvidas
- Carta de Serviços gov.br — Passaporte: https://www.gov.br/pt-br/servicos/passaporte
- LegJur — Decreto 11.348/2023 (estrutura do MJSP, DTI "e Comunicação"): https://www.legjur.com/legislacao/art/dec_00117592023-4
- PF — Portaria DTI/PF nº 931/2026: https://www.gov.br/pf/pt-br/assuntos/licitacoes/2026/diretoria-de-tecnologia-da-informacao-e-comunicacao-dti/inexigibilidade-de-licitacao/pregao-eletronico-no-90001-2026/portaria-integrantes-poc.pdf
- PF — Currículo do Diretor de TI e Comunicação: https://www.gov.br/pf/pt-br/composicao/diretoria-de-tecnologia-da-informacao-e-comunicacao-dti/dti/@@download
- DOU (via MJ) — extrato do contrato ABIS (Pregão 4/2020, IAFIS Systems do Brasil Ltda.): https://www.gov.br/mj/pt-br/acesso-a-informacao/licitacoes-e-contratos/contratos/2020/contrato-no-092-2020/publicacao_editora.pdf
- Tecnoblog — contrato ABIS (valor e vigência): https://tecnoblog.net/459233/pf-compra-sistema-para-guardar-biometria-de-50-milhoes-de-brasileiros/
- Participa+Brasil — Relatório de respostas da audiência pública do ABIS: https://www.gov.br/participamaisbrasil/blob/baixar/80672
- Participa+Brasil — ETP do ABIS (justificativa por capacidade): https://www.gov.br/participamaisbrasil/blob/baixar/74149
- STJ — Súmula 412: https://stj.jus.br/publicacaoinstitucional/index.php/sumstj/article/download/5322/5446
- IRIB — REsp 625.144/SP: https://www.irib.org.br/?p=65646
- Cebraspe (cópia) — Portaria MRE nº 428, de 15/12/2022 (RCB): https://cdn.cebraspe.org.br/concursos/mre_23/arquivos/REGULAMENTO_CONSULAR_BRASILEIRO.PDF
- PF — Decisão citando a Portaria MJ 218/2018: https://www.gov.br/pf/pt-br/assuntos/imigracao/lei-de-migracao/publicacoes/rio-de-janeiro/sei_08460-004920_2023_96.pdf
- Agência Câmara — MP 902/2019: https://www.camara.leg.br/noticias/610012-MEDIDA-PROVISORIA-ACABA-COM-MONOPOLIO-DA-CASA-DA-MOEDA-SOBRE-DINHEIRO-E-PASSAPORTE
- Estado de Minas — pedido de reajuste da taxa (protocolo em 2024): https://em.com.br/nacional/2025/03/7082770-pf-pede-e-governo-lula-pode-aumentar-taxa-de-emissao-de-passaporte.html
- O Povo — PF monitora sites intermediários (2024): https://www.opovo.com.br/noticias/brasil/2024/09/22/pf-monitora-sites-que-cobram-taxa-para-intermediar-obtencao-de-passaporte.html
- Tecnoblog — suspensão do agendamento após tentativa de invasão: https://tecnoblog.net/noticias/pf-tira-do-ar-site-de-emissao-de-passaporte-apos-suspeita-de-ataque/
- Mais Goiás — Procuradoria apura cobrança na emissão de passaportes: https://www.maisgoias.com.br/brasil/procuradoria-investiga-se-pf-faz-cobranca-abusiva-para-emitir-passaportes/
- JB — Idec (2017): https://www.jb.com.br/pais/noticias/2017/06/28/amp/idec-diz-que-suspensao-de-emissao-de-passaportes-e-ilegal.html
