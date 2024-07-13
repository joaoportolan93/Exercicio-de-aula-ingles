# TaskMeneger 📝
---
Este projeto permite que os usuarios possam criar, vizualizar e gerenciar suas tarefas rotuneiras de forma eficiente.

## Visão Geral do Software
Este código em C++ implementa um gerenciador de tarefas simples, permitindo ao usuário adicionar, visualizar, editar, remover, buscar e filtrar tarefas. Ele utiliza arrays para armazenar informações das tarefas, como título, descrição, data e status, e uma variável de controle para rastrear o número total de tarefas. O programa apresenta um menu interativo que permite ao usuário escolher entre diferentes opções para gerenciar suas tarefas, utilizando funções específicas para cada operação, como `criartarefas`, `visualizartarefas`, `editartarefa`, `removertarefa`, `buscartarefas`, `filtro` e `sairdoprograma`.
## Instalação do Programa

O TaskManager é um programa de código aberto e gratuito que pode ser facilmente instalado em qualquer sistema operacional. Para instalar o programa, basta seguir estas etapas:

1. Baixe o arquivo do programa a partir do repositório GitHub: [https://github.com/joaoportolan93/TaskManager](https://github.com/joaoportolan93/TaskManeger.git)
2. Extraia o arquivo baixado para uma pasta de sua escolha.
3. Abra o terminal e navegue até a pasta onde o programa foi extraído.
4. Execute o comando `./taskmanager` para iniciar o programa.

## Guia de uso básico

Ao iniciar o TaskManager, você será apresentado a um menu com as seguintes opções:

1. **Adicionar Tarefa:** Permite criar uma nova tarefa, inserindo seu título, descrição, data e status.
2. **Visualizar Tarefas:** Exibe uma lista de todas as tarefas existentes, com seus respectivos detalhes.
3. **Editar Tarefa:** Permite modificar os detalhes de uma tarefa existente, como título, descrição, data e status.
4. **Remover Tarefa:** Exclui uma tarefa existente da lista.
5. **Buscar Tarefa:** Permite encontrar uma tarefa específica usando seu título.
6. **Filtrar Tarefas por Status:** Exibe apenas as tarefas que possuem um determinado status.
7. **Sair:** Encerra o programa.

Para navegar pelo menu, basta digitar o número da opção desejada e pressionar Enter.

## Contribuição**

O TaskManager é um projeto de código aberto e você é bem-vindo a contribuir para seu desenvolvimento. Se você tiver alguma sugestão de melhoria ou correção de bug, por favor, envie um pull request para o repositório GitHub do projeto.

## Exemplo de uso

**Cenário:** Você precisa organizar suas tarefas para a semana.

**Passo a passo:**

1. Abra o TaskManager.
2. Na opção 1 ("Adicionar Tarefa"), crie as tarefas que você precisa realizar durante a semana, inserindo seus títulos, descrições, datas e status.
3. Na opção 2 ("Visualizar Tarefas"), visualize a lista de tarefas criadas.
4. Na opção 3 ("Editar Tarefa"), modifique as informações das tarefas conforme necessário.
5. Na opção 4 ("Remover Tarefa"), exclua as tarefas que você já concluiu.
6. Na opção 6 ("Filtrar Tarefas por Status"), filtre as tarefas por status para visualizar apenas as que estão pendentes, em andamento ou concluídas.
7. Utilize o menu para gerenciar suas tarefas ao longo da semana.
## **Conclusão**

O TaskManager é uma ferramenta útil para organizar e gerenciar suas tarefas diárias. Com seu menu intuitivo e fácil de usar, você pode facilmente criar, visualizar, editar, remover e buscar tarefas. O programa também oferece recursos adicionais, como filtragem por status, que podem ser úteis para organizar e priorizar suas atividades.

### **Versão Markdown**


## Guia de Instalação do TaskManager

**2. Instalação**

### Requisitos de Sistema

* Sistema operacional: Windows, Linux ou macOS
* Compilador C++ (como o GCC ou o Clang)

### Pré-requisitos

* Certifique-se de ter o compilador C++ instalado em seu sistema.
* Baixe o código-fonte do TaskManager do repositório GitHub: [https://github.com/joaoportolan93/TaskManager](https://github.com/joaoportolan93/TaskManeger.git)
* Extraia o arquivo baixado para uma pasta de sua escolha.

### Instalação

**1. Compilação do código-fonte**

Abra um terminal e navegue até a pasta onde o código-fonte do TaskManager foi extraído. Execute o seguinte comando para compilar o programa:

```
cmake . && make
```

Este comando irá gerar um executável chamado `taskmanager` na pasta `build`.

**2. Executando o TaskManager**

Para executar o TaskManager, navegue até a pasta `build` e execute o seguinte comando:

```
./taskmanager
```

**3. Criando um atalho (opcional)**

Se você deseja criar um atalho para o TaskManager, pode seguir estas etapas:

* **Windows:**
    1. Crie um atalho para o arquivo `taskmanager.exe` na pasta `build`.
    2. Você pode colocar este atalho na sua área de trabalho ou no menu Iniciar.
* **Linux:**
    1. Crie um atalho para o arquivo `taskmanager` na pasta `build`.
    2. Você pode colocar este atalho no seu menu de aplicativos ou na sua barra de tarefas.
* **macOS:**
    1. Crie um atalho para o arquivo `taskmanager` na pasta `build`.
    2. Você pode colocar este atalho na sua pasta Aplicativos ou na sua Dock.

**4. Desinstalando o TaskManager**

Para desinstalar o TaskManager, basta excluir a pasta onde o código-fonte foi extraído.

**Observações:**

* Se você não tiver um compilador C++ instalado, poderá baixá-lo gratuitamente a partir da internet.
* Certifique-se de que o caminho para o compilador C++ esteja configurado corretamente em seu ambiente de desenvolvimento.
* Se você encontrar qualquer problema durante a instalação, consulte a documentação do TaskManager ou procure ajuda online.
