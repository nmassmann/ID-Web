git log --oneline         (mostra os commits de forma resumida em uma única linha)
git log -p                (mostra as alterações em cada arquivo modificado)
git log --graph           (exibe o histórico de commits com representação visual dos branches)git status                (mostra o estado atual dos arquivos no repositório)
git diff                  (mostra a diferença entre arquivos modificados e o último commit, apenas os que não estão no stage)
git diff dc8e15..5b3fc88  (mostra as diferenças entre dois commits específicos)
git show                  (mostra detalhes de um commit específico, incluindo mudanças e metadados, caso não for informado o commit, o último será utilizado)
git branch                (lista todos os branches locais)
git branch Tarefa_A       (cria um novo branch chamado Tarefa_A)
git branch -d Tarefa_A    (deleta o branch chamado Tarefa_A)
git branch Tarefa_B       (cria um novo branch chamado Tarefa_B)
git checkout Tarefa_B     (altera para o branch Tarefa_B) - git commit para gerar um pull request
git switch Tarefa_B       (alterna para o branch Tarefa_B — comando mais moderno que checkout)
git switch -c Tarefa_C    (cria e alterna para um novo branch chamado Tarefa_C)
git checkout main         (altera para o branch main)
git merge Tarefa_C        (mescla a branch Tarefa_C com o que já temos na main)
git rebase main           (aplica as mudanças da branch atual sobre a branch main, reescrevendo a história)


https://git-school.github.io/visualizing-git/
