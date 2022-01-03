# Usuários


Um usuário é qualquer pessoa que realiza o login na Dashboard Service.

## Convidar usuários

Você pode convidar usuários para o Cypress através da [Dashboard Service](https://dashboard.cypress.io/). Os usuários 
convidados podem acompanhar todos os projetos e testes executados da organização.

### Convide usuários para uma organização

1. Acesse a página [Organizações](https://dashboard.cypress.io/organizations) para selecionar a organização para a qual 
deseja convidar o usuário

2. Clique em **Usuário**, e **Convidar usuário**. Observação: Você deve ser ['Proprietário' ou 'administrador'](https://docs.cypress.io/guides/dashboard/users#Sign-Up-with-an-Invitation)
 para convidar usuários.

3. Informe o e-mail, selecione a [função](https://docs.cypress.io/guides/dashboard/users#User-roles) e clique em 
**convidar usuário**.
Observação: Apenas proprietários podem conceder acesso de 'proprietário' para outros usuários.

4. O usuário receberá um e-mail com um link para aceitar o convite.

![invite-user-dialog](https://docs.cypress.io/_nuxt/img/invite-user-dialog.3df632b.png)

### Cadastre-se com um convite

Ao receber o e-mail, clique em **"Aceitar convite"** para ser redirecionado ao Cypress Dashboard. Logo após, você irá 
escolher o tipo de autenticação

- **Básico** (Google ou GitHub)  
- **Social** (E-mail e senha)
- **Login único**

#### Cadastro com autenticação básica

1. Clique em **"Não tem uma conta? Cadastre-se"**
2. Clique em **"Cadastre-se com e-mail"**
3. Informe o **e-mail** e crie uma **senha**
4. Clique em **"Cadastre-se"**

### Cadastro com autenticação social

1. Clique em **"Não tem uma conta? Cadastre-se"**
2. Clique em **"Cadastre-se com o Google"** ou **"Cadastre-se com o Google"**
3. Você pode precisar verificar através de seu provedor social, dependendo de suas configurações pessoais

### Cadastro com login único (SSO)

1. Acesse o [Guia SSO empresarial](https://docs.cypress.io/guides/dashboard/organizations#Slack-Integration)

## Funções do usuário

Os usuários podem ser atribuídos a funções que permitem acesso a determinados recursos do [Dashboard Service](https://dashboard.cypress.io/)

- **Membro:** Possui permissão para ver os projetos, execuções e chaves.
- **Administrador:** Possui permissão para convidar, editar e excluir usuários.
- **Proprietário:** Possui permissão para transferir ou excluir projetos. Excluir e editar uma organização.

Permissões para cada função de usuário na Dashboard Service.

|      Permissão                                                |                 |                      |                       |
| ------------------------------------------------------------- | --------------- | -------------------- |-----------------------|
|      Visualizar os resultados dos testes de projetos privados   |     Membro      |     Administrador     |     Proprietário     |
|      Visualizar as chaves de registro de projetos                 | Membro |  Administrador | Proprietário |
|      Visualizar as informações de faturamento e uso               |        |  Administrador | Proprietário |    
|      Editar informações de faturamento                            |        |  Administrador | Proprietário |   
|      Visualizar usuários convidados para a organização            |        |  Administrador | Proprietário |   
|      Reenviar convite para usuário convidado                      |        |  Administrador | Proprietário |   
|      Convidar 'membro' para a organização                         |        |  Administrador | Proprietário |
|      Convidar 'administrador' para a organização                          |        |  Administrador | Proprietário |
|      Visualizar as solicitações de usuários para ingressar na organização |   |  Administrador| Proprietário |
|      Aceitar solicitações de usuários para ingressar na organização |        |  Administrador | Proprietário|
|      Remover 'membro' da organização                          |        |  Administrador | Proprietário |
|      Remover 'administrador' da organização                          |        |  Administrador |Proprietário |
|      Editar 'membro' da organização                          |        |  Administrador | Proprietário |
|      Editar 'administrador' da organização                          |        |  Administrador | Proprietário |
|      Editar o nome do projeto                        |        |  Administrador | Proprietário |
|      Editar o status do projeto (privado / público}                     |        |  Administrador | Proprietário |
|      Adicionar ou excluir chaves de registro                     |        |  Administrador | Proprietário |
|      Configurar a integração do GitHub                     |        |  Administrador | Proprietário |
|      Configurar a integração com o Slack                   |        |  Administrador | Proprietário |
|      Convidar 'proprietário' para a organização            |        |          | Proprietário |
|      Editar 'proprietário' da organização            |        |          | Proprietário |
|      Remover 'proprietário' da organização           |        |          | Proprietário |
|      Adicionar, editar e remover usuário de uma organização pessoal           |        |          | Proprietário |
|      Editar o nome da organização           |        |          | Proprietário |
|      Excluir a organização           |        |          | Proprietário |
|      Transferir o projeto para outra organização           |        |          | Proprietário |
|      Excluir  o projeto           |        |          | Proprietário |
|      Configurar SSO               |        |          | Proprietário |

## Solicitação de usuário

Os usuários podem "solicitar" acesso a uma determinada organização. Se um desenvolvedor da sua equipe tiver acesso ao Cypress
e ao código-fonte do seu projeto, ele poderá solicitar o acesso à sua organização. Isso significa que, em vez de convidar
os membros da equipe antecipadamente, eles podem solicitar acesso e você pode optar por aceitar ou negar o acesso.

![request-access-to-organization](https://docs.cypress.io/_nuxt/img/request-access-to-organization.7e2a510.png)

## Atualização de usuário

As alterações podem ser feitas no endereço de e-mail principal associado à sua conta do Dashboard e no endereço de e-mail
para notificações de faturamento.

Para atualizar o endereço de e-mail principal associado ao seu painel, clique na imagem do seu perfil no canto superior 
esquerdo da página Organizações. Selecione **Gerenciar Perfil**. Vá para o campo **E-mail** e selecione seu endereço de 
e-mail. 
Obsevação: A lista de e-mail é limitada a e-mails fornecidos pelo provedor de login.

Se desejar atualizar o endereço de e-mail de cobrança, isso pode ser feito por meio da página **Cobrança e uso** no [Dashboard](https://dashboard.cypress.io/)
ou contate diretamente em billing@cypress.io .
