# PUBLICELL

### Plataforma SaaS de atendimento, CRM, ERP e automações

**Projeto pessoal • Desenvolvimento Full Stack • 2026**

O Publicell nasceu da ideia de centralizar diferentes necessidades de uma empresa em um único sistema.

Em vez de utilizar ferramentas separadas para atendimento, vendas, estoque, financeiro e automações, desenvolvi uma plataforma que conecta esses processos dentro do mesmo ambiente.

O sistema reúne atendimento via WhatsApp, CRM em Kanban, ERP comercial e financeiro, gestão de equipes, automações com N8N e integrações com inteligência artificial.

**React • TypeScript • Supabase • PostgreSQL • Tailwind CSS • WAHA • Meta Cloud API • N8N • OpenAI • Gemini**

---

## VISÃO GERAL DO SISTEMA

  <img width="1904" height="1079" alt="img1" src="https://github.com/user-attachments/assets/ec518b0a-4c17-427f-b63a-9638e41e8983" />
> Dashboard principal do Publicell, reunindo informações e acessos aos diferentes módulos da plataforma.

---

# O PROBLEMA

Durante o desenvolvimento, pensei em um problema comum de pequenas e médias empresas: várias ferramentas sendo utilizadas para cuidar de partes diferentes da mesma operação.

O atendimento acontece em um lugar.

Os clientes ficam registrados em outro.

O estoque é controlado separadamente.

O financeiro utiliza outra ferramenta.

E automações acabam dependendo de mais serviços externos.

Minha proposta com o Publicell foi experimentar como todas essas áreas poderiam conversar dentro de uma única plataforma.

---

# ATENDIMENTO VIA WHATSAPP

O módulo de atendimento permite que diferentes operadores gerenciem conversas de WhatsApp dentro do sistema.

Entre as funcionalidades desenvolvidas estão organização de atendimentos, departamentos, transferência de conversas, respostas rápidas, mensagens programadas, notas internas e histórico de comunicação.

<img width="1919" height="963" alt="atendimento" src="https://github.com/user-attachments/assets/3fb11cf1-a0e2-4772-be81-aae6ac172078" />
> Central de atendimento multicanal com conversas, histórico do cliente e ferramentas para gerenciamento do atendimento.

# CRM E PIPELINE DE VENDAS

Também desenvolvi um CRM visual utilizando um modelo Kanban.
  
Cada oportunidade pode avançar entre diferentes etapas do processo comercial, permitindo acompanhar contatos, responsáveis, tags, produtos de interesse e valores estimados.

<img width="1917" height="961" alt="pipe" src="https://github.com/user-attachments/assets/6c822f9a-dabc-40b2-a164-26e0732fbb7c" />
> Pipeline comercial do Publicell, utilizado para acompanhar oportunidades durante diferentes etapas do processo de venda.


# ERP COMERCIAL E FINANCEIRO

Uma das partes que mais expandi durante o projeto foi o módulo ERP.

Ele concentra produtos e serviços, controle de estoque, movimentações, clientes, ordens de serviço, contas a pagar e contas a receber.

O objetivo foi fazer com que atendimento, CRM e operação comercial compartilhassem os mesmos dados, evitando cadastros isolados.

<img width="1891" height="754" alt="vendass" src="https://github.com/user-attachments/assets/c693f294-0afa-482a-b48f-515f3e359468" />
> Dashboard do ERP com indicadores financeiros e operacionais.

<img width="463" height="793" alt="estoque_saida" src="https://github.com/user-attachments/assets/22e963fa-74f8-491d-9e4e-8b86b46b6730" />
<img width="482" height="615" alt="estoque_entrada" src="https://github.com/user-attachments/assets/2a020274-ffb0-4464-93e6-722da8210495" />
<img width="1903" height="958" alt="estoque" src="https://github.com/user-attachments/assets/325809e5-ebb2-49a4-8adf-612415aaaf70" />
<img width="1913" height="959" alt="cliente" src="https://github.com/user-attachments/assets/d3a4778a-2245-4a4b-a054-ef1aaed7af72" />
<img width="1903" height="960" alt="Receber" src="https://github.com/user-attachments/assets/f2fa6a63-0f78-460d-81ba-0ea005d81765" />
<img width="826" height="682" alt="produtos02" src="https://github.com/user-attachments/assets/604d0ca8-c8a1-4187-9240-411afa55482f" />
<img width="1920" height="959" alt="Produtos" src="https://github.com/user-attachments/assets/7aa80b06-ac16-4f72-b57d-044f09f0b208" />
<img width="1917" height="961" alt="pipe" src="https://github.com/user-attachments/assets/20d932ba-27a8-4573-b815-f1b5a0c03999" />
<img width="1903" height="961" alt="Pagar" src="https://github.com/user-attachments/assets/c2be2bf3-b4ea-4ae4-95b7-f669e76dff6d" />
<img width="1919" height="961" alt="OS" src="https://github.com/user-attachments/assets/2b8e2c6b-292c-44a3-84a8-b8da5f841011" />

---

# UM DOS MAIORES DESAFIOS

O projeto cresceu muito mais do que imaginei inicialmente.

Quanto mais módulos comecei a conectar, mais percebi que criar um sistema não era apenas criar telas.

Passei a lidar com autenticação, banco de dados, regras de negócio, permissões, integrações externas, comunicação em tempo real, deploy e problemas que só apareciam quando diferentes partes do sistema começavam a conversar.

Em vários momentos precisei voltar, reorganizar estruturas e refazer soluções.

E essa acabou sendo uma das partes mais importantes do projeto.

---

# O QUE APRENDI

O Publicell foi um dos projetos em que mais aprendi justamente porque precisei sair constantemente daquilo que eu já sabia.

Trabalhei e estudei conceitos envolvendo:

**Frontend**
React, TypeScript, componentes, estados, rotas e interfaces.

**Backend**
Banco relacional, autenticação, APIs, Edge Functions e Webhooks.

**Banco de dados**
PostgreSQL, relacionamentos, migrations e políticas de segurança.

**Integrações**
WhatsApp, Meta Cloud API, WAHA e N8N.

**Inteligência Artificial**
Integração de modelos e criação de agentes.

**Produto**
Comecei a pensar não apenas em como desenvolver uma funcionalidade, mas em como diferentes partes de um sistema precisam funcionar juntas para resolver um problema real.

---

## TECNOLOGIAS

React 18
TypeScript
Vite
Tailwind CSS
Radix UI
Supabase
PostgreSQL
Supabase Auth
Realtime WebSockets
Edge Functions
WAHA
WhatsApp Cloud API
N8N
OpenAI
Google Gemini
