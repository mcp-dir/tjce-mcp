# Ferramentas

Jurisprudência TJCE expõe 3 ferramentas (todas somente leitura).

### 1. `jurisprudencia_buscar`
**Input**: `termo`, `tipo` (opcional), `tribunais` (opcional), `data_de` (opcional), `data_ate` (opcional), `ordenar` (opcional), `max` (opcional)

Busca jurisprudência (acórdãos, súmulas, orientações jurisprudenciais, temas) por termo ou tese.

### 2. `jurisprudencia_sumulas`
**Input**: `termo`, `max` (opcional)

Busca SÚMULAS (incluindo vinculantes) por termo.

### 3. `jurisprudencia_documento`
**Input**: `id` (opcional), `numeracao` (opcional), `tribunal` (opcional), `ids` (opcional)

Lê o INTEIRO TEOR de uma decisão (texto completo do acórdão, não o resumo).

## Prompts de exemplo

```
Pesquise jurisprudência do TJCE direto do seu agente de IA, sem a sintaxe de busca do portal. Cada acórdão vem com órgão julgador, relator, data, o trecho exato que casou a busca e o link oficial. A mesma conexão alcança outros 16 tribunais, incluindo STF, STJ e TST. Grátis, sem login.
Jurisprudência do TJCE sobre negativa de cobertura por plano de saúde
Como o TJCE decide ação de despejo por falta de pagamento?
Leia o inteiro teor do acórdão que você achou e resuma a tese
```
