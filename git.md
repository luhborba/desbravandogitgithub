# Comandos Git Comuns

## Iniciar uma Área de Trabalho

- **clone**: Clonar um repositório para um novo diretório.
  ```sh
  git clone <url-do-repositório>
  ```

- **init**: Criar um repositório Git vazio ou reinitializar um repositório existente.
  ```sh
  git init
  ```

## Trabalhar na Alteração Atual

- **add**: Adicionar o conteúdo de arquivos ao índice (staging area).
  ```sh
  git add <arquivo>
  ```

- **mv**: Mover ou renomear um arquivo, diretório ou link simbólico.
  ```sh
  git mv <arquivo-antigo> <arquivo-novo>
  ```

- **restore**: Restaurar arquivos na árvore de trabalho.
  ```sh
  git restore <arquivo>
  ```

- **rm**: Remover arquivos da árvore de trabalho e do índice.
  ```sh
  git rm <arquivo>
  ```

## Examinar o Histórico e o Estado

- **diff**: Mostrar diferenças entre commits, commit e árvore de trabalho, etc.
  ```sh
  git diff
  ```

- **grep**: Imprimir linhas que correspondem a um padrão.
  ```sh
  git grep <padrão>
  ```

- **log**: Mostrar logs de commits.
  ```sh
  git log
  ```

- **show**: Mostrar vários tipos de objetos.
  ```sh
  git show <objeto>
  ```

- **status**: Mostrar o status da árvore de trabalho.
  ```sh
  git status
  ```

## Crescer, Marcar e Ajustar seu Histórico Comum

- **branch**: Listar, criar ou deletar branches.
  ```sh
  git branch
  git branch <nome-da-branch>
  git branch -d <nome-da-branch>
  ```

- **commit**: Registrar mudanças no repositório.
  ```sh
  git commit -m "mensagem do commit"
  ```

- **merge**: Unir duas ou mais histórias de desenvolvimento.
  ```sh
  git merge <nome-da-branch>
  ```

- **rebase**: Reaplicar commits em cima de outro ponto base.
  ```sh
  git rebase <branch-alvo>
  ```

- **reset**: Resetar o HEAD atual para o estado especificado.
  ```sh
  git reset --hard <commit>
  ```

- **switch**: Trocar de branches.
  ```sh
  git switch <nome-da-branch>
  ```



## Colaborar

- **fetch**: Baixar objetos e referências de outro repositório.
  ```sh
  git fetch <nome-do-remoto>
  ```

- **pull**: Buscar e integrar com outro repositório ou branch local.
  ```sh
  git pull <nome-do-remoto> <branch>
  ```

- **push**: Atualizar referências remotas junto com objetos associados.
  ```sh
  git push <nome-do-remoto> <branch>
  ```

