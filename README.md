# Instruções

1. Abra o PowerShell e abra uma nova guia.
2. Utilize o comando `cd repos` ou `cd Documents` dependendo de onde deseja guardar seus arquivos.
3. Use o comando `git clone https://github.com/Varani07/aulas_programacao.git`, ignore este passo se já tiver o projeto no diretório.
5. `cd aula_programacao`.
6. Caso não tenha realizado o passo 3, digite `git pull`, isso vai puxar a próxima aula do repositório remoto.
    1. Verifique em qual branch está com o comando `git branch -a`.
    2. Se não estiver na main/master vá para ela com `git checkout master`.
    3. Use `git branch -a` novamente e delete todas as branch's cujo nome estiver em branco com `git branch -d nome-branch`.
7. `code .` para abrir com o editor.
8. Após terminar as atividades, lembre de salvar os arquivos modificados com o comando `ctrl + s`.
9. Volte para o terminal e digite `git checkout -b aula-01-pronta`, `git add .`, `git commit -m "Aula finalizada"` e por fim `git push origin aula-01-pronta`.