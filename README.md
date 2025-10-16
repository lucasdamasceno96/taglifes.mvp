# taglifes.mvp

Com certeza! Aqui está o `README.md` completamente atualizado com o nome **Taglifes** e o domínio **taglifes.com**, pronto para ser usado na apresentação do seu projeto.

---

# 🩺 Taglifes – Segurança e Tranquilidade a um Scan de Distância

> **Status:** 💡 Ideia / Conceito (a validar)
> **Data de Criação:** 16 de Outubro de 2025
> **Autor:** Lucas Damasceno

---

## 🚀 Visão Geral

**Taglifes** é um SaaS (Software como Serviço) que permite a qualquer pessoa registrar informações essenciais de emergência (nome, tipo sanguíneo, contatos, alergias, etc.) em um perfil online. Esse perfil é vinculado a um **QR Code único**, que pode ser impresso em pulseiras, adesivos e outros produtos, garantindo acesso rápido a dados vitais.

Em caso de acidente, basta escanear o QR Code para exibir uma página pública minimalista, projetada para socorristas e transeuntes acessarem rapidamente as informações que podem salvar uma vida.

---

## 🧠 Propósito

O **Taglifes** nasce com a missão de salvar vidas por meio da tecnologia, oferecendo uma camada extra de segurança e tranquilidade para indivíduos e suas famílias. O objetivo é democratizar o acesso a identificação médica de emergência de forma simples, acessível e confiável.

---

## ⚙️ Funcionalidades (MVP)

- **Cadastro de Usuário:** Sistema de autenticação para gerenciamento de perfis.
- **Criação de Perfis de Emergência:** Formulário para preenchimento de informações vitais:
  - Nome completo e foto
  - Tipo sanguíneo
  - Alergias e condições médicas
  - Contatos de emergência (múltiplos)
  - Plano de saúde
- **Geração de QR Code:** Cada perfil gera um QR Code único com um link público (ex: `taglifes.com/p/lucas-damasceno`).
- **Página de Perfil Pública:**
  - Design limpo, de carregamento instantâneo e otimizado para celulares.
  - Acesso livre, sem necessidade de login.
  - Apenas exibe informações, não permite edição.
- **Área de Membros:** Painel para o usuário editar e gerenciar seus perfis.

---

## 🧩 Arquitetura Técnica Sugerida

- **Frontend:** **Next.js** (para performance, SEO e renderização rápida da página pública via ISR).
- **UI:** **TailwindCSS**.
- **Backend & Banco de Dados:** **Supabase** (PostgreSQL, Auth, Storage).
- **Deploy:** **Vercel**.

---

## 🛠️ Roadmap de Desenvolvimento

| Etapa | Descrição                                   | Status          |
| ----- | ------------------------------------------- | --------------- |
| 1     | Definição do escopo e design das telas      | 🟢 Em andamento |
| 2     | Configuração do Supabase e modelo de dados  | ⚪ A fazer      |
| 3     | Desenvolvimento do frontend em Next.js      | ⚪ A fazer      |
| 4     | Implementação da lógica de perfis e QR Code | ⚪ A fazer      |
| 5     | Deploy na Vercel com domínio customizado    | ⚪ A fazer      |
| 6     | Coleta de feedback com usuários beta        | ⚪ A fazer      |

---

## 💰 Modelo de Monetização

- **Plano Individual Anual:** Assinatura para 1 perfil de emergência.
- **Plano Família Anual:** Assinatura para múltiplos perfis (até 5) com gerenciamento centralizado.
- **Venda de Produtos:** Venda avulsa de pulseiras, adesivos e outros acessórios com o QR Code.

---

## 🔒 Privacidade e Segurança

O **Taglifes** será desenvolvido sob os princípios da **LGPD (Lei Geral de Proteção de Dados)**, garantindo:

- Armazenamento mínimo de informações necessárias.
- Criptografia de dados sensíveis.
- Consentimento explícito do usuário para a exibição pública dos dados do perfil.
- Políticas claras de privacidade e termos de uso.

---

## 🎯 Objetivos de Validação (MVP)

- ✅ Validar o interesse do público em uma solução de segurança pessoal baseada em QR Code.
- ✅ Obter feedback sobre a usabilidade da plataforma com um grupo de usuários reais (atletas, pais, idosos).
- ✅ Identificar o público-alvo com maior engajamento.
- ✅ Medir os custos operacionais para manter o serviço.
