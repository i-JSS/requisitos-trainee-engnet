<center>

#  Matriz de Rastreabilidade – Uber

</center>

---

<div align="justify">

## O que é uma matriz de rastreabilidade?

A **matriz de rastreabilidade** é uma ferramenta essencial em projetos de software, usada para assegurar que todos os requisitos levantados durante a fase de elicitação sejam devidamente implementados, testados e validados ao longo do desenvolvimento.  
No contexto do nosso projeto — inspirado no **Uber** — ela garante que cada funcionalidade do sistema (como solicitação de corridas, avaliação de motoristas ou pagamento) esteja conectada a um requisito específico, mantendo o controle e a coerência entre as entregas.

---

##  Funções da Matriz

- Garantir que **todos os requisitos levantados sejam atendidos** na versão final do sistema;  
- Permitir **rastreabilidade bidirecional** entre requisitos e funcionalidades;  
- Facilitar a **análise de impacto** de mudanças em requisitos;  
- Melhorar a **comunicação entre analistas, desenvolvedores e testadores**;  
- Ajudar no **processo de verificação e validação**;  
- Identificar **lacunas ou sobreposições** no desenvolvimento das features.

---

##  Nossa Abordagem

Para estruturar nossa matriz de rastreabilidade do sistema **Uber**, seguimos as etapas abaixo:

- **Mapeamento de Requisitos Funcionais:** identificação das principais funcionalidades relacionadas à experiência de motoristas e passageiros;  
- **User Story Mapping:** decomposição das histórias de usuário para melhor priorização e organização;  
- **Casos de Uso:** representação dos fluxos de interação entre passageiro, motorista e sistema;  
- **Análise de Impacto:** avaliação de como mudanças em uma história de usuário afetam outras partes do sistema;  
- **Feedback Cíclico:** validação contínua com base em simulações de uso real.

---

##  Tabela de Rastreabilidade do User Story Mapping

| Objetivo | ID da User Story | Descrição da User Story | Requisito |
|-----------|------------------|--------------------------|------------|
| Solicitar Corrida | US01 | Eu, como passageiro, quero solicitar uma corrida para ir de um ponto A a um ponto B. | R001 |
| Cancelar Corrida | US02 | Eu, como passageiro, quero poder cancelar uma corrida antes que o motorista chegue, caso eu mude de ideia. | R001 |
| Localização em Tempo Real | US03 | Eu, como passageiro, quero visualizar a localização do motorista em tempo real para acompanhar sua chegada. | R002 |
| Avaliar Corrida | US04 | Eu, como passageiro, quero avaliar o motorista após a corrida para contribuir com o sistema de reputação. | R003 |
| Histórico de Viagens | US05 | Eu, como passageiro, quero acessar meu histórico de corridas para revisar valores e trajetos anteriores. | R004 |
| Pagamento Digital | US06 | Eu, como passageiro, quero pagar minha corrida diretamente pelo aplicativo, utilizando cartão ou Pix. | R005 |
| Notificação de Chegada | US07 | Eu, como motorista, quero ser notificado quando o passageiro estiver no local de embarque. | R006 |
| Gerenciamento de Corridas | US08 | Eu, como motorista, quero aceitar ou recusar corridas conforme minha disponibilidade. | R007 |
| Cálculo de Tarifa | US09 | Eu, como sistema, devo calcular automaticamente o valor da corrida com base na distância e tempo estimados. | R008 |
| Suporte ao Usuário | US10 | Eu, como usuário, quero acessar um canal de suporte para resolver problemas relacionados a cobranças ou corridas. | R009 |
| Compartilhar Localização | US11 | Eu, como passageiro, quero compartilhar minha localização com um contato de confiança durante a corrida. | R010 |
| Notificações de Segurança | US12 | Eu, como passageiro, quero receber alertas de segurança durante viagens em horários noturnos. | R011 |
| Modo Motorista | US13 | Eu, como motorista, quero alternar entre o modo ativo e inativo para controlar quando estou disponível para corridas. | R012 |
| Estimativa de Tempo | US14 | Eu, como passageiro, quero visualizar o tempo estimado de chegada do motorista antes de confirmar a corrida. | R013 |

---

<center>

##  Histórico de Versão

</center>

<div style="margin: 0 auto; width: fit-content;">

| Data       | Versão | Descrição             | Autores                                   |
|------------|--------|-----------------------|-------------------------------------------|
| 17/10/2025 | `1.0`  |  Criação e Edição do Documento. | [Caio Leal ](https://github.com/CHZXD) |

</div>

</div>
