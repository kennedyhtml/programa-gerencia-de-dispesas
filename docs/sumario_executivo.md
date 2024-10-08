# Sumário Executivo

## 1. Introdução
A gestão financeira pessoal tem se tornado uma habilidade cada vez mais importante, em um mundo onde o controle de receitas e despesas é essencial para garantir uma vida financeira equilibrada. Contudo, muitas pessoas ainda encontram dificuldades para gerenciar suas finanças de forma eficaz, o que pode resultar em problemas como acúmulo de dívidas, falta de planejamento financeiro e incapacidade de atingir metas financeiras. Para resolver esse problema, este projeto propõe o desenvolvimento de um **Aplicativo de Gerenciamento de Finanças Pessoais**, que permitirá aos usuários registrar, acompanhar e analisar suas transações financeiras de maneira simples e intuitiva. O aplicativo será desenvolvido utilizando a linguagem Python, com interface gráfica construída em Tkinter, e armazenamento local das transações em um banco de dados SQLite.

## 2. Objetivo
O objetivo deste projeto é desenvolver um aplicativo capaz de ajudar os usuários a controlar suas finanças pessoais de maneira prática e eficiente. Ele permitirá o registro de receitas e despesas, a categorização dessas transações, e a geração de relatórios detalhados que fornecerão insights sobre o comportamento financeiro dos usuários. Além disso, o aplicativo oferecerá uma interface gráfica de fácil utilização, garantindo que pessoas com diferentes níveis de habilidade técnica possam utilizá-lo.

### Objetivos Específicos:
- Desenvolver uma solução **offline** para gerenciamento de finanças pessoais;
- Oferecer **privacidade total** ao usuário, garantindo que seus dados sejam armazenados localmente;
- Implementar uma **interface gráfica amigável** que facilite a interação com o sistema;
- Proporcionar uma **visualização clara** das finanças através de resumos financeiros e relatórios detalhados.

## 3. Público-Alvo
Este aplicativo é voltado para indivíduos que desejam manter um controle mais eficaz sobre suas finanças pessoais. Seu público-alvo inclui desde jovens adultos começando sua vida financeira, até profissionais com rotinas ocupadas que precisam de uma ferramenta acessível para monitorar suas finanças regularmente. O aplicativo também é ideal para aqueles que preferem uma solução offline e local, garantindo total controle sobre seus dados financeiros.

### Exemplos de Perfis do Público-Alvo:
- **Estudantes Universitários:** Buscando organizar gastos com estudos, transporte, alimentação e lazer.
- **Profissionais Liberais:** Precisam acompanhar entradas e saídas de recursos de forma ágil.
- **Famílias:** Interessadas em organizar o orçamento familiar, categorizando despesas como alimentação, moradia, lazer, entre outras.

## 4. Descrição do Produto
O **Aplicativo de Gerenciamento de Finanças Pessoais** será uma ferramenta desktop, baseada em Python, que permitirá aos usuários gerenciar suas finanças de maneira eficiente. Ele oferecerá funcionalidades como registro de transações (receitas e despesas), categorização dessas transações, visualização de um resumo financeiro atualizado e geração de relatórios detalhados.

### Funcionalidades Principais:
1. **Cadastro de Transações:** 
   - Permite o registro de receitas e despesas, com categorização opcional (ex: alimentação, transporte, lazer).
   - As transações serão armazenadas localmente no banco de dados SQLite.
2. **Resumo Financeiro:**
   - Apresenta um resumo consolidado das receitas, despesas e saldo total do usuário.
   - O saldo será atualizado em tempo real à medida que novas transações forem adicionadas.
3. **Relatórios Detalhados:**
   - Relatórios financeiros mensais, com gráficos mostrando despesas por categoria.
   - Relatórios personalizados com base em datas ou categorias selecionadas pelo usuário.
4. **Privacidade e Armazenamento Local:**
   - Todas as informações financeiras são armazenadas localmente, garantindo a privacidade e segurança dos dados do usuário.

### Tecnologias Utilizadas:
- **Python:** Linguagem de programação principal.
- **SQLite:** Banco de dados relacional leve para armazenamento das transações.
- **Tkinter:** Biblioteca Python para construção da interface gráfica.
- **Matplotlib ou Seaborn:** Para visualização de gráficos e relatórios financeiros.

## 5. Benefícios Esperados

### Benefícios para os Usuários:
- **Controle Financeiro Total:** O usuário terá controle completo sobre suas finanças pessoais, podendo gerenciar receitas, despesas e o saldo disponível.
- **Facilidade de Uso:** A interface gráfica simples e intuitiva permitirá que qualquer pessoa, independentemente de seu nível técnico, possa utilizar o aplicativo sem dificuldades.
- **Privacidade e Segurança:** Com os dados armazenados localmente no dispositivo do usuário, este poderá gerenciar suas informações com total segurança, sem risco de exposição em servidores de terceiros.
- **Planejamento Financeiro Eficaz:** Através dos relatórios detalhados, os usuários poderão identificar onde estão gastando mais e ajustar seu planejamento financeiro para otimizar suas finanças.

### Benefícios para o Desenvolvedor:
- **Desenvolvimento Pessoal:** O projeto oferece uma oportunidade para aprimorar habilidades em desenvolvimento de software, utilizando Python, banco de dados SQLite, e desenvolvimento de interface gráfica.
- **Organização de Código e Colaboração:** O uso de um repositório Git bem estruturado permitirá a prática de técnicas de controle de versão, documentação e colaboração com outros desenvolvedores.

## 6. Metodologia de Desenvolvimento
O desenvolvimento do projeto seguirá uma abordagem **ágil e iterativa**, onde as funcionalidades serão implementadas em fases, permitindo melhorias contínuas e ajustes baseados no feedback.

### Fases do Desenvolvimento:
1. **Fase 1 - Backend:**
   - Implementação das operações de criação, leitura, atualização e deleção (CRUD) no banco de dados.
   - Funcionalidade de cadastro de transações.
2. **Fase 2 - Interface Gráfica:**
   - Desenvolvimento da interface gráfica com Tkinter, possibilitando a interação dos usuários com o sistema.
3. **Fase 3 - Relatórios e Visualização:**
   - Implementação de funcionalidades para geração de relatórios e visualização de gráficos.
4. **Fase 4 - Testes e Refinamento:**
   - Realização de testes funcionais, ajustes na usabilidade e correção de bugs.

### Ferramentas Utilizadas:
- **Controle de Versão:** Git, para rastrear mudanças no código e colaborar em equipe.
- **Documentação:** Markdown, para documentar o projeto de maneira clara e organizada.
- **Ambiente de Desenvolvimento:** Python (com bibliotecas Tkinter, SQLite, Matplotlib), além de editores de código como Visual Studio Code ou PyCharm.

## 7. Estrutura do Repositório

A estrutura do repositório Git será organizada de forma a manter a clareza e modularidade do projeto, facilitando a navegação e a contribuição de novos desenvolvedores.

```plaintext
├── financas_pessoais/
│   ├── README.md                 # Descrição geral do projeto
│   ├── src/
│   │   ├── main.py               # Arquivo principal da aplicação
│   │   ├── database.py           # Lógica de interação com o banco de dados SQLite
│   │   ├── interface.py          # Interface gráfica em Tkinter
│   │   └── reports.py            # Geração de relatórios e gráficos
│   ├── docs/
│   │   ├── sumario_executivo.md  # Documento de Sumário Executivo
│   │   └── requisitos.md         # Documento de Requisitos Funcionais e Não-Funcionais
│   └── tests/
│       ├── test_main.py          # Testes unitários para funcionalidades principais
│       ├── test_database.py      # Testes unitários para o banco de dados
│       └── test_interface.py     # Testes de interface gráfica e usabilidade
