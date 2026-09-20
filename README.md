# Escala Operacional TWR/APP-RB

Repositório de rastreabilidade das versões da escala operacional e das regras usadas na análise/equalização.

## Versões mantidas

1. **Original** — arquivo recebido, sem reformulação.
2. **Reformulada sem redistribuição de operadores** — fórmulas, layout, legenda e indicadores corrigidos, preservando os turnos originais.
3. **Reformulada com redistribuição** — versão de trabalho em que os turnos podem ser alterados para equalização de workload, respeitando cobertura, habilitações, fadiga e antiguidade.

## Versão agressiva atual

Critérios vigentes em outubro/2026:
- TAF: 4 h de OA para qualquer operador que tenha ao menos uma ocorrência de TAF no mês.
- Instrutor: +8 h de OA quando a habilitação contém "I".
- 1S Carla: +10 h de EAD.
- 1S Paulo: +20 h por atividades de adjunto.
- 3S Camila Borges: +20 h por atividades de escalante.
- Antiguidade para desempate/distribuição residual: SO > 1S > 2S > 3S; DACTA André = 2S; DACTA Fábio e DACTA Thiago = 1S.
- Objetivo de equalização: amplitude entre maior e menor WL de até 2 pontos percentuais, com os menores WL preferencialmente concentrados nos mais antigos.
- A versão redistribuída deve partir da escala original, preservar a cobertura diária e minimizar alterações compatíveis com os critérios acima.

Os arquivos em `snapshots/` são exportações para preservação histórica. Os links nativos do Google Sheets ficam registrados em `docs/versoes.md`.


---

## Transição do repositório para FAB

A partir de 2026-09-19, este repositório também será usado como fonte de rastreabilidade de trabalhos relativos à Força Aérea Brasileira e deverá ser renomeado futuramente para **FAB / Força Aérea Brasileira**.

O projeto de revisão do Modelo Operacional APP-RB 2026-01 está documentado em `fab/modelo-operacional-app-rb/`.

> Observação de segurança: o repositório está atualmente público. Por isso, documentos de rastreabilidade aqui registrados devem evitar dados operacionais sensíveis, telefones, contingências detalhadas ou outros conteúdos que não devam ser publicados externamente. Esses conteúdos permanecem no Google Drive/documentos de trabalho enquanto o repositório não for tornado privado.
