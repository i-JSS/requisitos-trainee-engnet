<center>

# Análise de Protocolo - Uber

</center>

---

> A análise de protocolo tem como objetivo documentar, por observação controlada e simulação, o comportamento do usuário e do sistema durante o processo de solicitação de serviço no Uber, com o propósito de extrair requisitos funcionais e não funcionais, identificar decisões de design embutidas e criar artefatos rastreáveis para a etapa de elicitação.

---

<center>

## 1. Elicitação

</center>

> **Explicação:** Elicitação é o processo de descoberta, deciframento, obtenção e compreensão das necessidades básicas, expectativas e restrições de todas as pessoas envolvidas (clientes, usuários, parceiros e colaboradores) que um novo sistema de software deve satisfazer. Em outras palavras, é a fase de descobrir "O que" o software precisa e deve fazer.

> **Correlação:** Agora podemos relacionar a fase de Elicitação com a técnica de Análise de Protocolo. Já que ambas são diretamente relacionadas. 

---

<center>

---

## 1.1. Aplicação da Análise de Protocolo - Introspecção

</center>

> **Aplicação:** Nesse processo, iremos utilizar a técnica de Análise de Protocolo através da Observação. 

---
<center>

### 1.2. Cenário Analisado: Registro de Reclamação e Suporte ao usuário

| Item | Descrição |
| :--- | :--- |
| **Objetivo** | Analisar a usabilidade, a rastreabilidade e a transparência do processo que o aplicativo Uber oferece ao usuário para iniciar e acompanhar uma solicitação de suporte. O foco é identificar os requisitos funcionais relacionados à logística do suporte (como encontrar a viagem correta em que ocorreu alguma situação adversa e enviar a mensagem) e os requisitos não-funcionais ligados à segurança da informação e à expectativa de tempo de resposta. |
| **Técnica** | Análise de Protocolo por Introspecção |

---

<center>

## 1.3. Introspecção

</center>

> **Explicação:** O que é Introspecção? A Introspecção (ou Introspecção Controlada) é uma variação da observação onde o próprio analista é também o usuário. Isso traz uma vantagem de possibilidade de registrar as intenções do usuário e a análise simultaneamente pelo mesmo indivíduo, trazendo perspectivas da usabilidade do aplicativo.

---

<center>

## 2. Protocolo Registrado (Passos de Introspecção)

</center>

A tabela a seguir detalha a sequência de interações do usuário (passos) e as observações sobre o comportamento do sistema para o fluxo de Ajuda e Suporte.

| # | Ação do Usuário no App | Comportamento do Sistema | Observação / Decisão Elicitada |
| :--- | :--- | :--- | :--- |
| **1.** | Abrir o aplicativo da Uber (tela inicial). | O menu do Sistema apresenta opções de solicitações (viagem e envio de produto) e locais solicitados anteriormente (histórico de endereços). | **RF:** O Sistema deve apresentar um menu inicial claro e intuitivo, com opções de serviço e acesso ao histórico do usuário. |
| **2.** | Clicar em "Conta" (ícone de perfil no canto). | É exibida uma tela com acesso a um plano de fidelidade para desconto de corridas futuras, além das opções de "Ajuda", "Carteira", "Mensagem" e "Checagem de segurança". | **RF:** O Sistema deve centralizar funções de suporte, pagamento e segurança em uma única área de perfil. **RNF (Incentivo):** O Sistema deve promover planos de fidelidade e benefícios para retenção de clientes. |
| **3.** | Clicar em "Ajuda". | O Sistema informa o resumo da última viagem e oferece opções de suporte segmentadas: "Alterar avaliação", "Problemas com viagem e reembolso", "Conta", "Assinatura", "Acessibilidade", etc. | **RF:** O Sistema deve dar prioridade ao contexto recente do usuário (última viagem) para agilizar o suporte. **RF:** O Sistema deve segmentar o suporte em categorias claras para otimizar o fluxo de encaminhamento do usuário. |
| **4.** | Clicar em uma viagem anterior na lista de Ajuda. | O Sistema exibe o detalhe da viagem (mapa, valor) e as opções de suporte relevantes para aquele contexto (ex: "Item esquecido"). | **RF:** O Sistema deve rastrear e associar um conjunto de opções de suporte específicas a cada transação (rastreabilidade de dados). |
| **5.** | [] | [] | [] |

---

<center>

## 3. Requisitos Elicitados

</center>

Os requisitos a seguir foram extraídos diretamente da observação detalhada do protocolo de interação.

| Requisito | Descrição | Técnica |
| :--- | :--- | :--- |
| **REQ** | [DESCRIÇÃO] | Análise de Protocolo |
| **REQ** | [DESCRIÇÃO] | Análise de Protocolo |
| **REQ** | [DESCRIÇÃO] | Análise de Protocolo |

---

<center>

## Histórico de Versão

</center>

<div style="margin: 0 auto; width: fit-content;">

| Data | Versão | Descrição | Autores |
| :---: | :---: | :--- | :--- |
| 06/10/2025 | `1.0` | Criação do documento. | [João Carvalho](https://github.com/i-JSS) |
| 17/10/2025 | `1.1` | Implementação do Processo da Análise de Protocolo. | [Lenenni](https://github.com/stubaLA) |

</div>