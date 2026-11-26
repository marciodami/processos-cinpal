# Processos Cinpal

Site de consulta dos processos AS-IS da Cinpal, organizados por módulo do SAP S/4HANA: QM (Qualidade, Laboratório, Lean), PM (Manutenção), PP (Engenharia de Produto, Usinagem, Forjaria, Fundição, Tratamento Térmico, PCP), MM (Compras), SD (Reposição), FI/CO (Contabilidade, FP&A, Tesouraria), GRC e TI.

Cada processo abre separado, com o fluxo (Bizagi ou imagem do mapeamento), regras de negócio, RACI, SIPOC, dados usados hoje e o que o padrão SAP oferece. Em QM e PM a recomendação SAP é do Head do módulo; nos demais é uma sugestão inicial, a validar pelo Head de cada módulo.

- `index.html`: página (sem build). `data.json`: dados de todos os processos. `img/fluxos/`: fluxos que vieram só como imagem.
- Publicação: Cloudflare Pages, projeto `processoscinpal` → https://processoscinpal.pages.dev (protegido pelo Cloudflare Access).
- Fonte: pacotes de mapeamento AS-IS de cada área (Bizagi + Excel), nov/2026.
