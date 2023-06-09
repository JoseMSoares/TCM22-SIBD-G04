**Relatório de Especificação da Informação**

<hr>

# C1 - Introdução:

Descrição do Trabalho:

O nosso problema consta em criar e manter uma boa organização de diversos docentes, projetos, departamentos e estudantes de um polo universitário, no intuito de melhor organizar a informação e estar à "mão" para ser consultada  

Para resolver este problema vamos criar um sistema de identificação que esteja conectado à base de dados central permitindo a boa organização e classificar os diferentes grupos de pessoas e estas mesmas numa dada universidade.

Inicialmente iremos criar categorias para classificar de acordo com a base de dados seguindo com o procedimento de criar o sistema de maneira a melhor. Para tal consideramos que cada professor tem um NIF, nome, idade, posto e uma especialidade de investigação.

* Existem projetos com um número, um organismo financiador, uma data de início, uma data de final, e um orçamento.
* Cada organismo financiador possui nome e uma identificação
* Estudantes de pós-graduação têm um número de contribuinte, um nome, uma idade, e um plano de curso (ex. mestrado, doutoramento).
* Cada projecto tem um ou mais estudantes de pós-graduação (conhecidos como os assistentes de investigação).
* Sempre que um estudante de pós-graduação trabalha num projecto, terá que existir um professor a supervisionar esse trabalho. 
* Os estudantes podem trabalhar em vários projetos com supervisores eventualmente diferentes.
* Os departamentos têm um número, um nome, e um escritório principal.
* Os departamentos são liderados por um professor.
* Os professores podem trabalhar num ou mais departamentos. Associada a cada uma destas funções está uma percentagem do seu tempo.
* Os estudantes de pós-graduação estão associados a um departamento no qual fazem o seu curso.
* Cada estudante de pós-graduação tem um outro estudante mais velho que é o seu aconselhador.

Vamos portanto catalogar toda esta informação, de maneira a ficar melhor organizada e a ser possível a sua utilização noutros softwares e a sua própria consulta para qualquer interesse.


## Descrição dos requisitos do utilizador

Os tipos de utilizadores do sistema de informação e as funcionalidade a queestes terão acesso são:

Developer - responsável por manter o sistema e atualizá-lo.

As suas funcionalidades são:

* Criar e manter o sistema
* Manter a base de dados relevante
* Criar e manter a interface do sistema para uso eficaz
* Criar e manter acesso codificado à plataforma (usuário e palavra-passe associada)


---
[< Previous](rebd00.md) | [^ Main](https://github.com/JoseMSoares/TCM22-SIBD-G04) | [Next >](rebd02.md)
:--- | :---: | ---: 