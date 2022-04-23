 
 #  :octocat:  Passo a passo para não perder os seus commits  :octocat:

<br/>

### 1 - Criar um novo repositório no seu perfil do GitHub 

:exclamation: Clique no botão *"New"* logo no topo da página de seus repositórios como na figura a abaixo

<br/>

<img src="images/criando-novo-repositorio.png" alt="como criar um novo repositório" align="center" width="700">

---

<br/>

:exclamation: Clicando no botão *"New"*, você será redirecionada para a pagina de criação. Preencha os campos requiridos e clique no botão verde "Create repository" que fica no final da página

<br/>


<img src="images/preenchendo-os-campos-novo-repo.png" alt="preenchendo-os-campos-novo-repo" align="center" width="700"/>

<img src="images/clique-no-botao-verde.png" alt="clique-no-botao-verde" align="center" width="700"/>

---

<br/>

:exclamation: **Você será direcionada para a seguinte tela (guarde o SSH )**

<img src="images/copiar-ssh.png" alt="copiar-ssh" align="center" width="700"/>


---


<br/>

### 2 - Adicionar o seu repositório local ( branch que está o projeto da Trybe ) ao seu repositório criado

**Entre na sua branch do projeto da Trybe**

`git checkout <sua_branch>`

<br />

<br />

---

---

## :exclamation: :exclamation: Aviso da Trybe :exclamation: :exclamation:

_Importante : (ANTES DE DAR O PUSH PARA O SEU REPOSITÓRIO PESSOAL)
  Ajuste seu código para não ferir os Termos de Uso da Trybe ou o Manual da Pessoa Estudante : <br/>
     :heavy_check_mark: Remova todos os testes da Trybe que avaliam os requisitos do Projeto, assim como arquivos e pastas auxiliares ao avaliador da Trybe ( trybe.yml , .github/* e .trybe/* ). <br/>
     :heavy_check_mark: Edite o README apagando o conteúdo original ( depois preencha de acordo com nosso guia de README para projetos ! ) <br/>
     :heavy_check_mark: Se o Projeto não foi feito individualmente : garanta que as outras pessoas que contribuíram estão de acordo, dê os devidos créditos a elas no README , e também sinalize no README quais partes do código foram implementadas por você. <br/>
     :heavy_check_mark: Se a Trybe forneceu uma aplicação (ou parte dela) no Projeto e você apenas precisou complementá-la para realizar requisitos ( exemplo: requisitos de implementações de testes ): sinalize no README quais partes do código foram implementadas por você, e quais foram fornecidas pela Trybe_
     
---

---

<br />

<br />

:exclamation: **- Faça os commits. E adicione do remote ao seu repositório local.**

`git remote add <apelido_do_remote> <url_ssh_do_repositório>`

:exclamation: **nesse caso, eu apelidei o meu remote de tryunfo-repo - como na imagem abaixo**

<br/>


<img src="images/adicionando-remote-ao-local.png" alt="adicionando-remote-ao-local" align="center" width="700"/>

---

<br/>

**depois faça o push do seu repositorio local para o  remote** 

`git push <apelido_do_remote> <sua_branch>:main`
<br/>


<img src="images/fazendo-push-para-o-remoto.png" alt="fazendo-push-para-o-remoto" align="center" width="700"/>
<br/>
<img src="images/resultado-do-push.png" alt="resultado-do-push" align="center" width="700"/>
<br/>

---

##  checkered_flag:  Prontinho!!! Seu projeto já está dizendo "Olá, Mundo!"  checkered_flag:
