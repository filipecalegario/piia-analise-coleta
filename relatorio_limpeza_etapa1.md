# RELATÓRIO DE LIMPEZA DE DADOS
## Etapa 1 — Consulta à Comunidade UFPE sobre o Uso de IA

**Data de execução:** 01/12/2025 às 16:48

---

## 1. DADOS ORIGINAIS

| Métrica | Valor |
|---------|-------|
| Total de registros | 2182 |
| Total de colunas | 24 |

---

## 2. TRANSFORMAÇÕES REALIZADAS

### 2.1 Remoção de registros sem consentimento

| Descrição | Quantidade |
|-----------|------------|
| Registros sem consentimento removidos | 18 |
| Registros mantidos | 2164 |
| Taxa de exclusão | 0.8% |

### 2.2 Exclusão de coluna vazia

| Coluna removida | Motivo |
|-----------------|--------|
| "Coluna 1" | Completamente vazia (100% missing) |

### 2.3 Padronização de vínculos institucionais

**De 26 categorias originais para 5 categorias padronizadas:**

| Categoria Padronizada | Registros | % |
|-----------------------|-----------|---|
| Discente de Graduação | 792 | 36.6% |
| Docente | 555 | 25.6% |
| Discente de Pós-Graduação | 468 | 21.6% |
| Técnico-administrativo | 310 | 14.3% |
| Egresso | 39 | 1.8% |
| **TOTAL** | **2164** | **100%** |

---

## 3. ANÁLISE DE VALORES AUSENTES

| Variável | N Missing | % Missing |
|----------|-----------|----------|
| Comentarios_Finais | 1519 | 70.2% |
| Curso | 777 | 35.9% |
| Estrutura_Governanca | 479 | 22.1% |
| Impacto_Producao_Autoral | 293 | 13.5% |
| Impacto_Integridade_Academica | 286 | 13.2% |
| Medidas_Uso_Etico | 278 | 12.8% |
| Beneficios_Percebidos | 124 | 5.7% |
| Riscos_Preocupacoes | 106 | 4.9% |

**Variáveis completas (0% missing):** 16 variáveis

---

## 4. BASE DE DADOS FINAL

| Métrica | Valor |
|---------|-------|
| Total de registros válidos | 2164 |
| Total de variáveis | 24 |
| Arquivo gerado | data/dados_limpos_etapa1.xlsx |

---

## 5. VALIDAÇÃO

- [x] Todos os 2164 registros possuem consentimento válido
- [x] Coluna vazia removida
- [x] 100% dos vínculos mapeados para categorias padronizadas
- [x] Nomes de variáveis padronizados
- [x] Missing values documentados

---

*Relatório gerado automaticamente em 01/12/2025 às 16:48*
