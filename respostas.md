
## Coloque as suas respostas nesse arquivo e efetue um commit

Q1-Este sistema especialista (sistema-especialista-dinossauro) faz as perguntas de forma dinâmica ou seja nem sempre as mesmas perguntas são exibidas ao usuário, ou sempre as mesmas perguntas são exibidas ao usuário, na mesma ordem? (sim, não)


  * `Não`, as mesmas perguntas são feitas. O sistema segue o fluxograma de `Rede Semântica.pdf`.


Q2-Este sistema especialista (sistema-especialista-dinossauro) usa a técnica de encadeamento para frente e encademento para trás, ou nenhuma delas? (sim, não ou não sei)


  * `Nenhuma delas`.


Q3-Este sistema especialista (sistema-especialista-dinossauro) utiliza uma base de conhecimento baseada em regras do tipo "SE (antecedente)-ENTÃO (consequente)"? (sim, não ou não sei)


  * `Não`, a base de conhecimento está definida num arquivo de texto (`db.txt`). Nesse arquivo o dinossauro já possui os atributos a serem perguntados.


(opcional) Q4-Qual técnica esse "sistema especialista" utiliza?


  * As perguntas vão sendo efetuadas até que a probabilidade obitda das opções dadas pelo texto `db.txt` chegue em 1, ou seja, apenas 1 dinossauro se mantém como opção.
