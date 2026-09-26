# Base de referência do Cálculo de Prazos

`perfis.json`: perfis de tribunais com os feriados forenses lidos nos atos oficiais, para o app
**Cálculo de Prazos** (macOS). O app baixa este arquivo quando o usuário clica "Verificar atualizações",
mostra o que mudaria e só grava com confirmação. O app nunca consulta sites de tribunais.

Só dados públicos (feriados publicados em Diário Oficial). O código do app não está aqui.

## Fontes lidas (campo `fonte` de cada feriado)
- TJPE: Ato Conjunto nº 43/2025 (DJe 14/10/2025, feriados de 2026) e Ato nº 1502/2026 (DJe 25/09/2026, feriados de 2027).
- TRT6: Portaria TRT6-GP nº 495/2025 (feriados de 2026).
- JFPE: Portaria nº 126/DF/2026. TRF5: Ato nº 626/2025 da Presidência.
- Nacionais: Leis nº 662/1949, 10.607/2002, 6.802/1980, 14.759/2023; Justiça Federal: Lei nº 5.010/1966, art. 62.

`lidoEm` é a data da última leitura dos atos. Gerado pelo app: `CalculoPrazos --exportar-referencia perfis.json`.
