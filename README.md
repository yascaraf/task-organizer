# task-organizer
Um programa simples em que o usuário pode adicionar, listar, marcar como concluída e excluir tarefas diretamente pelo terminal. Ele grava os dados em um arquivo local (tasks.json), permitindo que as informações sejam salvas mesmo após fechar o programa.

### Funcionalidades
- Adicionar nova tarefa
- Listar todas as tarefas
- Marcar tarefa como concluída
- Remover tarefa
- Salvar e carregar tarefas de um arquivo

### Tecnologias Utilizadas
- Python 3
- Json
- Git

### Estrutura de Pastas

task-organizer/

│

├── main.py            # Arquivo principal

├── tasks.json         # Base de dados local (criada automaticamente)

├── README.md          # Documentação do projeto

└── requirements.txt   # Dependências (se houver)


### Como Usar

##### 1. Clonar o repositório

git clone https://github.com/seu-usuario/task-organizer.git

cd task-organizer

##### 2. Execuutar o programa
python main.py

##### 3. Seguir as opções do menu

[1] Adicionar tarefa

[2] Listar tarefas

[3] Concluir tarefa

[4] Remover tarefa

[5] Sair

### Possíveis Melhorias Futuras
- Adicionar campo de data de vencimento.
- Classificar tarefas por prioridade.
- Criar uma interface web ou GUI com Tkinter.
- Integrar com um banco de dados (SQLite).
