# Análise Comparativa: Metodologias Ágeis de Desenvolvimento

## 1. Evolução das Metodologias

### 1.1 Era Pré-Ágil (1970s-1990s)

**Modelo:** Waterfall / PMBOK  
**Características:**
- Requisitos definidos no início do projeto
- Fases sequenciais: análise → design → desenvolvimento → testes → deployment
- Rigidez e falta de adaptabilidade
- Documentação extensiva obrigatória

**Problema Critical (Standish Chaos Report, 1995):**
- 31.1% de projetos **cancelados** antes da conclusão
- 52.7% de projetos com **custo 189% acima** do orçamento original
- Apenas 16.2% completados **on-time e on-budget**
- Maiores empresas: apenas **9%** de sucesso completo

---

## 2. Os Principais Frameworks Ágeis

### 2.1 SCRUM

**Origem:** 1990s, Ken Schwaber e Jeff Sutherland  
**Natureza:** Framework prescritivo para equipes

#### Estrutura Atual (Scrum Guide 2020)

| Elemento | Descrição |
|----------|-----------|
| **Papéis** | Product Owner, Scrum Master, Developers |
| **Eventos** | Sprint, Sprint Planning, Daily Scrum, Sprint Review, Retrospective |
| **Artefatos** | Product Backlog, Sprint Backlog, Increment |
| **Duração Sprint** | Tipicamente 1-4 semanas |

**Adoção (State of Agile 2025):**
- 63% das organizações usam Scrum como metodologia principal
- Mais popular em equipes de desenvolvimento (71% usam Agile)
- Crescimento de 16% (2024-2025)

**Força:** Estrutura clara com papéis definidos  
**Fraqueza:** Pode ser inflexível; dificuldade em escalar

---

### 2.2 KANBAN

**Origem:** 1990s, derivado de práticas Toyota  
**Natureza:** Fluxo contínuo

#### Princípios

- **Visualização do trabalho:** Quadro Kanban (To Do → In Progress → Done)
- **Limitação de WIP (Work in Progress):** Reduz gargalos
- **Fluxo contínuo:** Sem sprints fixos
- **Melhoria contínua:** Análise de métricas

**Vantagem:** Flexibilidade e rapidez  
**Desafio:** Menos estruturado que Scrum

---

### 2.3 Metodologias em Escala

#### SAFe (Scaled Agile Framework)

**Estado de Adoção (2025):**
- 26% das empresas adotam SAFe em nível empresarial
- Mais adotado em grandes corporações
- Combina Scrum + Kanban + DevOps

**Estrutura:**
- Portfolio Level (estratégia)
- Program Level (coordenação de times)
- Team Level (Scrum/Kanban)

#### LeSS (Large-Scale Scrum)

**Conceito:** Scrum escalado com poucos ajustes  
**Adoção:** Crescente em startups e mid-market

---

### 2.4 DevOps e Engenharia de Software

**Convergência observada (DORA 2024-2025):**

| Métrica DORA | Elite Performers | High Performers | Definição |
|-------------|------------------|-----------------|-----------|
| **Deployment Frequency** | Múltiplas vezes/dia | 1x/semana | Frequência de deploy |
| **Lead Time** | <1 hora | 1-7 dias | Tempo de implementação |
| **MTTR** | <1 hora | 1-24 horas | Tempo para restaurar |
| **Change Failure Rate** | 0-15% | 16-30% | % de deploys que falham |

**CI/CD (Continuous Integration/Delivery):**
- 89% das empresas "Elite" praticam CI/CD
- Correlação direta com performance do produto
- Automação de testes e deploy reduz riscos

---

## 3. O Paradoxo da Adoção Ágil

### 3.1 Números de Adoção vs. Performance Real

**Dado chave (State of Agile 2025):**
- 71% das organizações declaram usar Agile
- Mas apenas **47%** reportam "alta satisfação" com os resultados
- 34% dizem enfrentar "barreiras substantivas" na implementação

### 3.2 O Fenômeno da "Agilidade de Fachada"

**Definição:** Conformidade ritual sem valor real

**Sinais de Aviso:**
- Reuniões diárias que não resolvem problemas
- Sprints realizados, mas sem mudança de velocidade
- Documentação ágil que é apenas mais rápida, não melhor
- Falta de autonomia real das equipes

**Raiz do problema (análise DORA 2025):**
> "A IA é um amplificador. Ela potencializa os pontos fortes de organizações com alto desempenho, mas também os pontos fracos daquelas com dificuldades."

A mesma lógica aplica-se à agilidade: frameworks amplificam a cultura organizacional, não a criam.

---

## 4. Dimensão Cultural

### 4.1 Fatores Críticos de Sucesso

**Baseado em análise de DORA, State of Agile e NTT DATA (América Latina 2024):**

1. **Liderança Ágil**
   - Suporte executivo genuine (não apenas formal)
   - Eliminação de micro-management
   - Foco em outcomes, não outputs

2. **Cultura Psicológica Segura**
   - Permissão para falhar e aprender
   - Transparência de dados
   - Colaboração cross-team

3. **Alinhamento Estratégico**
   - Objetivos claros (OKRs)
   - Conectar entregas ao valor de negócio
   - Revisão periódica de prioridades

4. **Engenharia de Plataforma**
   - Infraestrutura que habilita agilidade
   - Self-service para equipes
   - Pipelines automatizados

### 4.2 Desafios Regionais (América Latina)

**NTT DATA 2024:**
- **54.92%** dos respondentes são "Agilistas"
- Mas **resistência à mudança** é barrier #1 (67% mencionam)
- Falta de treinamento cultural (47%)
- Liderança não familiarizada (38%)

---

## 5. Conclusões Preliminares

1. **Evolução é real:** De waterfall rígido para agilidade contínua
2. **Adoção não é implementação:** Números altos escondem fraquezas reais
3. **Frameworks sozinhos não funcionam:** Cultura é o verdadeiro diferencial
4. **DevOps é complementar:** Não substitui Agile, mas potencializa
5. **IA muda o jogo:** Mas como amplificador, não como solução

---

## 6. Próximos Passos para a Monografia

- [ ] Seção 3.1: Detalhar "agilidade de fachada" com exemplos
- [ ] Seção 4: Análise profunda de barreiras culturais
- [ ] Gráficos: Comparação de métricas por framework
- [ ] Case studies: Fintechs vs. Consultorias
- [ ] Discussão: Por que a mudança cultural demora

---

**Fontes:**
- Standish Chaos Report (1995-2020)
- DORA Accelerate State of DevOps (2024-2025)
- State of Agile Report (17ª e 18ª edições)
- NTT DATA Agilidade na América Latina (2024)
- Scrum Guide 2020

**Atualizado:** 31/08/2026
