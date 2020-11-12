KARINE

NAYARA TESTEEE

<!-- # oficina-git-dupla

## Fork

Primeira pessoa:

- Faz o `fork` do repositório da Laboratória.
- Adicione sua dupla como colaboradora do seu projeto
- Clone do seu repositório
  ```bash
  git clone https://github.com/primeiraUser/oficina-git-dupla.git
  ```
- Entre na pasta do repositório

Segunda pessoa:

- Faz o `fork` do repositório da colega.
- Clone do seu repositório
  ```bash
  git clone https://github.com/segundaUser/oficina-git-dupla.git
  ```
- Entre na pasta do repositório
- Adicionar endereço remoto `upstream`
  ```bash
  git remote add upstream https://github.com/primeiraUser/oficina-git-dupla.git
  ```
- Criar `branch` para fazer suas alterações
  ```bash
  git checkout -b funcionalidade/alteracao
  ```
- Faz alteração no código
- Adiciona o `commit`
- Faz `push` da sua `branch` para `origin`
  ```bash
  git push origin funcionalidade/alteracao
  ```
- Vá para o Github e abra uma `pull request` para a `branch` da sua dupla

Primeira pessoa:

- Quando souber que sua dupla abriu uma nova `pull request`, vá até o Github, analise as alterações, aprove e faça o `merge` da `branch` dela com a `master`
- Traga as alterações do github para o seu repositório local
  ```bash
  git pull origin master
  ```
- Criar `branch` para fazer suas alterações
  ```bash
  git checkout -b funcionalidade/alteracao
  ```
- Faz alteração no código
- Adiciona o `commit`
- Faz `push` da sua `branch` para `origin`
  ```bash
  git push origin funcionalidade/alteracao
  ```
- Vá para o Github e abra uma `pull request` para a sua `branch master` (não esquecer de alterar o caminho para sua `branch`, ou o `pull request` será feito para o repositório da Lab!)

Segunda pessoa:

- Quando souber que sua dupla abriu uma nova `pull request`, vá até o Github, analise as alterações, aprove e faça o `merge` da `branch` dela com a `master`
- Traga as alterações do github para o seu repositório local e atualize seu repositório remoto
  ```bash
  git pull upstream master
  git push origin master
  ``` -->
