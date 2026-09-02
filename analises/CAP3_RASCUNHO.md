# 3 ADOÇÃO DECLARADA E PERFORMANCE REAL: EVIDÊNCIAS DO PARADOXO

Os capítulos anteriores estabeleceram o terreno teórico e metodológico deste trabalho. O Capítulo 1 percorreu a trajetória histórica dos frameworks ágeis, desde o Manifesto (2001) até a convergência entre Scrum, Kanban, SAFe, LeSS e DevOps em torno dos mesmos valores centrais. O Capítulo 2 descreveu os procedimentos adotados para investigar como esses frameworks são implementados na prática. Este capítulo desloca o foco da teoria para os dados: apresenta o panorama de adoção declarada, introduz critérios objetivos de performance e coloca os dois em confronto. O resultado desse confronto é o fenômeno que estrutura todo o argumento deste trabalho.

---

## 3.1 O Panorama de Adoção Declarada

A penetração de metodologias ágeis no mercado de tecnologia atingiu, na segunda metade da década de 2020, níveis que tornam difícil falar de "alternativa" ou "tendência". Segundo o relatório Agilidade na América Latina (NTT DATA, 2024), 93% das organizações latino-americanas declaram utilizar Scrum como metodologia de trabalho, e 82% declaram utilizar Kanban. O State of Agile Report (DIGITAL.AI, 2024) confirma a tendência em escala global, com 91% de adoção de Scrum entre as organizações pesquisadas. São números que, à primeira leitura, sugerem consolidação de uma transformação já realizada.

A leitura mais cuidadosa, porém, exige uma distinção que os próprios relatórios nem sempre tornam explícita: a diferença entre declaração de adoção e qualidade de implementação. Quando quase todas as organizações de um setor respondem afirmativamente à mesma pergunta ("Sua organização utiliza Scrum?"), o dado resultante mede penetração de vocabulário tanto quanto penetração de prática. A questão metodologicamente relevante não é se as organizações "usam Scrum", mas o que essa afirmação representa em termos de transformação concreta.

O próprio relatório NTT DATA (2024) oferece um dado que permite calibrar a afirmação anterior. Quando perguntadas não sobre adoção mas sobre maturidade, as respostas mudam de figura: apenas 38% das organizações relatam ter estabelecido uma cultura ágil de forma consistente. A diferença de 55 pontos percentuais entre os que declaram adoção (93%) e os que relatam maturidade cultural (38%) não é um resultado esperado para uma transformação bem-sucedida. Em qualquer modelo de difusão de inovação, espera-se que adoção preceda maturidade, e que o gap entre os dois diminua à medida que as organizações acumulam experiência. O que os dados sugerem, ao contrário, é um gap que persiste mesmo entre organizações que declaram usar Scrum há anos.

Um segundo dado do mesmo relatório reforça esse ponto: 75% das organizações pesquisadas reconhecem que a transformação da cultura organizacional é pré-condição para que metodologias ágeis funcionem. Combinado com o dado de que apenas 38% acreditam ter construído essa cultura, o resultado é um gap de 37 pontos percentuais entre quem sabe que cultura importa e quem consegue implementá-la. As organizações não estão ignorando o problema por falta de informação. Elas o reconhecem e, ainda assim, não conseguem superá-lo.

Esse conjunto de dados instala o paradoxo central deste trabalho: a adoção declarada é alta, a consciência sobre o que é necessário para que a adoção funcione é razoavelmente disseminada, mas a implementação efetiva permanece minoritária. Antes de investigar os mecanismos que sustentam esse paradoxo, é necessário estabelecer se ele é real, e não apenas um artefato de como as perguntas foram formuladas. Para isso, é preciso substituir a declaração de adoção por um critério independente de performance.

---

## 3.2 Métricas DORA: Um Critério Independente de Performance

A principal limitação dos dados de adoção declarada é que eles dependem da autopercepção das organizações. Uma organização que acredita estar praticando Scrum pode estar fazendo algo consideravelmente diferente do que o Scrum Guide prescreve, sem que isso apareça nas respostas ao questionário. Para contornar essa limitação, é necessário um critério externo à declaração: dados que meçam o resultado da implementação, não a implementação em si.

As métricas DORA (DevOps Research and Assessment) respondem a essa necessidade. Desenvolvidas ao longo de quatro anos com uma amostra de mais de 23.000 profissionais de tecnologia em organizações de diferentes portes e setores, as métricas DORA consistem em quatro indicadores objetivos da capacidade de entrega de software (FORSGREN; HUMBLE; KIM, 2018):

a) frequência de deploy: com que regularidade a organização publica novas versões de software em produção;

b) lead time for changes: o tempo entre a solicitação de uma alteração e sua disponibilidade ao usuário final;

c) time to restore service: o tempo necessário para recuperar o serviço após uma falha;

d) change failure rate: a proporção de mudanças que resultam em falha ou degradação de serviço.

Com base nessas métricas, as organizações são classificadas em quatro níveis de performance: elite, alta, média e baixa. O Quadro 1 apresenta os benchmarks correspondentes a cada nível, conforme reportado pelo relatório DORA/Google Cloud (2024).

**Quadro 1 - Benchmarks de performance por nível DORA**

| Métrica | Elite | Alta | Média | Baixa |
|---|---|---|---|---|
| Frequência de deploy | Múltiplas vezes por dia | Semanal a mensal | Mensal a semestral | Menos de uma vez por semestre |
| Lead time for changes | Menos de 1 hora | 1 dia a 1 semana | 1 semana a 1 mês | 1 a 6 meses |
| Time to restore service | Menos de 1 hora | Menos de 1 dia | 1 dia a 1 semana | Mais de 1 semana |
| Change failure rate | 0% a 15% | 16% a 25% | 26% a 45% | 46% a 60% |
| Distribuição das organizações | ~18% | ~22% | ~25% | ~35% |

Fonte: DORA/Google Cloud (2024); Forsgren, Humble e Kim (2018).

O Quadro 1 revela, já na última linha, o dado mais relevante para este trabalho: apenas 18% das organizações pesquisadas operam no nível elite de performance. Outros 22% operam no nível alto. Isso significa que aproximadamente 60% das organizações operam nos níveis médio ou baixo, onde a frequência de deploy é inferior a uma vez por mês e o lead time ultrapassa uma semana.

A métrica de lead time merece atenção especial. O Scrum Guide (SCHWABER; SUTHERLAND, 2020) prescreve Sprints com duração máxima de um mês, ao final das quais deve ser produzido um incremento de software pronto para uso. Em uma organização que pratica Scrum como prescrito, o lead time deveria ser, no máximo, da ordem das Sprints: dias a semanas. Lead times de meses contradizem diretamente o modelo de entrega iterativa e incremental que Scrum operacionaliza.

Os dados do relatório NTT DATA (2024) para a América Latina mostram que 36% das organizações pesquisadas operam com lead time superior a 30 dias. Combinado com o dado de que 93% dessas mesmas organizações declaram usar Scrum, tem-se uma incompatibilidade empírica: ou essas organizações não estão praticando Scrum como o Scrum Guide define, ou estão praticando de uma forma que não produz o efeito que o framework promete produzir. Em qualquer dos dois casos, o resultado é o mesmo: a declaração de adoção não se traduz em performance compatível com o que a metodologia visa entregar.

### 3.2.1 Distribuição de Adotantes de Scrum por Quartil DORA

O cruzamento entre declaração de adoção de Scrum e quartil DORA de performance oferece a evidência mais direta do paradoxo que este capítulo documenta. Se Scrum garantisse, por si mesmo, os resultados que promete, seria esperado que organizações que o declaram se concentrassem nos quartis superiores de performance. Os dados sugerem o contrário: adotantes declarados de Scrum aparecem distribuídos ao longo de todos os quartis DORA, sem concentração nos superiores (DORA/GOOGLE CLOUD, 2024; NTT DATA, 2024).

A implicação é direta: o framework declarado não é preditor confiável de performance. Organizações com Scrum declarado podem estar no quartil elite ou no quartil baixo. O que diferencia umas das outras não é a presença ou ausência do framework, mas algo que o framework declarado não captura. Identificar esse algo é a tarefa do Capítulo 4. Por ora, basta registrar empiricamente que a correlação entre declaração de adoção e performance mensurável é fraca.

---

## 3.3 Barreiras Estruturais e a Natureza do Problema

O confronto entre alta adoção declarada e performance heterogênea levanta uma questão: por que as organizações que declaram Scrum não colhem a performance que Scrum promete? O Capítulo 4 tratará dos mecanismos causais em detalhe. Este capítulo se limita a registrar o que as próprias organizações identificam como impedimento.

O relatório NTT DATA (2024) mapeou as principais barreiras que as organizações pesquisadas apontam como obstáculos à transformação ágil efetiva. Os resultados estão sintetizados no Quadro 2.

**Quadro 2 - Barreiras à transformação ágil identificadas pelas organizações**

| Barreira | % das organizações que apontam |
|---|---|
| Cultura organizacional inadequada | 72% |
| Estilo de liderança inadequado | 60% |
| Treinamento e desenvolvimento insuficientes | 47% |
| Resistência à mudança | 41% |
| Falta de alinhamento estratégico | 38% |
| Recursos insuficientes | 32% |

Fonte: NTT DATA (2024).

O Quadro 2 tem uma característica que merece registro explícito: nenhuma das barreiras listadas é de natureza técnica. Não há menção a ausência de ferramentas, incompatibilidade de stack tecnológico ou limitações de infraestrutura. Todas as barreiras identificadas pelas próprias organizações residem no domínio organizacional: cultura, liderança, resistência à mudança, alinhamento estratégico. São exatamente os elementos que o Scrum Guide não prescreve e que nenhum framework de processo pode, por si mesmo, criar.

Esse dado adquire peso histórico adicional quando contrastado com os resultados do Chaos Report de 1994 (STANDISH GROUP, 1994). Os principais fatores de falha identificados há trinta anos foram: falta de envolvimento do usuário (12,4% dos casos), suporte executivo insuficiente (9,3%) e requisitos incompletos associados à ausência de liderança adequada. Traduzidos para o vocabulário de 2024, esses fatores correspondem, respectivamente, a cultura organizacional inadequada, estilo de liderança inadequado e falta de alinhamento estratégico. Os nomes mudam; a natureza do problema, não.

Essa estabilidade histórica das barreiras tem uma implicação direta para o argumento deste trabalho: se os obstáculos à entrega bem-sucedida de software permanecem os mesmos ao longo de três décadas de evolução de frameworks, a hipótese de que adicionar um novo framework resolve o problema parece insuficiente. Os frameworks evoluíram; as barreiras, não. O que muda com Scrum, Kanban, SAFe ou DevOps é o modo de organizar o trabalho, não as condições organizacionais que determinam se esse modo será efetivo ou não. Quando essas condições não se transformam, o resultado é o que os dados documentam: alta adoção declarada de frameworks com baixa correspondência em performance real.

### 3.3.1 Adoção de Fachada como Fenômeno Nomeável

O conjunto de dados analisado neste capítulo permite nomear o fenômeno que documentam. A situação em que uma organização realiza formalmente as práticas prescritas por frameworks ágeis, tornando-as visíveis nos processos e na comunicação institucional, sem transformar simultaneamente as estruturas organizacionais subjacentes que determinam como o trabalho é realmente realizado, pode ser denominada "agilidade de fachada".

O conceito não implica má-fé. A organização pode genuinamente acreditar que está praticando Scrum quando realiza Daily Scrums, mantém um backlog priorizado, executa Sprints com revisões e retrospectivas. Esses elementos constituem a dimensão visível e formalizada do framework. O que frequentemente não é transformado são as condições que deveriam tornar esses ritos funcionais: a autonomia real dos times para tomar decisões, a redistribuição de autoridade que desfaz a necessidade de múltiplas camadas de aprovação, o redesenho de sistemas de incentivo que ainda recompensam comportamentos incompatíveis com colaboração e entrega iterativa.

Quando os ritos existem mas as condições não são criadas, o resultado observável nos dados é o registrado neste capítulo: lead time que permanece alto apesar do Scrum declarado, satisfação com a transformação que diminui com o tempo em vez de aumentar, e um gap entre o número de organizações que declaram adoção e o número que colhe performance mensurável compatível com essa adoção.

O Quadro 3 sintetiza o contraste entre os indicadores de agilidade declarada e os de agilidade verificável, conforme os dados disponíveis.

**Quadro 3 - Agilidade declarada versus agilidade verificável: síntese dos dados**

| Dimensão | Indicador | Dado | Fonte |
|---|---|---|---|
| Declarada | Adoção de Scrum | 93% | NTT DATA (2024) |
| Declarada | Consciência sobre cultura ágil | 75% | NTT DATA (2024) |
| Verificável | Cultura ágil implementada consistentemente | 38% | NTT DATA (2024) |
| Verificável | Performance elite (DORA) | ~18% | DORA/Google Cloud (2024) |
| Verificável | Lead time superior a 30 dias | 36% | NTT DATA (2024) |
| Gap | Adoção declarada vs. maturidade cultural | 55 pp | NTT DATA (2024) |
| Gap | Consciência sobre cultura vs. implementação efetiva | 37 pp | NTT DATA (2024) |

Fonte: elaborado pela autora com base em NTT DATA (2024) e DORA/Google Cloud (2024).

O Quadro 3 organiza em uma única leitura o argumento central deste capítulo: há adoção declarada maciça e consciência razoavelmente disseminada sobre o que é necessário para que essa adoção funcione, mas os indicadores verificáveis de performance mostram que a transformação efetiva permanece minoritária. O gap entre a coluna "declarada" e a coluna "verificável" é o espaço empírico em que o fenômeno da agilidade de fachada opera.

A pergunta que esse espaço abre não pode ser respondida com mais dados de adoção: é uma pergunta sobre mecanismos. Por que organizações que sabem que cultura importa não conseguem transformá-la? Por que a presença dos ritos ágeis não gera, por si mesma, as condições que tornariam esses ritos eficazes? O Capítulo 4 retoma essa pergunta a partir dos mecanismos que a literatura acadêmica e os dados disponíveis permitem identificar.
