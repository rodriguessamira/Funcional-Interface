
<img width=100% src="https://capsule-render.vercel.app/api?type=rounded&height=95&color=F4D9D0&text=Functional%20Interface&reversal=false&section=header&textBg=false&fontColor=474A51&animation=fadeIn&fontAlign=50&fontSize=70"/>

Qualquer interface com um SAM (Single Abstract Method) é uma interface funcional e sua implementação pode ser tratada
como
expressões lambda.

- `Consumer<T>`: Representa uma operação que aceita um argumento do tipo T e não retorna nenhum resultado. É utilizada
  principalmente para realizar ações ou efeitos colaterais nos elementos do Stream sem modificar ou retornar um valor.

- `Supplier<T>`: Representa uma operação que não aceita nenhum argumento e retorna um resultado do tipo T. É comumente
  usada para criar ou fornecer novos objetos de um determinado tipo.

- `Function<T, R>`: Representa uma função que aceita um argumento do tipo T e retorna um resultado do tipo R. É
  utilizada para transformar ou mapear os elementos do Stream em outros valores ou tipos.

- `Predicate<T>`: Representa uma função que aceita um argumento do tipo T e retorna um valor booleano (verdadeiro ou
  falso). É comumente usada para filtrar os elementos do Stream com base em alguma condição.

- `BinaryOperator<T>`: Representa uma operação que combina dois argumentos do tipo T e retorna um resultado do mesmo
  tipo T. É usada para realizar operações de redução em pares de elementos, como somar números ou combinar objetos.

[<img src= 'https://img.shields.io/badge/Ir_para_Códigos-FFB6C1?style=for-the-badge&' alt='Ir para Códigos' height='35' border='0'>](https://github.com/rodriguessamira/Funcional-Interface/tree/main/src)



### Referências:

- Todo o estudo de Collection foi feito pela link a seguir: https://github.com/digitalinnovationone/ganhando_produtividade_com_Stream_API_Java/blob/master/src/functional_interface/README.md?plain=1
