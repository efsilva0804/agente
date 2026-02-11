# Design Brief - Dashboard de Agentes Contábeis

## Visão Geral
Dashboard de monitoramento e gestão para 17 agentes virtuais de IA em um escritório contábil. Necessita transmitir profissionalismo, confiabilidade e eficiência.

## Design Philosophy
**Minimalismo Corporativo com Acentos Estratégicos**

- **Paleta de Cores**: Azul profundo (#1e40af) como primária, com cinzas neutros e acentos verdes para status positivo
- **Tipografia**: Fonte sans-serif moderna (Inter/Poppins) com hierarquia clara
- **Espaçamento**: Generoso, com grid de 8px para consistência
- **Componentes**: Cards com sombras sutis, indicadores de status visuais claros

## Seções Principais

### 1. Header
- Logo/Branding do sistema
- Título "Dashboard de Agentes Contábeis"
- Indicador de status geral do sistema

### 2. Sidebar de Navegação
- Menu de categorias de agentes (Fiscal, DP, Contabilidade, Especializado)
- Links para diferentes views

### 3. Dashboard Principal
- **Grid de Status dos Agentes**: Cards 3x6 mostrando cada agente
  - Nome do agente
  - Status (Idle/Running/Error)
  - Tarefas completadas
  - Última atividade
  
- **Estatísticas Gerais**
  - Total de agentes ativos
  - Tarefas em fila
  - Taxa de sucesso
  - Tempo médio de processamento

- **Submissão de Tarefas**
  - Formulário para selecionar agente e tipo de tarefa
  - Campos de entrada de dados
  - Botão de submissão

### 4. Histórico de Tarefas
- Tabela com tarefas recentes
- Status, tempo de execução, resultado
- Filtros por agente/tipo/data

## Paleta de Cores
- **Primária**: #1e40af (Azul Profundo)
- **Secundária**: #64748b (Cinza Azulado)
- **Sucesso**: #16a34a (Verde)
- **Aviso**: #ea580c (Laranja)
- **Erro**: #dc2626 (Vermelho)
- **Fundo**: #f8fafc (Cinza Claro)
- **Texto**: #1e293b (Cinza Escuro)

## Tipografia
- **Display**: Poppins Bold (24-32px)
- **Heading**: Inter SemiBold (18-20px)
- **Body**: Inter Regular (14-16px)
- **Small**: Inter Regular (12px)

## Componentes Especiais
- **Status Badges**: Cores visuais + ícones
- **Progress Bars**: Para taxa de sucesso/fila
- **Real-time Indicators**: Pulsação suave para agentes em execução
- **Charts**: Gráficos de desempenho ao longo do tempo
