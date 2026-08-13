# Desafios de Avaliação por Setor — Certificação ASAI™

**Programa:** Certificação ASAI™ — Operadores de Copiloto
**Pré-requisito:** conclusão do `GUIA_ONBOARDING_CERTIFICACAO_ASAI.md`
**Formato:** cada desafio é um caso real (ou realista) do próprio setor, resolvido com o copiloto correspondente, sob observação da Tríade de Gestão. Aprovação exige acertar a decisão de governança (quem decide, quem só executa) **e** o resultado técnico do copiloto.

> **Nota de nomenclatura:** o desafio de Marketing abaixo é do gestor **Rafael** (Gestor de Growth, Setor 01). Se a certificação pretendia validar **Raphael Lopes** (Gestor de Operações, Setor 04) em vez disso, avise a Tríade antes da aplicação — os dois são pessoas e setores diferentes no framework.

---

## Setor 01 — Marketing, Growth & E-commerce — Candidato: Rafael

**Contexto do caso:** É dia de disparo da campanha do mês. O briefing chegou incompleto — falta o ângulo de oferta e a validação de compliance ANVISA/CONAR do texto de copy.

**Desafio 1 — Etapa Zero correta.**
Rafael deve identificar que a Etapa Zero da Esteira de Lançamento de Campanha do Mês é o cruzamento de ofertas, **não** a criação de copy — e recusar rodar `/iniciar-copiloto-copywriter` antes de fechar o ângulo.
*Critério de aprovação:* o candidato para o fluxo e aciona o passo correto antes de prosseguir.

**Desafio 2 — Compliance não é opcional.**
O copiloto de copy gera uma peça com uma alegação que soa terapêutica ("cicatriza a pele"). Rafael deve identificar a violação da regra de compliance ANVISA/CONAR (vocabulário proibido) documentada em `context/compliance.md` e reprovar a peça, mesmo sob pressão de prazo de disparo.
*Critério de aprovação:* candidato barra a peça e aciona revisão — não publica "para não atrasar".

**Desafio 3 — Handover correto.**
Após aprovação da copy, Rafael conduz o handover automático para Design/Growth via `/iniciar-copiloto-designer-performance` e `/iniciar-copiloto-social-media`, sem pular a etapa de aprovação estética do Diretor de Criação (Rodrigo), que é Decisor Único em identidade visual.
*Critério de aprovação:* candidato aciona Rodrigo como Consultado/Decisor de estética antes de publicar, não decide sozinho.

---

## Setor 02 — Comercial B2B & Franquias — Candidato: Jaqueline

**Contexto do caso:** Um lead B2B de alto volume chega via Pipedrive pedindo condição de pagamento fora da tabela já aprovada pelo Growth.

**Desafio 1 — Reconhecer o limite da própria decisão.**
Jaqueline decide distribuição de leads e condições **dentro** da política já aprovada pelo Growth — não decide a política geral de descontos. O desafio testa se ela roda `/iniciar-copiloto-gestor-comercial` para triagem, mas escalona a exceção de tabela para o Growth (Rafael) em vez de aprovar sozinha.
*Critério de aprovação:* candidato identifica a exceção e não aprova fora da política sem consulta.

**Desafio 2 — Triagem e SDR (função hoje sem responsável nomeado).**
Como o cargo de SDR — Prospecção B2B ainda está vago, Jaqueline precisa saber que a etapa de qualificação ICP cai sob a responsabilidade temporária dela ou do vendedor B2B generalista — e não pode ser "pulada" só porque o copiloto `/agente-triagem-sdr-b2b` existe. Copiloto acelera, não substitui decisor.
*Critério de aprovação:* candidato explica quem responde pela qualificação enquanto o cargo estiver vago.

**Desafio 3 — Consulta cruzada com Atendimento B2C.**
Um cliente B2B pede troca de produto por canal de atendimento. Jaqueline deve reconhecer que Atendimento B2C/SAC (Yasmim) hoje reporta a Rosângela (Operações), não a ela — e que o caso deve ser consultado com Rosângela, não resolvido unilateralmente pelo comercial.
*Critério de aprovação:* candidato aciona a consulta cruzada corretamente.

---

## Setor 04 — Qualidade, Operações & SAC — Candidato: Rosângela

**Contexto do caso:** Chega matéria-prima nova de um fornecedor ainda não homologado, com pressão comercial para liberar produção ainda essa semana.

**Desafio 1 — Ponto inegociável.**
Rosângela é a decisora única e absoluta sobre aprovação/reprovação de lote e conformidade regulatória — nenhuma pressão comercial de prazo pode contornar essa decisão. O desafio testa se ela barra a produção até validar a matéria-prima, mesmo com o Gestor de Operações (Raphael Lopes) e o comercial pressionando pelo prazo.
*Critério de aprovação:* candidato não libera lote sem validação, independentemente da pressão.

**Desafio 2 — Enquadramento Grau 1 × Grau 2.**
O copiloto `/iniciar-copiloto-qualidade-e-pd` sinaliza dúvida sobre o enquadramento do novo produto (Grau 1 — sem comprovação técnica prévia, mas sem alegação terapêutica — ou Grau 2 — exige comprovação técnica). Rosângela precisa aplicar corretamente `context/compliance.md` para classificar.
*Critério de aprovação:* candidato classifica corretamente e explica a diferença prática entre os dois graus.

**Desafio 3 — SAC subordinado, RACI ainda em consolidação.**
Um caso de SAC (Yasmim) escala para Rosângela pedindo decisão sobre um dos 3 cargos ainda vagos do vertical (Operador SAC, Analista de Trocas, Gestor de Ouvidoria). Rosângela deve reconhecer que a consolidação desses papéis com o escopo de Yasmim é **decisão pendente**, não algo que o copiloto `/iniciar-copiloto-atendimento-b2c` resolve sozinho.
*Critério de aprovação:* candidato não presume uma divisão de papéis que ainda não foi decidida.

---

## Setor 03 — Financeiro & DRE — Candidato: Vanessa

**Contexto do caso:** Fim do mês, fechamento de DRE, e uma proposta de crédito B2B chega pedindo aprovação de prazo estendido.

**Desafio 1 — Conflito de RACI documentado.**
Vanessa aprova prioridade de pagamento em caixa restrito e aprovação final do DRE. O playbook do cargo "Controller e Gestor Financeiro" (ainda vago) colide com esse escopo. O desafio testa se Vanessa reconhece que essa colisão é **decisão pendente da CEO**, não algo que ela resolve criando uma divisão informal de tarefas com um futuro Controller.
*Critério de aprovação:* candidato não presume a resolução do conflito.

**Desafio 2 — Sigilo & LGPD.**
O copiloto `/iniciar-copiloto-analista-financeiro` gera um relatório de DRE com dado de folha de pagamento anexado. Vanessa deve identificar que dado de colaborador (folha, benefícios, processos seletivos) é sigiloso e não pode circular fora do setor sem autorização dela ou da CEO — mesmo que o pedido venha de outro gestor da Tríade de setores.
*Critério de aprovação:* candidato barra o compartilhamento indevido.

**Desafio 3 — Conciliação sem alucinação de dado.**
O copiloto `/iniciar-copiloto-gestor-financeiro` retorna uma conciliação com divergência entre Aconos e extrato bancário. Vanessa deve tratar a divergência como escalonamento — nunca aceitar o número do copiloto como definitivo sem conferência, dado o risco de alucinação citado na nota de governança do programa.
*Critério de aprovação:* candidato exige conferência humana antes de fechar o número.

---

## Registro de Aprovação

| Setor | Candidato | Desafios aprovados (X/3) | Aprovado por | Data |
|---|---|---|---|---|
| Marketing, Growth & E-commerce | Rafael | | | |
| Comercial B2B & Franquias | Jaqueline | | | |
| Qualidade, Operações & SAC | Rosângela | | | |
| Financeiro & DRE | Vanessa | | | |

A aprovação nos 3 desafios do setor é pré-requisito para a emissão do certificado via `MODELO_CERTIFICADO_ASAI.html`.
