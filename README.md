# 🇧🇷 VetorCerto

**Plataforma pública de inclusão social e produtiva — Conectando talentos locais a oportunidades de trabalho digno.**

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Licença](https://img.shields.io/badge/license-Apache%202.0-blue)
![Versão](https://img.shields.io/badge/version-1.0.0-green)

---

## 📖 Sobre o Projeto

O **VetorCerto** é uma plataforma digital que conecta **trabalhadores autônomos** (pedreiros, eletricistas, diaristas, cuidadores, etc.) a **cidadãos e empresas** que precisam de serviços. Com foco em **inclusão social, geração de renda e trabalho digno**, o sistema utiliza **ciência de dados e geolocalização** para mapear a demanda por bairro e direcionar a mão de obra de forma inteligente.

Alinhado aos **ODS 8 (Trabalho Decente)** e **ODS 11 (Cidades Sustentáveis)**, o VetorCerto nasceu em Guarapuava (PR) com potencial de escala nacional.

---

## 🎯 Objetivos

- **Trabalho digno:** Valorizar o trabalhador autônomo brasileiro.
- **Inclusão produtiva:** Facilitar o acesso ao mercado para profissionais informais.
- **Gestão baseada em dados:** Oferecer aos gestores públicos indicadores territoriais de demanda.
- **Cidades sustentáveis:** Integrar territórios urbanos por meio de dados de demanda por bairro.

---

## 👥 Perfis de Usuários

| Perfil | Descrição |
| :--- | :--- |
| **Cidadão** | Solicita serviços em sua região. |
| **Profissional (Prestador)** | Oferece serviços e atende solicitações. |
| **Gestor Público** | Consulta KPIs, mapa de calor e relatórios. |
| **Coordenador** | Gerencia todo o sistema, usuários e conteúdos. |

---

## 🛠️ Tecnologias Utilizadas

| Camada | Tecnologia |
| :--- | :--- |
| **Frontend** | React 19, TypeScript, Tailwind CSS, Vite |
| **Backend** | Supabase (PostgreSQL, Auth, Realtime) |
| **Mapas** | Google Maps Platform (Geocoding, Maps JS API) |
| **Design** | Tokens com cores institucionais do Governo Federal |
| **Deploy** | Hostinger (Node.js Web App) |

---

## 🗺️ Funcionalidades Principais

- ✅ **Landing institucional** com identidade do Governo Federal
- ✅ **Autenticação e papéis** (Cidadão, Profissional, Gestor, Coordenador)
- ✅ **CRUD de serviços** (solicitar e ofertar)
- ✅ **Google Maps** com geolocalização, marcadores coloridos e raio de busca
- ✅ **Notificações em tempo real** (Supabase Realtime)
- ✅ **Avaliação bilateral** (nota 1 a 5 + comentário)
- ✅ **Painel do Gestor** com KPIs, gráficos, mapa de calor e relatórios
- ✅ **Dados do CEPLUG** (Guarapuava) integrados
- ✅ **LGPD e RLS** (Row Level Security) em todas as tabelas

---

## 🏛️ Para Gestores Públicos e Formuladores de Políticas

O VetorCerto foi projetado para ser uma **ferramenta de governança**, ajudando cidades e estados a:

- **Mapear a demanda por serviços** em cada bairro, permitindo a alocação eficiente de recursos e políticas de capacitação profissional.
- **Gerar relatórios de impacto** com indicadores claros (ODS 8 e 11), prontos para serem usados em planejamentos estratégicos e prestações de contas.
- **Promover a inclusão produtiva**, conectando trabalhadores informais a oportunidades reais de renda, em alinhamento com programas como o Cadastro Único e o Sine.
- **Criar um ecossistema de trabalho digno** com transparência, avaliação bilateral e dados abertos.

**Pronto para implantação imediata.** Este piloto em Guarapuava/PR já utiliza dados reais do CEPLUG, podendo ser adaptado para qualquer município brasileiro.

## 📦 Instalação e Configuração

### Pré-requisitos

- Node.js (v18+)
- Bun (recomendado) ou npm
- Conta no Supabase
- Chave da Google Maps Platform

