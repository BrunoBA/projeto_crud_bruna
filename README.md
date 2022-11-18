# projeto_crud_bruna
Projeto CRUD

O Projeto é sobre persistencia de dados, cada dado deve ter o nome mais um identificador único

ex:

| Identificador      | Nome |
| :- | :- |
|1  | Bruno    
|2  | Bruna    
|3  | Vanessa  
...
|76  | Neymar  
|77  | Vini Jr.  


Deve ser implementado um CLI simples com os seguintes comandos


1. [Adicionar](#Adicionar)
2. [Exibir](#exibir)
3. [Listar](#listar)
4. [Alterar](#alterar)
5. [Remover](#remover) 

## Adicionar

> Ao selecionar a opção 1, deve ser perguntado o nome da pessoa a ser inserida e atribuir um identificador único ao mesmo


## Exibir

> Deve perguntar o identificador da pessoa, e exibir o seu nome na tela, caso a pessoa não exista, informe ao usuário que esse usuário não existe ou foi removido


## Listar

> Deve mostrar todos as pessoas cadastradas


## Alterar

> Deve perguntar o identificador da pessoa, e perguntar o novo nome. O identificador do usuário deve permanecer intacto


## Remover

> Deve perguntar o identificador da pessoa, e então excluir


## Funcionamento

> Os identificadores devem ser únicos, se um usuário foi removido, outro usuário não pode ter o mesmo id


Ex:
| Identificador      | Nome |
| :- | :- |
|1  | Bruno    
|2  | Bruna    
|__3__  | __Vanessa__

_(3 foi removido)_

| Identificador      | Nome |
| :- | :- |
|1  | Bruno    
|2  | Bruna    


E então uma nova pessoa foi inserida
_(inserido Vaneuza)_

| Identificador      | Nome |
| :- | :- |
|1  | Bruno    
|2  | Bruna    
|__4__  | __Vaneuza__

## Armazenamento
Pode ser usado qualquer tipo de arquivo para persistência dos dados