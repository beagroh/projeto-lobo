# Como utilizar o Git:

- Criar novo repositório no GitHub
- Criar pasta no computador para o projeto
- Dentro da pasta, executar o seguinte comando para inicializar o git (Somente na primeira vez):
```bash
$ git init
```
- Adicionar o repositório do git na pasta:
```bash
$ git remote add origin https://github.com/beagroh/bikcraft.git
```
### Sempre que houverem novas alterações, fazer o passo a passo abaixo:
- Adicionar os arquivos no `staged`:
```bash
$ git add .
```
- Commitar as alterações:
```bash
$ git commit -m "Mensagem do commit"
```
- Dar o push para enviar os arquivos para o Git:
```bash
$ git push origin master
```