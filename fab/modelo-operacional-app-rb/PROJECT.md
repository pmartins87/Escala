# Projeto — Modelo Operacional APP-RB 2026-01

**Status:** EM REVISÃO  
**Última atualização:** 2026-09-19

## Objetivo

Revisar o Modelo Operacional do APP-RB sem alterar o arquivo-base original, trabalhando em uma cópia nativa do Google Docs, de forma que:

1. o conteúdo e a estrutura atendam à norma específica aplicável ao Modelo Operacional;
2. a redação e a apresentação estejam compatíveis com as normas de redação oficial aplicáveis;
3. cada anotação de Nelson seja analisada criticamente, e não aceita automaticamente;
4. decisões rejeitadas ou ajustadas sejam justificadas em notas explicativas;
5. a exportação Google Docs → PDF seja validada visualmente antes do encerramento.

## Arquivos

### Original imutável
- Google Drive: `Modelo APP-RB 2026-01 - Em Edição.docx`
- Drive file id: `1OO-0P8PQQ1EOJMbJPbs0UvQqTE_Babfm`

### Cópia de trabalho
- Google Docs: `Modelo APP-RB 2026-01 - Revisão normativa e formatação`
- Document id: `1SfpexYhyB11sz71RkPYWdITi75NP9IoXvJIb5e0v4P8`

## Hierarquia normativa adotada

1. **CIRCEA 100-57/2025** — norma específica para Modelo Operacional e Manual do Órgão ATC. É a referência principal para estrutura, conteúdo, manutenção da numeração e elementos obrigatórios.
2. **Manual de Redação da Presidência da República** — referência expressamente indicada pela CIRCEA 100-57 para redação textual.
3. **ABNT NBR 6024** — referência expressamente indicada pela CIRCEA 100-57 para numeração progressiva das seções.
4. **NSCA 5-3/2026** — norma geral vigente do COMAER para comunicações oficiais e atos normativos, usada subsidiariamente quando compatível com a norma específica.
5. **NSCA 5-2/2023 e NSCA 5-1/2011** — apenas como histórico/apoio, pois foram revogadas. Não serão usadas para sobrepor regras vigentes.

## Regras de preservação

- O arquivo original não será alterado.
- Nenhuma sugestão de comentário será aplicada apenas por ter sido proposta.
- Alterações operacionais/factuais exigem fonte normativa ou documental suficiente.
- Se a fonte disponível não sustentar a alteração, a decisão fica como `VERIFICAR`, não como aceita.
- Itens obrigatórios da estrutura da CIRCEA 100-57 não serão removidos; quando não aplicáveis, será observado o tratamento determinado pela própria circular.

## Roadmap e gates

### G0 — Preservação e rastreabilidade
- [x] localizar original no Drive;
- [x] criar cópia de trabalho nativa Google Docs;
- [x] preservar comentários na conversão;
- [x] iniciar fonte de verdade no GitHub.

**Gate:** PASS.

### G1 — Consolidação normativa
- [x] identificar CIRCEA 100-57;
- [x] identificar Manual de Redação;
- [x] identificar NSCA 5-1, 5-2 e 5-3 e vigência;
- [ ] fechar especificação objetiva de formatação e capitalização por tipo de elemento.

**Gate:** ABERTO.

### G2 — Auditoria do documento-base
- [ ] mapear estrutura, estilos, cabeçalhos, rodapés, tabelas e quebras;
- [ ] gerar PDF-base pela conversão atual;
- [ ] verificar perdas introduzidas pelo Google Docs.

**Gate:** ABERTO.

### G3 — Revisão das anotações de Nelson
- [ ] classificar todas as anotações em ACEITAR / REJEITAR / AJUSTAR / VERIFICAR;
- [ ] registrar fundamento e efeito de cada decisão;
- [ ] não aplicar alterações factuais sem comprovação.

**Gate:** ABERTO.

### G4 — Implementação
- [ ] corrigir redação, estrutura e formatação na cópia Google Docs;
- [ ] atualizar sumário/paginação apenas após estabilização;
- [ ] manter rastreabilidade das mudanças.

**Gate:** BLOQUEADO até G1–G3 terem evidência suficiente para cada lote.**

### G5 — Notas explicativas
- [ ] criar documento separado;
- [ ] explicar obrigatoriamente todas as sugestões rejeitadas;
- [ ] registrar de forma resumida as aceitas/ajustadas.

### G6 — Validação PDF
- [ ] exportar diretamente do Google Docs para PDF;
- [ ] inspecionar todas as páginas;
- [ ] corrigir quebras, cabeçalhos, rodapés, sumário, tabelas e paginação;
- [ ] repetir até não haver defeito material de apresentação.

**Critério de encerramento:** PDF exportado da cópia nativa passa na auditoria visual e normativa; notas explicativas e GitHub estão atualizados.

## Critérios que fariam mudar uma decisão

- edição mais nova da CIRCEA 100-57 ou outra norma específica aplicável;
- determinação expressa do CINDACTA IV/DECEA incompatível com o critério atual;
- evidência oficial operacional mais recente (AIP, ROTAER, cartas, Modelo aceito, AVOP/CAOp etc.);
- constatação de que uma regra geral da NSCA 5-3 não se aplica ao gênero documental MOp.

## Próximo passo concreto

Fechar G1 e G2, levantar integralmente os comentários de Nelson e iniciar a matriz de decisão antes de modificar conteúdo substantivo.
