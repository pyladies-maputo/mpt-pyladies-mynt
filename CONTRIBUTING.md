Contribuindo na PyLadies Maputo
============
Para contribuir com o repositório PyLadies Maputo, encontre uma problema/[issue](https://github.com/pyladies-maputo/mpt-pyladies-mynt/issues) aberta.
Qualquer problema não atribuído pode resolver! Para que o mesmo seja atribuído a ti, precisas ser um membro do [Grupo de Colaboradores](https://github.com/orgs/pyladies-maputo/teams/pycoders); 
Basta adicionar uma mensagem sobre o problema no qual gostarias de trabalhar e nós o adicionaremos à equipe para 
que possamos ti atribuir esse problema. 

Observe labels/tag: 
- bugs
- duplicate
- investigate
- good first issue 

Se fores novo contribuir para o código aberto, ou apenas novo em contribuir para o repositório PyLadies Maputo,
confira a tag `good first issue`. Essas são questões mais simples que seriam boas para os contribuintes de primeira viagem.

Praticando
------------------
1. Faça o fork do projeto
2. Clone o projeto para a seu computadosr `git clone https://github.com/<seu_user>/mpt-pyladies-mynt.git`
3. Crie uma branch para a feature em que vais trabalhará: `git checkout -b user-nova-feature`
4. Faça commit das suas alterações: `git commit -m 'Adiciona nome da feature'`
5. Faça push desses commits para sua branch: `git push origin user-nova-feature`
6. Envie um PR (pull request) para o nosso repositório

Update do fork
------------------

Caso não tenha mais o projeto em seu computador:

- Clone o projeto para a seu computador `git clone https://github.com/<seu_user>/mpt-pyladies-mynt.git`

No seu computador:

1. Adicione um novo remote: `git remote add upstream https://github.com/pyladies-maputo/mpt-pyladies-mynt`
2. Obtenha todas as branches deste novo remote: `git fetch upstream`
3. Certifique-se de que está na branch main: `git checkout main`
4. Atualize sua branch main, unindo seus commits (que não estão no projeto original) ao projeto atualizado: `git rebase upstream/main`
5. Atualize seu fork no GitHub: `git push origin main`

**Observação**: Se for a primeira vez a fazer rebase, talvez precise usar o "-f": `git push -f origin main`

Preparando o ambiente local
--------------------------
- Antes de mais nada, verifique a versão **Python 3.11.6** instalado pelo comando `python --version`.

Para criar um `virtualenv` e instalar os pacotes necessários para o projeto,
siga as instruções no [README](https://github.com/pyladies-maputo/mpt-pyladies-mynt/blob/main/README.md)
