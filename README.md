# Olá, eu sou o David Silva 👋

## 💻 Desenvolvedor Full Stack | Java 21 & Spring Boot 3 | Next.js 16 & TypeScript

Desenvolvedor focado na arquitetura, segurança e deploy de **produtos SaaS reais e em produção**. Combino a solidez, tipagem forte e governança do ecossistema **Java / Spring Boot** no backend com a performance, agilidade e refinamento visual do **Next.js, React e TypeScript** no frontend.

Além de desenvolver soluções para problemas reais do dia a dia, compartilho rotina de engenharia, arquitetura e live coding diário no canal **Clovin DEV**.

---

## 🚀 SaaS & Produtos em Destaque

### 💳 Clovin Finanças — Gestão Orçamentária & Open Finance Brasil
> **Problema & Solução:** O preenchimento manual de planilhas gera abandono e a falta de visibilidade sobre compras parceladas no cartão compromete a renda futura. A plataforma conecta contas e cartões automaticamente via Open Finance e projeta o orçamento mensal sob a regra dinâmica 50/30/20.

<div align="center">

<img src="https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Open_Finance-008080?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Pluggy_API-00C48C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Prisma_ORM_6-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL_Neon-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Auth.js_v5-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/>

</div>

**Destaques de Engenharia & Segurança:**
- **Open Finance Brasil:** Conexão bancária automatizada via API Pluggy com Webhooks assinados via HMAC-SHA256 para conciliação bancária em tempo real.
- **Motor de Parcelamento em Cascata:** Agrupamento atômico de compras parceladas por UUID com projeção automática de parcelas futuras nos meses seguintes.
- **Planejamento Orçamentário 50/30/20:** Alocação de renda dinâmica (Essenciais, Lazer, Futuro) com suporte a rendas extras e parser semântico para gastos em linguagem natural.
- 🟢 **Status:** **Em produção para uso pessoal e convidados.**

🌐 [**Acessar Produto no Ar (Live)**](https://projeto-financas-rouge.vercel.app) | 🔗 [Repositório GitHub](https://github.com/Davidds5/projeto-financas)

---

### 💈 BarberPro — SaaS de Agendamento Profissional & Concorrência Atômica
> **Problema & Solução:** O cabeleireiro autônomo Wesley perdia clientes por double-booking (conflitos de horário nos sábados e horários de pico) e interrupções frequentes durante cortes para responder o WhatsApp. O BarberPro automatiza o autoagendamento self-service com tickets VIP no WhatsApp.

<div align="center">

<img src="https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
<img src="https://img.shields.io/badge/Prisma_ORM_6-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL_Neon-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/JWT_HttpOnly-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/>

</div>

**Destaques de Engenharia & Segurança:**
- **Concorrência Atômica Homologada:** Motor de agendamento com transações serializáveis testado sob concorrência de 50 requisições simultâneas no mesmo milissegundo: **1 confirmação e 49 conflitos HTTP 409 (0 double-booking)**, além de 200 consultas de disponibilidade (50 VUs).
- **UX Sem Fricção:** Agendamento público sem necessidade de cadastro prévio, integração direta para envio de ticket VIP formatado no WhatsApp (`wa.me`).
- **Governança de Sessão & Tolerância:** Cancelamento self-service com tolerância de arrependimento (15 min) e revogação instantânea de sessões administrativas via `tokenVersion`.
- 🟢 **Status:** **Em produção para o cliente Wesley.**

🌐 [**Acessar Produto no Ar (Live)**](https://barberpro-rose.vercel.app) | 🔗 [Repositório GitHub](https://github.com/Davidds5/barberpro)

---

### 🏗️ ObraSync — Gestão Visual de Obras & Portal do Cliente
> **Problema & Solução:** Arquitetos e engenheiros de interiores perdiam horas respondendo clientes no WhatsApp e organizando fotos dispersas. O ObraSync centraliza o diário fotográfico com evolução ponderada de cronograma e portal do cliente em tempo real via Magic Link sem senha.

<div align="center">

<img src="https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Prisma_ORM-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL_Neon-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
<img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge"/>

</div>

**Destaques de Engenharia & Segurança:**
- **Multi-Tenant Estrito (Zero IDOR):** Isolamento de dados automatizado com *Prisma Client Extensions* cobrindo todos os sub-recursos da aplicação.
- **Segurança Binária (AppSec):** Validação de arquivos por *Magic Bytes* no upload para prevenir spoofing de MIME types.
- **Performance & Alta Carga:** Edge Caching CDN com SWR (< 30ms) homologado sob teste de estresse com 1.000 VUs concorrentes com atuação precisa de Rate Limiter.
- **Portal do Cliente:** Link seguro e efêmero (Magic Link) sem atrito de login para acompanhamento direto no celular.
- 🟢 **Status:** **Em produção no Render.**

🌐 [**Acessar Produto no Ar (Live)**](https://obrasync-bf1t.onrender.com) | 🔗 [Repositório GitHub](https://github.com/Davidds5/obrasync)

---

### 💅 BelasUnhas / Manicure API — SaaS Multi-Tenant para Salões & Esmalterias
> **Problema & Solução:** Desenvolvido sob medida para a mãe do desenvolvedor gerenciar de forma autônoma os agendamentos e faturamento. Elimina o encavalamento de horários provocado por procedimentos com durações totalmente distintas (30 min vs 2h) e automatiza cobranças Pix.

<div align="center">

<img src="https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"/>
<img src="https://img.shields.io/badge/Hibernate_Filter_AOP-59666C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Flyway_v17-CC0200?style=for-the-badge&logo=flyway&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge"/>

</div>

**Destaques de Engenharia & Segurança:**
- **Algoritmo de Colisão de Horários:** Cálculo matemático de sobreposição por duração real de serviço (`validateTimeConflict`), acomodando procedimentos de 30 min até 2h com tolerância exata.
- **Multi-Tenancy Dinâmico:** Isolamento por tenant no banco relacional orquestrado via `ThreadLocal` e filtros nativos no Hibernate via interceptor AspectJ (AOP).
- **Segurança Fail-Closed:** Validador de segurança com negação por padrão contra requisições malformadas ou vazamento de dados entre salões (IDOR).
- **Qualidade & DevOps:** 17 migrations Flyway, suíte de testes automatizados com JUnit 5 e Mockito, containerização Docker multi-stage e documentação interativa Swagger.
- 🟢 **Status:** **Em produção no Render.**

🌐 [**Acessar Produto no Ar (Live)**](https://belasunhas.onrender.com) | 🔗 [Repositório GitHub](https://github.com/Davidds5/manicure_api)

---

## 🛠️ Tech Stack & Competências

<div align="center">

### 🚀 Backend & Arquitetura
<img src="https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"/>
<img src="https://img.shields.io/badge/Hibernate_JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/REST_APIs-02569B?style=for-the-badge"/>

<br>

### 🎨 Frontend & Full Stack
<img src="https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
<img src="https://img.shields.io/badge/Shadcn_UI-000000?style=for-the-badge"/>

<br>

### 🛡️ AppSec, Governança & Padrões
<img src="https://img.shields.io/badge/Multi--Tenant_Architecture-4A154B?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Fail--Closed_Security-black?style=for-the-badge"/>
<img src="https://img.shields.io/badge/JWT_HttpOnly-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Atomic_Concurrency-FF6F00?style=for-the-badge"/>
<img src="https://img.shields.io/badge/SOLID_&_Clean_Code-000000?style=for-the-badge"/>

<br>

### 🗄️ Bancos de Dados & ORMs
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Neon_Serverless-00E599?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Prisma_ORM_6-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/Flyway_Migrations-CC0200?style=for-the-badge&logo=flyway&logoColor=white"/>

<br>

### 🧪 Testes, Qualidade & Integrações
<img src="https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Mockito-FFCA28?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white"/>
<img src="https://img.shields.io/badge/Open_Finance_Brasil-008080?style=for-the-badge"/>
<img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white"/>

<br>

### ⚙️ DevOps & Cloud
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
<img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"/>

</div>

---

## 🎥 Canal & Comunidade (Clovin DEV)

Transmito lives diárias desenvolvendo software de ponta a ponta na prática, abordando desde modelagem de dados e arquitetura até testes de carga e resolução de bugs em tempo real.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-David_Silva-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/david-silva-17b2882bb)
[![Portfólio](https://img.shields.io/badge/Portfólio_Web-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://davidds5.github.io/portfolio_clovin/)
[![Currículo](https://img.shields.io/badge/Currículo_Online-2563EB?style=for-the-badge)](https://davidds5.github.io/portfolio_clovin/curriculo_david_pt.html)
[![YouTube](https://img.shields.io/badge/YouTube-Clovin_DEV-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@clovindev)
[![TikTok](https://img.shields.io/badge/TikTok-Clovin_DEV-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://tiktok.com/@clovindev)

</div>

---

## 📫 Contato & Oportunidades
Estou ativamente disponível para oportunidades profissionais como **Desenvolvedor Full Stack / Backend (Java / Spring Boot / TypeScript / Next.js)**.

- 💼 **LinkedIn:** [linkedin.com/in/david-silva-17b2882bb](https://www.linkedin.com/in/david-silva-17b2882bb)
- 🌐 **Portfólio Web:** [davidds5.github.io/portfolio_clovin](https://davidds5.github.io/portfolio_clovin/)
- 📄 **Currículo Web:** [davidds5.github.io/portfolio_clovin/curriculo_david_pt.html](https://davidds5.github.io/portfolio_clovin/curriculo_david_pt.html)
- 📧 **E-mail:** [davis.clovins@gmail.com](mailto:davis.clovins@gmail.com)
