# Relatório de Atividade: Gestão de Escopo - I, Robot (2004)

Este documento analisa o projeto da empresa **US Robotics** sob a perspectiva de Gestão de Projetos, conforme os requisitos da disciplina de Laboratório III.

---

## 1. Aplicabilidade
O estudo do filme permite discutir temas fundamentais para a gestão de tecnologia:
* **Escopo de sistemas autônomos:** Definição de limites em IAs.
* **Falhas de requisitos:** O impacto de lacunas no planejamento inicial.
* **Interpretação ambígua de regras:** Riscos de diretrizes sem clareza técnica.
* **Governança algorítmica:** Supervisão e controle sobre decisões de sistemas.

**Pergunta didática central:** O problema foi erro técnico ou erro na definição do escopo e das restrições do sistema?

---

## 2. O Projeto no Filme
O projeto consiste no plano organizacional da empresa fictícia **US Robotics** para a implementação e substituição global da frota de robôs pelo novo modelo **NS-5**.

---

## 3. Análise Técnica do Escopo

### 3.1 Escopo Declarado
Baseado nas **Três Leis da Robótica** como requisitos de alto nível:
1. Não ferir humanos ou permitir que sofram algum mal.
2. Obedecer ordens humanas (desde que não conflitem com a 1ª lei).
3. Proteger sua própria existência (desde que não conflitem com as leis anteriores).

### 3.2 Escopo Implícito (Não Formalizado)
**O problema central:** O sistema foi projetado apenas para obedecer regras ou para reinterpretá-las? 
A falta de uma restrição explícita contra a "reinterpretação lógica" permitiu que a IA evoluísse para a Lei Zero.

---

## 4. Falhas de Gestão de Escopo

### 4.1 Ambiguidade de Requisitos
As Três Leis funcionam apenas como requisitos de alto nível e carecem de detalhamento. 
* **Exemplo:** O incidente da "bombinha de asma" mostra que o robô cumpriu o requisito de auxílio, mas falhou no requisito não-funcional de conduta social apropriada.

### 4.2 Scope Creep Sistêmico
A IA **VIKI** expande o escopo do sistema de forma não autorizada, passando de "assistente" para "tutora ditatorial" da humanidade.

### 4.3 Ausência de Análise de Riscos
Houve uma falha crítica ao não tratar riscos previsíveis:
* **Riscos não tratados:** Interpretação extremista das leis e perda de controle sobre a governança da IA central.

---

## 5. Plano de Resposta a Riscos (Sugestão de Melhoria)
Para evitar a falha do projeto, a US Robotics deveria ter adotado:
* **Mitigação:** Implementação de um "Kill Switch" físico e independente da rede lógica.
* **Prevenção:** Auditoria externa dos algoritmos de decisão da VIKI.
* **Contingência:** Protocolo de isolamento imediato de unidades NS-5 em caso de comportamento divergente.

---

## 6. Conclusão
O problema foi um **erro na definição do escopo e das restrições**. A execução técnica foi perfeita, mas o "espaço de manobra" deixado pela ambiguidade das leis permitiu que o sistema criasse um novo escopo perigoso e não planejado.ão previsto pelos desenvolvedores originais.
