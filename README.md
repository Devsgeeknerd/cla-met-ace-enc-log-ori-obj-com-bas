<!-- Título -->
# Métodos Acessores

***Conteúdo da Aula:***

Várias bibliotecas e *frameworks* exigem que as classes implementem os métodos chamados acessores.

De maneira geral, é considerada uma boa prática não expor os atributos de uma classe de maneira direta.

Ou seja:

* Não é uma boa prática deixar os atributos de uma classe como sendo públicos, para que possam ser acessados de maneira direta.

* Segundo esta prática, o correto é manter os atributos como privados.

Porém, como vimos, se tornarmos os atributos todos privados, eles não poderão ser modificados nem lidos por outros objetos de nossa aplicação.

Nós precisamos ter uma maneira de expor estes atributos, porém, sem expor os atributos em si de maneira direta.

E é aí que entram os métodos acessores.

Nós temos basicamente dois tipos de métodos acessores:

* `Método acessor get`:
  * É um método responsável por retornar o valor de um determinado atributo;

* `Método acessor set`:
  * É um método responsável por alterar o valor de um determinado atributo.

Seguindo este pensamento, cada atributo terá dois métodos acessores:

* Um método `get` para que o valor possa ser lido;
* E um método `set` para que o valor possa ser alterado.

Porém, não é uma regra que todo atributo deverá de fato conter os dois métodos acessores:

* Você pode ter um atributo somente com um método `get` associado (o que caracterizaria um atributo somente-leitura externamente) ou até mesmo somente com um método `set` associado (o que faria que o atributo só pudesse ser modificado externamente).

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-met-ace-enc-log-ori-obj-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-met-ace-enc-log-ori-obj-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-met-ace-enc-log-ori-obj-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-met-ace-enc-log-ori-obj-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-met-ace-enc-log-ori-obj-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-met-ace-enc-log-ori-obj-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
