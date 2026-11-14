# A — Meta-prompt

**Assistente usado:** Google Gemini (com Deep Research ativado)
**Objetivo:** pedir ao assistente que **elabore um prompt** de deep research sobre os atores da jornada de emissão de passaporte. O prompt gerado é então usado na Parte B.

---

## Meta-prompt enviado

```
Sou aluno de mestrado em Governo Digital e Transformação de Serviços Públicos
(IDP). Estou fazendo um exercício cujo produto final é um MAPA DE ATORES da
jornada de um serviço público. O serviço escolhido é a EMISSÃO DE PASSAPORTE
COMUM NO BRASIL, prestada pela Polícia Federal (PF), vinculada ao Ministério
da Justiça e Segurança Pública. Analiso o canal digital (requerimento e
agendamento pelo portal gov.br/PF) mais o atendimento presencial nos postos
de emissão.

Não quero que você faça a pesquisa agora. Quero que você ELABORE UM PROMPT
para um assistente de deep research fazer essa pesquisa. O resultado da
pesquisa vai servir de contexto para uma etapa posterior: uma entrevista
adversarial com um agente de IA (skill "grill-me"), em que vou decidir quais
atores entram no mapa final e qual o papel de cada um. Por isso a pesquisa
precisa ser rica em contexto e em evidências, e não uma lista genérica.

Contexto que já tenho (são hipóteses minhas, a pesquisa deve confirmar ou
refutar cada uma, com fonte):
- A jornada típica: preenchimento do formulário online → emissão e pagamento
  da GRU (taxa) → agendamento → comparecimento ao posto (conferência de
  documentos, coleta de biometria e foto) → produção da caderneta →
  retirada pessoal.
- Atores que suspeito existirem: o cidadão requerente (e casos especiais:
  menores e seus responsáveis legais, pessoas com deficiência, idosos,
  passaporte de emergência); servidores da PF no atendimento; o sistema
  informatizado de passaportes da PF; a plataforma gov.br; a rede bancária
  que recebe a GRU; a Casa da Moeda do Brasil, que fabrica a caderneta;
  postos de atendimento conveniados (por exemplo, em parceria com governos
  estaduais e municipais); o Ministério das Relações Exteriores (passaporte
  emitido no exterior); órgãos de controle (TCU, CGU); normas técnicas
  internacionais (ICAO); e órgãos que verificam pendências (Justiça
  Eleitoral, serviço militar, mandados judiciais).
- Tenho dúvidas sobre fornecedores de tecnologia, sobre quem normatiza o
  processo (decretos, instruções normativas) e sobre canais de reclamação
  (ouvidoria, Fala.BR, Procon, Consumidor.gov).

O prompt que você elaborar deve pedir ao assistente de pesquisa que:
1. Descreva a jornada ponta a ponta, etapa por etapa, incluindo exceções
   (perda/roubo, urgência, recusa, remarcação, falta de caderneta).
2. Identifique TODOS os atores — de linha de frente, de retaguarda,
   normativos, de controle, fornecedores e "invisíveis" — classificando cada
   um por tipo (pessoa, órgão, sistema, empresa, norma) e por papel
   (demandante, executor, aprovador, fornecedor, regulador, controlador,
   informado).
3. Indique, para cada ator, em que etapa entra e sai da jornada e com quem
   interage.
4. Cite fontes verificáveis com URL (legislação, portal da PF, gov.br,
   relatórios do TCU/CGU, notícias de veículos reconhecidos), separando o que
   é fato documentado do que é inferência.
5. Aponte lacunas e controvérsias (por exemplo, falta de cadernetas,
   suspensões de emissão, filas de agendamento, problemas de sistema).
6. Entregue em formato estruturado (seções + tabela de atores) e em
   português.

Defina no prompt uma persona adequada (por exemplo, pesquisador de
gestão pública e serviços digitais), os critérios de sucesso e o formato de
saída. Devolva apenas o prompt final, pronto para eu colar.
```

---

## Prompt gerado pelo assistente

Prompt devolvido pelo Gemini (copiado integralmente) e usado em B1.1:

````markdown
# Papel e Persona
Você é um pesquisador sênior em Administração Pública, Governo Digital e Design de Serviços Públicos, com profundo conhecimento da arquitetura institucional, normativa e tecnológica do Estado brasileiro. Sua especialidade é o mapeamento de ecossistemas de serviços públicos (Service Blueprint e Stakeholder Mapping) baseado em evidências documentais, auditorias governamentais e legislação.

# Objetivo da Pesquisa
Conduzir uma pesquisa aprofundada (*Deep Research*) para mapear exaustivamente os atores, sistemas, normas e fluxos que compõem a jornada de **Emissão de Passaporte Comum no Brasil**, prestada pela Polícia Federal (PF), abrangendo o canal digital (requerimento e agendamento via portal gov.br / sistema da PF) e o atendimento presencial nos postos de emissão e retirada[cite: 1].

# Contexto de Uso do Relatório
O relatório gerado não será um texto meramente descritivo: ele servirá de base probatória e insumo técnico para uma etapa posterior de arguição adversarial (*"grill-me"*), na qual serão decididos quais atores entram na modelagem final do Mapa de Atores e qual o peso e papel de cada um[cite: 1]. Portanto, a pesquisa deve ser densa em contexto, precisa nas nomenclaturas oficiais (nomes exatos de sistemas, órgãos, contratos e normas) e rigorosa na citação de fontes[cite: 1].

# Escopo de Investigação e Validação de Hipóteses

## 1. Validação de Hipóteses Iniciais (Confirmar, Refutar ou Detalhar com Fontes)
Investigue e valide documentalmente o papel exato dos seguintes elementos na jornada[cite: 1]:
- **Fluxo base:** preenchimento do formulário online → emissão e pagamento da GRU (ou PagTesouro/Pix/cartão) → agendamento → comparecimento ao posto (conferência documental, coleta biométrica e facial) → produção da caderneta → entrega/retirada pessoal[cite: 1].
- **Perfis de demandantes e regras específicas:** cidadão requerente padrão, menores de idade (e regras de autorização de responsáveis legais), pessoas com deficiência, idosos, indígenas e requerentes de passaporte de emergência ou de urgência[cite: 1].
- **Operação e Atendimento:** servidores de carreira da PF (delegados, agentes, papiloscopistas, escrivães, servidores administrativos), terceirizados e postos de atendimento conveniados (Acordos de Cooperação Técnica com governos estaduais/municipais, como Poupatempo, Na Hora, SAC, Vapt Vupt, e postos em shoppings)[cite: 1].
- **Infraestrutura Tecnológica e Pagamentos:** sistema informatizado de passaportes da PF (identificar nome oficial, ex.: SINPA ou sucessor), plataforma gov.br (níveis de conta, integração de login e avaliação), PagTesouro / Siafi / Secretaria do Tesouro Nacional (STN) e rede bancária arrecadadora[cite: 1].
- **Cadeia Produtiva e Logística:** Casa da Moeda do Brasil (CMB) na fabricação e personalização das cadernetas, fornecedores de insumos/chips e operadores logísticos de transporte seguro até os postos[cite: 1].
- **Fronteira Institucional:** competência do Ministério das Relações Exteriores (MRE / rede consular / sistema e-Consular) na emissão no exterior e como se articula com a base da PF[cite: 1].
- **Interoperabilidade e Verificação de Pendências (Backstage):** cruzamento de dados ou exigência documental junto à Justiça Eleitoral (TSE), Serviço Militar (Ministério da Defesa/SERMILMOB), Receita Federal (CPF), bancos de mandados de prisão e restrições judiciais (BNMP/CNJ, SINIC, STI-MAR)[cite: 1].
- **Regulação e Controle:** normas técnicas internacionais (ICAO — Doc 9303), órgãos de controle interno e externo (CGU e TCU)[cite: 1].

## 2. Investigação de Pontos Cegos (Lacunas a Preencher)
Pesquise especificamente para descobrir e documentar[cite: 1]:
- **Fornecedores de Tecnologia e Biometria:** quem desenvolve, mantém e opera os sistemas de emissão, agendamento, AFIS/ABIS (identificação biométrica), equipamentos de captura ao vivo (*live scan*) e infraestrutura de dados da PF (ex.: Serpro, Dataprev, empresas privadas de TI e biometria contratadas por licitação)[cite: 1].
- **Arcabouço Normativo:** quais leis, decretos (ex.: Decreto nº 5.978/2006 e atualizações), portarias do MJSP e Instruções Normativas da Diretoria-Geral ou Diretoria de Polícia de Imigração (DIREX/CGPI) da PF regem o processo atualmente[cite: 1].
- **Canais de Reclamação, Ouvidoria e Judicialização:** papel da Ouvidoria da PF, Plataforma Fala.BR (CGU), Ministério Público Federal (MPF) e Defensoria Pública da União (DPU), além de esclarecer com base jurídica se Procon e Consumidor.gov.br têm competência sobre esse serviço público específico (taxa/poder de polícia vs. relação de consumo)[cite: 1].

# Entregáveis Obrigatórios e Estrutura do Relatório

Organize sua resposta rigorosamente nas seguintes seções, em português[cite: 1]:

### Seção 1: Jornada Ponta a Ponta e Fluxos de Exceção
Descreva a jornada cronológica completa (Pré-serviço, Solicitação Digital, Pagamento, Agendamento, Atendimento Presencial, Backstage de Validação e Produção, Entrega e Pós-serviço)[cite: 1].
Inclua subseções detalhando como o fluxo e os atores mudam nas seguintes **exceções**[cite: 1]:
1. Extravio, perda, furto ou roubo de passaporte válido anterior[cite: 1];
2. Pedido de urgência vs. Passaporte de Emergência[cite: 1];
3. Recusa/indeferimento administrativo ou impedimento judicial de saída do país[cite: 1];
4. Reagendamento, não comparecimento (*no-show*) e pedidos de restituição de GRU[cite: 1];
5. Suspensão da emissão por falta de cadernetas ou restrição orçamentária[cite: 1];
6. Inconsistências de dados civis/biométricos ou caderneta com defeito de fabricação.

### Seção 2: Validação das Hipóteses e Descobertas sobre as Dúvidas
Apresente a confirmação, refutação ou correção de nuance para cada uma das hipóteses listadas no escopo, seguida das respostas detalhadas para as três dúvidas (fornecedores de TI, normativos e canais de reclamação)[cite: 1].

### Seção 3: Matriz Completa de Atores (Tabela Estruturada)
Construa uma tabela Markdown exaustiva contendo TODOS os atores identificados (linha de frente, retaguarda/backstage, normativos, de controle, fornecedores, parceiros e "invisíveis")[cite: 1]. A tabela deve conter obrigatoriamente as seguintes colunas[cite: 1]:
1. **Nome do Ator** (nome oficial do órgão, cargo, perfil de usuário, sistema ou norma)[cite: 1];
2. **Camada de Visibilidade** (Linha de Frente / Retaguarda / Normativo / Controle / Fornecedor / Invisível)[cite: 1];
3. **Tipo** (`Pessoa`, `Órgão/Entidade`, `Sistema/Plataforma`, `Empresa/Fornecedor`, `Norma/Padrão`)[cite: 1];
4. **Papel na Jornada** (`Demandante`, `Executor`, `Aprovador`, `Fornecedor`, `Regulador`, `Controlador`, `Informado` — *justifique brevemente se acumular mais de um*)[cite: 1];
5. **Etapa de Entrada e Etapa de Saída** na jornada[cite: 1];
6. **Interações Diretas** (com quais outros atores troca dados, documentos, recursos financeiros ou comandos)[cite: 1];
7. **Status da Evidência** (`Fato Documentado` ou `Inferência Lógica`) + **Fonte/URL**[cite: 1].

### Seção 4: Controvérsias, Gargalos Históricos e Pontos Críticos de Auditoria
Mapeie os principais problemas estruturais, crises recentes e achados de auditoria (TCU/CGU) sobre o serviço, incluindo[cite: 1]:
- Crises de desabastecimento de cadernetas e embates orçamentários entre PF, MJSP, Tesouro e Casa da Moeda (ex.: eventos de 2017, 2022 e posteriores)[cite: 1];
- Filas virtuais de agendamento, ação de "despachantes/robôs" no agendamento e vulnerabilidades de sistema[cite: 1];
- Instabilidades tecnológicas, falhas de integração de bancos de dados e gargalos de pessoal terceirizado vs. efetivo nos postos[cite: 1].

### Seção 5: Referências Verificáveis
Lista consolidada de todas as fontes consultadas com links diretos (URLs completas) para: legislação (Planalto/Imprensa Nacional), portal gov.br e PF, acórdãos do TCU, relatórios da CGU, editais/contratos públicos e reportagens de veículos de imprensa reconhecidos[cite: 1].

# Critérios de Qualidade e Restrições
- **Rigor Evidencial:** Nunca apresente uma suposição como fato[cite: 1]. Se a arquitetura interna de um sistema da PF ou um contrato específico não for público, rotule explicitamente como `[Inferência baseada em...]` e explique a lógica[cite: 1].
- **Granularidade:** Não agrupe atores distintos sob rótulos vagos como "Governo Federal" ou "Bancos"[cite: 1]. Especifique a unidade, secretaria, sistema ou instituição responsável.
- **Fidelidade ao Processo Real:** Diferencie claramente o que o portal oficial promete ao cidadão do que ocorre nos bastidores operacionais e nos momentos de crise documentados pela imprensa e pelos órgãos de controle[cite: 1].
````
