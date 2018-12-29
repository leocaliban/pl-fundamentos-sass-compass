# Práticas realizadas na leitura no livro Fundamentos de SASS e COMPASS

## CAPA
## AUTOR

## Preparando o ambiente 

* Instalar o [Ruby](https://rubyinstaller.org/)

* Intalar o SASS e Compass:

Excecutar ```gem install compass``` na CLI.

## Compilar SCSS

Executar ```sass --watch ARQUIVO.scss:ARQUIVO.css``` na pasta onde estão os arquivos de estilo, para compilar o SASS.

Ex:```sass --watch style.scss:style.css```

### Monitorando CSS em diferentes diretórios

```sass --watch dir/ARQUIVO.scss:dir/ARQUIVO.css```

## Definindo formatos de saída para a CSS

- nested
- expanded
- compact
- compressed

EX: ```sass sass/style.scss css/style.css --style compressed```

## Utilização do KOALA para compilas SASS

* Instalar o [Koala](http://koala-app.com/) 

## Compilador online SASS

* [Sassmeister](https://www.sassmeister.com/)