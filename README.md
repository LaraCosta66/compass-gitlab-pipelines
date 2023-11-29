# compass-gitlab-pipelines
![compass Logo](./images/compass.png)

### Pré-requisitos
- GitLab Account
- VsCode installed

## GitLab
- Passo 1: Crie um projeto no GitLab

![repo](./images/repo.png)

- Passo 2: Clone esse repositório na sua máquina

![repo](./images/clone.png)

### VSCode

- Passo 3: Abra o repositório no Vscode 

![abrir vscode](./images/open.png)

- Passo 4: Crie o arquivo **gitlab-ci.yml**

![file](./images/gitlab-file.png)

- Passo 5: Faça Commit e envie as alterações para o repositório


```
git status
git add . 
git commit -m 'add file'
git push origin main
```
![comandos](./images/git-comm.png)

### Volte ao GitLab

 - Na barra lateral esquerda, clique em **"Build"** e depois em **"Pipeline"**, você deve ver a pipeline sendo executada.

![pipeline](./images/pipeline-done.png)