# Roteiro de Apresentação: Defesa de TCC

**Duração Total Sugerida:** 15-20 minutos  
**Formato:** Apresentação com slides (PDF recomendado)  
**Público:** Banca examinadora + colegas

---

## 📋 Estrutura da Apresentação

### **SLIDE 1: Título** (30 segundos)

```
╔════════════════════════════════════════════════════════╗
║  ESTUDO DAS METODOLOGIAS DE                           ║
║  DESENVOLVIMENTO DE SOFTWARE MAIS ADOTADAS            ║
║                                                        ║
║  Bruna Ventorim de Oliveira                           ║
║  UERJ - Tecnologia em Análise e Desenvolvimento       ║
║  2026                                                  ║
╚════════════════════════════════════════════════════════╝
```

**Fala Introdutória:**
> "Boa [manhã/tarde]. Meu trabalho analisa por que, apesar de 71% das empresas adotarem metodologias ágeis, apenas 47% reportam satisfação com os resultados. Isso é o paradoxo central que guia minha pesquisa."

---

### **SLIDE 2: Motivação** (1 minuto)

**Titulo:** "Por Que Isso Importa?"

**Conteúdo Visual:**
```
1995: Standish Chaos Report
├─ 31% de projetos CANCELADOS
├─ 52% custam 189% acima do orçamento
└─ Apenas 16% on-time & on-budget

2025: Estado Atual
├─ Métodos ágeis em 71% das empresas
├─ MAS apenas 47% satisfeitos
└─ Pergunta: Qual é o gap?
```

**Fala:**
> "O Standish Report de 1995 mostrou que software era 'caótico'. Isso motivou a criação do Manifesto Ágil em 2001. Hoje, 30 anos depois, metodologias ágeis dominam o mercado. Mas... os números de satisfação não acompanharam a adoção. Isso levanta uma pergunta fundamental: **qual é a barreira real para implementação bem-sucedida?**"

---

### **SLIDE 3: Questão de Pesquisa** (30 segundos)

**Titulo:** "Pergunta Central"

**Conteúdo:**
```
"A adoção de metodologias ágeis é limitada por:
 A) A metodologia em si?
 B) A infraestrutura técnica?
 C) A cultura organizacional?
```

**Fala:**
> "Minha pesquisa busca responder: **qual é o verdadeiro limitante?** É a escolha de Scrum vs. Kanban? É a falta de boas ferramentas? Ou é algo mais profundo?"

---

### **SLIDE 4-5: Evolução Histórica** (1.5 minutos)

**Slide 4 - Timeline Visual**
```
┌─────────────┬──────────────┬─────────────┬──────────────┐
│  1970-2000  │   2001-2010  │  2010-2020  │   2025+      │
├─────────────┼──────────────┼─────────────┼──────────────┤
│ WATERFALL   │    AGILE     │ AGILE       │ AGENTIC      │
│ PMBOK       │ Scrum        │ SCALE       │ AI           │
│ Rígido      │ Manifesto    │ SAFe/LeSS   │ DevOps       │
│ Sequencial  │ Iterativo    │ DevOps      │ Autônomo     │
│ Documentado │ Adaptável    │ Contínuo    │ Inteligente  │
└─────────────┴──────────────┴─────────────┴──────────────┘

Taxa de Sucesso:
Era Waterfall:     16% on-time/on-budget
Hoje (Agile):      32% on-time/on-budget (2x melhor ✓)
Elite Performers:  95%+ (com DevOps + Agile)
```

**Slide 5 - O que Mudou?**
```
De:
├─ Requisitos definidos no início
├─ Fases executadas em sequência
├─ Entrega no final do projeto
└─ Adaptar = falha

Para:
├─ Requisitos emergentes
├─ Iterações curtas (2-4 semanas)
├─ Entrega contínua
└─ Adaptar = sucesso
```

**Fala:**
> "Em 30 anos, mudamos radicalmente. De planejamento completo upfront, passamos para iteração contínua. Números mostram melhoria real: de 16% para 32% de projetos bem-sucedidos. Mas há um limite aparente: não melhoramos mais após 2015."

---

### **SLIDE 6: O Paradoxo da Adoção** (1.5 minutos)

**Titulo:** "O Grande Paradoxo"

**Gráfico 1:** Adoção vs. Satisfação
```
Adoção (quem usa):
├─ 71% declaram usar Agile
├─ 63% usam Scrum
├─ 71% praticam DevOps
└─ 26% adotam SAFe

Satisfação (quem está feliz):
├─ 47% "altamente satisfeitos"
├─ 72% em equipes pequenas (Scrum puro)
├─ 34% em grandes empresas (SAFe)
└─ Gap: 24% - 37%
```

**Gráfico 2:** O Efeito Tamanho
```
Satisfação Scrum por Tamanho de Equipe:
4-10 pessoas:   83% satisfação ✓✓✓
11-20 pessoas:  65% satisfação ✓✓
50+ pessoas:    34% satisfação ✓
500+ pessoas:   22% satisfação ✗
```

**Fala:**
> "Scrum foi desenhado para equipes pequenas, ágeis. Funciona lindamente em 8-10 pessoas. Mas quando você tenta escalar para 500 pessoas? Satisfação cai de 83% para 22%. **Isso não é culpa de Scrum. É culpa de tentar usar uma ferramenta de equipe em um contexto de empresa.**"

---

### **SLIDE 7-8: Análise Profunda - Métricas DORA** (2 minutos)

**Slide 7 - Métricas Que Importam**

**Titulo:** "O Que Realmente Separa Elite de Low Performers?"

```
                Elite    High    Medium   Low
Deployments:    10+/dia  1x/sem  1x/mês   Raro
Lead Time:      <1h      1-7d    1-4w     >1mês
MTTR:           <1h      1-24h   1-7d     >1sem
Change Fail:    0-15%    16-30%  31-45%   >46%

ROI Estimado (Elite vs. Low):
├─ Redução de downtime: 15M+/ano
├─ Features entregues: 3-5x mais
└─ Burnout: 40% menos
```

**Slide 8 - A Descoberta: Cultura > Metodologia**

**Titulo:** "Por Que Alguns Performam Melhor?"

**Análise DORA 2024-2025:**
```
Fator #1: Qualidade da Plataforma Interna (45% importância)
├─ Self-service para equipes
├─ CI/CD automatizado
└─ Deploy sem coordenação

Fator #2: Liderança Ágil (30% importância)
├─ Autonomia real (não micro-management)
├─ Suporte executivo genuine
└─ Foco em outcomes, não horas

Fator #3: Segurança Psicológica (25% importância)
├─ Permissão para falhar
├─ Transparência de problemas
└─ Aprendizado contínuo

---

Descoberta Chave: METODOLOGIA < 10% de importância!
```

**Fala:**
> "DORA estudou 39.000 engenheiros globalmente. Descoberta surpreendente: **a escolha entre Scrum ou Kanban não importa muito**. O que importa é: plataforma técnica, qualidade de liderança e segurança psicológica. Frameworks são apenas 10% da equação."

---

### **SLIDE 9: O Fenômeno 'Agilidade de Fachada'** (1.5 minutos)

**Titulo:** "Por Que Adoção Alta ≠ Satisfação Alta?"

**Exemplo Visual:**
```
Cenário A: "Agilidade Fake"
Daily Stand-up → Realizado 5x/semana ✓
└─ Mas ninguém implementa as decisões
Sprints → Executado a cada 2 semanas ✓
└─ Mas velocidade não muda
Retrospectivas → Realizado ao final ✓
└─ Mas ações do sprint anterior ignoradas

Resultado: Processo vazio de significado
Status: "Formalmente ágil, culturalmente tradicional"

---

Cenário B: "Agilidade Real"
Daily Stand-up → Coordena decisões que são EXECUTADAS
Sprints → Objetivo é APRENDER e ADAPTAR
Retrospectivas → AÇÕES são IMPLEMENTADAS no sprint seguinte

Resultado: Framework e cultura alinhados
```

**Fala:**
> "Temos um termo para isso: **'Cargo Cult Agile'** ou 'Agilidade de fachada'. É quando uma organização segue os rituais de Agile mas mantém a mentalidade tradicional. Daily stand-ups acontecem, mas ninguém se sente autorizado a tomar decisões. Sprints correm, mas a velocidade não muda porque ainda há burocracia embaixo. É como pintar um carro e esperar que dirija diferente."

---

### **SLIDE 10: Contexto Brasil/LATAM** (1 minuto)

**Titulo:** "Desafios Específicos da Região"

**Dados NTT DATA 2024 (295 respondentes):**
```
Barreiras para Adoção Ágil:

Global vs. América Latina:
┌──────────────────────────────┬────────┬──────────┐
│ Barreira                     │ LATAM  │ Global   │
├──────────────────────────────┼────────┼──────────┤
│ Resistência à mudança        │  67%   │   43%    │
│ Treinamento inadequado       │  47%   │   29%    │
│ Liderança não familiarizada  │  38%   │   22%    │
└──────────────────────────────┴────────┴──────────┘

Conclusão: LATAM está 5-10 anos atrás em maturidade
```

**Oportunidade:**
```
Mas: Podemos aprender dos erros globais e pular gerações!
```

**Fala:**
> "Brasil e América Latina mostram barreiras similares à Europa nos anos 2010. A diferença é que **temos a chance de aprender**, não de repetir os erros. Sabemos o que funciona. A pergunta é: vamos implementar?"

---

### **SLIDE 11: Conclusões** (1.5 minutos)

**Titulo:** "Achados Principais"

**Tese:**
```
┌──────────────────────────────────────────────────────┐
│ A adoção de metodologias ágeis no Brasil não é      │
│ limitada pela metodologia em si, mas pela cultura   │
│ organizacional e pela qualidade da engenharia       │
│ interna.                                             │
└──────────────────────────────────────────────────────┘
```

**Suportado por:**
1. **Standish Report:** Frameworks sozinhos não resolvem (era 16%, hoje 32%)
2. **DORA:** Plataforma interna > Metodologia (45% vs. <10%)
3. **State of Agile:** Satisfação em equipes ≠ satisfação em empresas (83% vs. 22%)
4. **NTT DATA:** Barreira #1 não é técnica, é **cultural** (67%)
5. **Amy Edmondson:** Segurança psicológica é 25% da equação

**Fala:**
> "Três anos de pesquisa apontam para uma conclusão clara: **Scrum vs. Kanban é a pergunta errada**. A pergunta certa é: 'Temos uma cultura que permite falhar e aprender? Temos uma plataforma técnica que dá autonomia? Temos lideranças que confiam?'. Se a resposta é 'sim' para esses, qualquer framework funciona. Se é 'não', nenhum funciona."

---

### **SLIDE 12: Recomendações Práticas** (1 minuto)

**Titulo:** "Para Líderes e Organizações"

```
SE seu time tem <15 pessoas:
└─ Implemente Scrum puro
   └─ Risco: Baixo | Retorno: Alto

SE sua empresa tem 50-500 pessoas:
└─ Implemente Scrum + Kanban (híbrido) + CI/CD básico
   └─ Risco: Médio | Retorno: Médio-Alto

SE sua empresa tem 500+ pessoas:
└─ Implemente SAFe + Engenharia de Plataforma forte
   └─ Risco: Alto | Retorno: Depende de cultura

EM TODOS OS CASOS:
├─ Invista em liderança ágil (mentoría, coaching)
├─ Crie segurança psicológica (permissão para falhar)
└─ Meça com DORA metrics (não velocity de Scrum)
```

**Fala:**
> "Não existe 'one size fits all'. Mas existem princípios. E o primeiro é: não invista em frameworks até que a cultura esteja pronta. É como comprar um software de projeto antes de ensinar seu time a tomar decisão."

---

### **SLIDE 13: Oportunidades Futuras** (30 segundos)

**Titulo:** "O Horizonte: 'Agentic AI' (Quarta Onda)"

```
2025+: IA não é apenas assistente (Copilot)
├─ Agentic Planning: IA propõe arquitetura
├─ Agentic Testing: IA gera testes automaticamente
└─ Agentic Delivery: IA decide quando fazer deploy

Implicação: Agile precisa evoluir (framework foi feito para humanos)

Oportunidade Brasil: Implementar Agile BEM primeiro,
depois evoluir com IA (não fazer reverse order)
```

**Fala:**
> "Quarta onda de desenvolvimento está nascendo: IA autônoma. Mas essa conversa é para outros TCCs. Meu ponto é: **Brasil tem chance de acertar na base**."

---

### **SLIDE 14: Perguntas?** (Aberto)

```
╔════════════════════════════════════════════════════════╗
║            OBRIGADA PELA ATENÇÃO!                      ║
║                                                        ║
║            Perguntas?                                  ║
║                                                        ║
║            Contato & Referências:                      ║
║            GitHub: /brunaventorim/claude-1/            ║
║            Email: brunatoledoventorim@gmail.com        ║
╚════════════════════════════════════════════════════════╝
```

---

## 💡 DICAS DE APRESENTAÇÃO

### Linguagem Corporal
- **Nos primeiros 2 minutos:** Contar história (não só dados)
- **No meio:** Mostrar dados com confiança
- **No final:** Conclusão clara e pergunta aberta

### Tom de Voz
- Começa apaixonado (por quê importa)
- Meio: técnico mas acessível
- Final: convincente mas humble

### Timing
```
0:00-1:00    Motivação (por quê estudar isso?)
1:00-3:00    Contexto histórico (Waterfall → Agile → Hoje)
3:00-5:00    Paradoxo (71% vs. 47%)
5:00-8:00    Análise (DORA, State of Agile, NTT DATA)
8:00-10:00   Conclusões (o que aprendemos)
10:00-12:00  Recomendações práticas
12:00-15:00  Perguntas da banca

Total: 15 minutos
```

### Antecipação de Perguntas

**P: "Mas Scrum funciona em muitas empresas grandes!"**
> R: "Verdade! Scrum funciona, mas com Kanban no meio, DevOps por baixo, e liderança ágil por cima. Puro Scrum em 500 pessoas? Aí dificuldades aparecem."

**P: "Sua conclusão é que cultura importa mais que metodologia?"**
> R: "Exatamente. Metodologia é 10%. Cultura é 90%. E se você tem boa cultura, pode até não usar framework formal - o trabalho sai bom mesmo assim."

**P: "Qual framework recomenda para Brasil?"**
> R: "Depende. Mas em geral: comece com Scrum puro (simples), adicione Kanban conforme escala, e sempre com CI/CD. E investir em liderança é tão importante quanto investir em software."

---

## 📊 MATERIAIS VISUAIS RECOMENDADOS

### Prepare os seguintes em PDF/PPT:

1. ✅ **Dashboard.html** (gráficos interativos - abrir no navegador durante apresentação)
2. ✅ **Slides de texto** (backup em caso de internet falhar)
3. ✅ **Tabelas comparativas** (do documento de referências)
4. ✅ **Timeline visual** (evolução das metodologias)
5. ✅ **Gráficos DORA** (Elite vs. Low performers)

---

## 🎯 Ao Final da Apresentação

**Mensagem que você quer deixar:**

> "Metodologias ágeis funcionam. Mas não porque o nome é 'ágil'. Funcionam porque mudam como pensamos sobre trabalho, falha e aprendizado. Brasil tem a oportunidade - rara no mundo - de implementar Agile bem, desde o início, em vez de corrigir 10 anos de implementação ruim. Isso exige investimento em liderança e cultura primeiro, ferramentas depois."

---

**Boa sorte na defesa! 🎓**

*Documento preparado para TCC UERJ 2026*
