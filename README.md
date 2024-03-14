# algo-divergente
Para clonar este repositório foi utilizado o seguinte comando:
```git
git clone https://github.com/FilipeS0usa/algo-divergente.git
```
## Initial commit
Para o primeiro commit foram utilizados os seguintes comandos:

```bash
git add README.md
git commit -m "Initial commit"
git push
```
git add para adicionar o ficheiro
git commit para fazer o commit com a respectiva mensagem
git push para enviar para o repositório remoto

## Filipe Silva


## Hugo Almeida

- Para clonar este repositório foi utilizado o seguinte comando:
```git
git clone https://github.com/Grilinux/algo-divergente.git
```
- A partir do fork que fiz no repositório do Silva.
- Criei um ficheiro .py chamado codigoalmeida.py para ser revisto pelos colegas de grupo.
`touch codigoalmeida.py`
- Fiz commit com esse comentário.

- Criei um novo branch
`git checkout -b "brunch_do_almeida"`

- Fiz mudanças no ficheiro codigoalmeida.py e voltei a dar commit.
- Nova feature no codigoalmeida.py e novo commit.
`git commit -m "nova feature super fixe no codigo"`

- Fiz `git checkout main` para puder fazer git cherry-pick de uma das versões do branch em que estava a trabalhar.
- Fiz `git cherry-pick b2e2f67` de uma das versões para o main. Houve conflitos que foram resolvidos eliminando as linhas sobrepostas entre as duas versões e depois de resolvidos os conflitos fiz `git cherry-pick continue`.

- Fiz `git merge` entre os dois branchs. Resolvi conflitos no merge (eliminando as linhas que estavam sobrepostas entre as duas versões) 
- Depois de resolvidos os conflitos fiz `git add .` e `git commit -m "mensagem"`.

- Fiz um novo branch `git checkout -b novinho_brunch_almeida`
- Criei um novo ficheiro .py nesse branch chamado novinhocodigoalmeida.py
- Dei commit desse ficheiro
- Vou atualizando a documentação à medida que faço alguma coisa nova
- Fiz rebase deste novo branch para o main
`git checkout main | git rebase novinho_brunch_almeida`

- Introduzi uma tag num dos commits antigos como sendo a versão 1.0 do programa
`git tag v1.0 755c038`

## João Correia
