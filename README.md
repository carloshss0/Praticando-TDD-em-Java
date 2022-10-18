# Praticando TDD com Java


## Foi praticada a metolodogia de Desenvolvimento de Software TDD - Test Driven Development.

Com base nos requisitos de uma aplicação, que nesse caso era calcular o reajuste no salário de um funcionário. Os critérios para reajuste seria com base na avaliação de desempenho de dado funcionário. Quanto melhor fosse a avaliação, maior seria o percentual de aumento.


Tendo os requisitos, escrevi um código "rascunho" considerando apenas uma única funcionalidade, que nesse caso era para o caso da avaliação ser "A DESEJAR".
Obviamente de início o código não compila. Para o teste funcionar, foi necessário implementar os métodos e classes necessários para tal. Após isso, o código funcionou e passou no teste.


Em seguida, escrevi testes para o caso do funcionário ter outros critérios de avaliação, como "BOM" ou "OTIMO". Novamente o código não funcionou, foi feita a implementação necessária para o código funcionar com esses parâmetros. O código funcionou e passou nos testes unitários.

Enfim, fiz uma refatoração no código para facilitar a manutenção e evitar códigos duplicados. Na implementação inicial o código ficou com muitos if/else encadeados. Caso fosse acrescentado mais paraâmetros de avaliação, o código começaria a dar mais trabalho de manuntenção e dificultaria em fazer melhorias. Esse foi o motivo que levou a decisão de fazer a refatoração


Com base no que foi feito, observei que foi passado por todos os ciclos do TDD:

- 1: Escrever um teste que falhe,
- 2: Fazer o código funcionar,
- 3: Eliminar redundâncias (refatoração)


