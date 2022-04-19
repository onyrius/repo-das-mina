# :octocat: Passo a passo para não perder os seus commits :octocat:

---

## 1 - Criar um novo repositório no seu perfil do GitHub 

Clique no botão "New" logo no topo da página de seus repositórios como na figura a abaixo

<img src="images/criando-novo-repositorio.png" alt="como criar um novo repositório">

<p>Clicando no botão "New", você será redirecionada para a pagina de criação. Preencha os campos requiridos e clique no botão verde "Create repository" que fica no final da página </p>

<img src="images/preenchendo-os-campos-novo-repo.png" alt="preenchendo-os-campos-novo-repo"/>

<img src="images/clique-no-botao-verde.png" alt="clique-no-botao-verde"/>

<p>Você será direcionada para a seguinte tela</p>

#### guarde o SSH 

<img src="images/copiar-ssh.png" alt="copiar-ssh"/>

## 2 - Adicionar o seu repositório da Trybe ao seu repositório criado

Entre na sua branch do projeto da Trybe

`git checkout <sua_branch>`

**Aviso da Trybe**

_Importante : Ajuste seu código para não ferir os Termos de Uso da Trybe ou o Manual da Pessoa Estudante :
Remova todos os testes da Trybe que avaliam os requisitos do Projeto, assim como arquivos e pastas auxiliares ao avaliador da Trybe ( trybe.yml , .github/* e .trybe/* ). Edite o README apagando o conteúdo original ( depois preencha de acordo com nosso guia de README para projetos ! ) Se o Projeto não foi feito individualmente : garanta que as outras pessoas que contribuíram estão de acordo, dê os devidos créditos a elas no README , e também sinalize no README quais partes do código foram implementadas por você.
Se a Trybe forneceu uma aplicação (ou parte dela) no Projeto e você apenas precisou complementá-la para realizar requisitos ( exemplo: requisitos de implementações de testes ): sinalize no README quais partes do código foram implementadas por você, e quais foram fornecidas pela Trybe_

- Faça os comites. E adicione do remote ao seu repositório local.

`git remote add <apelido_do_remote> <url_ssh_do_repositório>`

 nesse caso, eu apelidei o meu remote de tryunfo-repo - como na imagem abaixo

<img src="images/adicionando-remote-ao-local.png" alt="adicionando-remote-ao-local"/>

depois faça o push do seu repositorio local para o  remote 

`git push <apelido_do_remote> <sua_branch>:main`

<img src="images/fazendo-push-para-o-remoto.png" alt="fazendo-push-para-o-remoto"/>
<img src="images/resultado-do-push" alt="resultado-do-push"/>