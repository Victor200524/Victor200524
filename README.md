<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=Victor%20Hugo%20Donaire&fontSize=42&fontColor=58a6ff&animation=fadeIn&fontAlignY=38&desc=Desenvolvedor%20Full%20Stack%20em%20forma%C3%A7%C3%A3o%20%7C%20Java%20%C2%B7%20Spring%20Boot%20%C2%B7%20React&descAlignY=58&descColor=8b949e"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Ol%C3%A1%2C+eu+sou+o+Victor+Hugo+%F0%9F%91%8B;Desenvolvedor+Full+Stack+em+forma%C3%A7%C3%A3o;Java+%C2%B7+Spring+Boot+%C2%B7+React+%C2%B7+Next.js;Buscando+est%C3%A1gio+em+desenvolvimento+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victor-hugo-donaire-de-oliveira-31b778165/)
[![Email](https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:victor.donaire@hotmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/victorh_donaire/)
![Status](https://img.shields.io/badge/Dispon%C3%ADvel%20para-Est%C3%A1gio-2ea44f?style=for-the-badge)

</div>

---

## 👨‍💻 Sobre mim

Estudante do **8º termo de Ciência da Computação na Unoeste** (Presidente Prudente, SP). Desenvolvo aplicações web full stack com **Java e Spring Boot** no back-end e **Next.js, React e TypeScript** no front-end.

Antes da computação, programei máquinas CNC na indústria e coordenei cronogramas de projetos audiovisuais. Foi lá que aprendi a trabalhar com prazo, precisão e gente.

- 🔭 **Construindo agora:** sistema de gestão da Paróquia São Miguel Arcanjo (voluntário)
- ⚙️ **Próximo passo nele:** confirmação automática de pagamentos via webhook do Mercado Pago
- 🎓 **Na faculdade:** TCC em visão computacional com redes neurais
- 🎯 **Buscando:** estágio em desenvolvimento

---

## 🚀 Projetos em destaque

### ⛪ Sistema de Gestão – Paróquia São Miguel Arcanjo
> 🟡 *Em desenvolvimento · Projeto voluntário · Desenvolvido sozinho, do banco ao front-end*

Sistema que vai atender secretaria, padre, coordenadores de pastorais e acampamentos e participantes de retiros.

```mermaid
flowchart LR
    U["👤 Usuários<br/>6 perfis de acesso"] --> F["🌐 Front-end<br/>Next.js 16 · React 19 · TypeScript"]
    F -->|"REST + JWT"| A["⚙️ API REST<br/>Spring Boot · Spring Security<br/>~17 controllers"]
    A --> D[("🐘 PostgreSQL<br/>Spring Data JPA")]
    A -->|"Link de pagamento"| M["💳 Mercado Pago SDK"]
    M -.->|"Webhook (em desenvolvimento)"| A
```

<details>
<summary><b>📋 Ver funcionalidades</b></summary>

<br/>

- 🔐 Autenticação com **Spring Security + JWT** e controle de acesso com 6 perfis (Coordenador Geral, Padre, Secretaria, Coordenador de Acampamento, Servo, Campista)
- ✅ Fluxo de aprovação de cadastros (ativo, inativo e pendente)
- 🏕️ Gestão de acampamentos com geração de links de pagamento via **Mercado Pago**
- 📦 Controle de estoque com entradas, saídas, transferências entre acampamentos e perdas por validade, com saldo recalculado automaticamente
- 📝 Formulários de inscrição dinâmicos: a coordenação cria as perguntas sem mexer no código
- ⛪ Cadastro de comunidades, pastorais, horários de missa e doações
- 📊 Dashboard com estatísticas e últimas movimentações
- 📖 API documentada com **Swagger/OpenAPI**

</details>

<!-- Se o repositório for público, descomente a linha abaixo com o link: -->
<!-- 🔗 **[Ver repositório](https://github.com/Victor200524/NOME-DO-REPO)** -->

---

### 🏭 Autoflex – Controle de Estoque e Planejamento de Produção
> 🟢 *Concluído · Desenvolvido como teste técnico para vaga Full Stack*

Calcula a produção máxima possível com o estoque disponível e **sugere o plano de produção de maior faturamento**, priorizando os produtos de maior valor.

![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_(Neon)-316192?style=flat-square&logo=postgresql&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

- Algoritmo de priorização baseado em valor e disponibilidade de insumos
- Histórico de produção persistente para rastrear estoque e faturamento
- Exportação de relatórios em PDF (jsPDF) e API documentada com Swagger

🔗 **[Ver repositório](https://github.com/Victor200524/NOME-DO-REPO)**

---

### 🧠 TCC – Estimativa de Volume Corporal a partir de Imagens 2D
> 🟡 *Em andamento · Trabalho de Conclusão de Curso*

Pipeline em **Python** que gera **1.000 avatares sintéticos** com o modelo **SMPL** e treina redes neurais **MLP** sobre medidas antropométricas para estimar o volume do corpo humano.

| Métrica | Melhor resultado |
|---|---|
| **R²** | 99,55% |
| **Erro médio (MAE)** | 0,90 litro |

🔗 **[Ver repositório](https://github.com/Victor200524/NOME-DO-REPO)**

---

## 🛠️ Stack

<table>
  <tr>
    <td><b>Back-end</b></td>
    <td>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
      <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"/>
      <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>Front-end</b></td>
    <td>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>Banco de dados</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>Ferramentas</b></td>
    <td>
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
      <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"/>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
      <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>IA / Dados</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
    </td>
  </tr>
</table>

---

## 📚 Formação e certificações

- 🎓 **Bacharelado em Ciência da Computação** – Unoeste · 2023 – 2026
- ☁️ **Microsoft Azure Fundamentals (AZ-900)**
- 🍎 **Algoritmos e POO com Swift** – HackaTruck MakerSpace · 2025
- 🔧 **Aprendizagem Industrial em Mecânica de Usinagem** – SENAI · 2020 – 2021

---

## 🐍 Contribuições

<div align="center">

<!-- Requer o workflow .github/workflows/snake.yml rodando. Se não for usar, apague esta seção inteira. -->
<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/Victor200524/Victor200524/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Victor200524/Victor200524/output/github-contribution-grid-snake.svg"/>
  <img alt="Cobrinha de contribuições" src="https://raw.githubusercontent.com/Victor200524/Victor200524/output/github-contribution-grid-snake-dark.svg"/>
</picture>

</div>

---

<div align="center">

### 💬 Vamos conversar?

Se você está contratando para **estágio em desenvolvimento**, me chama no [LinkedIn](https://www.linkedin.com/in/victor-hugo-donaire-de-oliveira-31b778165/) ou por [e-mail](mailto:victor.donaire@hotmail.com). 🤝

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=120&section=footer"/>

</div>
