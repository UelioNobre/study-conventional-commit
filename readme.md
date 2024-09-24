# Conventional Commits

Para visualizar Conventional Commits de uma maneira mais amigável e organizada, existem algumas ferramentas que podem ser integradas ao fluxo de desenvolvimento, facilitando a visualização dos commits de forma mais intuitiva. Aqui estão algumas opções populares:

### `Commitizen`

O Commitizen ajuda a padronizar e gerar mensagens de commits no formato convencional, tornando os commits consistentes e fáceis de entender. Ele possui uma interface interativa que orienta os desenvolvedores durante a criação das mensagens de commit.

Instalação:

bash
```sh
$ npm install -g commitizen
````

> Depois de instalar, basta usar o comando abaixo em vez de git commit:

```sh
$ git cz
```

O **Commitizen** oferece uma experiência guiada para criar mensagens de commit no formato convencional.


---

### `Conventional Changelog`

O Conventional Changelog pode ser utilizado para gerar um changelog (histórico de alterações) automaticamente a partir dos conventional commits, exibindo os commits de forma organizada e amigável.

`Instalação:`

```bash
npm install -g conventional-changelog-cli
```

`Gerar o changelog:`

```bash
conventional-changelog -p angular -i CHANGELOG.md -s
```

Isso criará um arquivo CHANGELOG.md que lista todos os commits com informações claras sobre novas funcionalidades, correções de bugs, etc.

> Pensa: gerar o changelog depois que passar nos testes/aprovação e enviar ao repositório remoto.

E por fim, a saída do comando changelog

---


### O que há de novo?
- Página index.html
- Página contato.html