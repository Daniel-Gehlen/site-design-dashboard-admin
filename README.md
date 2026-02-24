## 📄 About (English)
**Admin Dashboard Interface** - A comprehensive data management prototype built with HTML5 and CSS3. Features collapsible sidebar navigation, KPI metric cards, interactive data table with status badges, sales chart placeholder, calendar component, and real-time notifications panel. Implements dark theme, CSS Grid for layouts, hover effects, and responsive design for desktop/tablet. Perfect for internal systems, analytics platforms, and backoffice applications.

---

### 📚 README.md


# 📊 AdminDash - Design Dashboard / Admin

![Versão](https://img.shields.io/badge/versão-1.0.0-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Dark Mode](https://img.shields.io/badge/theme-dark-1E293B)
![Responsivo](https://img.shields.io/badge/responsivo-sim-success)

## 📋 Sobre o Projeto

Este é um protótipo funcional de um site com **Design Dashboard / Admin**, desenvolvido a partir de um diagrama ASCII art. O projeto demonstra um layout complexo com muitos dados, gráficos, métricas em tempo real e funcionalidades administrativas, típico de sistemas internos, analytics e backoffice.

### 🎯 Características do Design

- Menu lateral fixo com navegação principal
- Cards de métricas (KPIs) com indicadores de performance
- Gráfico de vendas (placeholder visual)
- Tabela de dados com múltiplas colunas e status
- Calendário interativo
- Painel de notificações em tempo real
- Design dark mode profissional
- Foco em visualização de dados

## 🏗️ Estrutura do Site

```
+------------------+---------------------------------------------------+
|                  |                                                   |
|     MENU         |  +----------+  +----------+                       |
|     LATERAL      |  | GRÁFICO  |  | MÉTRICAS |                       |
|                  |  |          |  |  KPI     |                       |
| - Home           |  +----------+  +----------+                       |
| - Vendas         |                                                   |
| - Clientes       | +----------------------------------------------+ |
| - Relatórios     | | TABELA DE DADOS                               | |
| - Config         | | Col1 | Col2 | Col3 | Col4 | Col5              | |
|                  | |------|------|------|------|------|             | |
|                  | | Dado1| Dado2| Dado3| Dado4| Dado5|             | |
|                  | | Dado1| Dado2| Dado3| Dado4| Dado5|             | |
|                  | +----------------------------------------------+ |
|                  |                                                   |
|                  | +----------+  +----------+                       |
|                  | | CALENDÁRIO|  | NOTIFICAÇÕES|                   |
|                  | +----------+  +----------+                       |
+------------------+---------------------------------------------------+
```

## ✨ Funcionalidades Implementadas

### Menu Lateral

- ✅ **5 itens principais**: Home, Vendas, Clientes, Relatórios, Config
- ✅ Item ativo (Home) destacado em azul
- ✅ Efeitos hover em todos itens
- ✅ Ícones intuitivos (🏠, 📈, 👥, 📄, ⚙️)
- ✅ Versão do sistema (v2.4.0) e status "Online"

### Cabeçalho do Dashboard

- ✅ Título "Dashboard Overview"
- ✅ Data e hora em tempo real (24 Fev 2026 • 14:32)
- ✅ Badge estilizado

### Cards de Métricas e Gráfico (Linha 1)

- **Gráfico de Vendas:**
  - Card "Receita Mensal" com indicador de crescimento (+23%)
  - Placeholder visual com padrão diagonal
  - Ícone 📈 representando gráfico

- **Métricas KPI (3 cards clicáveis):**
  - Receita Total: R$ 187.450 (+12,5%)
  - Vendas: 1.284 (+8,3%)
  - Visitantes: 8.492 (+21,2%)
  - Cada KPI com badge de variação verde

### Tabela de Dados

- ✅ **5 colunas**: ID, Cliente, Produto, Valor, Status, Data
- ✅ **5 linhas de exemplo** com transações reais
- ✅ **Status badges** coloridos:
  - 🟢 Success (Pago) - Verde
  - 🟡 Warning (Pendente) - Amarelo
  - 🔵 Processando - Azul
- ✅ Hover nas linhas com destaque
- ✅ Linhas clicáveis para detalhes
- ✅ Botão "Exportar ↓" no cabeçalho

### Calendário

- ✅ Mês atual: Fevereiro 2026
- ✅ Dias da semana (DOM a SÁB)
- ✅ Dia atual (24) destacado em azul
- ✅ Dias de outros meses em cinza
- ✅ Navegação entre meses (botão ◀ clicável)
- ✅ Dias clicáveis

### Notificações

- ✅ **4 notificações** com ícones diferentes:
  - 💰 Nova venda (R$ 4.299) - Há 5 min
  - 👤 Novo cliente (15 cadastros) - Há 23 min
  - 📊 Relatório mensal disponível - Há 1h
  - ⚠️ Estoque baixo (5 produtos) - Há 3h
- ✅ Indicador "3 novas" não lidas
- ✅ Timestamps realistas
- ✅ Notificações clicáveis

### Rodapé do Dashboard

- ✅ Copyright do sistema
- ✅ Links rápidos: Configurações, Ajuda, Perfil
- ✅ Todos clicáveis com feedback

### Interatividade JavaScript

- ✅ Alertas personalizados para cada elemento
- ✅ Feedback visual em hovers
- ✅ Estado ativo no menu

## 🎨 Paleta de Cores (Dark Theme)

| Cor | Hexadecimal | Uso |
|-----|-------------|-----|
| Azul Claro | `#38bdf8` | Destaques, links, gradiente |
| Azul Escuro | `#2563eb` | Menu ativo, badges |
| Verde | `#4ade80` | Variações positivas |
| Amarelo | `#eab308` | Status pendente |
| Cinza 900 | `#0f172a` | Fundo principal |
| Cinza 800 | `#0b1120` | Fundo conteúdo |
| Cinza 700 | `#1e293b` | Cards, bordas |
| Cinza 400 | `#94a3b8` | Textos secundários |
| Branco | `#ffffff` | Textos principais |

## 📱 Responsividade

O dashboard se adapta para diferentes telas:

- **Desktop (1200px+):** Menu lateral fixo + conteúdo à direita
- **Tablet (768px - 1199px):**
  - Menu lateral vira horizontal no topo
  - Cards de métricas se ajustam
  - Tabela com scroll horizontal
- **Mobile (< 768px):**
  - Tudo empilhado verticalmente
  - Menu em scroll horizontal
  - Calendário e notificações um abaixo do outro

## 🔗 Links e Navegação

| Elemento | Ação (alerta) |
|----------|---------------|
| Menu Home | "Home - Dashboard principal" |
| Menu Vendas | "Vendas - Relatório de vendas" |
| Menu Clientes | "Clientes - Gerenciar clientes" |
| Menu Relatórios | "Relatórios - Gerar relatórios" |
| Menu Config | "Configurações - Ajustes do sistema" |
| KPI Receita | "Métrica de Receita Total" |
| KPI Vendas | "Métrica de Vendas" |
| KPI Visitantes | "Métrica de Visitantes" |
| Exportar | "Exportar dados" |
| Linhas da tabela (5) | "Detalhes da transação #[ID]" |
| Navegação calendário | "Mês anterior" |
| Dias do calendário | (sem ação específica) |
| "3 novas" | "Marcar todas como lidas" |
| Notificações (4) | "Notificação: [mensagem]" |
| Rodapé Config | "Configurações do sistema" |
| Rodapé Ajuda | "Ajuda e suporte" |
| Rodapé Perfil | "Perfil do usuário" |

## 📊 Dados da Tabela

| ID | Cliente | Produto | Valor | Status | Data |
|----|---------|---------|-------|--------|------|
| #2456 | João Silva | Notebook Pro | R$ 4.299 | ✅ Pago | 24/02 |
| #2455 | Maria Oliveira | Smartphone X | R$ 2.499 | ✅ Pago | 24/02 |
| #2454 | Carlos Santos | Fone Bluetooth | R$ 349 | ⏳ Pendente | 23/02 |
| #2453 | Ana Costa | Smartwatch | R$ 899 | ✅ Pago | 23/02 |
| #2452 | Pedro Souza | Tablet | R$ 1.599 | 🔄 Processando | 23/02 |

## 🚀 Como Executar

1. Clone este repositório
2. Abra o arquivo `index.html` em qualquer navegador moderno
3. Navegue pelo menu lateral
4. Explore os KPIs, gráfico e tabela
5. Interaja com calendário e notificações
6. Redimensione a tela para testar responsividade

## 💻 Tecnologias Utilizadas

- **HTML5 semântico** - Estrutura de dashboard
- **CSS3 Avançado:**
  - **Flexbox** para menu lateral e linhas de cards
  - **CSS Grid** para calendário
  - **Dark theme** consistente
  - **Gradientes** no logo e placeholders
  - **Transitions** para hovers suaves
  - **Box shadows** para profundidade
  - **Border-radius** para cards modernos
  - **Media queries** para responsividade
- **JavaScript mínimo** - Alertas interativos
- **Tipografia** - Inter, Segoe UI (moderna para dashboards)

## 📊 Componentes do Dashboard

| Componente | Função |
|------------|--------|
| Menu Lateral | Navegação principal do sistema |
| Gráfico | Visualização de tendências |
| KPIs | Métricas de negócio em tempo real |
| Tabela | Dados transacionais detalhados |
| Status Badges | Indicadores visuais de estado |
| Calendário | Visualização temporal |
| Notificações | Alertas e atualizações |
| Data/Hora | Contexto temporal |

## 📌 Casos de Uso

Este template é ideal para:
- **Sistemas internos** - ERP, CRM, gestão empresarial
- **Analytics platforms** - Google Analytics, dashboards de dados
- **Backoffice** - Administração de e-commerces
- **SaaS** - Painéis de controle para assinantes
- **Monitoramento** - Status de servidores, sistemas
- **Fintechs** - Visualização de transações

## 🧩 Diferenciais

- ✅ **Menu lateral completo** com 5 itens principais
- ✅ **KPIs interativos** com indicadores de variação
- ✅ **Gráfico placeholder** com design profissional
- ✅ **Tabela funcional** com 5 colunas e status coloridos
- ✅ **Calendário real** com dia atual destacado
- ✅ **4 notificações** com timestamps realistas
- ✅ **Dark mode** agradável para uso prolongado
- ✅ **ASCII art demonstrativo** no topo
- ✅ **Todos elementos clicáveis** para demonstração

## 🧪 Validação do ASCII Art

| Elemento ASCII | Implementação |
|----------------|---------------|
| MENU LATERAL | ✅ 5 itens: Home, Vendas, Clientes, Relatórios, Config |
| GRÁFICO | ✅ Card com placeholder "📈 GRÁFICO DE VENDAS" |
| MÉTRICAS KPI | ✅ 3 KPIs: Receita, Vendas, Visitantes |
| TABELA DE DADOS | ✅ 5 colunas, 5 linhas com dados reais |
| CALENDÁRIO | ✅ Fevereiro 2026 com dia 24 destacado |
| NOTIFICAÇÕES | ✅ 4 notificações com ícones |

## 👨‍💻 Autor

Desenvolvido como demonstração de design dashboard/admin baseado em diagrama ASCII art por Daniel Gehlen.

---

## 📝 Notas de Versão

### v1.0.0 (24/02/2026)

- ✅ Implementação completa do design ASCII art
- ✅ Menu lateral com 5 itens e estado ativo
- ✅ Gráfico placeholder com design profissional
- ✅ 3 KPIs com valores e variações percentuais
- ✅ Tabela de 5 colunas × 5 linhas com status badges
- ✅ Calendário interativo com dia atual
- ✅ 4 notificações com timestamps
- ✅ Rodapé com links rápidos
- ✅ Design dark mode completo
- ✅ Responsividade para tablets/mobile
- ✅ Todos elementos clicáveis

### Próximas Melhorias (Sugestões)

- [ ] Gráfico real com Chart.js ou D3.js
- [ ] Dados dinâmicos via API
- [ ] Modo claro/escuro toggle
- [ ] Filtros na tabela
- [ ] Paginação dos dados
- [ ] Gráficos adicionais (pizza, barras)
- [ ] Perfil de usuário dropdown
- [ ] Busca global no dashboard

---

**📅 Última atualização:** 24 de Fevereiro de 2026
