# comandos git 
neste arquivo será apresentado os comandos git para uso futuro.

## no primeiro uso em um computador
para quw o git avise e saiba quem fez as alterações é necessário 
configurar o usuário nas configurações globais do git.
```bash
git config --global user.name "Rodrigo A. Lima Dos Santos"

git config --global user.email "rodrigosantos5510jau@gmail.com"
```

### comandos para gestão do git 
para inicializar uma pasta como repositório git usamos o comando init.
só utilizamos este comando 1 vez
```bash
git init
```
para ver a situação do repositório utilizamos o comando status.
ele pode ser executado a qualquer momento pata sane a situação da pasta.
se estiver vermelho precisa adicionar os arquivos, se estiver vede estão prontos 
para salvar (commit).
se não aparecer nada, ou o arquivo não está salvo ou já está tudo ok.
```bash
git status
```

para adicionar todos os arquivos modificados para serem versionados utilizamos p add
```bash
git status
```


para criar uma vesão de tudo que foi modificado até aquele momento utilizamos o commit. <br>
## importante 
```bash
git push
```
pull baixa todas as atualizações que o repositório tem no github e não está no seu pc.
