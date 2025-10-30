# 🏷️ Taglifes.com

**Segurança para sua família a um scan de distância.**

> Projeto em construção — lançamento oficial previsto para **Dezembro de 2025**.

---

## 🌎 Visão do Projeto

O **Taglifes.com** é uma plataforma que conecta **identificação inteligente** com **segurança pessoal**.  
A proposta é simples: qualquer pessoa (ou pet) pode ter um **perfil de emergência** acessível via **QR Code** — presente em **pulseiras, adesivos ou coleiras**.  
Em situações de emergência, basta escanear o código para ter acesso imediato às **informações vitais** do usuário.

### Exemplos de uso

- 👧 Crianças com pulseiras de identificação.
- 🐶 Pets com coleiras QR Code.
- 🧓 Idosos com condições médicas específicas.
- 🏍️ Motociclistas e esportistas com adesivos em capacetes ou equipamentos.

---

## 🚀 Objetivo

Garantir **segurança e tranquilidade** por meio de tecnologia acessível, simples e de baixo custo, possibilitando que qualquer pessoa tenha um **perfil digital de emergência** com informações essenciais como:

- Nome, tipo sanguíneo, alergias e plano de saúde.
- Contatos de emergência.
- Histórico médico básico.

---

## 🧩 Estrutura do Projeto

| Camada              | Tecnologia                | Descrição                                                                                                  |
| ------------------- | ------------------------- | ---------------------------------------------------------------------------------------------------------- |
| **Frontend**        | HTML5 + Tailwind CSS      | Site estático, responsivo e rápido. Hospedado gratuitamente (GitHub Pages ou Vercel).                      |
| **Backend (MVP)**   | PocketBase ou Supabase    | Backend serverless, com autenticação, banco de dados e API pronta. Ideal para prototipagem com custo zero. |
| **Banco de Dados**  | PostgreSQL (via Supabase) | Gerencia perfis, planos e QR Codes. Gratuito até o limite de uso do plano.                                 |
| **QR Code Service** | `qrcode` (lib JS)         | Geração local de QR Codes sem dependência de APIs externas.                                                |
| **Infraestrutura**  | Vercel / Cloudflare Pages | Hospedagem gratuita, SSL incluso, e deploy automatizado via Git.                                           |
| **Domínio**         | `taglifes.com`            | Domínio principal com redirecionamento para as páginas estáticas.                                          |

---

## 💸 Estratégias de Baixo Custo

A arquitetura foi planejada para **minimizar custos fixos e de manutenção**.  
Algumas práticas adotadas:

1. **Frontend estático**

   - Sem necessidade de servidor dedicado.
   - Hospedagem gratuita (Vercel ou GitHub Pages).
   - Carregamento ultra rápido via CDN.

2. **Backend serverless (PocketBase ou Supabase)**

   - Sem custo inicial.
   - Escalabilidade automática conforme o número de usuários.
   - Eliminação de custos com VPS ou containers.

3. **Banco de dados gratuito (PostgreSQL/Supabase)**

   - Inclui autenticação, storage e REST API.
   - Suficiente para o MVP e primeiros milhares de usuários.

4. **Infraestrutura minimalista**

   - Zero custos com load balancers, Kubernetes ou instâncias cloud.
   - Uso intensivo de CDN e cache para reduzir requisições diretas ao backend.

5. **Pagamentos simples (Stripe ou Mercado Pago Checkout)**
   - Cobrança pontual por plano (sem recorrência).
   - Integração direta no frontend.

---

## 🧱 Planos Disponíveis (Previstos)

| Plano         | Valor            | Recursos                                                    |
| ------------- | ---------------- | ----------------------------------------------------------- |
| **Modo Demo** | Gratuito         | Preenchimento de perfil e geração de QR Code (não público). |
| **Básico**    | R$ 9,90 (único)  | Perfil ativo com informações essenciais.                    |
| **Premium**   | R$ 29,90 (único) | Alergias, múltiplos contatos e histórico médico.            |
| **Família**   | R$ 79,90 (único) | Até 5 perfis Premium + painel de gestão.                    |

---

## 📅 Roadmap

| Fase                               | Período          | Entregas                                                            |
| ---------------------------------- | ---------------- | ------------------------------------------------------------------- |
| **Fase 1 — MVP Estático**          | Out–Dez/2025     | Landing page, captação de interessados e lista de espera.           |
| **Fase 2 — Backend & QR Codes**    | Jan–Mar/2026     | Criação de perfis, geração de QR Codes e links personalizados.      |
| **Fase 3 — Produtos Físicos**      | Abr–Jun/2026     | Pulseiras, adesivos e coleiras personalizadas.                      |
| **Fase 4 — App Mobile (Opcional)** | 2º semestre/2026 | App nativo para Android/iOS com notificações e atualização offline. |

---

## 🧠 Filosofia Técnica

> "Escalabilidade começa na simplicidade."

- Foco inicial em **entregar valor**, não complexidade.
- Evitar microserviços e cloud complexa no MVP.
- Crescimento orgânico conforme a base de usuários.
- Cada decisão técnica deve ser guiada por **baixo custo + alta confiabilidade**.

---

## 🧪 Tecnologias Futuras (Planejadas)

- **Next.js + Supabase Auth** → para páginas dinâmicas e perfis públicos.
- **Edge Functions (Cloudflare Workers)** → para geração de QR Code instantânea.
- **Stripe Webhooks** → para automação dos upgrades de plano.
- **IA (versão futura)** → sugestões automáticas de informações médicas a partir de prompts.

---

## 📧 Contato e Colaboração

Quer colaborar, testar ou sugerir melhorias?  
Entre em contato:

**Lucas Damasceno**  
📩 [contato@taglifes.com](mailto:contato@taglifes.com)  
🌐 [https://taglifes.com](https://taglifes.com)

---

## 🛡️ Licença

Este projeto está licenciado sob a **MIT License** — uso livre para fins pessoais e acadêmicos, com atribuição.

---

> _"Taglifes.com é mais que tecnologia — é segurança e tranquilidade a um scan de distância."_  
> — Equipe Taglifes
