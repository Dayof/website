Site Pyladies DF
====================
[![Build Status](https://app.codeship.com/projects/bca2dab0-d874-0134-15a2-326e4d300ce2/status?branch=master)](https://app.codeship.com/projects/bca2dab0-d874-0134-15a2-326e4d300ce2/status?branch=master)

Contribuindo
------------

Para contribuir com o projeto veja o guia de [Contribuição](https://github.com/pyladiesdf/website/blob/master/CONTRIBUTING.md). Lá você encontrará instruções detalhadas de como fazer a sua contribuição.

Instalando e Rodando
--------------------

- Para apenas rodar localmente o site, você precisa do [virtualenv](https://virtualenv.pypa.io/en/stable/) instalado na sua máquina.

Para instalar o virtualenv basta fazer:

```console
$ pip install virtualenv
```
- Assumindo que seu git e virtualenv já estão configurados, faça o clone do repositório

``` console
$ git clone git@github.com:pyladiesdf/website.git
```

- Rode o comando para criação de ambiente virtual e instalação das dependências

``` console
$ make install
```
> Obs.: Esse comando criará uma virtual env, então rode-o fora de qualquer ambiente virtual.

- Rode o projeto

``` console
$ make up
```

Abra o browser em [localhost:8000](http://localhost:8000) para ver o conteúdo gerado.

Links Úteis
-----------

* Documentação Pelican - http://docs.getpelican.com/en/3.6.3/
* Virtualenv - http://docs.python-guide.org/en/latest/dev/virtualenvs/
* Pyenv - https://github.com/yyuu/pyenv
* Criar um grupo PyLadies - https://brazilpyladies.gitbooks.io/handbook/content/

Sobre este Template
-------------------

Template das [PyLadies Brasil](https://github.com/pyladies-brazil/br-pyladies-pelican)!
