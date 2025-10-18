<center>

# Matriz de Rastreabilidade – Uber

</center>

---

<div align="justify">

## O que e uma matriz de rastreabilidade?

A **matriz de rastreabilidade** é uma ferramenta essencial em projetos de software, usada para assegurar que todos os requisitos levantados durante a fase de elicitação sejam devidamente implementados, testados e validados ao longo do desenvolvimento.  
No contexto do nosso projeto — inspirado no **Uber** — ela garante que cada funcionalidade do sistema (como solicitação de corridas, avaliação de motoristas ou pagamento) esteja conectada a um requisito específico, mantendo o controle e a coerência entre as entregas.

---

## Funcoes da Matriz

- Garantir que **todos os requisitos levantados sejam atendidos** na versão final do sistema;  
- Permitir **rastreabilidade bidirecional** entre requisitos e funcionalidades;  
- Facilitar a **analise de impacto** de mudanças em requisitos;  
- Melhorar a **comunicacao entre analistas, desenvolvedores e testadores**;  
- Ajudar no **processo de verificacao e validacao**;  
- Identificar **lacunas ou sobreposicoes** no desenvolvimento das features.

---

## Nossa abordagem

Para estruturar nossa matriz de rastreabilidade do sistema **Uber**, seguimos as etapas abaixo:

- **Mapeamento de Requisitos Funcionais:** identificacao das principais funcionalidades relacionadas à experiencia de motoristas e passageiros;  
- **User Story Mapping:** decomposicao das historias de usuario para melhor priorizacao e organizacao;  
- **Casos de Uso:** representacao dos fluxos de interacao entre passageiro, motorista e sistema;  
- **Analise de Impacto:** avaliacao de como mudanças em uma historia de usuario afetam outras partes do sistema;  
- **Feedback Ciclico:** validacao continua com base em simulacoes de uso real.

---

## Tabela de Rastreabilidade do User Story Mapping

| Objetivo | ID da User Story | Descricao da User Story | Requisito |
|-----------|------------------|--------------------------|------------|
| Solicitar Corrida | US01 | Eu, como passageiro, quero solicitar uma corrida para ir de um ponto A a um ponto B. | R001 |
| Cancelar Corrida | US02 | Eu, como passageiro, quero poder cancelar uma corrida antes que o motorista chegue, caso eu mude de ideia. | R001 |
| Localizacao em Tempo Real | US03 | Eu, como passageiro, quero visualizar a localizacao do motorista em tempo real para acompanhar sua chegada. | R002 |
| Avaliar Corrida | US04 | Eu, como passageiro, quero avaliar o motorista apos a corrida para contribuir com o sistema de reputacao. | R003 |
| Historico de Viagens | US05 | Eu, como passageiro, quero acessar meu historico de corridas para revisar valores e trajetos anteriores. | R004 |
| Pagamento Digital | US06 | Eu, como passageiro, quero pagar minha corrida diretamente pelo aplicativo, utilizando cartao ou Pix. | R005 |
| Notificacao de Chegada | US07 | Eu, como motorista, quero ser notificado quando o passageiro estiver no local de embarque. | R006 |
| Gerenciamento de Corridas | US08 | Eu, como motorista, quero aceitar ou recusar corridas conforme minha disponibilidade. | R007 |
| Calculo de Tarifa | US09 | Eu, como sistema, devo calcular automaticamente o valor da corrida com base na distancia e tempo estimados. | R008 |
| Suporte ao Usuario | US10 | Eu, como usuario, quero acessar um canal de suporte para resolver problemas relacionados a cobrancas ou corridas. | R009 |
| Compartilhar Localizacao | US11 | Eu, como passageiro, quero compartilhar minha localizacao com um contato de confianca durante a corrida. | R010 |
| Notificacoes de Seguranca | US12 | Eu, como passageiro, quero receber alertas de seguranca durante viagens em horarios noturnos. | R011 |
| Modo Motorista | US13 | Eu, como motorista, quero alternar entre o modo ativo e inativo para controlar quando estou disponivel para corridas. | R012 |
| Estimativa de Tempo | US14 | Eu, como passageiro, quero visualizar o tempo estimado de chegada do motorista antes de confirmar a corrida. | R013 |

---

<center>

## Historico de Versao

</center>

<div style="margin: 0 auto; width: fit-content;">

| Data       | Versao | Descricao             | Autores                                   |
|------------|--------|-----------------------|-------------------------------------------|
| 17/10/2025 | `1.0`  | Criacao e Edicao do Documento. | [Caio Leal](https://github.com/CHZXD) |

</div>

</div>
