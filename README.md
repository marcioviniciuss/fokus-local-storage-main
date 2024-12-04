# Projeto Pomodoro com Gerenciamento de Tarefas

Este projeto combina um **temporizador Pomodoro** com um sistema de **gerenciamento de tarefas**, permitindo aumentar a produtividade de forma prática e eficiente.

O projeto foi desenvolvido a partir de uma base existente no GitHub, com foco em melhorar as funcionalidades utilizando JavaScript.

## 🚀 Funcionalidades

### Temporizador Pomodoro
- Modo Foco (25 minutos).
- Pausas curtas (5 minutos) e longas (15 minutos).
- Alteração dinâmica do contexto (foco ou descanso) com atualização do título e imagem.
- Sons de alerta:
  - Início/pausa do cronômetro.
  - Finalização do tempo.
- Integração com música ambiente opcional, com botão para ativar/desativar.

### Gerenciamento de Tarefas
- Adição de tarefas.
- Seleção de uma tarefa ativa, exibindo sua descrição.
- Edição de tarefas existentes.
- Marcar tarefas como concluídas ao final de um ciclo Pomodoro.
- Exclusão de:
  - Tarefas concluídas.
  - Todas as tarefas (reset).

## 🧠 O que foi desenvolvido

### Sistema de tarefas
- Estrutura para armazenar tarefas no **LocalStorage**.
- Criação dinâmica de elementos HTML para listar tarefas.
- Controle do estado das tarefas (ativas/concluídas).
- Botão de edição para renomear tarefas existentes.
- Botões de exclusão com lógica para remover apenas tarefas concluídas ou todas as tarefas.

### Uso de CSS pronto
- A base de CSS foi utilizada para focar no desenvolvimento das funcionalidades JavaScript.

## ⚙️ Tecnologias Utilizadas
- **HTML5** para a estrutura do projeto.
- **CSS3** (já pronto) para o layout e design.
- **JavaScript** para a lógica e funcionalidades.

## 📚 O que foi aprendido
- Manipulação de DOM com JavaScript.
- Utilização de eventos personalizados para comunicação entre módulos (ex.: evento `FocoFinalizado`).
- Persistência de dados no **LocalStorage**.
- Criação e manipulação dinâmica de elementos HTML.
- Controle do estado de tarefas e integração com o temporizador Pomodoro.

## Imagem do projeto
![fokus-local-storag](https://github.com/user-attachments/assets/e8232016-36a7-46fe-8621-7c4fa0e3f2ff)
