# Ferramentas

Jurisprudência TJMA expõe 3 ferramentas (todas somente leitura).

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
Pesquise jurisprudência do TJMA direto do Claude, ChatGPT ou do seu agente. Cada decisão traz órgão julgador, relator, data, o trecho que casou a busca e o link no site oficial. A mesma conexão alcança outros 16 tribunais, incluindo STF, STJ e TST. Grátis, sem login.
Jurisprudência do TJMA sobre dano moral por inscrição indevida
Como o TJMA decide ação possessória de imóvel urbano?
Leia o inteiro teor do acórdão que você achou e resuma a tese
```
