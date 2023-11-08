# Exercício 7: Vem Ser Tech - Front End | Ada Tech

## Sobre

 - Foi realizado um exercício no qual dados de parceiros de uma empresa são recebidos em formato de array e devem ser devidamente organizados em um Objeto, utilizando JavaScript.
_______________

### Como executar o projeto em desenvolvimento:
1. Clone esse repositório
```
git@github.com:BrendaRSS/exercise-seven-adatech.git
```
2. Abra um novo terminal dentro do projeto e execute:
```
node <nome-do-arquivo.js>
```

### Enunciado do exercício eategorização de Parceiros

Uma empresa de engenharia precisa fazer a separação de seus parceiros/sócios em duas modalidades, parceiros PF, pessoas físicas no qual possuem CPF e PJ pessoas jurídicas no qual possuem CNPJ, dito isso temos a seguinte lista:

| parceirosId      | nome            |
|------------------|-----------------|
| 19660156627897   | Fernanda Santos |
| 23998058019370   | Rafael Souza    |
| 92291338611      | Maria Silva     |
| 55443795656      | Maria Souza     |
| 77743761456      | Ana Costa       |
| 47202302326      | Maria Ferreira  |
| 58017232567      | Sofia Costa     |
| 16733009491247   | Lucas Silva     |
| 63351859919      | Rafael Souza    |
| 84297701780      | Carlos Oliveira |


O resultado final desse agrupamento deverá ser algo como:

    const parceirosAgrupados = {
      PF: [
        { parceirosId: '12345678901', nome: 'Carlos Antonio' },
        { parceirosId: '12345678901', nome: 'Informática' },
      ],
      PJ: [
        { parceirosId: '12345678901234', nome: 'Empresa Xpto Ltda.' },
        { parceirosId: '12345678901235', nome: 'Construtora' },
      ]
    }