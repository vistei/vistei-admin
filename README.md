<img src="https://img.shields.io/badge/current version-1.0.0-blue" />

## 🖥 Painel Administrativo Vistei

Bem-vindo(a) ao painel administrativo da Vistei. O nosso portal administrativo é a plataforma onde você pode visualizar, gerenciar e parametrizar a sua empresa na Vistei. Nessa documentação você encontrará as instruções para uso da plataforma web, para acessar a documentação da API, <a href="">clique aqui</a>.

## Índice

<ul>
  <li><a href="#user-access">Usuários e acessos</a></li>
  <ul>
    <li><a href="#first-access">Primeiro acesso</a></li>
    <li><a href="#access-profiles">Perfis de acesso</a></li>
    <li><a href="#users-invite">Convidando usuários</a></li>
    <li><a href="#password-recover">Alteração e recuperação de senha</a></li>
  </ul>
  <li><a href="">Gestão de constantes</a></li>
  <ul>
    <li><a href="">Constante tipo de objetos</a></li>
    <li><a href="">Constante tipo de fotos</a></li>
    <li><a href="">Constante tipo de Vistorias</a></li>
  </ul>
  <li><a href="">Gestão de vistorias</a></li>
  <ul>
    <li><a href="">Solicitando visotias</a></li>
    <li><a href="">Busca e filtragem</a></li>
    <li><a href="">Emitindo um laudo de vistoria</a></li>
  </ul>
  <li><a href="">Painel do desenvolvedor</a></li>
   <ul>
    <li><a href="">Credenciais de acesso</a></li>
    <li><a href="">Resetando credenciais de acesso</a></li>
  </ul>
</ul>

<hr/>

## <a name="user-access"></a>Usuários e acessos

###  <a name="first-access"></a>Primeiro acesso

O primeiro acesso da sua empresa na plataforma Vistei é criado pelo nosso time no momento da integração. O primeiro acesso criado é o usuário MASTER da sua empresa. Ele poderá parametrizar a ferramenta e convidar novos usuários. No momento da integração, você receberá um e-mail contendo o seu usuário e uma senha padrão que poderá ser alterada posteriormente. Com o seu usuário e senha em mãos, basta acessar o endereço <a href="https://portal.vistei.tech" target="_blank">https://portal.vistei.tech</a> e fazer o login na plataforma.

### <a name="access-profiles"></a>Perfis de acesso (beta)

O portal administrativo da Vistei tem alguns perfis de acesso pré-definidas que você pode aplicar aos seus usuários.

<table>
  <thead>
    <td>Perfil</td>
    <td>Descrição</td>
  </thead>
  <tbody>
    <tr>
      <td>MASTER</td>
      <td>O usuário MASTER possui acesso completo a todas as telas e funcionalidade do sistema.</td>
    </tr>  
    <tr>
      <td>Administrador</td>
      <td>As pessoas com o perfil de acesso administrador a possuem acesso liberado a todas as telas e funcionalidades do sistema. Porém, pessoas com este acesso não podem alterar as informações cadastrais da sua empresa na plataforma Vistei.</td>
    </tr>  
    <tr>
      <td>Backoffice</td>
      <td>As pessoas com o perfil de acesso backoffice possuem acesso aos módulos operacionais. Elas podem solicitar e acompanhar vistorias, emitir laudos, convidar e gerenciar usuários e parametrizar as constantes do sistema.</td>
    </tr>
    <tr>
      <td>Desenvolvedor</td>
      <td>As pessoas com o perfil de acesso desenvolvedor possuem acesso à àrea do desenvolvedor. Nela, é possível gerenciar as credenciais de acesso e as configurações de conexão via API.</td>
    </tr> 
    <tr>
      <td>Vistoriador</td>
      <td>As pessoas com o perfil de acesso vistoriador possuem acesso ao módulo de vistoria. Nele é possível solicitar novas vistorias, acompanhar os status das vistorias existentes e emitir laudos de vistoria.</td>
    </tr> 
  </tbody>
</table>


### <a name="users-invite"></a>Convidando usuários

Convidar um novo usuário é muito simples. Na página inicial da nossa <a href="https://portal.vistei.tech" target="_blank">plataforma</a>, clique em 'Configurar usuários' e, em seguida, clique no botão 'Convites'. Na página de convites, você consegue ver uma listagem de todos os convites que foram enviados na sua plataforma. Para convidar um novo colaborador, clique em 'Convidar usuário' e preencha as seguintes informações:
<ul>
  <li>Nome do usuário</li>
  <li>E-mail do usuário</li>
  <li>Perfil de acesso (saiba mais em <a href="">perfis de acesso</a>)</li>
</ul/>
  
### <a name="password-recover"></a>Alteração e recuperação de senha
  
Existem duas maneiras de alterar a sua senha de acesso ao sistema. Caso esteja logado no sitema e lembre a sua senha, basta acessar o menu 'Alterar senha', inserir a sua senha atual, criar uma nova senha e confirmar as alterações. Caso tenha perdido o acesso à sua conta ou esquecido a sua senha de acesso, na tela de login basta escolher a opção 'Esqueceu a senha?'. Na página de recuperação, será solicitado que você informe o seu e-mail e você receberá uma mensagem com um código de recuperação que permitirá que você altere a sua senha.
