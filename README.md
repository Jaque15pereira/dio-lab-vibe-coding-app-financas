##💸 App de Organização de Finanças Pessoais com Vibe Coding/

## 🎯 **prompt final** (PRD):

# Product Requirements Document (PRD)  
Aplicativo Mobile de Organização de Finanças Pessoais via Chat

## 1. Visão do Produto e do MVP
O produto será um aplicativo mobile que permite ao usuário controlar suas finanças pessoais de forma simples e acessível, usando uma interface de chat em linguagem natural.  
O MVP terá como foco reduzir a fricção inicial para usuários iniciantes, oferecendo:
- Registro de gastos via texto;
- Classificação automática de despesas;
- Definição de metas simples;
- Recomendações básicas de economia;
- Consulta a extratos e gráficos.

## 2. Principais Casos de Uso
- Registrar gasto via chat: Usuário digita “gastei 50 reais no supermercado” e o sistema registra automaticamente.  
- Consultar saldo de gastos no mês: Usuário pergunta “quanto já gastei este mês?” e recebe resposta resumida.  
- Ver metas e progresso: Usuário define meta (“quero gastar no máximo 500 reais com lazer”) e acompanha evolução.  
- Receber dicas de economia: O “Agente Financeiro” sugere ações simples, como “reduza gastos em delivery, já representam 20% do seu orçamento”.  
- Consulta a extrato: Usuário pede “me mostre minhas últimas transações” e recebe lista.  
- Visualizar gráficos: Usuário acessa gráficos simples de categorias e evolução mensal.

## 3. Requisitos Funcionais
- Registro de gastos via chat  
  - Interpretar texto em linguagem natural.  
  - Extrair valor, categoria e descrição.  
  - Caso a interpretação seja incerta, pedir confirmação: “Você quis dizer gasto de R$50 em supermercado?”  

- Classificação automática de transações  
  - Categorizar despesas em grupos pré-definidos (alimentação, transporte, lazer, etc.).  
  - Permitir correção manual pelo usuário.  

- Metas simples  
  - Usuário define meta por categoria ou valor total.  
  - Sistema acompanha progresso e alerta quando estiver próximo do limite.  

- Dicas de economia  
  - Baseadas em regras simples no MVP (ex.: se categoria >20% do total, sugerir redução).  

- Extrato e gráficos  
  - Extrato em formato de lista com filtros básicos (por período, categoria).  
  - Gráficos simples (pizza para categorias, linha para evolução mensal).  

## 4. Requisitos Não Funcionais
- Simplicidade de interface: foco em chat e visualizações básicas.  
- Performance razoável: respostas do chat em até 2 segundos.  
- Privacidade básica: dados armazenados localmente ou em nuvem segura, sem exposição em respostas inadequadas.  
- Acessibilidade: design universal com suporte a leitores de tela e contraste adequado.  

## 5. Dados e Estrutura Básica
- Usuário: ID, nome, email (opcional).  
- Transações: ID, valor, descrição, categoria, data/hora.  
- Categorias: lista pré-definida (alimentação, transporte, lazer, etc.).  
- Metas: categoria, valor limite, período.  
- Interações de chat: histórico de mensagens, interpretação, confirmação.  

## 6. Dependências / Integrações
- MVP não terá integração com bancos.  
- Visão futura: integração com cartões e contas bancárias para importação automática de transações.  

## 7. Plano de Validação
- Interpretação de texto: testes com frases variadas para medir taxa de acerto (>80% no MVP).  
- Classificação de categorias: validar precisão com dataset de exemplos.  
- Utilidade das dicas: pesquisa qualitativa com usuários (percepção de relevância).  
- Testes de usabilidade: acompanhar tempo de aprendizado e abandono.  

## Prints das interações com a IA: 
<img width="886" height="404" alt="image" src="https://github.com/user-attachments/assets/df492080-3430-4765-9aa5-239440d981cc" />
<img width="886" height="373" alt="image" src="https://github.com/user-attachments/assets/f446f03f-5a0b-4966-a2b7-7bdde8e1e3f9" />
<img width="886" height="337" alt="image" src="https://github.com/user-attachments/assets/67afafb2-9c82-4636-8fae-cf29817d3f41" />
<img width="886" height="442" alt="image" src="https://github.com/user-attachments/assets/11b5a5b4-afa3-4f2f-a131-3178963695a5" />
<img width="886" height="398" alt="image" src="https://github.com/user-attachments/assets/40ddae8f-72eb-403f-8c7c-901b09d3a248" />
<img width="1090" height="427" alt="image" src="https://github.com/user-attachments/assets/b0047472-42c6-491c-950f-5ce2fc9c1752" />
<img width="1090" height="513" alt="image" src="https://github.com/user-attachments/assets/9dd0827e-6eee-443e-803e-f74201777a9f" />
<img width="1090" height="493" alt="image" src="https://github.com/user-attachments/assets/337f0cfc-7464-4305-ba2b-6a9f5fab15ce" />
## Resumo do que o seu **App de Finanças Pessoais** faz:

# Resumo do Aplicativo - Chat Wallet

O **Chat Wallet** é um aplicativo mobile de organização de finanças pessoais que utiliza uma interface de chat em linguagem natural para simplificar o controle de gastos.
Link de acesso ao app (Resultado Lovable): https://say-your-spend.lovable.app/
<img width="1360" height="682" alt="image" src="https://github.com/user-attachments/assets/7ff3b5dd-4400-427c-82a8-7b694724ee10" />

## Principais Funcionalidades
- **Registro de gastos via chat**: o usuário informa despesas em texto livre, e o motor de NLP interpreta valor, categoria e descrição.  
- **Classificação automática**: transações categorizadas em até 10 grupos (alimentação, transporte, lazer, saúde etc.), com possibilidade de ajuste manual.  
- **Metas financeiras**: definição de limites por categoria ou valor total, com acompanhamento por barras de progresso.  
- **Resumo financeiro**: visão geral dos gastos do mês, número de transações e distribuição por categoria.  
- **Extrato**: lista de transações agrupadas por data, com opção de excluir itens.  
- **Gráficos**: visualizações simples (pizza para categorias, linha para evolução mensal) para facilitar entendimento dos hábitos de consumo.  
- **Dicas de economia**: recomendações contextuais do “Agente Financeiro”, baseadas em padrões de gastos (ex.: alertar sobre categorias que representam grande parte do orçamento).  

## Design e Implementação do MVP
- Layout mobile-first com navegação inferior.  
- Tema escuro com acentos em verde.  
- Dados salvos em `localStorage` para simplificar a primeira versão.  

## Essência
O app combina **chat inteligente + visualizações simples** para ajudar iniciantes a controlar suas finanças sem complexidade.



## Reflexão sobre o processo**:
  - O que funcionou bem? Refinamento feito previamente com Copilot, ajudou muito dada a limitação de créditos no Lovable.
  - O que não funcionou como o esperado? Primeiro PRD comando no Lovable não resultou em APP e sim em outro PRD. Prompt ajustado e nova tentativa com êxito.Contudo, seria importante mais tentativas no mesmo dia, aumentar os créditos disponíveis gratuidamente.
  - O que aprendeu sobre conversar com IAs? Necessário que sejam das orientações com o máximo de detalhe e objetividade, para se atingir o resultado esperado. 
