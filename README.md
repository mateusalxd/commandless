# Commandless

Comandos utilizados para executar containers com CLI de ferramentas.

## Requisitos

- Docker

## Como usar?

- escolha qual ferramenta pretende utilizar
- copie o arquivo para um diretório, por exemplo:

```bash
# execute dentro do diretório do repositório
mkdir ~/.commandless/
cp maven_slim ~/.commandless/
```

- criar um `alias` para o comando

```bash
alias mvn="~/.commandless/maven_slim"
```

## Padrão dos nomes dos arquivos

Como os comandos dependem das imagens, duas informações são utilizadas para organização, o nome da imagem e a tag, ficando `nome_tag`.
