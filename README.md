# Onuvelo
## Sistema de gerenciamento de projetos em crochê 

* ### Função exibir menu
 **`exibirMenu():`**
 
```java script
    - Menu Onuvelo -
    1. Adicionar projeto
    2. Listar projetos
    3. Mudar projeto
    4. Concluir projetos
    5. Excluir projeto
    6. Sair    
```    

 A função **Exibir Menu** mostra ao usuário todas as opções possíveis que podem ser selecionadas, e é através da condicional, o *switch* que vai apresentar a função escolhida pelo usuário.

 * ###  Função adicionar

 A função ```adicionar()``` vai armazenar a resposta do usuário, pedindo o nome do projeto, o fio e/ou material, a data de entrega e o preço, logo o ```croche.push``` vai adicionar as respostas no array.

```java script 
let croche = []
```

 * ### Função listar

Na função ```listarProjetos()``` tudo que foi armazenado pela funçao adicionar, vai ser apresentado ao usuário, mostrando também a opção de **concluido**, o qual tem o valor de boolean.

Exemplo:

```Lista de projetos: 
1. Nome: Patinho
   Fio/material: Amigurumi
   Data de entrega: 25/07
   Preço: R$30.00
   Concluído: Não
```
Caso não possua nada dentro da array **croche**, a menssagem *"Nenhum projeto cadastrado"* vai ser exibida,através de uma condicional e assim funciona nas demais funções também.

 * ### Função mudar projeto

Caso o usuario queira alterar um de seus projetos, ele terá que digitar o número do projeto escolhido, e assim alterar as propriedades.

```javascript
... 
rl.question('Novo preço: ', (preco) => {
        croche[numero - 1] = {
                nome: nome, 
                fio: fio,
                data: data, 
                preco: parseFloat(preco)
        }
        console.log('Projeto alterado com sucesso!!!')
        exibirMenu()
})
```

* ### Função projeto concluído

Função ```projetoConcluido()``` é a parte do código que altera o valor de **concluído** para TRUE. E assim que for listado, o projeto será marcado como feito.

Exemplo:
```
Lista de projetos: 
1. Nome: Patinho
   Fio/material: Amigurumi
   Data de entrega: 25/07
   Preço: R$30.00
   Concluído: Sim
```

* ### Função Excluir

A função ```excluir()```, vai simplismente eliminar o projeto que o usuário selecionar. 







