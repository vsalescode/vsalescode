<div align="center">

# João Victor Sales

**Desenvolvedor Backend · Java & Spring Boot · Node.js · Sistemas em tempo real**

Brasil · Disponível para vagas de backend (júnior / estágio), remoto ou híbrido

<a href="https://linkedin.com/in/vsalescode"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://portfolio-vsalescode.vercel.app"><img src="https://img.shields.io/badge/Portfólio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="mailto:vsalescode@gmail.com"><img src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>

</div>

## Em números

<div align="center">
<img src="https://img.shields.io/badge/REGISTROS_INGERIDOS-2_MILH%C3%95ES-58A6FF?style=for-the-badge&labelColor=0D1117" alt="Registros Ingeridos: 2 MILHÕES" />
<img src="https://img.shields.io/badge/M%C3%93DULOS_PORTADOS-8%2B-3FB950?style=for-the-badge&labelColor=0D1117" alt="Módulos Portados: 8+" />
<img src="https://img.shields.io/badge/ESTANDES_AO_VIVO-200%2B-F778BA?style=for-the-badge&labelColor=0D1117" alt="Estandes Ao Vivo: 200+" />
<img src="https://img.shields.io/badge/USU%C3%81RIOS_NO_BETA-~10-D29922?style=for-the-badge&labelColor=0D1117" alt="Usuários No Beta: ~10" />
</div>

## Sobre mim

Desenvolvo backends: APIs REST, autenticação, pipelines de dados e funcionalidades em tempo real. Minha stack principal é Java com Spring Boot, e também trabalho com TypeScript e Node.js.

Em 2026, no estágio na Hiwis, entreguei sistemas para três clientes (VTEX, MAXI e Fullcine) que as equipes passaram a usar no dia a dia, de um pipeline com 2 milhões de registros a uma planta 3D sincronizada ao vivo durante o VTEX DAY. Desde então sigo construindo projetos completos, da modelagem do banco aos testes e à documentação.

Estudo Engenharia de Software na UNINTER desde 2025.

## Projetos

<table>
<tr>
<td width="50%" valign="top">

### [Mini ERP](https://github.com/vsalescode/mini-erp)
API de controle de estoque e vendas, construída módulo a módulo (em andamento).

`Java 21` `Spring Boot` `PostgreSQL` `Flyway` `Testcontainers` `Docker`

Arquitetura hexagonal modular documentada em ADRs, migrações versionadas com Flyway e testes de integração contra um PostgreSQL real via Testcontainers.

</td>
<td width="50%" valign="top">

### [Nilo](https://nilovoice.vercel.app)
App desktop de comunicação por voz e comunidades, com compartilhamento de tela. Em beta fechado, com cerca de 10 usuários e 7 versões lançadas.

`TypeScript` `React` `Electron` `Fastify` `Socket.IO` `WebRTC` `PostgreSQL` `Prisma`

Voz e tela compartilhada em tempo real com WebRTC, presença e canais com Socket.IO, autenticação JWT com renovação de sessão e atualização automática do app no Windows.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [AppyFlow](https://github.com/vsalescode/appyflow)
Assistente self-hosted que encontra vagas, avalia a compatibilidade com o seu perfil e gera currículos personalizados em LaTeX/PDF.

`TypeScript` `Next.js` `Prisma` `PostgreSQL` `Zod` `Vitest` `Docker`

Leitura do currículo com IA e saída estruturada, em que cada informação extraída guarda o trecho original como evidência. Arquitetura em camadas, autenticação com Argon2 e worker de busca com provedores plugáveis.

</td>
<td width="50%" valign="top">

### [Iris](https://github.com/vsalescode/iris)
Assistente de voz para Windows que abre programas, cuida de arquivos e do Gmail e lembra de conversas anteriores.

`Python` `FastAPI` `WebSocket` `Gemini Live` `SQLite` `Three.js`

Voz em tempo real via WebSocket, com modo reserva quando a Gemini Live cai. Ferramentas protegidas por permissões em três níveis (autônomo, perguntar, proibido), confirmação antes de enviar e-mails, log de auditoria e proteção contra ordens escritas dentro de e-mails. Memória de longo prazo em SQLite.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [API Vendas BI](https://github.com/vsalescode/api-vendas-bi)
API de vendas com painel de faturamento mensal.

`Java 21` `Spring Boot` `PostgreSQL` `MapStruct` `Bean Validation`

Endpoints com paginação, filtros por período e tratamento de erros, e um painel de faturamento que lê de uma view do PostgreSQL.

</td>
<td width="50%" valign="top">

### [netblame](https://github.com/vsalescode/netblame)
Descobre onde a sua conexão está falhando: no PC, no roteador, no provedor ou na rota até o servidor.

`Python` `Windows` `Redes`

Testa gateway, DNS, TCP e cada salto da rota em paralelo e aponta o trecho com defeito por eliminação. Gera um relatório HTML bilíngue, sem precisar de administrador nem de dependências externas.

</td>
</tr>
</table>

Vale ver também: [microsserviços com Spring Boot e OpenFeign](https://github.com/vsalescode/bff-agendador-tarefas) (BFF + serviços de usuário, tarefas e notificações, com PostgreSQL e MongoDB).

## Experiência

### Hiwis · Estagiário de Desenvolvimento de Software e IA
*mar/2026 – ago/2026 · remoto · projetos sob demanda para clientes*

**MAXI** · hub interno de gestão comercial e financeira, cerca de 20 usuários
- API em Java que ingere CSV no PostgreSQL, com tratamento, normalização e validação de cerca de 2 milhões de registros.
- APIs REST em Node.js/Express com autenticação JWT, controle de acesso, filtros e paginação, e consultas SQL otimizadas com índices e cache.
- Painéis de BI dentro do Hub, como a análise de equipamentos (utilização, faturamento, payback e depreciação), usada para decidir quais equipamentos estão em eventos, quais já se pagaram e quais precisam de manutenção.
- Portal "Meus Eventos": o vendedor consulta seus eventos, custos e comissão, e o administrador define comissões e custos e ajusta valores importados de uma API externa.
- Radar Comercial, a pedido do comercial: busca automática de eventos e clientes em potencial (SerpAPI e cron jobs), com análise por IA e scoring de leads. O comercial passou a prospectar clientes pela ferramenta.
- Atendimento via WhatsApp e registro de ocorrências automatizados com n8n e IA.

**Fullcine** · adaptação multiempresa do Hub
- Portei todos os módulos do Hub da MAXI (mais de 8) para a Fullcine, reconectando-os às fontes de dados dela e refazendo o tratamento dos dados. Passaram a ser usados no dia a dia da empresa.
- Separei autenticação, permissões e dados por empresa e implementei as regras financeiras da Fullcine.

**VTEX** · painel de montagem do VTEX DAY 2026
- Transformei a planta 2D em PNG do evento em um painel 3D interativo (React, TypeScript e Three.js) para acompanhar a montagem de mais de 200 estandes: progresso por frente de obra, status, atrasos e filtros.
- Login por usuário, fotos do estado dos estandes e sincronização em tempo real para 5+ usuários com Firebase/Firestore. Usado no evento, com ajustes publicados durante a operação.

> "Durante esse período, demonstrou comprometimento, boa postura profissional e abertura para receber feedbacks, apresentando evolução na qualidade de suas entregas à medida que desenvolvia novas competências."
> Hélder Wege, fundador da Hiwis e meu supervisor direto ([recomendação no LinkedIn](https://linkedin.com/in/vsalescode))

### Desenvolvedor freelancer
*jun/2020 – ago/2025 · atuação esporádica, em sua maioria projetos privados*
- HUDs e interfaces para servidores de FiveM (HTML, CSS, JavaScript e Lua), sites, landing pages, bots para Discord e integrações com APIs, com correção de bugs e refatoração.

## Stack

<img src="https://skillicons.dev/icons?i=java,spring,ts,nodejs,react,nextjs,python,postgres,mysql,mongodb,prisma,docker,git,postman&theme=dark" />

- **Backend:** Java, Spring Boot, Node.js, Express, Fastify, Next.js, REST, JWT, OpenFeign
- **Dados:** PostgreSQL, MySQL, MongoDB, Firestore, Prisma, JPA, Flyway, BI
- **Tempo real:** WebSocket, Socket.IO, WebRTC
- **Testes e ferramentas:** JUnit 5, Mockito, Testcontainers, Jest, Vitest, Docker, GitHub Actions, n8n

**Idiomas:** português (nativo), inglês (intermediário), espanhol (básico)
