# TCC_CONTEXT.md — Contexto do Trabalho de Conclusão de Curso

> Documento de inicialização para sessões no Claude Code.
> Atualizado em: setembro de 2026.
> Repositório: `brunaventorim/tcc`, branch `dev`.

---

## Identificação

- **Curso:** TADS — Tecnologia em Análise e Desenvolvimento de Sistemas
- **Instituição:** UERJ
- **Tipo de pesquisa:** Bibliográfica e documental (Gil 2002 / Lakatos & Marconi)
  - Natureza: aplicada
  - Abordagem: qualitativa
  - Objetivo: explicativo

---

## Tema e Pergunta Central

**Tema:** Estudo das metodologias de desenvolvimento de software mais adotadas.

**Subtítulo (em avaliação):** Agilidade de fachada — a lacuna entre adoção declarada de metodologias ágeis e os resultados esperados.

**Pergunta central:** Por que o gap entre adotar metodologias ágeis e alcançar seus resultados persiste, mesmo após a maturação dos frameworks e a publicação de evidências de desempenho?

**Argumento central:** O problema não está nos frameworks, mas em falhas de implementação enraizadas na cultura organizacional e no comportamento da liderança — o que o trabalho nomeia como "agilidade de fachada".

---

## Estrutura do Trabalho

| Capítulo    | Conteúdo                                                      |
|-------------|---------------------------------------------------------------|
| Introdução  | Contextualização, justificativa, objetivos, estrutura         |
| Cap. 1      | Fundamentos teóricos: paradigma pré-ágil → Manifesto → frameworks → ecossistema |
| Cap. 2      | Metodologia da pesquisa                                       |
| Cap. 3      | Instalação do paradoxo via dados empíricos                    |
| Cap. 4      | Explicação interpretativa do paradoxo (por que ele persiste)  |
| Cap. 5      | Conclusão: limitações, pesquisas futuras, implicações práticas |

**Distinção crítica Cap. 3 / Cap. 4:** O Cap. 3 instala o paradoxo com dados; o Cap. 4 explica por que ele persiste em nível interpretativo. Confundi-los produz um capítulo que repete em vez de avançar.

**Status atual:** Capítulos 1 e 2 escritos e validados pela orientadora. Caps. 3, 4 e 5 a escrever.

---

## Normas de Formatação ABNT/UERJ

- Fonte: Arial 12pt
- Espaçamento: 1,5
- Recuo de parágrafo: 1,25 cm (uniforme, sem exceções)
- Alinhamento: justificado
- Margens: 3/3/2/2 cm, papel A4
- Citações longas (bloco): recuo de 4 cm

---

## Regras de Escrita

### Proibições absolutas

- **Sem travessões (—) em nenhum ponto do documento.** Substituir por vírgula, ponto-e-vírgula, dois-pontos ou reestruturar a frase. Tratado como marcador de escrita por IA.
- **Vocabulário banido:** "internalização", "paradoxalmente", "marcadamente", "de forma inequívoca", "nessa lacuna", "cabe destacar", "é importante salientar", "evidencia-se que", "no que tange". Qualquer expressão que soe a preenchimento de parágrafo.
- **Títulos de seção:** formato nominal descritivo. Nunca assertivo ("A agilidade falha porque...") e nunca em forma de pergunta. Complemento por dois-pontos é permitido.
- **PMBOK é um guia, não uma metodologia.** Enquadrar assim de forma consistente em todo o texto.

### Parágrafos e frases

- **Aberturas de parágrafo variadas.** Nenhum conector lógico deve se repetir em parágrafos consecutivos. Proibido abrir dois parágrafos seguidos com "Dessa forma", "Portanto", "Nesse sentido", "Assim sendo" ou equivalentes. Quando o parágrafo não precisar de conector, começar direto com o argumento.
- **Frases curtas a médias.** Quando uma frase ultrapassar três linhas, revisar: provavelmente dá para dividir em duas ou eliminar um trecho redundante.
- **Sem repetição de palavra-chave no mesmo parágrafo.** Se o termo precisar aparecer mais de uma vez, usar sinônimo ou referenciar pronominalmente na segunda ocorrência.
- **Um argumento por parágrafo.** A frase de abertura enuncia; o restante desenvolve ou evidencia. Parágrafo que faz duas coisas deve ser dividido.

### Voz analítica

- **Fontes sustentam o argumento; não são o argumento.** O texto não narra o que cada fonte diz em sequência. A autora interpreta, confronta ou sintetiza; a fonte é convocada para sustentar uma posição já enunciada.
- **Proibido o padrão "Segundo X, Y. Segundo Z, W."** Dois dados de fontes diferentes no mesmo bloco devem ser mediados por análise própria ou conectados por uma relação explícita (contraste, confirmação, extensão).
- **Dados e percentuais precisam de enquadramento.** Não soltar número sem dizer o que ele significa para o argumento. Ex.: não "72% apontam cultura organizacional como barreira"; mas "a recorrência desse dado em diferentes estudos sugere que o obstáculo não é pontual".

### Citações e dados

- **Citação direta só quando o enunciado exato importa.** Para conceitos, definições e argumentos, parafrasear com atribuição. Citação literal reservada para definições fundadoras (ex.: Manifesto Ágil) ou formulações cujo enunciado preciso é relevante para a análise.
- **Dado quantitativo exige fonte e ano na mesma frase ou na imediatamente seguinte.** Nunca deixar percentual solto sem referência clara.
- **Fontes em diálogo, não em fila.** Quando dois estudos apontam na mesma direção, articular a convergência. Quando divergem, nomear a tensão. Evitar empilhar citações que dizem a mesma coisa sem mediação analítica.
- **Gray literature (NTT DATA, BAI, State of Agile, JCURV) precisa de enquadramento de fonte** na primeira vez que aparecer em cada capítulo: tipo de estudo, amostra, ano. Não tratar como se tivesse o mesmo peso de artigo indexado.

---

## Mapeamento Completo de Fontes

### Fontes confirmadas com placement definido

#### Chaos Report (Standish Group, 1994)
- **Arquivo:** `chaosreport.pdf`
- **Dados centrais:** 16,2% sucesso, 31,1% cancelados, 189% custo médio
- **Placement:**
  - Introdução: menção sem dados
  - 1.1: desenvolvimento completo como evidência da crise pré-ágil
  - 2.2 §1: fontes primárias
- **Argumento a destacar:** O relatório já identificava falhas culturais/organizacionais (falta de envolvimento do usuário, falta de suporte executivo) — não técnicas. Isso antecipa diretamente a tese central e deve ser explicitado na seção 1.1.

#### Varajão & Trigo (2024, ACM Queue)
- **Arquivo:** `3687999.pdf`
- **Placement:**
  - 1.1: uma linha de nuance à metodologia do Chaos Report
  - 2.1: reforça viés de desejabilidade em dados autodeclarados
  - 2.2 §2: literatura acadêmica indexada
  - 4.2: **uso principal** — quando critérios de sucesso se expandem além do triângulo de ferro, taxas de sucesso sobem; demonstra empiricamente que o critério de medição define o que se enxerga (mecanismo central do paradoxo)

#### NTT DATA 2024 — Agilidade na América Latina
- **Arquivo:** `NTTDATA_Agilidade_na_America_Latina_2024.pdf`
- **Dados confirmados:**
  - 93% de adoção do Scrum
  - 75% declaram ter cultura ágil; 38% dizem que ela está consolidada (gap de 37 p.p.)
  - 72% apontam cultura organizacional como barreira
  - 60% apontam estilo de liderança como barreira
  - Dados de lead time: páginas 13 e 45
- **Placement:** Cap. 3 (dados centrais do paradoxo)
- **Atenção:** A estatística de 45% do SAFe pertence ao State of Agile/Digital.ai — não ao NTT DATA.

#### NTT DATA 2022 — Agilidade na América Latina
- **Arquivo:** `NTT_DATA_Agilidad2022_PT.pdf`
- **Status:** INCLUIR — argumento longitudinal
- **Dados principais:**
  - 72% barreira cultura organizacional
  - 69% estilo de liderança
  - 66% silos entre áreas
  - 62% processos burocráticos
  - 61% resistência à mudança
  - 90% adotam agilidade em TI/Software Development
  - Benefícios: adaptação à mudança (40% excelente), experiência do cliente (28%), engajamento de equipes (27%)
  - Redução de custos: benefício que menos melhora — consistente em todas as edições
- **Placement:** Cap. 3 — usar em par com NTT DATA 2024 para demonstrar que as barreiras persistem sem variação estrutural entre 2022 e 2024. Argumento longitudinal, não duplicação de snapshot.

#### DORA — ROI of DevOps Transformation (2020)
- **Arquivo:** `theroiofdevopstransformationgoogleclouddora_1.pdf`
- **Placement:** Cap. 3 (desempenho de entrega como critério analítico)

#### DORA — Accelerate State of DevOps 2022
- **Arquivo:** `2022doraacceleratestateodevopsreportportbrbma.pdf`
- **Placement:** 4.3 — cultura generativa / tipologia de Westrum: cultura → performance organizacional

#### DORA — Accelerate State of DevOps 2024
- **Arquivos:** `2024doraacceleratestateodevopsreportptbr_3160.pdf` e `2024doraacceleratestateodevopsreportptbr_361117.pdf`
- **Placement:** 1.3.2 + Cap. 4 (atualização da base de evidências DORA)
- **Atenção:** Os dois arquivos provavelmente correspondem a partes ou versões distintas — verificar sobreposição antes de usar.

#### DORA 2025 — State of AI-Assisted Software Development (PT-BR)
- **Arquivo:** `2025_abridged_state_of_ai_assisted_software_development_ptbr_1.pdf`
- **Placement: Conclusão apenas** — observação prospectiva sobre IA e agilidade
- **Risco de escopo:** introduzir IA como variável pode atrair escrutínio da banca. Manter restrito à conclusão, como horizonte futuro.

#### State of Agile 17ª Edição (Digital.ai)
- **Arquivo:** `RESA17thAnnualStateOfAgileReport_1.pdf`
- **Placement:** Cap. 3 — dados de adoção + contraste waterfall (28% ainda usam Waterfall; proporção maior em organizações grandes)

#### State of Agile 18ª Edição (Digital.ai)
- **Arquivo:** `Digitalai18thStateofAgile_1.pdf`
- **Placement:** Cap. 3 — adoção atual
- **Dado corrigido:** 45% de adoção do SAFe → atribuição correta é Digital.ai, não NTT DATA

#### Agile Manifesto (Beck et al., 2001)
- **Placement:** Cap. 1

#### Scrum Guide 2010 (Schwaber & Sutherland)
- **Arquivo:** `ScrumGuide2010.pdf`
- **Placement:** Cap. 1

#### Scrum Guide 2020 (PT-BR)
- **Arquivo:** `2020ScrumGuidePortugueseBR3_0_1.pdf`
- **Placement:** Cap. 1

#### Kanban (Anderson, 2010)
- **Placement:** Cap. 1

#### Sutherland & Sutherland (2014)
- **Placement:** Cap. 1 — citação indireta; paráfrase sem número de página (sem citação verbatim)

#### Forsgren, Humble & Kim — Accelerate (2018)
- **Arquivo:** `1803_05969v1.pdf`
- **Placement:** Cap. 1 + Cap. 4

#### Adkins (2010)
- **Status:** PENDENTE — decidir com orientadora: citar no corpo ou remover das referências

---

### Fontes novas avaliadas em setembro de 2026

#### 3rd State of Agile Culture Report (JCURV / Agile Business Consortium, 2023)
- **Arquivo:** `3rdStateofAgileCultureReport.pdf`
- **Descrição:** 23 páginas, +1.000 respondentes, metodologia com implicit reaction times (IRT) — captura reação implícita além da resposta declarada, reduzindo viés de desejabilidade
- **Status:** INCLUIR — validar nível de evidência com orientadora antes de finalizar
- **Dados principais:**
  - Apenas 10% dos líderes demonstram qualidades de liderança pós-heroica
  - 71% dos funcionários não acreditam que seus líderes conseguem responder a mudanças de mercado
  - 44% se sentem empoderados pelos seus líderes
  - 41% têm clareza sobre a direção da organização e da equipe
  - 42% recebem treinamento ou coaching em agilidade
  - Capacidade de feedback caiu de 72% (2022) para 38% (2023)
  - Liderança ágil percebida: 47% em 2023, vs. 56% pré-pandemia (estagnada)
  - Correlação 0,82: liderança pós-heroica e cultura ágil forte
  - Correlação 0,86: liderança pós-heroica e capacidade de resposta ao mercado
  - Cultura ágil forte associada a aumento de 277% na performance comercial
- **Placement:** Cap. 4 — liderança como barreira estrutural explicativa do paradoxo
- **Nota de fonte:** Gray literature de setor (parceria entre consultoria JCURV, Agile Business Consortium e empresa de neurotech Truthsayers). Nível similar ao NTT DATA — não é literatura acadêmica indexada. Enquadrar como tal.

#### Business Agility Report 2023 (Business Agility Institute — BAI)
- **Arquivo:** `202311_BAIBusinessAgilityReport2023.pdf`
- **Descrição:** 6ª edição, 26 páginas, 215 organizações
- **Status:** OPCIONAL — não prioritário; entra apenas se a decisão for incluir o BAI como fonte
- **Dados principais:**
  - Business Agility Index global caiu pela primeira vez em 5 anos (de 5,0 para 4,4 em 2023)
  - Colaboração caiu 8%; capacidades estratégicas caíram 6%
  - Liderança e gestão: desafio #1 pelo segundo ano consecutivo
  - Resistência à mudança: desafio perene desde a 1ª edição (2018)
  - Governança: "última área a se transformar"
  - Apenas 18% das organizações transformando múltiplas funções (queda em relação a anos anteriores)
- **Placement potencial:** Cap. 4 — argumento de persistência longitudinal dos desafios (liderança + resistência à mudança documentadas desde 2018)
- **Restrição de uso:** Não citar o índice numérico isoladamente — requer explicação do framework BAI que não vale o espaço disponível

#### Business Agility Report 2025 (Business Agility Institute — BAI)
- **Arquivo:** `2025BusinessAgilityReport_121225.pdf`
- **Descrição:** 8ª edição, 30 páginas, 244 organizações
- **Status:** INCLUIR SE BAI ENTRAR — mais forte dos dois para o argumento do TCC
- **Dados principais:**
  - Apenas 22% das organizações declaram que governança apoia a agilidade
  - "Barreiras à business agility são culturais e sistêmicas, não de processo" (formulação direta)
  - Líderes verbalmente apoiam agilidade enquanto comportamentos de comando e controle a contradizem (articulação explícita da fachada)
  - 86% relatam benefícios tangíveis da agilidade
  - IA: organizações com alta maturidade ágil adotam IA com maior eficácia (score 6,6 vs. 4,2 para baixa maturidade)
  - 58% das organizações passaram por reestruturação significativa nos últimos 12 meses
- **Placement potencial:**
  - Cap. 4: barreiras sistêmicas + liderança contraditória
  - Conclusão (opcional): relação entre maturidade ágil e adoção de IA — complementar ao DORA 2025
- **Nota:** O BAI não tem o peso institucional do DORA ou Digital.ai. Decisão de inclusão pendente de avaliação da orientadora.

---

### Fontes excluídas

| Fonte                        | Motivo                                                               |
|------------------------------|----------------------------------------------------------------------|
| Lean Inception (Caroli, 2017)| Excluída — não deve aparecer em corpo, lista de fontes ou referências |
| McKinsey                     | Excluída — gray literature sem rigor metodológico adequado           |
| Prasanth, Valsala & Soomro   | Excluída — tema tangencial, indexação insuficiente                   |
| Agile Trends PRE25 eBooks    | Pendente — conclusão apenas se aprovado pela orientadora             |

---

## Questões Abertas — Validar com Orientadora

1. **Escopo do objetivo "d":** implicações práticas em um TCC de pesquisa bibliográfica
2. **Parágrafo não citado no Cap. 2** que se apoia em Varajão & Trigo sem nomeá-los
3. **Adkins (2010):** citar no corpo ou remover das referências
4. **Fontes BAI:** nível de evidência aceitável para o trabalho?
5. **3rd State of Agile Culture Report:** nível de evidência aceitável?
6. **Agile Trends PRE25 eBooks:** aprovado para conclusão?
7. **DORA 2025:** dado de AI em IA-assisted dev pode entrar na conclusão como gancho prospectivo?

---

## Correções Pré-Entrega Identificadas

1. Estatística de 45% do SAFe estava atribuída ao NTT DATA — corrigir para State of Agile/Digital.ai
2. Datas de acesso incompletas nas referências
3. Conflito de nomenclatura dos relatórios DORA — dois relatórios distintos (ROI of DevOps 2020 e Accelerate State of DevOps 2024) com anos inconsistentes entre corpo e referências; separar entradas e corrigir anos
4. Adkins (2010) aparece nas referências mas nunca é citado no corpo — remover ou citar
5. Expressões de escrita IA a revisar: "marcadamente", "de forma inequívoca", "nessa lacuna"

---

## Arquivos no Repositório

| Arquivo                                                          | Descrição                        |
|------------------------------------------------------------------|----------------------------------|
| `TCC_CONTEXT.md`                                                 | Este documento                   |
| `fluxograma-tcc.html`                                            | Fluxograma visual da estrutura do TCC |
| `chaosreport.pdf`                                                | Chaos Report 1994                |
| `NTTDATA_Agilidade_na_America_Latina_2024.pdf`                   | NTT DATA 2024                    |
| `NTT_DATA_Agilidad2022_PT.pdf`                                   | NTT DATA 2022                    |
| `theroiofdevopstransformationgoogleclouddora_1.pdf`              | DORA ROI of DevOps 2020          |
| `2022doraacceleratestateodevopsreportportbrbma.pdf`              | DORA Accelerate 2022             |
| `2024doraacceleratestateodevopsreportptbr_3160.pdf`              | DORA Accelerate 2024 (parte 1)   |
| `2024doraacceleratestateodevopsreportptbr_361117.pdf`            | DORA Accelerate 2024 (parte 2)   |
| `2025_abridged_state_of_ai_assisted_software_development_ptbr_1.pdf` | DORA 2025 AI-assisted dev    |
| `RESA17thAnnualStateOfAgileReport_1.pdf`                         | State of Agile 17ª ed.           |
| `Digitalai18thStateofAgile_1.pdf`                                | State of Agile 18ª ed.           |
| `2020ScrumGuidePortugueseBR3_0_1.pdf`                            | Scrum Guide 2020 PT-BR           |
| `ScrumGuide2010.pdf`                                             | Scrum Guide 2010                 |
| `1803_05969v1.pdf`                                               | Forsgren et al. — Accelerate (2018) |
| `3687999.pdf`                                                    | Varajão & Trigo (2024, ACM Queue)|
| `3rdStateofAgileCultureReport.pdf`                               | 3rd State of Agile Culture Report (2023) |
| `202311_BAIBusinessAgilityReport2023.pdf`                        | BAI Business Agility Report 2023 |
| `2025BusinessAgilityReport_121225.pdf`                           | BAI Business Agility Report 2025 |
| `ANEXO_1__Manual_para_elaborac_a_o_de_TCC__Orientac_o_es_Gerais.pdf` | Manual UERJ               |
| `Guia_Editorial_para_Produc_a_o_de_um_TCC_com_Escrita_Acade_mica_Autoral.pdf` | Guia editorial |

---

## Acesso ao Documento no Google Drive

- **Introdução + sumário (validados):** fileId `1ZXtqoQnntRs4ajkuSU5FsLMr1tl2pbiAalLTkMauDEA`
- **Cap. 1 (working document):** fileId `1CvJtdhL9zixDFxU7oPakoHJdaymbfNHhhmCYkpPB2jE`
- **Documento principal (sessões anteriores):** fileId `1pm_6QqpIVYCyY6d0QSezN6SDXJZ4occsq2K0xh1GYAI`

Leitura via `Google Drive:read_file_content` com o fileId. O conector suporta leitura e criação, não edição direta. Fluxo de edição: ler → modificar → criar novo arquivo.

---

## Notas de Infraestrutura

- GitHub raw URLs bloqueadas por política de rede — upload direto via interface do chat é o caminho confiável
- Arquivos PDF do projeto armazenados como ZIPs no repositório — ler via `zipfile` em Python com ordenação numérica (`key=lambda x: int(x.replace('.txt',''))`) para os arquivos `.txt` de página
- Geração de `.docx`: biblioteca Node.js `docx`
- Verificação de PDF: `soffice --headless --convert-to pdf` + `pdftoppm -jpeg` para inspeção visual
