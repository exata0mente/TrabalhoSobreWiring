O Trabalho
==========

O trabalho deverá ser apresentado como composição da nota 1 da matéria de Laboratório Integrado II.

**Data de Entrega: 04/10/2018**

O Grupo
=======

Lucas Silva

Renato Frutuoso

Ricardo Bezerra

Robson Araújo

O Professor
===========

Bruno Abrantes - 03299@unifieo.br

Ferramentas
=============
Quadro no Trello[^1]

Repositório no GitHub[^2]

Ferramenta Git[^3]


Tópicos a serem pesquisados
==========================

[x] Breve história - Ricardo
[x] Wiring e o Arduino - Ricardo
[ ] Hardware Wiring - Renado
[ ] Software Wiring - Ricardo
[ ] Principais funções do Wiring (na perspectiva do Arduíno) - Ricardo
[ ] Wiring e o ARM - Lucas

Como utilizar o Git?
=====================

De forma bem sucinta o *workflow* abaixo mostrará como interagir neste repositório usando o git. Recomendo maior aprofundamento a quem interessar.

Copiar o repositório para o computador
---------

* No repositório há um botão **Clone or Download**. Copie a URL.
* Em seu computador, utilizando o git, digite:

```bash
git clone "url_copiada"
```

Este comando baixar todo o conteúdo e arquivos que estão no repositório para o seu computador.

Trabalhando com o git
---------------------

Sempre que for iniciar uma atividade, para que os arquivos que estão na sua pasta sejam os mais recentes do repositório, utilize o comando *pull*.

```bash
git pull
```

Este comando copiará os arquivos do repositório e **sobrescreverá** os arquivos de sua pasta. Por favor ler o *help* deste comando

Após o pull, faça as alterações necessárias.

Quando efetuar alguma mudança em algum arquivo, utilize o comando ´git status´ para verificar quais arquivos são **novos** ou **modificados**.

Finalizando as alterações, utilize o comando ```git add . ``` para colocar todos os arquivos novos ou modificados em "acompanhamento".

Depois, é necessário consolidar as alterações utilizando o ```git commit```. Este comando abrirá uma tela para comentar sobre do que se trata o commit. Recomendo dar uma pesquisada sobre boas práticas em commits.

Por fim, basta utilizar o comando ```git push``` para enviar as suas alterações consolidadas ao repositório no github.

Este workflow é bem basicão, algumas coisas foram omitidas para evitar confusão mas recomendo MUITO ler sobre o git, principalmente a documentação do próprio site. Se precisar de ajuda *mim chami*.


Dicas para outros projetos
=========================

* Markdown
* LaTeX
* Branchs, Issues e WorkFlows do Git

[^1]: https://trello.com/c/MYouwU9U
[^2]: https://github.com/exata0mente/TrabalhoSobreWiring 
[^3]: https://git-scm.com/book/pt-br/v2
