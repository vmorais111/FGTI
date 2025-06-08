# Entrega 1 - APP de Gestão de Estudos para Pessoas com TDAH

#  Visão do Produto

Trata-se de um aplicativo mobile responsivo voltado para estudantes que enfrentam dificuldades de foco e organização devido ao Transtorno de Déficit de Atenção e Hiperatividade (TDAH). A aplicação oferece funcionalidades como cadastro de atividades de estudo, divisão de grandes tarefas em micrometas, controle de tempo com técnicas como Pomodoro, envio de lembretes inteligentes e visualização de progresso em uma interface simples e amigável, além de gameficação para mostrar o avanço na conquista de metas.

## Objetivo

Desenvolver um sistema de gestão de estudos online, intuitivo e personalizável, que ajude estudantes com TDAH a organizar seus horários, acompanhar seu progresso e manter a motivação, respeitando as particularidades cognitivas do transtorno.

## Motivação

Pessoas com TDAH frequentemente enfrentam dificuldades para manter uma rotina estruturada de estudos, resultando em ansiedade, baixa produtividade e frustração. Métodos tradicionais de organização não funcionam bem para esse público. Um aplicativo feito sob medida, focado em microgerenciamento e estímulo positivo, pode aumentar significativamente a eficiência dos estudos e o bem-estar dos usuários.

# Project Model Canvas

![image](https://github.com/user-attachments/assets/72b00c30-1b6b-40bd-8c0c-35348af5fd0c)

# Personas Mapeadas

## Persona 1: Ana Paula

- **Cargo / Função:** Estudante de Medicina
- **Empresa:** Universidade Federal do Rio de Janeiro (UFRJ)
- **Gênero:** Feminino
- **Formação/Educação:** Ensino médio completo, cursando ensino superior
- **Mídias usadas:** Instagram, YouTube, WhatsApp
- **Objetivos:**
  - Manter uma rotina de estudos organizada
  - Dividir grandes matérias em pequenas metas diárias
- **Desafios:**
  - Sensacão de sobrecarga
  - Falta de constância nos estudos
- **Como a empresa pode ajudá-la:**
  - Organização automática de tarefas
  - Visualização de conquistas diárias

## Persona 2: Lucas Santana

- **Cargo / Função:** Estudante de cursinho preparatório para concurso
- **Empresa:** Cursinho Aprova Mais
- **Gênero:** Masculino
- **Formação/Educação:** Ensino médio completo
- **Mídias usadas:** YouTube, Facebook, Telegram
- **Objetivos:**
  - Manter ritmo de estudo consistente
  - Melhorar administração do tempo
- **Desafios:**
  - Procrastinação frequente
  - Dificuldade em lembrar prazos
- **Como a empresa pode ajudá-lo:**
  - Lembretes inteligentes
  - Aplicação de técnicas de produtividade

## Persona 3: Larissa Gomes

- **Cargo / Função:** Estudante EAD de Administração
- **Empresa:** Universidade Estaácio de Sá (EAD)
- **Gênero:** Feminino
- **Formação/Educação:** Ensino médio completo, cursando ensino superior à distância
- **Mídias usadas:** Instagram, WhatsApp, Google Calendar
- **Objetivos:**
  - Organizar tarefas do curso
  - Receber lembretes visuais de atividades
- **Desafios:**
  - Esquecimento de prazos
  - Dificuldade em iniciar grandes projetos
- **Como a empresa pode ajudá-la:**
  - Agendamento de pequenas tarefas
  - Alertas automáticos de prazos e progresso
---
# Entrega 2
## User Stories Detalhadas

| User Story | Descrição | Critérios de Aceitação | Definition of Done (DoD) |
|------------|-----------|------------------------|---------------------------|
| US01 | Como estudante com TDAH, quero cadastrar minhas atividades com título, descrição e prazo, para organizar minha rotina e reduzir esquecimentos. | - Usuário pode inserir título, descrição, prazo e prioridade.<br>- O sistema valida campos obrigatórios.<br>- As atividades são salvas no banco de dados. | - Interface implementada e validada.<br>- Integração com backend funcional.<br>- Dados persistem após reinício do app. |
| US02 | Como usuário com dificuldade de iniciar grandes tarefas, quero subdividir minhas atividades em micrometas, para progredir de forma leve e contínua. | - Interface permite adicionar subtarefas.<br>- Micrometas visíveis na atividade.<br>- Sistema mostra percentual de conclusão. | - Micrometas integradas.<br>- Atualização da barra de progresso.<br>- Testes com diferentes níveis de divisão. |
| US03 | Como estudante que se distrai facilmente, quero usar um cronômetro baseado na técnica Pomodoro, para manter foco durante os estudos. | - Ciclos de 25 minutos com pausas.<br>- Avisos sonoros e visuais.<br>- Botões para iniciar, pausar e resetar. | - Temporizador funcional.<br>- Testes em diferentes dispositivos.<br>- Persistência entre sessões. |
| US04 | Como usuário distraído, quero receber lembretes automáticos antes dos prazos, para evitar perder tarefas importantes. | - Notificações push com antecedência.<br>- Texto inclui nome e horário.<br>- Opção de desativar lembretes. | - Integração com sistema de notificações.<br>- Testes com horários variados.<br>- Feedback positivo em testes. |
| US05 | Como estudante visual, quero acompanhar meu progresso com gráficos e indicadores, para entender minha evolução. | - Barras de progresso por atividade.<br>- Percentual por micrometa.<br>- Indicadores semanais e mensais. | - Gráficos funcionais e responsivos.<br>- Atualização em tempo real.<br>- Interface validada. |
| US06 | Como usuário que precisa de estímulos, quero ver recompensas visuais quando completo tarefas, para me manter motivado. | - Exibição de conquistas visuais.<br>- Sistema desbloqueia conforme progresso.<br>- Área para visualizar conquistas. | - Sistema de pontos/conquistas funcionando.<br>- Integração com progresso.<br>- Testes com múltiplos perfis. |
| US07 | Como usuário recorrente, quero acessar meu histórico de estudos e dados pessoais, para acompanhar meu desempenho. | - Tela de perfil com dados do usuário.<br>- Estatísticas de evolução. | - Integração com autenticação.<br>- Informações sincronizadas.<br>- Testes com diferentes cadastros. |
| US08 | Como estudante ou terapeuta, quero exportar meu progresso em PDF ou Excel, para acompanhar a evolução e compartilhar com terceiros. | - Botão de exportação funcional.<br>- Arquivo com tarefas, tempos e progresso.<br>- Download e compartilhamento habilitados. | - Exportação funcional.<br>- Arquivo compatível com Excel.<br>- Validação dos dados exportados. |
| US09 | Como usuário desorganizado, quero receber alertas sobre tarefas vencidas ou urgentes, para não perder prazos. | - Sistema identifica e alerta tarefas vencidas.<br>- Alertas visuais e sonoros diferenciados. | - Algoritmo de verificação funcional.<br>- Notificações configuráveis.<br>- Testes com tarefas vencidas e atuais. |
| US10 | Como desenvolvedor, quero publicar o app na Play Store, para permitir que qualquer usuário possa usá-lo. | - App segue diretrizes da Play Store.<br>- Publicação com descrição, imagens e versão. | - APK assinado e submetido.<br>- Publicação aprovada.<br>- Link funcional disponível. |
| US11 | Como usuário com limitações, quero que o app ofereça alto contraste e leitura por voz, para acessibilidade plena. | - Opção de alto contraste.<br>- Leitura por voz integrada. | - Testes com acessibilidade Android.<br>- Validação com usuários reais.<br>- Feedback especializado incluído. |
| US12 | Como estudante disciplinado, quero receber um relatório mensal do meu desempenho, para acompanhar minha evolução ao longo do tempo. | - Geração automática mensal.<br>- Envio por e-mail ou acesso via app.<br>- Dados com tempo estudado e progresso. | - Função de agendamento ativa.<br>- Arquivo gerado e enviado.<br>- Testes de envio realizados. |

## Product Backlog com User Stories
Considerando que o desenvolvimento do produto iniciar-se-á em 05/08/2024 e será trabalhado até 22/11/2024. O backlog foi distribuído em 7 sprints de duas semanas e 1 sprint de 9 dias úteis; dado os 79 dias úteis do cronograma.

| User Story | Funcionalidade                                                                 | Prioridade | Sprint |
|------------|----------------------------------------------------------------------------------|------------|--------|
| US01       | Cadastro de atividades com título, descrição, prazo e prioridade                | Alta       | 1      |
| US02       | Criação de micrometas dentro de uma atividade                                   | Alta       | 2      |
| US03       | Timer Pomodoro com alertas sonoros e visuais                                    | Alta       | 2      |
| US04       | Lembretes inteligentes (push) com personalização de horário                     | Média      | 3      |
| US05       | Visualização do progresso por atividade e por micrometa                         | Média      | 3      |
| US06       | Gamificação: exibição de conquistas (ícones, barras, medalhas)                  | Média      | 4      |
| US07       | Perfil do usuário com histórico e estatísticas                                  | Média      | 5      |
| US08       | Exportação de progresso em PDF ou Excel                                         | Baixa      | 6      |
| US09       | Notificações de atividades vencidas e próximas                                  | Alta       | 6      |
| US10       | Publicação e testes em loja (Play Store)                                        | Alta       | 7      |
| US11       | Configurações de acessibilidade (alto contraste, leitura por voz)               | Média      | 7      |
| US12       | Relatório mensal gerado automaticamente                                         | Baixa      | 8      |

## Plano de Releases e Roadmap

**Período do Projeto:** 05/08/2024 a 22/11/2024  
**Duração Total:** 79 dias úteis (~16 semanas)

### Releases Planejadas

#### Release 1 – MVP Funcional (Entrega: 13/09/2024)
- US01: Cadastro de atividades
- US02: Criação de micrometas
- US03: Timer Pomodoro
- US04: Lembretes inteligentes
- US05: Visualização de progresso

**Objetivo:** Entregar funcionalidades essenciais para organização e foco.

---

#### Release 2 – Funcionalidades Avançadas (Entrega: 25/10/2024)
- US06: Gamificação
- US07: Perfil do usuário
- US08: Exportação de progresso
- US09: Notificações de prazos
- US11: Acessibilidade
- US12: Relatório mensal

**Objetivo:** Ampliar recursos com foco em personalização, motivação e inclusão.

---

#### Release 3 – Publicação Final (Entrega: 22/11/2024)
- US10: Publicação na Play Store

**Objetivo:** Tornar o app disponível ao público.

---

##  Simulação de Distribuição do Backlog (Sprints)

| Sprint | Período               | User Stories                |
|--------|------------------------|-----------------------------|
| 1      | 05/08 – 16/08         | US01                        |
| 2      | 19/08 – 30/08         | US02, US03                  |
| 3      | 02/09 – 13/09         | US04, US05                  |
| 4      | 16/09 – 27/09         | US06                        |
| 5      | 30/09 – 11/10         | US07                        |
| 6      | 14/10 – 25/10         | US08, US09                  |
| 7      | 28/10 – 08/11         | US10, US11                  |
| 8      | 11/11 – 22/11 (9 dias)| US12 + Testes finais        |

### Cerimônias Scrum por Sprint
- **Planejamento:** 1º dia útil (2h)
- **Daily Scrum:** Todos os dias úteis (15 min)
- **Revisão (Sprint Review):** Último dia útil (1h)
- **Retrospectiva:** Último dia útil após a review (1h)

---

## Plano de Custos do Projeto

### Premissas e Hipóteses
- 2 desenvolvedores (4h/dia) de 05/08 a 22/11
- Consultor pedagógico TDAH contratado por 1 mês (20h)
- Infraestrutura própria (notebook, energia, internet)
- Serviços gratuitos (Firebase free tier, notificações push)
- Taxa Google Play incluída

### Estimativas de Custo

| Item                                   | Custo Estimado (R$) |
|----------------------------------------|----------------------|
| Horas de Desenvolvimento (320h)        | R$ 16.000,00         |
| Consultoria Pedagógica (20h)           | R$ 2.000,00          |
| Licença Google Play                    | R$ 135,00            |
| Infraestrutura e energia               | R$ 500,00            |
| Testes e prototipagem                  | R$ 300,00            |
| **Total Geral**                        | **R$ 18.935,00**     |

### Distribuição por Release
- **Release 1 (MVP):** R$ 8.000,00  
- **Release 2 (Avançadas):** R$ 7.800,00  
- **Release 3 (Publicação):** R$ 3.135,00

