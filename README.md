# KanbanApp

## Sobre
Bem-vindo ao KanbanApp! Este é um aplicativo de quadro Kanban simples Ele permite que você organize suas tarefas em colunas diferentes.

## Funcionalidades
- Criação, edição e exclusão de cartões de tarefas.
- Movimentação de cartões entre as colunas do quadro.

## Tecnologias Utilizadas
- **Angular CLI:** Utilizado para construir a interface de usuário.
- **Angular CDK (Component Dev Kit)**: O Angular CDK fornece uma série de componentes e utilitários que ajudam a criar interfaces de usuário complexas e acessíveis de forma mais fácil. Ele é especialmente útil para o KanbanApp, pois oferece funcionalidades avançadas para manipulação de arrastar e soltar (drag and drop), que são essenciais para a interação com os cartões de tarefas em um quadro Kanban.
- **Karma (karma.conf.js):** O Karma é um test runner utilizado para execução de testes unitários no Angular. O arquivo karma.conf.js é a configuração do Karma para o projeto, onde podemos definir quais testes serão executados e como. É especialmente útil para o KanbanApp garantir que as funcionalidades críticas, como a movimentação de cartões entre colunas, estejam funcionando corretamente e sem bugs.
- **TypeScript:** Linguagem de programação utilizada para desenvolver o código do front end.
- **HTML/SCSS:** Utilizados para estruturação e estilização da aplicação.
- **Bulma:** Utilizado para estilizar a interface do usuário de forma rápida e responsiva. O Bulma é um framework CSS leve e altamente personalizável, o que facilita a criação de layouts visualmente atraentes para o KanbanApp. Além disso, sua abordagem baseada em classes facilita a aplicação de estilos consistentes em todo o aplicativo.

## Como Usar
1. **Instalação:**
 - Certifique-se de ter o Angular e o Angular CLI instalados em sua máquina. 
- Clone este repositório
- Navegue até o diretório do projeto: `cd kanban-app`
- Instale as dependências, incluindo o Angular CDK e o Bulma: `npm install @angular/cdk bulma`
- Inicie o servidor de desenvolvimento: `ng serve`
- Acesse o aplicativo em seu navegador: 
`http://localhost:4200`

2. **Uso:**
   - Ao acessar o aplicativo, você verá um quadro Kanban com colunas padrão.
   - Clique em "Adicionar Tarefa" para criar um novo cartão.
   - Arraste e solte os cartões entre as colunas para atualizar seu status.

3. **Contribuição:**
   - Se você tiver alguma sugestão de melhoria ou encontrar algum problema, por favor, sinta-se à vontade para contribuir!
   - Faça suas alterações e envie um pull request.
