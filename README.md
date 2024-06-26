### Função exibir Menu 

 **`function exibirMenu()`**
 
 

    - Menu Onuvelo -
    1. Adicionar projeto
    2. Listar projetos
    3. Mudar projeto
    4. Concluir projetos
    5. Excluir projeto
    6. Sair    
    


 A função exibir menu: Vai apresentar o que cada função

 ### switch
 no switch o usuario vai escolher a sua opção,bnele vai apresentar cada função que o usuário vai escolher como

 ```adicionar()```

 ###  Função adicionar

 A função adicionar vai basicamente armazenar a resposta do usuário, vai pedir o nome do projeto que voce quer, o fio/material, e a data de entrega, logo no ```croche.push``` vai puxar/empurrar o que o usuario vai especificar na função

 ### Funcão listar

Na função listar vai apresentar tudo que foi pedido na função adicionar

### Função mudar projeto

Caso o usuario queira mudar o seu projeto, ele vai alterar o projeto que ja havia sido adicionado

Exemplo: ``` console.log('Lista de projetos: ')
        croche.forEach((croches, index) => {
        console.log(`${index + 1}. Nome: ${croches.nome}`)
        })```

### Função projeto concluído

função projeto concluido
é nessa fase do projeto que tudo que foi planejado é colocado em pratica e finalizado.

### Função Excluir

A função excluir, vai eliminar o projeto que o usuário  havia listado antes.






