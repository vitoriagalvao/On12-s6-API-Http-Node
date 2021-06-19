# On11-TodasEmTech-s6-Introducao-Node
Turma Online 11 - Todas em Tech | Back-end | 2021 | Introdução à API:
HTTP e NodeJS

## Para o lar
Abra o PullRequest Respondendo as seguintes questões:

1) Qual a relação entre os métodos HTTP e o CRUD?
Os métodos HTTP e CRUD estão relacionados a ação que fazemos de forma intuitiva ou não ao trabalhar com requisições. Com os dois métodos é possivel criar, deletar e atualizar.
 
2) Comente, com exemplos, a diferença entre o PUT e o PATCH.
O PATCH é usado para atualizar partes de um recurso, exemplo:
Exemplo: (/usuario/1234) :
Resultado: {'name': 'João'}
 
 Enquanto o PUT é usado para guardar um recurso na URL e caso já seja existente, deve ser atualizado, senão, é criado. Exemplo:

Exemplo: (/usuario/1234) :
Resultado: {'id': 1234, 'name': 'Joao', 'idade': 25, 'documento': '123.321.12-X'}

3) Assim como na aula, apresente os dados dos JSONs no console 
    - No colors-rgb.js apresente o nome da cor e o codigo RGB como no exemplo: "gainsboro - rgb(220, 220, 220, 1)"
    - No estados-cidade.js apresente o nome do Estado, a sigla e todas as cidadades, sem arrays aparentes no console
    - No filmes.js apresente titulo, plot, generos e lingua. Genero e lingua devem ser apresentados em arrays no console.

4) Defina o conceito de idempotência e como uma API pode ser idempotente
Podemos definir idempotência ou idempotente os métodos que não sofrem alterações no servidor quando são chamados varias vezes. Sendo assim, entendo que uma API pode ser considerada idempotente quando ela não causa alterações que prejudiquem o processo. Exemplo; ao utilizar a API do Spotify para integrar com o instagram, os usuários faram muitas requisições para aquela API, então é importante que mantenha a integridade dos dados.

5) Cite alguns diferentes padrões de projetos de software
Abstract Factory; é um padrão de projeto que permite a crição de familias de objetos relacionados ou dependentes por meio de uma única interface e sem que a classe seja especificada.
Factory Method; permite ás classes delegar para as subclasses decidirem, isso é feito através da criação de objetos que chama o método numa interface e implementa por uma classe "filha" ou abstrata.
Singleton; garante que um objeto terá apenas uma única instância, isto é, que uma classeirá gerar apenas um objetoe que ele estará disponivel de forma única para todo o escopo da aplicação.