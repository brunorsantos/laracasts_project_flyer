# Project flyer - Laracasts

Projeto de estudo da aula Project Build "ProjectFlyer" With Me

## Initial Setup

Alterar chave do projeto via artisan(atualmente já é feito via composer create projetct), alterar banco para o desejado.
Criar repositorio no git, dar add e commit nos arquivos do projeto

```sh
git add .
git commit -m 'Commit inicial'
git push -u origin master
git remote add origin [Endereco do projeto]
```


## Basic Gulp Housekeeping

Via npm deve se atualizar as dependencias do Gulp que estão em package.json
Executar com sudo e com parametro para nao gerar links simbolicos quando estiver usando maquina virtual no windows

```sh
sudo npm install --non-bin-links
```

Foi necessario executar o comando para forcar a inslatação do sass devido a problema ao rodar o gulp posteriormente, portanto, caso isso ocorra, tentar:
```sh
npm rebuild node-sass
```

Excutar 'gulp' para rodar as tarefas criadas no laravel elixir em gulpfile.js

