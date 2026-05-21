# Olá, eu sou o Eduardo Nogueira! 👋

<div align="center">
  <img src="https://img.shields.io/badge/Psicologia%20%F0%9F%A7%A0-Formado-9b59b6?style=for-the-badge" alt="Psicologia" />
  <img src="https://img.shields.io/badge/ADS%20%F0%9F%92%BB-Graduando-3498db?style=for-the-badge" alt="ADS" />
  <img src="https://img.shields.io/badge/Empreendedor%20%F0%9F%92%BC-WASD-2ecc71?style=for-the-badge" alt="WASD" />
</div>

---

### 🧠 Sobre Mim
Sou graduado em **Psicologia** e atualmente cursando **Análise e Desenvolvimento de Sistemas** pela faculdade Descomplica. Acredito que a combinação entre o entendimento do comportamento humano e a engenharia de software me dá uma perspectiva única para criar sistemas que não apenas funcionam tecnicamente, mas que são intuitivos e focados na melhor experiência do usuário.

Sou cofundador e desenvolvedor na **[WASD Soluções Digitais](https://wasd.tec.br)**, uma agência especializada no desenvolvimento de sistemas web sob medida, integrações de APIs e soluções com Inteligência Artificial. 

*   📍 Localizado em **Itupeva / Jundiaí - SP**
*   🌱 Estudando e implementando ativamente **Inteligência Artificial** aplicada a automações de processos de negócios.

---

### 💼 Empreendimentos & Projetos em Destaque

#### 🚀 **[WASD Soluções Digitais](https://wasd.tec.br)** (Agência de Software)
*   **O que é:** Agência de desenvolvimento de software sob medida, especializada em sistemas web robustos, automações inteligentes de processos com IA e integrações complexas de APIs.
*   **Atuação e Engenharia de Infraestrutura:** 
    *   **Infraestrutura Cloud**: Arquitetura corporativa implantada em instâncias dedicadas **Oracle Cloud Infrastructure (OCI Ampere A1 Flex ARM64)** rodando sob Linux Ubuntu.
    *   **Containerização**: Virtualização e orquestração de ecossistemas de microsserviços via **Docker & Docker Compose**, garantindo portabilidade e alta eficiência.
    *   **Segurança & Roteamento**: Configuração de proxy reverso utilizando **Nginx Proxy Manager**, com geração e renovação automática de certificados SSL/TLS (Let's Encrypt) para tráfego criptografado e seguro de múltiplos domínios e APIs.
    *   **Automação & ETL**: Construção de fluxos e pipelines automatizados com a ferramenta **n8n**, conectando CRM, canais de mensageria e APIs de modelos de linguagem (LLMs) para otimizar rotinas empresariais.

#### 📰 **Jornal Expressão** (Portal de Notícias & CMS Comercial)
*   **O que é:** Um ecossistema completo de produção para um portal de notícias real, composto pelo site público otimizado e por um painel administrativo (CMS) personalizado de alta performance.
*   **Arquitetura & Detalhes Técnicos:**
    *   **Frontend & UX**: Single Page Application (SPA) construída com **React 18**, **TypeScript**, **Vite** e **Tailwind CSS**. Interface premium otimizada com controle de acessibilidade de fontes, suporte a modo escuro nativo e pré-carregamento dinâmico de rotas (*prefetching*).
    *   **Editor WYSIWYG**: Editor rico baseado no **TipTap** que permite escrita fluida com **extensões personalizadas de incorporação de mídias responsivas** (YouTube, Vimeo, etc.) e controle avançado de estado local para evitar perda de rascunhos em alternância de abas.
    *   **Visualização em Tempo Real (Preview)**: Aba de preview integrada que emula com fidelidade o design público exato da matéria.
    *   **Backend Serverless & RBAC**: Banco PostgreSQL gerenciado no **Supabase** com políticas estritas de segurança em nível de linha (**RLS**). Autenticação e controle de cargos baseados em papéis (**RBAC**) para três níveis (`admin`, `journalist`, `intern`).
    *   **Edge Computing & Deno**: Funções de borda (**Supabase Edge Functions**) escritas em TypeScript para Deno:
        *   `publish-scheduled`: Função acionada via **cron job** no Linux a cada minuto para automatizar a publicação de notícias pré-agendadas pelos redatores.
        *   `admin-create-user`: Registro seguro de usuários com cargos específicos.
        *   `rss` & `sitemap`: Geração dinâmica sob demanda de feeds XML para SEO e Google News.
    *   **Garantia de Qualidade**: Cobertura de testes automatizados de componentes e integração utilizando **Vitest** e **React Testing Library** (24 testes).

#### 📱 **AlwaysMed** (Mobile App & SaaS Farmacológico)
*   **O que é:** Um aplicativo mobile de lembretes e controle de estoque de medicamentos de uso pessoal e para dependentes, operando em modelo de negócios Freemium.
*   **Arquitetura & Detalhes Técnicos:**
    *   **Desenvolvimento Híbrido**: Desenvolvido com **React 18** e **TypeScript** empacotado como aplicativo nativo (Android e iOS) através do **Capacitor 8**, garantindo código base unificado e performance nativa.
    *   **Gestão de Assinaturas e Compras In-App**: Integração com o SDK do **RevenueCat** para controle de compras no aplicativo (modelo vitalício premium).
    *   **Mecanismo de Lembretes & Alarmes**: Sistema dinâmico e insistente para alertas de medicamentos estruturado no app.
    *   **Modo Cuidador & Sincronização**: Compartilhamento e sincronização em tempo real de agendas médicas entre múltiplos dispositivos utilizando as APIs e banco do **Supabase**.
    *   **Internacionalização (i18n)**: Suporte completo e dinâmico a múltiplos idiomas (Português, Inglês e Espanhol) estruturado com a biblioteca **react-i18next**.
    *   **UI Acessível & Estilização**: Componentes de interface responsivos e altamente acessíveis criados com **Radix UI** e customizados através de classes **Tailwind CSS**.

---

### 🛠️ Tecnologias e Ferramentas

<table>
  <tr>
    <td valign="top" width="50%">
      <h4>Backend & Linguagens</h4>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
      <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
    </td>
    <td valign="top" width="50%">
      <h4>Frontend, UI & Mobile</h4>
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
      <img src="https://img.shields.io/badge/Capacitor-111111?style=for-the-badge&logo=capacitor&logoColor=119EFF" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h4>Banco de Dados, Cloud & SaaS</h4>
      <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Supabase-181818?style=for-the-badge&logo=supabase&logoColor=3ECF8E" />
      <img src="https://img.shields.io/badge/RevenueCat-F25F5C?style=for-the-badge&logo=revenuecat&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
    </td>
    <td valign="top" width="50%">
      <h4>Qualidade & Testes</h4>
      <img src="https://img.shields.io/badge/Vitest-7A9B3E?style=for-the-badge&logo=vitest&logoColor=white" />
      <img src="https://img.shields.io/badge/Testing_Library-E33332?style=for-the-badge&logo=testing-library&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h4>Automações & Ferramentas</h4>
      <img src="https://img.shields.io/badge/n8n-FF6D5A?style=for-the-badge&logo=n8n&logoColor=white" />
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
      <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
      <img src="https://img.shields.io/badge/Linux_Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
    </td>
    <td valign="top" width="50%">
    </td>
  </tr>
</table>

---

### 🎓 Formação Relevante
*   **Graduação em Análise e Desenvolvimento de Sistemas** — Faculdade Descomplica *(Em andamento)*
*   **Desenvolvedor Web Full Stack** — *Generation Brasil* (447 horas de carga horária focadas em Java, Spring Boot, React, metodologias ágeis e desenvolvimento de mentalidades/soft skills)
*   **Bacharelado em Psicologia** — *Faculdade de Psicologia de formação base*

---

### 🤝 Conecte-se Comigo

<div align="left">
  <a href="https://www.linkedin.com/in/eduardo-nogueira-silva" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:eduardo7_@hotmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://wasd.tec.br" target="_blank">
    <img src="https://img.shields.io/badge/Website_WASD-000000?style=for-the-badge&logo=web&logoColor=white" alt="WASD Soluções" />
  </a>
</div>
