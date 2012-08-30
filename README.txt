EFActiveRecord � um modelo de implementa��o do Partner utilizando recursos do Entity Framework. 

Para entender o funcionamento da biblioteca acesse a pasta repositorio e veja os arquivos contidos nela, depois veja a implementa��o no modelo e posteriormente no Controller.

Quer entender mais  sobre o Active Record leia o texto abaixo:


Em Engenharia de software, active record � um padr�o de projeto encontrado em softwares que armazenam seus dados em Banco de dados relacionais. Assim foi nomeado por Martin Fowler em seu livro Patterns of Enterprise Application Architecture[1]. A interface de um certo objeto deve incluir fun��es como por exemplo Inserir(Insert), Atualizar(Update), Apagar(Delete) e propriedades que correspondam de certa forma diretamente �s colunas do banco de dados associado.
Active record � uma abordagem para acesso de dados num banco de dados. Uma tabela de banco de dados ou vis�o(view) � embrulhada(wrapped) em uma classe. Portanto, uma inst�ncia de um objeto � amarrada a um �nico registo(tupla) na tabela. Ap�s a cria��o e grava��o de um objeto, um novo registo � adicionado � tabela. Qualquer objeto carregado obt�m suas informa��es a partir do banco de dados. Quando um objeto � atualizado, o registro correspondente na tabela tamb�m � atualizado. A classe de embrulho implementa os m�todos de acesso(setter e getter) ou propriedades para cada coluna na tabela ou vis�o.

fonte: http://pt.wikipedia.org/wiki/Active_record