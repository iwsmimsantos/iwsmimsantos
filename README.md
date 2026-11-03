# Iasmim Santos

Engenheira de Software Júnior na Klubi, fintech de crédito e consórcio, e estudante de Engenharia de Software no Inteli (formatura prevista em 2027). Moro em São Paulo.

Construo software que leva IA para produção com segurança: agentes de IA com MCP, assistente de atendimento testada e monitorada, e sistemas de pagamento em que um erro mexe com dinheiro de cliente.

[LinkedIn](https://www.linkedin.com/in/iasmim-/) · iasmim.jesus@sou.inteli.edu.br

## Em destaque

<table>
  <tr>
    <td width="290" valign="top">
      <a href="https://github.com/iwsmimsantos/food-match"><img src="https://github.com/iwsmimsantos/food-match/raw/main/docs/demo.gif" width="270" alt="Food Match em uso"></a>
    </td>
    <td valign="top">
      <b><a href="https://github.com/iwsmimsantos/food-match">Food Match</a></b>
      <br><br>
      Para quem abre o app de delivery e não sabe o que pedir: alguns "quero / não quero" e o app aprende o gosto da pessoa, tira a rotina dela e sugere pratos novos, explicando cada escolha com IA.
      <br><br>
      Protótipo da ideia que ficou em 3º lugar no ideathon do iFood. Com 4 escolhas, acerta o dobro de pratos novos que mostrar os mais pedidos, numa avaliação simulada.
      <br><br>
      <code>Python</code> <code>FastAPI</code> <code>Thompson sampling</code> <code>Claude</code>
    </td>
  </tr>
  <tr>
    <td width="290" valign="top">
<pre>
$ suporte pendentes
reembolso R$ 34,90 · P1003
  aguardando aprovação

$ suporte aprovar --por ana
reembolso R$ 34,90 · executada

proposta de R$ 500:
  barrada pela política
</pre>
    </td>
    <td valign="top">
      <b><a href="https://github.com/iwsmimsantos/agente-suporte-mcp">Agente de suporte com MCP e aprovação humana</a></b>
      <br><br>
      Um agente de IA atende chamados de delivery por um servidor MCP: confere o pedido, os pagamentos e o rastreio e propõe reembolso ou cupom. Nenhum dinheiro se move sem uma pessoa aprovar, e a política fica no código, não no prompt.
      <br><br>
      Versão aberta de um protótipo que fiz no trabalho. Os testes incluem um modelo mal-intencionado tentando dar R$ 500, e nenhum centavo sai.
      <br><br>
      <code>Python</code> <code>MCP</code> <code>Claude</code> <code>human-in-the-loop</code>
    </td>
  </tr>
</table>

## Na Klubi, desde janeiro de 2026

Comecei como estagiária e fui efetivada em abril. Trabalho de ponta a ponta, da tela ao banco, nos sistemas que movimentam dinheiro de cliente.

- **Pagamentos e conciliação:** construí ferramentas de conciliação e painéis internos que tiraram trabalho manual do time financeiro, e lidero a migração dos estornos de desistência para o Mercado Pago.
- **IA em produção:** cuidei dos testes e do monitoramento da assistente de IA que atende os clientes e prototipei um servidor MCP para agentes de IA resolverem chamados com aprovação humana.
- **Produto do zero:** criei a negociação de planos personalizados no CRM de vendas, com cobrança do sinal e trava contra venda duplicada.
- **Operação do consórcio:** juntei em uma só tela o que antes eram três para operar o sorteio mensal e corrigi causas recorrentes de clientes que pagavam e ficavam sem o plano.

São mais de 130 pull requests integrados em 5 repositórios. O código da empresa é privado. Abaixo estão os projetos que posso mostrar.

## Projetos do Inteli

São 11 projetos em grupo, de 10 semanas cada, com empresas parceiras. Cada repositório tem uma seção "Minha participação" com o que eu fiz.

| Projeto | Parceiro | O que é | Tecnologias |
|---|---|---|---|
| [Central de Pesquisas](#projetos-com-código-privado) | Sindusfarma | Pipeline de dados e Data Warehouse com camadas Bronze, Silver e Gold e dashboards | dbt, ClickHouse, Prefect, Power BI |
| [BP Pipe](#projetos-com-código-privado) | Jacto | Back-end e esteira de CI/CD para software de drones, com 99 testes automatizados | Python, FastAPI, GitLab CI/CD |
| [Veridian](#projetos-com-código-privado) | Sankhya | Suíte de testes automatizados para uma API fiscal, com resiliência e rastreamento distribuído | OpenTelemetry, Kubernetes |
| [Estação Paraíso](https://github.com/iwsmimsantos/estacao-paraiso-metro) | Metrô de SP | Arquitetura segura e escalável, preparada para agentes de IA | Testes automatizados, observabilidade |
| [Júpiter](https://github.com/iwsmimsantos/jupiter-ia-comgas) | Comgás | IA que ampliou o monitoramento de qualidade de 1% para 20% das 120 mil ligações por mês | React, FastAPI, BERT, Terraform, AWS |
| [Ineri](https://github.com/iwsmimsantos/ineri-btg-pactual) | BTG Pactual | App que verifica a adequação do perfil de investidor (CVM 175) | C#, .NET, Python, PostgreSQL |
| [InCloud](https://github.com/iwsmimsantos/incloud-centro-paula-souza) | Centro Paula Souza | Sistema de apoio a estudantes com necessidades especiais | Angular, Node.js, AWS |
| [IoTrack](https://github.com/iwsmimsantos/iotrack-rfid-prodesp) | Prodesp | Rastreamento de patrimônio com etiquetas RFID | ESP32, React |
| [DIPA](https://github.com/iwsmimsantos/dipa-segmentacao-unipar) | Unipar | Segmentação de beneficiários de plano de saúde com machine learning | Python, K-means |
| [DIVE](https://github.com/iwsmimsantos/dive-plataforma-dell) | Dell | Plataforma web com os manuais de montagem da linha de produção | JavaScript, Jest |
| [100º Celsius](https://github.com/iwsmimsantos/100-celsius-jogo-fmusp) | FMUSP | Jogo educativo sobre prevenção de queimaduras | JavaScript |

### Projetos com código privado

Os três projetos de 2026 (Central de Pesquisas, BP Pipe e Veridian) estão no GitLab do Inteli, que é privado. Posso mostrar em entrevista.

## Fora da sala de aula

| Projeto | O que é | Tecnologias |
|---|---|---|
| [Food Match](https://github.com/iwsmimsantos/food-match) | Protótipo da ideia que ficou em 3º no ideathon do iFood: quero / não quero que aprende o gosto a cada escolha e sugere pratos novos, com explicação por IA e avaliação simulada | Python, FastAPI, Thompson sampling, Claude |
| [Agente de suporte com MCP](https://github.com/iwsmimsantos/agente-suporte-mcp) | Agente de IA que resolve chamados de delivery com aprovação humana, operações fechadas e trilha de auditoria | Python, MCP, Claude |
| [Gedui](https://github.com/iwsmimsantos/gedui-landing-page) | Site de um cliente real, feito pela Inteli Júnior, a empresa júnior do Inteli, e no ar em [gedui.com.br](https://gedui.com.br) | Next.js, TypeScript, AWS |
| [QI Tech Inovacamp](https://github.com/iwsmimsantos/qitech-inovacamp) | Hackathon: plataforma de financiamento educacional com motor de score | Express, Next.js, PostgreSQL |
| [TrackTrade](https://github.com/iwsmimsantos/tracktrade) | Hackathon: tokenização de ativos esportivos na blockchain Stellar | Python, Rust |
| [Hackathon Santa Casa](https://github.com/iwsmimsantos/hackathon-santa-casa) | Hackathon na área de saúde | JavaScript |

Em outubro de 2026, no ideathon do iFood no encontro anual de bolsistas da Fundação Behring, meu grupo ficou em **3º lugar** com o [Food Match](https://github.com/iwsmimsantos/food-match): para quem abre o app e não sabe o que pedir, o iFood oferece uma tela de "quero / não quero" e, a cada escolha, entende melhor o gosto da pessoa até recomendar pratos novos, com base em usuários parecidos.

**Pesquisa:** faço iniciação científica no Inteli, uma revisão sistemática da literatura sobre preconceito regional e pertencimento de jovens em STEM.

Participei do L'Oréal Brandstorm 2026, a competição de inovação da L'Oréal para universitários, e fui semifinalista do Technovation em 2023.

Também participo do Grace Hopper Women's Collective, que apoia mulheres em tecnologia, fui da Liga de Empreendedorismo e Inovação do Inteli e fui selecionada para o Programa Black Finance.

## Stack

**Linguagens:** TypeScript, Python, JavaScript, SQL, C#

**IA:** LLMs, agentes de IA (MCP), engenharia de prompt, NLP (BERT), avaliação de resultados de IA

**Back-end e front-end:** Node.js, FastAPI, GraphQL, APIs REST, React, Next.js

**Dados e infraestrutura:** MySQL, PostgreSQL, BigQuery, AWS, Docker, Terraform, Datadog, CI/CD
