# Curso Digital:

## O que é Git ?

Git é um sistema de versionamento de código, que guarda os registros de versão como **snapshots** ( fotos ) do estado do proejto, além da referência/caminho para esse snapshot.

### Untracked

Arquivos novos que ainda não foram adicionados ao stage ou commitados.

### Unmodified

Arquivos já existentes que não sofreram algum tipo de alteração

### Modified

Arquivos já existentes que foram modificados.

### Staged

Arquivos prontos para serem commitados

---

## Comandos Git

- git add _nome_arquivo_: adiciona arquivo para área de stage

- git rm _nome_arquivo_: remove o arquivo do repositório

- git restore _nome_arquivo_: desfaz alterações

- git restore -s ou --staged _nome_arquivo_: desfaz alterações do arquivo que está na área de stage

- git push: envia as alterações para o repositório remoto

- git fetch: busca as alterações do repositório remoto, mas não faz nenhuma alteração no repositório local, apenas atualiza as referência remotas, como branh, commits

- git diff: mostra as diferenças entre os arquivos do diretório, pode ser usado para verificar diferença entre commits específicos

- git pull : junção do fetch com o merge, ele pega as alterações do repositório remoto e as sincroniza com o local

- git branch: cria uma nova ramificação para trabalhar durante o desenvolvimento, podendo unir ela a branch principal futuramente

- git checkout _nome_da_branch_: muda de branch

- git merge: une uma branch a outra podendo haver conflitos entre elas.
