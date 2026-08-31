# 📊 Dashboards Interativos - TCC Metodologias Ágeis

Este diretório contém visualizações de dados para sua monografia. Existem três versões com diferentes estilos e propósitos.

---

## 🎯 Qual Usar?

### 1. **dashboard_tcc_narrativo.html** ⭐ RECOMENDADO
**Propósito:** Apresentação na defesa + Inclusão na monografia

**Características:**
- ✅ Storytelling completo (Chaos → Evolução → Paradoxo → DORA → Insights)
- ✅ Explicações detalhadas de cada seção
- ✅ Métricas DORA explicadas com cards específicos
- ✅ Insights explícitos e claros
- ✅ Design acadêmico profissional
- ✅ Otimizado para PDF/print
- ✅ Separação clara: Metodologias Ágeis vs DevOps

**Quando usar:**
- Apresentação oral na banca (mostrar ao vivo)
- Screenshots para incluir na monografia PDF
- Enviar para orientadora como resumo visual
- Base para criar slides em PowerPoint

---

### 2. **dashboard_tcc_academico.html**
**Propósito:** Versão limpa e profissional (anterior ao narrativo)

**Características:**
- Paleta de cores acadêmica (azuis profundos)
- 6 gráficos sem narrativa
- Validação de dados documentada
- Apropriado para PDF

**Quando usar:**
- Se preferir uma versão mais compacta
- Quando não há espaço para explicações detalhadas

---

### 3. **dashboard_metodologias.html**
**Propósito:** Versão exploratória original (colorida)

**Características:**
- Mais visual e interativo
- 6 gráficos com design colorido
- Sem as explicações

**Quando usar:**
- Exploração de dados pessoal
- **NÃO recomendado para monografia/defesa** (cores muito vibrantes)

---

## 📖 Como Usar o Dashboard Narrativo

### Para Abrir:
1. Abra `dashboard_tcc_narrativo.html` em qualquer navegador
2. Explore os gráficos interativos (hover para mais detalhes)
3. Role para baixo para ver as explicações e insights

### Para Capturar Tela:
- **Chrome/Firefox:** F12 → Device Toolbar → Capturar tela
- Ou: Print screen de cada seção

### Para Incluir na Monografia:
1. Tire screenshots de cada seção
2. Ou inclua link para versão online
3. Cada seção está bem documentada com:
   - Descrição do que mostra
   - Dados e fontes
   - Insights extraídos

---

## 🎨 Design & Cores

**Paleta Acadêmica:**
- 🔵 Primária: #1a3a52 (azul escuro)
- 🔵 Secundária: #2c5aa0 (azul profissional)
- 🔵 Acentos: #4a7ba7, #6d95b8, #8bafd4
- ✅ Validada para print e PDF

**Fontes:**
- Segoe UI / Tahoma (Web-safe)
- Pronta para leitura em tela e papel

---

## 📊 Seções do Dashboard Narrativo

| Seção | Foco | Gráficos | Objetivo |
|-------|------|----------|----------|
| **1. Problema** | Chaos Report 1995 | 1 (bar) | Mostrar por que Agile foi necessário |
| **2. Evolução** | 1995-2025 | 1 (line) | Visualizar adoção ao longo do tempo |
| **3. Adoção** | Metodologias vs DevOps | 2 (doughnut) | Separar frameworks de práticas |
| **4. Paradoxo** | 71% vs 47% | 1 (bar) | Evidenciar o argumento central |
| **5. DORA** | Métricas com cards | 1 (radar) + 4 cards | Explicar o que importa medir |
| **6. Insights** | Conclusões | 6 cards | Resumir descobertas |

---

## 💾 Validação de Dados

Todos os números usados estão validados em:
```
graficos/VALIDACAO_DADOS_DASHBOARD.md
```

**Fontes principais:**
- ✅ Standish Chaos Report (1995)
- ✅ State of Agile Reports (2023-2025)
- ✅ DORA Accelerate (2024-2025)
- ✅ NTT DATA Agilidade LATAM (2024)

---

## 🔗 Links & Referências

- **Monografia:** README.md (raiz do projeto)
- **Validação:** VALIDACAO_DADOS_DASHBOARD.md
- **Análises:** ../analises/insights_chave.md
- **Referências:** ../referencias/referencias_estruturadas.md

---

## 📝 Notas Técnicas

- **Framework:** HTML5 + Chart.js (sem dependências externas)
- **Compatibilidade:** Chrome, Firefox, Safari, Edge (últimas 2 versões)
- **Responsivo:** Adapta-se a mobile/tablet (recomenda-se desktop)
- **Print:** Otimizado com CSS @media print
- **Acessibilidade:** Tabelas de dados incluídas, cores testadas para daltonismo

---

## 🚀 Próximos Passos

### Se quiser expandir:
1. **Adicionar mais gráficos**: Seção 7 com comparativo Brasil vs Global
2. **Interatividade avançada**: Filtros por região/setor
3. **Versão interativa em PDF**: Com links e campos interativos

### Se quiser customizar:
1. Edite as cores em: `const colors = {...}`
2. Modifique dados em: `data: { ... }`
3. Altere explicações em: `<div class="explanation">...</div>`

---

## ❓ Dúvidas?

- **Qual usar na defesa?** `dashboard_tcc_narrativo.html`
- **Como incluir na monografia?** Screenshots das seções ou link online
- **As cores são apropriadas?** Sim, validadas para print acadêmico
- **Posso mudar?** Sim, edite o arquivo HTML

---

**Criado:** 31/08/2026  
**Versão:** 2.0 (com storytelling narrativo)  
**Status:** ✅ Pronto para uso acadêmico
