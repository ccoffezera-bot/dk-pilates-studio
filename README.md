# DK Pilates Studio — Website Oficial

Website editorial premium e contemporâneo desenvolvido para o **DK Pilates Studio**, localizado no Jardim São Paulo, Zona Norte de São Paulo (SP).

---

## 🏛️ Sobre o Projeto

O site foi concebido com uma direção de arte editorial sofisticada, inspirada no design minimalista de arquitetura e bem-estar contemporâneo, evitando os padrões visuais genéricos de academias convencionais.

### Principais Destaques:
- **Identidade Editorial Refinada**: Paleta de cores neutras aquecidas (travertino, areia, off-white e grafite escuro).
- **Tipografia Cuidadosa**: Pareamento tipográfico entre a clássica serifada *Cormorant Garamond* e a geométrica *Plus Jakarta Sans*.
- **Fotografia de Alta Resolução**: Imagens autênticas retratando os aparelhos clássicos (*Universal Reformer*, *Cadillac Trapeze Table*) e movimentos biomecânicos precisos.
- **Bento Grid de Modalidades & Aparelhos**: Apresentação dinâmica dividida entre métodos (Pilates Clássico, Funcional, Reabilitação Postural) e os equipamentos oficiais.
- **Seletor de Mensagens para WhatsApp**: Conversor de intenção permitindo que o visitante escolha o motivo do contato (Aula experimental, Dores na coluna/Reabilitação, Aparelhos, Planos) e inicie a conversa com texto já formatado.
- **Fatos e Dados Confirmados**: Endereço real na Rua Gaspar Soares, 88 (Jardim São Paulo), horários de funcionamento, botões de navegação para Google Maps/Waze e integração com convênios (TotalPass, Gurupass, Wellhub).
- **Acessibilidade & Performance**: Respeito às diretrizes WCAG AA, suporte a `prefers-reduced-motion` e carregamento ultrarrápido sem dependência de banco de dados ou autenticação pesada.

---

## 🛠️ Tecnologias Utilizadas

- **React 19** com componentes funcionais e hooks modernos.
- **TypeScript** com tipagem estrita para segurança e manutenibilidade.
- **Tailwind CSS v4** com tokens personalizados e `@import "tailwindcss";`.
- **Vite 8** para empacotamento rápido e otimização de produção.
- **Lucide React** para iconografia limpa e sem ruídos visuais.

---

## 📂 Estrutura de Pastas

```
├── index.html                   # Entry point HTML com fontes e Schema.org JSON-LD
├── metadata.json                # Metadados oficiais do app
├── package.json                 # Dependências e scripts npm
├── vite.config.ts               # Configuração do Vite e plugins
├── tsconfig.json                # Configurações TypeScript
├── src/
│   ├── main.tsx                 # Ponto de entrada React
│   ├── App.tsx                  # Componente principal integrando as seções
│   ├── index.css                # Configurações globais e tipografia Tailwind
│   ├── data/
│   │   └── studioData.ts        # Dados estruturados e fatos confirmados do estúdio
│   ├── assets/
│   │   └── images/              # Fotografias editoriais de alta fidelidade
│   └── components/
│       ├── Navbar.tsx           # Top Bar Contract (3 zonas) e menu mobile
│       ├── Hero.tsx             # Hero editorial com imagem 16:9 e CTAs
│       ├── AboutPhilosophy.tsx  # Filosofia biomecânica e espaço do estúdio
│       ├── BentoModalities.tsx  # Bento Grid de modalidades e aparelhos
│       ├── InteractiveWhatsAppLauncher.tsx # Seletor interativo de mensagens
│       ├── LocationHours.tsx    # Endereço, mapa, Waze e horários
│       ├── FaqAccordion.tsx     # Acordeom de perguntas frequentes
│       ├── Footer.tsx           # Rodapé editorial com dados confirmados
│       └── FloatingWhatsApp.tsx # Botão de acesso rápido respeitando sticky cap
└── README.md                    # Documentação do projeto
```

---

## 🚀 Como Executar Localmente

### Pré-requisitos
- Node.js 18+ instalado
- npm ou bun

### Instalação e Execução
```bash
# 1. Instalar as dependências
npm install

# 2. Executar o servidor de desenvolvimento
npm run dev

# 3. Compilar para produção
npm run build

# 4. Validar tipos TypeScript
npm run lint
```

---

## 📍 Informações do Estúdio

- **Nome**: DK Pilates Studio
- **Endereço**: Rua Gaspar Soares, 88, Sala Pilates - Jardim São Paulo, São Paulo - SP, CEP 02041-020
- **Telefone / WhatsApp**: (11) 97626-4452
- **Link Direto WhatsApp**: [https://wa.me/5511976264452](https://wa.me/5511976264452)
- **Horários**:
  - Segunda a Sexta: 06:00 às 22:00
  - Sábado: 08:00 às 12:00
  - Domingo e Feriados: Fechado
- **Convênios**: TotalPass, Gurupass, Wellhub (Gympass)
