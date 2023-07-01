Para editar o link do repositório remoto em seu clone local, você pode seguir os seguintes passos:

Passo 1: Verifique o link atual configurado com o comando abaixo:

```
git remote -v
```

Esse comando exibirá os links do repositório remoto (origem) e suas referências (fetch/push).

Passo 2: Para editar o link, use o comando `git remote set-url origin` seguido pelo novo link desejado. Por exemplo, se você deseja alterar o link para "https://github.com/seu-usuario/seu-repositorio.git", execute o seguinte comando:

```
git remote set-url origin https://github.com/seu-usuario/seu-repositorio.git
```

Passo 3: Para verificar se o link foi alterado corretamente, execute novamente o comando `git remote -v` para exibir os links atualizados.

Dessa forma, você terá atualizado o link do repositório remoto em seu clone local para o novo link que você especificou.